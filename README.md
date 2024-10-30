# Token hub

**Token hub allows users to update token metadata by leveraging [Ethereum Attestation Service](https://attest.org/).**
**Our schema will be on Base and users can submit attesations through our UI [here](https://wallet.coinbase.com/token-hub) or directly onchain through EAS**

## Schema 

| Variable           | Type       | Description                                      |
|--------------------|------------|--------------------------------------------------|
| `chainId`          | `uint256`  | token chain ID                                   |
| `contractAddress`  | `address`  | token contract address                           |
| `name`             | `string`   | token name                                       |
| `symbol`           | `string`   | token symbol                                     |
| `description`      | `string`   | token description                                |
| `imageUrl`         | `string`   | link to token image                              |
| `websiteUrl`       | `string`   | link to token website                            |
| `whitePaperUrl`    | `string`   | link to token whitepaper                         |
| `codebaseUrl`      | `string`   | link to codebase                                 |
| `socialMediaUrls`  | `[]string` | list of social media URLs                        |
| `auditUrls`        | `[]string` | list of audit URLs                               |
| `migratedToAddress`| `address`  | token has migrated to another contract address   |
| `version`          | `string`   | token version (e.g., v2 after 1 migration)       |
| `email`            | `string`   | email for contact                                |
| `canonicalChainId` | `uint256`  | chain ID of the canonical token                  |
| `canonicalAddress` | `address`  | canonical token to get metadata from             |
