# Manifold Contract Addresses

## Overview

This document provides a comprehensive list of all Manifold smart contract deployments across multiple blockchain networks. It serves as an authoritative reference for developers, security vendors, and integration partners.

## Table of Contents

- [Networks](#networks)
- [Core Contracts](#core-contracts)
- [Marketplace Contracts](#marketplace-contracts)
- [Claim Extensions](#claim-extensions)
- [Burn/Redeem Extensions](#burnredeem-extensions)
- [Special Extensions](#special-extensions)
- [Infrastructure Contracts](#infrastructure-contracts)
- [Delegation Registry](#delegation-registry)
- [Royalty System](#royalty-system)
- [Supported ERC20 Tokens](#supported-erc20-tokens)
- [Deprecated Contracts](#deprecated-contracts)

## Networks

| Network | Chain ID | Block Explorer |
|---------|----------|---------------|
| Ethereum Mainnet | 1 | [etherscan.io](https://etherscan.io) |
| Sepolia Testnet | 11155111 | [sepolia.etherscan.io](https://sepolia.etherscan.io) |
| Optimism | 10 | [optimistic.etherscan.io](https://optimistic.etherscan.io) |
| Base | 8453 | [basescan.org](https://basescan.org) |
| Shape | 360 | [explorer.shape.network](https://explorer.shape.network) |
| Apechain | 33139 | [apescan.io](https://apescan.io) |

## Core Contracts

### Manifold Creator Core

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| CREATE2 Contract Deployer | - | Ethereum Mainnet | `0xF3Cd1e9326D1965935B287b1eE75c7183359A88A` | [View](https://etherscan.io/address/0xF3Cd1e9326D1965935B287b1eE75c7183359A88A) |
| CREATE2 Contract Deployer | - | Sepolia | `0xF3Cd1e9326D1965935B287b1eE75c7183359A88A` | [View](https://sepolia.etherscan.io/address/0xF3Cd1e9326D1965935B287b1eE75c7183359A88A) |
| CREATE2 Contract Deployer | - | Optimism | `0xF3Cd1e9326D1965935B287b1eE75c7183359A88A` | [View](https://optimistic.etherscan.io/address/0xF3Cd1e9326D1965935B287b1eE75c7183359A88A) |
| CREATE2 Contract Deployer | - | Base | `0xF3Cd1e9326D1965935B287b1eE75c7183359A88A` | [View](https://basescan.org/address/0xF3Cd1e9326D1965935B287b1eE75c7183359A88A) |
| CREATE2 Contract Deployer | - | Shape | `0xF3Cd1e9326D1965935B287b1eE75c7183359A88A` | [View](https://explorer.shape.network/address/0xF3Cd1e9326D1965935B287b1eE75c7183359A88A) |
| CREATE2 Contract Deployer | - | Apechain | `0xF3Cd1e9326D1965935B287b1eE75c7183359A88A` | [View](https://apescan.io/address/0xF3Cd1e9326D1965935B287b1eE75c7183359A88A) |

### Manifold ERC721 Edition

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| ERC721 Edition | v1 | Ethereum Mainnet | `0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC` | [View](https://etherscan.io/address/0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC) |
| ERC721 Edition | v1 | Sepolia | `0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC` | [View](https://sepolia.etherscan.io/address/0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC) |
| ERC721 Edition | v1 | Optimism | `0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC` | [View](https://optimistic.etherscan.io/address/0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC) |
| ERC721 Edition | v1 | Base | `0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC` | [View](https://basescan.org/address/0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC) |
| ERC721 Edition | v1 | Shape | `0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC` | [View](https://explorer.shape.network/address/0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC) |
| ERC721 Edition | v1 | Apechain | `0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC` | [View](https://apescan.io/address/0xF72a0831B071aDba60BEF4F90D1f42B83687e2eC) |
| ERC721 Edition | v2 | Ethereum Mainnet | `0x76Da6Eb8C7BA072937E917286d3A23dC7ccBED99` | [View](https://etherscan.io/address/0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99) |
| ERC721 Edition | v2 | Sepolia | `0x76Da6Eb8C7BA072937E917286d3A23dC7ccBED99` | [View](https://sepolia.etherscan.io/address/0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99) |
| ERC721 Edition | v2 | Optimism | `0x76Da6Eb8C7BA072937E917286d3A23dC7ccBED99` | [View](https://optimistic.etherscan.io/address/0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99) |
| ERC721 Edition | v2 | Base | `0x76Da6Eb8C7BA072937E917286d3A23dC7ccBED99` | [View](https://basescan.org/address/0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99) |
| ERC721 Edition | v2 | Shape | `0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99` | [View](https://explorer.shape.network/address/0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99) |
| ERC721 Edition | v2 | Apechain | `0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99` | [View](https://apescan.io/address/0x76Da6Eb8C7Ba072937E917286d3A23dC7ccBED99) |
| ERC721 Edition | - | Ethereum Mainnet | `0xc68afc6A3B47b108Db5e48fB53a10D2D9c11b094` | [View](https://etherscan.io/address/0xc68afc6A3B47b108Db5e48fB53a10D2D9c11b094) |
| ERC721 Edition | - | Sepolia | `0x414c181d58f3b0d56fa9f60f9e50ef79b79bda53` | [View](https://sepolia.etherscan.io/address/0x414c181d58f3b0d56fa9f60f9e50ef79b79bda53) |

## Marketplace Contracts

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Marketplace | - | Ethereum Mainnet | `0x5246807fB65d87b0D0a234E0f3D42374de83B421` | [View](https://etherscan.io/address/0x5246807fB65d87b0D0a234E0f3D42374de83B421) |
| Marketplace | - | Sepolia | `0x5246807fB65d87b0D0a234E0f3D42374de83B421` | [View](https://sepolia.etherscan.io/address/0x5246807fB65d87b0D0a234E0f3D42374de83B421) |
| Marketplace | - | Optimism | `0x5246807fB65d87b0D0a234E0f3D42374de83B421` | [View](https://optimistic.etherscan.io/address/0x5246807fB65d87b0D0a234E0f3D42374de83B421) |
| Marketplace | - | Base | `0x5246807fB65d87b0D0a234E0f3D42374de83B421` | [View](https://basescan.org/address/0x5246807fB65d87b0D0a234E0f3D42374de83B421) |
| Marketplace | - | Shape | `0x5246807fB65d87b0D0a234E0f3D42374de83B421` | [View](https://explorer.shape.network/address/0x5246807fB65d87b0D0a234E0f3D42374de83B421) |
| Marketplace | - | Apechain | `0x5246807fB65d87b0D0a234E0f3D42374de83B421` | [View](https://apescan.io/address/0x5246807fB65d87b0D0a234E0f3D42374de83B421) |
| Marketplace | v1 | Ethereum Mainnet | `0x7ef865963d3a005670b8f8df6aed23e456fa75e0` | [View](https://etherscan.io/address/0x7ef865963d3a005670b8f8df6aed23e456fa75e0) |
| Marketplace | v2 | Ethereum Mainnet | `0x3a3548e060be10c2614d0a4cb0c03cc9093fd799` | [View](https://etherscan.io/address/0x3a3548e060be10c2614d0a4cb0c03cc9093fd799) |
| Christie's Marketplace | - | Ethereum Mainnet | `0x9d3c936d7e2ff74b068862f439925b570e46775f` | [View](https://etherscan.io/address/0x9d3c936d7e2ff74b068862f439925b570e46775f) |
| Marketplace Private Listing | - | Ethereum Mainnet | `0x4eb327e272d11882510146e57ffafb5ea2f2b1d6` | [View](https://etherscan.io/address/0x4eb327e272d11882510146e57ffafb5ea2f2b1d6) |
| Marketplace Private Listing | - | Ethereum Mainnet | `0x821F593ee72A187188AB3Fb1e68d58EBBe478E70` | [View](https://etherscan.io/address/0x821F593ee72A187188AB3Fb1e68d58EBBe478E70) |
| Marketplace Private Listing | - | Sepolia | `0x821F593ee72A187188AB3Fb1e68d58EBBe478E70` | [View](https://sepolia.etherscan.io/address/0x821F593ee72A187188AB3Fb1e68d58EBBe478E70) |
| Marketplace Private Listing | - | Optimism | `0x821F593ee72A187188AB3Fb1e68d58EBBe478E70` | [View](https://optimistic.etherscan.io/address/0x821F593ee72A187188AB3Fb1e68d58EBBe478E70) |
| Marketplace Private Listing | - | Base | `0x821F593ee72A187188AB3Fb1e68d58EBBe478E70` | [View](https://basescan.org/address/0x821F593ee72A187188AB3Fb1e68d58EBBe478E70) |
| Marketplace Private Listing | - | Shape | `0x821F593ee72A187188AB3Fb1e68d58EBBe478E70` | [View](https://explorer.shape.network/address/0x821F593ee72A187188AB3Fb1e68d58EBBe478E70) |
| Marketplace Private Listing | - | Apechain | `0x821F593ee72A187188AB3Fb1e68d58EBBe478E70` | [View](https://apescan.io/address/0x821F593ee72A187188AB3Fb1e68d58EBBe478E70) |

## Claim Extensions

### Latest Versions (Cross-Chain)

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Claim Extension ERC721 | v8 | Ethereum Mainnet | `0x5889E848b2423344F7969bC158100c07595c0137` | [View](https://etherscan.io/address/0x5889E848b2423344F7969bC158100c07595c0137) |
| Claim Extension ERC721 | v8 | Sepolia | `0x5889E848b2423344F7969bC158100c07595c0137` | [View](https://sepolia.etherscan.io/address/0x5889E848b2423344F7969bC158100c07595c0137) |
| Claim Extension ERC721 | v8 | Optimism | `0x5889E848b2423344F7969bC158100c07595c0137` | [View](https://optimistic.etherscan.io/address/0x5889E848b2423344F7969bC158100c07595c0137) |
| Claim Extension ERC721 | v8 | Base | `0x5889E848b2423344F7969bC158100c07595c0137` | [View](https://basescan.org/address/0x5889E848b2423344F7969bC158100c07595c0137) |
| Claim Extension ERC721 | v8 | Shape | `0x5889E848b2423344F7969bC158100c07595c0137` | [View](https://explorer.shape.network/address/0x5889E848b2423344F7969bC158100c07595c0137) |
| Claim Extension ERC721 | v8 | Apechain | `0x5889E848b2423344F7969bC158100c07595c0137` | [View](https://apescan.io/address/0x5889E848b2423344F7969bC158100c07595c0137) |
| Claim Extension ERC1155 | v8 | Ethereum Mainnet | `0x88438f4d4B8516E758a319ad16924DA60e1E56CC` | [View](https://etherscan.io/address/0x88438f4d4B8516E758a319ad16924DA60e1E56CC) |
| Claim Extension ERC1155 | v8 | Sepolia | `0x88438f4d4B8516E758a319ad16924DA60e1E56CC` | [View](https://sepolia.etherscan.io/address/0x88438f4d4B8516E758a319ad16924DA60e1E56CC) |
| Claim Extension ERC1155 | v8 | Optimism | `0x88438f4d4B8516E758a319ad16924DA60e1E56CC` | [View](https://optimistic.etherscan.io/address/0x88438f4d4B8516E758a319ad16924DA60e1E56CC) |
| Claim Extension ERC1155 | v8 | Base | `0x88438f4d4B8516E758a319ad16924DA60e1E56CC` | [View](https://basescan.org/address/0x88438f4d4B8516E758a319ad16924DA60e1E56CC) |
| Claim Extension ERC1155 | v8 | Shape | `0x88438f4d4B8516E758a319ad16924DA60e1E56CC` | [View](https://explorer.shape.network/address/0x88438f4d4B8516E758a319ad16924DA60e1E56CC) |
| Claim Extension ERC1155 | v8 | Apechain | `0x88438f4d4B8516E758a319ad16924DA60e1E56CC` | [View](https://apescan.io/address/0x88438f4d4B8516E758a319ad16924DA60e1E56CC) |
| Claim Extension ERC721 | v7 | Ethereum Mainnet | `0x23aa05A271dEbfFaa3D75739af5581f744B326e4` | [View](https://etherscan.io/address/0x23aa05A271dEbfFaa3D75739af5581f744B326e4) |
| Claim Extension ERC721 | v7 | Sepolia | `0x23aa05A271dEbfFaa3D75739af5581f744B326e4` | [View](https://sepolia.etherscan.io/address/0x23aa05A271dEbfFaa3D75739af5581f744B326e4) |
| Claim Extension ERC721 | v7 | Optimism | `0x23aa05A271dEbfFaa3D75739af5581f744B326e4` | [View](https://optimistic.etherscan.io/address/0x23aa05A271dEbfFaa3D75739af5581f744B326e4) |
| Claim Extension ERC721 | v7 | Base | `0x23aa05A271dEbfFaa3D75739af5581f744B326e4` | [View](https://basescan.org/address/0x23aa05A271dEbfFaa3D75739af5581f744B326e4) |
| Claim Extension ERC721 | v7 | Shape | `0x23aa05A271dEbfFaa3D75739af5581f744B326e4` | [View](https://explorer.shape.network/address/0x23aa05A271dEbfFaa3D75739af5581f744B326e4) |
| Claim Extension ERC721 | v7 | Apechain | `0x23aa05A271dEbfFaa3D75739af5581f744B326e4` | [View](https://apescan.io/address/0x23aa05A271dEbfFaa3D75739af5581f744B326e4) |
| Claim Extension ERC1155 | v7 | Ethereum Mainnet | `0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE` | [View](https://etherscan.io/address/0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE) |
| Claim Extension ERC1155 | v7 | Sepolia | `0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE` | [View](https://sepolia.etherscan.io/address/0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE) |
| Claim Extension ERC1155 | v7 | Optimism | `0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE` | [View](https://optimistic.etherscan.io/address/0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE) |
| Claim Extension ERC1155 | v7 | Base | `0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE` | [View](https://basescan.org/address/0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE) |
| Claim Extension ERC1155 | v7 | Shape | `0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE` | [View](https://explorer.shape.network/address/0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE) |
| Claim Extension ERC1155 | v7 | Apechain | `0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE` | [View](https://apescan.io/address/0x26bbEa7803dCac346d5F5F135b57cf2C752a02BE) |
| Claim Extension ERC721 | v6 | Ethereum Mainnet | `0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E` | [View](https://etherscan.io/address/0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E) |
| Claim Extension ERC721 | v6 | Sepolia | `0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E` | [View](https://sepolia.etherscan.io/address/0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E) |
| Claim Extension ERC721 | v6 | Optimism | `0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E` | [View](https://optimistic.etherscan.io/address/0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E) |
| Claim Extension ERC721 | v6 | Base | `0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E` | [View](https://basescan.org/address/0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E) |
| Claim Extension ERC721 | v6 | Shape | `0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E` | [View](https://explorer.shape.network/address/0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E) |
| Claim Extension ERC721 | v6 | Apechain | `0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E` | [View](https://apescan.io/address/0x1eb73FEE2090fB1C20105d5ba887e3C3bA14a17E) |
| Claim Extension ERC1155 | v6 | Ethereum Mainnet | `0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65` | [View](https://etherscan.io/address/0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65) |
| Claim Extension ERC1155 | v6 | Sepolia | `0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65` | [View](https://sepolia.etherscan.io/address/0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65) |
| Claim Extension ERC1155 | v6 | Optimism | `0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65` | [View](https://optimistic.etherscan.io/address/0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65) |
| Claim Extension ERC1155 | v6 | Base | `0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65` | [View](https://basescan.org/address/0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65) |
| Claim Extension ERC1155 | v6 | Shape | `0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65` | [View](https://explorer.shape.network/address/0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65) |
| Claim Extension ERC1155 | v6 | Apechain | `0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65` | [View](https://apescan.io/address/0x04BA6cf3c5aA6d4946F5b7f7AdF111012a9FAc65) |

### Mainnet-Specific Versions

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Claim Extension ERC721 | v5 | Ethereum Mainnet | `0x3b8c2feb0f4953870f825df64322ec967aa26b8c` | [View](https://etherscan.io/address/0x3b8c2feb0f4953870f825df64322ec967aa26b8c) |
| Claim Extension ERC1155 | v5 | Ethereum Mainnet | `0xdb8d79c775452a3929b86ac5deab3e9d38e1c006` | [View](https://etherscan.io/address/0xdb8d79c775452a3929b86ac5deab3e9d38e1c006) |
| Claim Extension ERC721 | v4 | Ethereum Mainnet | `0x7581871e1c11f85ec7f02382632b8574fad11b22` | [View](https://etherscan.io/address/0x7581871e1c11f85ec7f02382632b8574fad11b22) |
| Claim Extension ERC1155 | v4 | Ethereum Mainnet | `0xe7d3982e214f9dfd53d23a7f72851a7044072250` | [View](https://etherscan.io/address/0xe7d3982e214f9dfd53d23a7f72851a7044072250) |
| Claim Extension ERC721 | v3 | Ethereum Mainnet | `0xa46f952645d4deec07a7cd98d1ec9ec888d4b61e` | [View](https://etherscan.io/address/0xa46f952645d4deec07a7cd98d1ec9ec888d4b61e) |
| Claim Extension ERC1155 | v3 | Ethereum Mainnet | `0x44e94034afce2dd3cd5eb62528f239686fc8f162` | [View](https://etherscan.io/address/0x44e94034afce2dd3cd5eb62528f239686fc8f162) |
| Claim Extension ERC721 | v2 | Ethereum Mainnet | `0x5ebfd58c5ead1025755f7490e510ccf2c0b4a444` | [View](https://etherscan.io/address/0x5ebfd58c5ead1025755f7490e510ccf2c0b4a444) |
| Claim Extension ERC1155 | v2 | Ethereum Mainnet | `0x4e32004d8b81847a670b4a1778ace4dcf2bba01e` | [View](https://etherscan.io/address/0x4e32004d8b81847a670b4a1778ace4dcf2bba01e) |
| Claim Extension ERC721 | v1 | Ethereum Mainnet | `0xb08aa31cc2b8c0582be42d38bb643292e0a4b9eb` | [View](https://etherscan.io/address/0xb08aa31cc2b8c0582be42d38bb643292e0a4b9eb) |
| Claim Extension ERC1155 | v1 | Ethereum Mainnet | `0xca71c5270eff44eb6d813a92c0ba12577bddf208` | [View](https://etherscan.io/address/0xca71c5270eff44eb6d813a92c0ba12577bddf208) |

### Specialized Claim Extensions

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Claim Signature Minting ERC721 | v1 | Ethereum Mainnet | `0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1` | [View](https://etherscan.io/address/0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1) |
| Claim Signature Minting ERC721 | v1 | Sepolia | `0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1` | [View](https://sepolia.etherscan.io/address/0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1) |
| Claim Signature Minting ERC721 | v1 | Optimism | `0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1` | [View](https://optimistic.etherscan.io/address/0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1) |
| Claim Signature Minting ERC721 | v1 | Base | `0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1` | [View](https://basescan.org/address/0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1) |
| Claim Signature Minting ERC721 | v1 | Shape | `0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1` | [View](https://explorer.shape.network/address/0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1) |
| Claim Signature Minting ERC721 | v1 | Apechain | `0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1` | [View](https://apescan.io/address/0x56FE278eC785e8aE6dFb0fda0Af4cc7a1b62BAF1) |
| Claim Signature Minting ERC1155 | v1 | Ethereum Mainnet | `0x85C71E0BDE93A1719b1bE9358172Ad472090217C` | [View](https://etherscan.io/address/0x85C71E0BDE93A1719b1bE9358172Ad472090217C) |
| Claim Signature Minting ERC1155 | v1 | Sepolia | `0x85C71E0BDE93A1719b1bE9358172Ad472090217C` | [View](https://sepolia.etherscan.io/address/0x85C71E0BDE93A1719b1bE9358172Ad472090217C) |
| Claim Signature Minting ERC1155 | v1 | Optimism | `0x85C71E0BDE93A1719b1bE9358172Ad472090217C` | [View](https://optimistic.etherscan.io/address/0x85C71E0BDE93A1719b1bE9358172Ad472090217C) |
| Claim Signature Minting ERC1155 | v1 | Base | `0x85C71E0BDE93A1719b1bE9358172Ad472090217C` | [View](https://basescan.org/address/0x85C71E0BDE93A1719b1bE9358172Ad472090217C) |
| Claim Signature Minting ERC1155 | v1 | Shape | `0x85C71E0BDE93A1719b1bE9358172Ad472090217C` | [View](https://explorer.shape.network/address/0x85C71E0BDE93A1719b1bE9358172Ad472090217C) |
| Claim Signature Minting ERC1155 | v1 | Apechain | `0x85C71E0BDE93A1719b1bE9358172Ad472090217C` | [View](https://apescan.io/address/0x85C71E0BDE93A1719b1bE9358172Ad472090217C) |
| Claim Updatable Mint Fee ERC721 | v1 | Ethereum Mainnet | `0xe78d5842B6842056AAC519E927030B6F6e80A2D6` | [View](https://etherscan.io/address/0xe78d5842B6842056AAC519E927030B6F6e80A2D6) |
| Claim Updatable Mint Fee ERC721 | v1 | Sepolia | `0xe78d5842B6842056AAC519E927030B6F6e80A2D6` | [View](https://sepolia.etherscan.io/address/0xe78d5842B6842056AAC519E927030B6F6e80A2D6) |
| Claim Updatable Mint Fee ERC721 | v1 | Optimism | `0xe78d5842B6842056AAC519E927030B6F6e80A2D6` | [View](https://optimistic.etherscan.io/address/0xe78d5842B6842056AAC519E927030B6F6e80A2D6) |
| Claim Updatable Mint Fee ERC721 | v1 | Base | `0xe78d5842B6842056AAC519E927030B6F6e80A2D6` | [View](https://basescan.org/address/0xe78d5842B6842056AAC519E927030B6F6e80A2D6) |
| Claim Updatable Mint Fee ERC721 | v1 | Shape | `0xe78d5842B6842056AAC519E927030B6F6e80A2D6` | [View](https://explorer.shape.network/address/0xe78d5842B6842056AAC519E927030B6F6e80A2D6) |
| Claim Updatable Mint Fee ERC721 | v1 | Apechain | `0xe78d5842B6842056AAC519E927030B6F6e80A2D6` | [View](https://apescan.io/address/0xe78d5842B6842056AAC519E927030B6F6e80A2D6) |
| Claim Updatable Mint Fee ERC1155 | v1 | Ethereum Mainnet | `0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86` | [View](https://etherscan.io/address/0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86) |
| Claim Updatable Mint Fee ERC1155 | v1 | Sepolia | `0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86` | [View](https://sepolia.etherscan.io/address/0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86) |
| Claim Updatable Mint Fee ERC1155 | v1 | Optimism | `0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86` | [View](https://optimistic.etherscan.io/address/0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86) |
| Claim Updatable Mint Fee ERC1155 | v1 | Base | `0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86` | [View](https://basescan.org/address/0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86) |
| Claim Updatable Mint Fee ERC1155 | v1 | Shape | `0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86` | [View](https://explorer.shape.network/address/0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86) |
| Claim Updatable Mint Fee ERC1155 | v1 | Apechain | `0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86` | [View](https://apescan.io/address/0x5E90E85ff40a4bC6F3e59cE12BeaEAa616F5ab86) |
| Claim USDC Only ERC721 | v1 | Ethereum Mainnet | `0x48b471fb4f2d996c251b570ac5cd84542ebdfad2` | [View](https://etherscan.io/address/0x48b471fb4f2d996c251b570ac5cd84542ebdfad2) |
| Claim USDC Only ERC721 | v1 | Sepolia | `0x4f976fd3d311bef8a3c5bff0e59c1650a20d2570` | [View](https://sepolia.etherscan.io/address/0x4f976fd3d311bef8a3c5bff0e59c1650a20d2570) |
| Claim Tip ERC721 | - | Ethereum Mainnet | `0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd` | [View](https://etherscan.io/address/0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd) |
| Claim Tip ERC721 | - | Sepolia | `0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd` | [View](https://sepolia.etherscan.io/address/0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd) |
| Claim Tip ERC721 | - | Optimism | `0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd` | [View](https://optimistic.etherscan.io/address/0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd) |
| Claim Tip ERC721 | - | Base | `0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd` | [View](https://basescan.org/address/0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd) |
| Claim Tip ERC721 | - | Shape | `0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd` | [View](https://explorer.shape.network/address/0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd) |
| Claim Tip ERC721 | - | Apechain | `0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd` | [View](https://apescan.io/address/0xdB4859261D1f1f85134971E1bCa1fcD9b5E443dd) |
| Claim Tip ERC1155 | - | Ethereum Mainnet | `0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525` | [View](https://etherscan.io/address/0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525) |
| Claim Tip ERC1155 | - | Sepolia | `0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525` | [View](https://sepolia.etherscan.io/address/0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525) |
| Claim Tip ERC1155 | - | Optimism | `0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525` | [View](https://optimistic.etherscan.io/address/0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525) |
| Claim Tip ERC1155 | - | Base | `0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525` | [View](https://basescan.org/address/0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525) |
| Claim Tip ERC1155 | - | Shape | `0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525` | [View](https://explorer.shape.network/address/0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525) |
| Claim Tip ERC1155 | - | Apechain | `0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525` | [View](https://apescan.io/address/0x4BE90E9E368B01c5f7550e6BDe0272E0BaA48525) |
| Claim Tip ERC721 | - | Ethereum Mainnet | `0xe8f23c38334e936820997817a65682b597c8c53f` | [View](https://etherscan.io/address/0xe8f23c38334e936820997817a65682b597c8c53f) |
| Claim Tip ERC1155 | - | Ethereum Mainnet | `0x6799835bc1960d005e65b54862d1efee5cfbd860` | [View](https://etherscan.io/address/0x6799835bc1960d005e65b54862d1efee5cfbd860) |
| Claim Soulbound ERC721 | - | Ethereum Mainnet | `0x0582a44b123fb333840b881e1521ceee4660f93b` | [View](https://etherscan.io/address/0x0582a44b123fb333840b881e1521ceee4660f93b) |
| Claim Soulbound ERC1155 | - | Ethereum Mainnet | `0x5bcd4a62a8bca29f5c0a6f41fecf8a70b8f4f46a` | [View](https://etherscan.io/address/0x5bcd4a62a8bca29f5c0a6f41fecf8a70b8f4f46a) |

## Burn/Redeem Extensions

### Latest Versions (Cross-Chain)

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Burn Redeem ERC721 | v5 | Ethereum Mainnet | `0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2` | [View](https://etherscan.io/address/0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2) |
| Burn Redeem ERC721 | v5 | Sepolia | `0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2` | [View](https://sepolia.etherscan.io/address/0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2) |
| Burn Redeem ERC721 | v5 | Optimism | `0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2` | [View](https://optimistic.etherscan.io/address/0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2) |
| Burn Redeem ERC721 | v5 | Base | `0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2` | [View](https://basescan.org/address/0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2) |
| Burn Redeem ERC721 | v5 | Shape | `0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2` | [View](https://explorer.shape.network/address/0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2) |
| Burn Redeem ERC721 | v5 | Apechain | `0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2` | [View](https://apescan.io/address/0xE264Ea735b8073b5BCC6d5cfb2eb9B48D6aaaeE2) |
| Burn Redeem ERC1155 | v5 | Ethereum Mainnet | `0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2` | [View](https://etherscan.io/address/0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2) |
| Burn Redeem ERC1155 | v5 | Sepolia | `0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2` | [View](https://sepolia.etherscan.io/address/0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2) |
| Burn Redeem ERC1155 | v5 | Optimism | `0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2` | [View](https://optimistic.etherscan.io/address/0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2) |
| Burn Redeem ERC1155 | v5 | Base | `0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2` | [View](https://basescan.org/address/0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2) |
| Burn Redeem ERC1155 | v5 | Shape | `0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2` | [View](https://explorer.shape.network/address/0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2) |
| Burn Redeem ERC1155 | v5 | Apechain | `0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2` | [View](https://apescan.io/address/0xFc29813Beeb3c7395C7A5f8dfC3352491D5ea0E2) |
| Burn Redeem ERC721 | v4 | Ethereum Mainnet | `0xD5957D474B1f1319385d3Feb0649e2FdB5142915` | [View](https://etherscan.io/address/0xD5957D474B1f1319385d3Feb0649e2FdB5142915) |
| Burn Redeem ERC721 | v4 | Sepolia | `0xD5957D474B1f1319385d3Feb0649e2FdB5142915` | [View](https://sepolia.etherscan.io/address/0xD5957D474B1f1319385d3Feb0649e2FdB5142915) |
| Burn Redeem ERC721 | v4 | Optimism | `0xD5957D474B1f1319385d3Feb0649e2FdB5142915` | [View](https://optimistic.etherscan.io/address/0xD5957D474B1f1319385d3Feb0649e2FdB5142915) |
| Burn Redeem ERC721 | v4 | Base | `0xD5957D474B1f1319385d3Feb0649e2FdB5142915` | [View](https://basescan.org/address/0xD5957D474B1f1319385d3Feb0649e2FdB5142915) |
| Burn Redeem ERC721 | v4 | Shape | `0xD5957D474B1f1319385d3Feb0649e2FdB5142915` | [View](https://explorer.shape.network/address/0xD5957D474B1f1319385d3Feb0649e2FdB5142915) |
| Burn Redeem ERC721 | v4 | Apechain | `0xD5957D474B1f1319385d3Feb0649e2FdB5142915` | [View](https://apescan.io/address/0xD5957D474B1f1319385d3Feb0649e2FdB5142915) |
| Burn Redeem ERC1155 | v4 | Ethereum Mainnet | `0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913` | [View](https://etherscan.io/address/0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913) |
| Burn Redeem ERC1155 | v4 | Sepolia | `0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913` | [View](https://sepolia.etherscan.io/address/0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913) |
| Burn Redeem ERC1155 | v4 | Optimism | `0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913` | [View](https://optimistic.etherscan.io/address/0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913) |
| Burn Redeem ERC1155 | v4 | Base | `0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913` | [View](https://basescan.org/address/0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913) |
| Burn Redeem ERC1155 | v4 | Shape | `0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913` | [View](https://explorer.shape.network/address/0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913) |
| Burn Redeem ERC1155 | v4 | Apechain | `0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913` | [View](https://apescan.io/address/0x92C3E92574D1c0B758c3c1a4feA51A25AbE43913) |
| Burn Redeem Updatable Fee ERC721 | v1 | Ethereum Mainnet | `0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29` | [View](https://etherscan.io/address/0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29) |
| Burn Redeem Updatable Fee ERC721 | v1 | Sepolia | `0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29` | [View](https://sepolia.etherscan.io/address/0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29) |
| Burn Redeem Updatable Fee ERC721 | v1 | Optimism | `0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29` | [View](https://optimistic.etherscan.io/address/0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29) |
| Burn Redeem Updatable Fee ERC721 | v1 | Base | `0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29` | [View](https://basescan.org/address/0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29) |
| Burn Redeem Updatable Fee ERC721 | v1 | Shape | `0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29` | [View](https://explorer.shape.network/address/0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29) |
| Burn Redeem Updatable Fee ERC721 | v1 | Apechain | `0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29` | [View](https://apescan.io/address/0x8A81E8f6509Dd4Be2908c0dA0373CC0E36aA7f29) |
| Burn Redeem Updatable Fee ERC1155 | v1 | Ethereum Mainnet | `0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd` | [View](https://etherscan.io/address/0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd) |
| Burn Redeem Updatable Fee ERC1155 | v1 | Sepolia | `0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd` | [View](https://sepolia.etherscan.io/address/0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd) |
| Burn Redeem Updatable Fee ERC1155 | v1 | Optimism | `0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd` | [View](https://optimistic.etherscan.io/address/0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd) |
| Burn Redeem Updatable Fee ERC1155 | v1 | Base | `0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd` | [View](https://basescan.org/address/0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd) |
| Burn Redeem Updatable Fee ERC1155 | v1 | Shape | `0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd` | [View](https://explorer.shape.network/address/0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd) |
| Burn Redeem Updatable Fee ERC1155 | v1 | Apechain | `0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd` | [View](https://apescan.io/address/0x0EA8a897ECB5BC1b48e190FB1aa3e7a01aE621fd) |
| Cross-chain Burn | v1 | Ethereum Mainnet | `0xB942A3f2e9F54982F901ffb2A863BE3985b118ED` | [View](https://etherscan.io/address/0xB942A3f2e9F54982F901ffb2A863BE3985b118ED) |
| Cross-chain Burn | v1 | Sepolia | `0xB942A3f2e9F54982F901ffb2A863BE3985b118ED` | [View](https://sepolia.etherscan.io/address/0xB942A3f2e9F54982F901ffb2A863BE3985b118ED) |
| Cross-chain Burn | v1 | Optimism | `0xB942A3f2e9F54982F901ffb2A863BE3985b118ED` | [View](https://optimistic.etherscan.io/address/0xB942A3f2e9F54982F901ffb2A863BE3985b118ED) |
| Cross-chain Burn | v1 | Base | `0xB942A3f2e9F54982F901ffb2A863BE3985b118ED` | [View](https://basescan.org/address/0xB942A3f2e9F54982F901ffb2A863BE3985b118ED) |
| Cross-chain Burn | v1 | Shape | `0xB942A3f2e9F54982F901ffb2A863BE3985b118ED` | [View](https://explorer.shape.network/address/0xB942A3f2e9F54982F901ffb2A863BE3985b118ED) |
| Cross-chain Burn | v1 | Apechain | `0xB942A3f2e9F54982F901ffb2A863BE3985b118ED` | [View](https://apescan.io/address/0xB942A3f2e9F54982F901ffb2A863BE3985b118ED) |

### Mainnet-Specific Versions

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Burn Redeem ERC721 | v5 | Ethereum Mainnet | `0x53b59fb7906367c8d44b694a2f82fedd4911458c` | [View](https://etherscan.io/address/0x53b59fb7906367c8d44b694a2f82fedd4911458c) |
| Burn Redeem ERC721 | v3 | Ethereum Mainnet | `0x20847f61e494e72d55d32a542c519e27d229aedb` | [View](https://etherscan.io/address/0x20847f61e494e72d55d32a542c519e27d229aedb) |
| Burn Redeem ERC1155 | v3.1 | Ethereum Mainnet | `0xd391032fec8877953c51399c7c77fbcc93ee3e2a` | [View](https://etherscan.io/address/0xd391032fec8877953c51399c7c77fbcc93ee3e2a) |
| Burn Redeem ERC1155 | v3 | Ethereum Mainnet | `0xde659726cfd166aca4867994d396efef386ead68` | [View](https://etherscan.io/address/0xde659726cfd166aca4867994d396efef386ead68) |
| Burn Redeem ERC721 | v2 | Ethereum Mainnet | `0x23a553a150ab2f5f88c01c0449b672d9f7efeb36` | [View](https://etherscan.io/address/0x23a553a150ab2f5f88c01c0449b672d9f7efeb36) |
| Burn Redeem ERC1155 | v2 | Ethereum Mainnet | `0xfa1b15df09c2944a91a2f9f10a6133090d4119bd` | [View](https://etherscan.io/address/0xfa1b15df09c2944a91a2f9f10a6133090d4119bd) |
| Burn Redeem ERC1155 | v1 | Ethereum Mainnet | `0xa4fb4bfbd70ae8c81ece9e0fcceffa9953e120cb` | [View](https://etherscan.io/address/0xa4fb4bfbd70ae8c81ece9e0fcceffa9953e120cb) |

## Special Extensions

### Gacha (Serendipity)

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| ERC1155 Gacha | v2 | Ethereum Mainnet | `0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d` | [View](https://etherscan.io/address/0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d) |
| ERC1155 Gacha | v2 | Sepolia | `0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d` | [View](https://sepolia.etherscan.io/address/0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d) |
| ERC1155 Gacha | v2 | Optimism | `0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d` | [View](https://optimistic.etherscan.io/address/0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d) |
| ERC1155 Gacha | v2 | Base | `0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d` | [View](https://basescan.org/address/0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d) |
| ERC1155 Gacha | v2 | Shape | `0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d` | [View](https://explorer.shape.network/address/0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d) |
| ERC1155 Gacha | v2 | Apechain | `0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d` | [View](https://apescan.io/address/0x40AE3553a2dBBE463F84dA97BdA5607cfD03B40d) |
| ERC1155 Gacha | v1 | Ethereum Mainnet | `0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e` | [View](https://etherscan.io/address/0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e) |
| ERC1155 Gacha | v1 | Sepolia | `0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e` | [View](https://sepolia.etherscan.io/address/0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e) |
| ERC1155 Gacha | v1 | Optimism | `0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e` | [View](https://optimistic.etherscan.io/address/0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e) |
| ERC1155 Gacha | v1 | Base | `0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e` | [View](https://basescan.org/address/0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e) |
| ERC1155 Gacha | v1 | Shape | `0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e` | [View](https://explorer.shape.network/address/0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e) |
| ERC1155 Gacha | v1 | Apechain | `0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e` | [View](https://apescan.io/address/0x53C37ccC1C48f63BD35FFc93952d0880d7529b9e) |

### Physical Claims

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Physical Claim GA | v1 | Ethereum Mainnet | `0xDD4013A64ca6b99CF4C976F76d85C1946134496E` | [View](https://etherscan.io/address/0xDD4013A64ca6b99CF4C976F76d85C1946134496E) |
| Physical Claim GA | v1 | Sepolia | `0xDD4013A64ca6b99CF4C976F76d85C1946134496E` | [View](https://sepolia.etherscan.io/address/0xDD4013A64ca6b99CF4C976F76d85C1946134496E) |
| Physical Claim GA | v1 | Optimism | `0xDD4013A64ca6b99CF4C976F76d85C1946134496E` | [View](https://optimistic.etherscan.io/address/0xDD4013A64ca6b99CF4C976F76d85C1946134496E) |
| Physical Claim GA | v1 | Base | `0xDD4013A64ca6b99CF4C976F76d85C1946134496E` | [View](https://basescan.org/address/0xDD4013A64ca6b99CF4C976F76d85C1946134496E) |
| Physical Claim GA | v1 | Shape | `0xDD4013A64ca6b99CF4C976F76d85C1946134496E` | [View](https://explorer.shape.network/address/0xDD4013A64ca6b99CF4C976F76d85C1946134496E) |
| Physical Claim GA | v1 | Apechain | `0xDD4013A64ca6b99CF4C976F76d85C1946134496E` | [View](https://apescan.io/address/0xDD4013A64ca6b99CF4C976F76d85C1946134496E) |
| Physical Claims | - | Optimism | `0xba8b5776ec3124c74883dbf202a2143ec4393764` | [View](https://optimistic.etherscan.io/address/0xba8b5776ec3124c74883dbf202a2143ec4393764) |

### Frame Claims

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Frame Lazy Claim ERC1155 | v4 | Ethereum Mainnet | `0x078A559090D5e4342f11f194864da091628a7C86` | [View](https://etherscan.io/address/0x078A559090D5e4342f11f194864da091628a7C86) |
| Frame Lazy Claim ERC1155 | v4 | Sepolia | `0x078A559090D5e4342f11f194864da091628a7C86` | [View](https://sepolia.etherscan.io/address/0x078A559090D5e4342f11f194864da091628a7C86) |
| Frame Lazy Claim ERC1155 | v4 | Optimism | `0x078A559090D5e4342f11f194864da091628a7C86` | [View](https://optimistic.etherscan.io/address/0x078A559090D5e4342f11f194864da091628a7C86) |
| Frame Lazy Claim ERC1155 | v4 | Base | `0x078A559090D5e4342f11f194864da091628a7C86` | [View](https://basescan.org/address/0x078A559090D5e4342f11f194864da091628a7C86) |
| Frame Lazy Claim ERC1155 | v4 | Shape | `0x078A559090D5e4342f11f194864da091628a7C86` | [View](https://explorer.shape.network/address/0x078A559090D5e4342f11f194864da091628a7C86) |
| Frame Lazy Claim ERC1155 | v4 | Apechain | `0x078A559090D5e4342f11f194864da091628a7C86` | [View](https://apescan.io/address/0x078A559090D5e4342f11f194864da091628a7C86) |
| Frame Lazy Claim ERC1155 | v3 | Ethereum Mainnet | `0xBCE51276c44FF6c53D6597C11d432c1194C00B22` | [View](https://etherscan.io/address/0xBCE51276c44FF6c53D6597C11d432c1194C00B22) |
| Frame Lazy Claim ERC1155 | v3 | Sepolia | `0xBCE51276c44FF6c53D6597C11d432c1194C00B22` | [View](https://sepolia.etherscan.io/address/0xBCE51276c44FF6c53D6597C11d432c1194C00B22) |
| Frame Lazy Claim ERC1155 | v3 | Optimism | `0xBCE51276c44FF6c53D6597C11d432c1194C00B22` | [View](https://optimistic.etherscan.io/address/0xBCE51276c44FF6c53D6597C11d432c1194C00B22) |
| Frame Lazy Claim ERC1155 | v3 | Base | `0xBCE51276c44FF6c53D6597C11d432c1194C00B22` | [View](https://basescan.org/address/0xBCE51276c44FF6c53D6597C11d432c1194C00B22) |
| Frame Lazy Claim ERC1155 | v3 | Shape | `0xBCE51276c44FF6c53D6597C11d432c1194C00B22` | [View](https://explorer.shape.network/address/0xBCE51276c44FF6c53D6597C11d432c1194C00B22) |
| Frame Lazy Claim ERC1155 | v3 | Apechain | `0xBCE51276c44FF6c53D6597C11d432c1194C00B22` | [View](https://apescan.io/address/0xBCE51276c44FF6c53D6597C11d432c1194C00B22) |
| Frame Lazy Claim ERC1155 | v2 | Ethereum Mainnet | `0xce407bF636a0cf78B5A77e2953CaB505f2956f26` | [View](https://etherscan.io/address/0xce407bF636a0cf78B5A77e2953CaB505f2956f26) |
| Frame Lazy Claim ERC1155 | v2 | Sepolia | `0xce407bF636a0cf78B5A77e2953CaB505f2956f26` | [View](https://sepolia.etherscan.io/address/0xce407bF636a0cf78B5A77e2953CaB505f2956f26) |
| Frame Lazy Claim ERC1155 | v2 | Optimism | `0xce407bF636a0cf78B5A77e2953CaB505f2956f26` | [View](https://optimistic.etherscan.io/address/0xce407bF636a0cf78B5A77e2953CaB505f2956f26) |
| Frame Lazy Claim ERC1155 | v2 | Base | `0xce407bF636a0cf78B5A77e2953CaB505f2956f26` | [View](https://basescan.org/address/0xce407bF636a0cf78B5A77e2953CaB505f2956f26) |
| Frame Lazy Claim ERC1155 | v2 | Shape | `0xce407bF636a0cf78B5A77e2953CaB505f2956f26` | [View](https://explorer.shape.network/address/0xce407bF636a0cf78B5A77e2953CaB505f2956f26) |
| Frame Lazy Claim ERC1155 | v2 | Apechain | `0xce407bF636a0cf78B5A77e2953CaB505f2956f26` | [View](https://apescan.io/address/0xce407bF636a0cf78B5A77e2953CaB505f2956f26) |
| Frame Lazy Claim ERC1155 | v1 | Ethereum Mainnet | `0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f` | [View](https://etherscan.io/address/0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f) |
| Frame Lazy Claim ERC1155 | v1 | Sepolia | `0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f` | [View](https://sepolia.etherscan.io/address/0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f) |
| Frame Lazy Claim ERC1155 | v1 | Optimism | `0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f` | [View](https://optimistic.etherscan.io/address/0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f) |
| Frame Lazy Claim ERC1155 | v1 | Base | `0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f` | [View](https://basescan.org/address/0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f) |
| Frame Lazy Claim ERC1155 | v1 | Shape | `0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f` | [View](https://explorer.shape.network/address/0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f) |
| Frame Lazy Claim ERC1155 | v1 | Apechain | `0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f` | [View](https://apescan.io/address/0x9E1CB71b68B5933488918e6fB7fC6EeA3FF8CE9f) |
| Frame Paymaster | - | Ethereum Mainnet | `0xAD45e959705E018875607C050e9D903e41E417C9` | [View](https://etherscan.io/address/0xAD45e959705E018875607C050e9D903e41E417C9) |
| Frame Paymaster | - | Sepolia | `0xAD45e959705E018875607C050e9D903e41E417C9` | [View](https://sepolia.etherscan.io/address/0xAD45e959705E018875607C050e9D903e41E417C9) |
| Frame Paymaster | - | Optimism | `0xAD45e959705E018875607C050e9D903e41E417C9` | [View](https://optimistic.etherscan.io/address/0xAD45e959705E018875607C050e9D903e41E417C9) |
| Frame Paymaster | - | Base | `0xAD45e959705E018875607C050e9D903e41E417C9` | [View](https://basescan.org/address/0xAD45e959705E018875607C050e9D903e41E417C9) |
| Frame Paymaster | - | Shape | `0xAD45e959705E018875607C050e9D903e41E417C9` | [View](https://explorer.shape.network/address/0xAD45e959705E018875607C050e9D903e41E417C9) |
| Frame Paymaster | - | Apechain | `0xAD45e959705E018875607C050e9D903e41E417C9` | [View](https://apescan.io/address/0xAD45e959705E018875607C050e9D903e41E417C9) |

### Other Special Extensions

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Artist Proof Beta | - | Ethereum Mainnet | `0xF6B73A9f684740E6fDA95487d11cd789965a807d` | [View](https://etherscan.io/address/0xF6B73A9f684740E6fDA95487d11cd789965a807d) |
| Artist Proof Beta | - | Sepolia | `0xF6B73A9f684740E6fDA95487d11cd789965a807d` | [View](https://sepolia.etherscan.io/address/0xF6B73A9f684740E6fDA95487d11cd789965a807d) |
| Artist Proof Beta | - | Optimism | `0xF6B73A9f684740E6fDA95487d11cd789965a807d` | [View](https://optimistic.etherscan.io/address/0xF6B73A9f684740E6fDA95487d11cd789965a807d) |
| Artist Proof Beta | - | Base | `0xF6B73A9f684740E6fDA95487d11cd789965a807d` | [View](https://basescan.org/address/0xF6B73A9f684740E6fDA95487d11cd789965a807d) |
| Artist Proof Beta | - | Shape | `0xF6B73A9f684740E6fDA95487d11cd789965a807d` | [View](https://explorer.shape.network/address/0xF6B73A9f684740E6fDA95487d11cd789965a807d) |
| Artist Proof Beta | - | Apechain | `0xF6B73A9f684740E6fDA95487d11cd789965a807d` | [View](https://apescan.io/address/0xF6B73A9f684740E6fDA95487d11cd789965a807d) |
| Airdrop Verifier | - | Ethereum Mainnet | `0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7` | [View](https://etherscan.io/address/0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7) |
| Airdrop Verifier | - | Sepolia | `0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7` | [View](https://sepolia.etherscan.io/address/0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7) |
| Airdrop Verifier | - | Optimism | `0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7` | [View](https://optimistic.etherscan.io/address/0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7) |
| Airdrop Verifier | - | Base | `0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7` | [View](https://basescan.org/address/0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7) |
| Airdrop Verifier | - | Shape | `0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7` | [View](https://explorer.shape.network/address/0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7) |
| Airdrop Verifier | - | Apechain | `0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7` | [View](https://apescan.io/address/0x65a9e36BA55AE6e2Ee80502cEBA62d6741857AB7) |
| Airdrop Verifier | - | Ethereum Mainnet | `0x65a9e36ba55ae6e2ee80502ceba62d6741857ab7` | [View](https://etherscan.io/address/0x65a9e36ba55ae6e2ee80502ceba62d6741857ab7) |
| ERC721 Mint Guard | - | Ethereum Mainnet | `0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9` | [View](https://etherscan.io/address/0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9) |
| ERC721 Mint Guard | - | Sepolia | `0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9` | [View](https://sepolia.etherscan.io/address/0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9) |
| ERC721 Mint Guard | - | Optimism | `0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9` | [View](https://optimistic.etherscan.io/address/0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9) |
| ERC721 Mint Guard | - | Base | `0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9` | [View](https://basescan.org/address/0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9) |
| ERC721 Mint Guard | - | Shape | `0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9` | [View](https://explorer.shape.network/address/0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9) |
| ERC721 Mint Guard | - | Apechain | `0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9` | [View](https://apescan.io/address/0x7946a4bc596E0172c4F7fCc5a1Da3a019eF85eB9) |
| ERC1155 Mint Guard | - | Ethereum Mainnet | `0xBCEabf7B3c7b784589afB411802c7C050c4dfC00` | [View](https://etherscan.io/address/0xBCEabf7B3c7b784589afB411802c7C050c4dfC00) |
| ERC1155 Mint Guard | - | Sepolia | `0xBCEabf7B3c7b784589afB411802c7C050c4dfC00` | [View](https://sepolia.etherscan.io/address/0xBCEabf7B3c7b784589afB411802c7C050c4dfC00) |
| ERC1155 Mint Guard | - | Optimism | `0xBCEabf7B3c7b784589afB411802c7C050c4dfC00` | [View](https://optimistic.etherscan.io/address/0xBCEabf7B3c7b784589afB411802c7C050c4dfC00) |
| ERC1155 Mint Guard | - | Base | `0xBCEabf7B3c7b784589afB411802c7C050c4dfC00` | [View](https://basescan.org/address/0xBCEabf7B3c7b784589afB411802c7C050c4dfC00) |
| ERC1155 Mint Guard | - | Shape | `0xBCEabf7B3c7b784589afB411802c7C050c4dfC00` | [View](https://explorer.shape.network/address/0xBCEabf7B3c7b784589afB411802c7C050c4dfC00) |
| ERC1155 Mint Guard | - | Apechain | `0xBCEabf7B3c7b784589afB411802c7C050c4dfC00` | [View](https://apescan.io/address/0xBCEabf7B3c7b784589afB411802c7C050c4dfC00) |

## Infrastructure Contracts

### Operator Filterer

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Operator Filterer | - | Ethereum Mainnet | `0x3e31cb740351d8650b36e8ece95a8efcd1fc28c2` | [View](https://etherscan.io/address/0x3e31cb740351d8650b36e8ece95a8efcd1fc28c2) |

### Optimism Specific

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Optimism Refund Shim | - | Optimism | `0x28a72d7e0f1fab1d78f3c4cdd7880c3b01b8a519` | [View](https://optimistic.etherscan.io/address/0x28a72d7e0f1fab1d78f3c4cdd7880c3b01b8a519) |

## Delegation Registry

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Delegation Registry | v2 | Ethereum Mainnet | `0x00000000000000447e69651d841bD8D104Bed493` | [View](https://etherscan.io/address/0x00000000000000447e69651d841bD8D104Bed493) |
| Delegation Registry | v2 | Sepolia | `0x00000000000000447e69651d841bD8D104Bed493` | [View](https://sepolia.etherscan.io/address/0x00000000000000447e69651d841bD8D104Bed493) |
| Delegation Registry | v2 | Optimism | `0x00000000000000447e69651d841bD8D104Bed493` | [View](https://optimistic.etherscan.io/address/0x00000000000000447e69651d841bD8D104Bed493) |
| Delegation Registry | v2 | Base | `0x00000000000000447e69651d841bD8D104Bed493` | [View](https://basescan.org/address/0x00000000000000447e69651d841bD8D104Bed493) |
| Delegation Registry | v2 | Shape | `0x00000000000000447e69651d841bD8D104Bed493` | [View](https://explorer.shape.network/address/0x00000000000000447e69651d841bD8D104Bed493) |
| Delegation Registry | v2 | Apechain | `0x00000000000000447e69651d841bD8D104Bed493` | [View](https://apescan.io/address/0x00000000000000447e69651d841bD8D104Bed493) |
| Delegation Registry | v1 | Ethereum Mainnet | `0x00000000000076A84feF008CDAbe6409d2FE638B` | [View](https://etherscan.io/address/0x00000000000076A84feF008CDAbe6409d2FE638B) |
| Delegation Registry | v1 | Sepolia | `0x00000000000076A84feF008CDAbe6409d2FE638B` | [View](https://sepolia.etherscan.io/address/0x00000000000076A84feF008CDAbe6409d2FE638B) |
| Delegation Registry | v1 | Optimism | `0x00000000000076A84feF008CDAbe6409d2FE638B` | [View](https://optimistic.etherscan.io/address/0x00000000000076A84feF008CDAbe6409d2FE638B) |
| Delegation Registry | v1 | Base | `0x00000000000076A84feF008CDAbe6409d2FE638B` | [View](https://basescan.org/address/0x00000000000076A84feF008CDAbe6409d2FE638B) |
| Delegation Registry | v1 | Shape | `0x00000000000076A84feF008CDAbe6409d2FE638B` | [View](https://explorer.shape.network/address/0x00000000000076A84feF008CDAbe6409d2FE638B) |
| Delegation Registry | v1 | Apechain | `0x00000000000076A84feF008CDAbe6409d2FE638B` | [View](https://apescan.io/address/0x00000000000076A84feF008CDAbe6409d2FE638B) |

## Royalty System

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| Royalty Registry | - | Ethereum Mainnet | `0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA` | [View](https://etherscan.io/address/0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA) |
| Royalty Registry | - | Sepolia | `0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA` | [View](https://sepolia.etherscan.io/address/0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA) |
| Royalty Registry | - | Optimism | `0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA` | [View](https://optimistic.etherscan.io/address/0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA) |
| Royalty Registry | - | Base | `0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA` | [View](https://basescan.org/address/0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA) |
| Royalty Registry | - | Shape | `0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA` | [View](https://explorer.shape.network/address/0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA) |
| Royalty Registry | - | Apechain | `0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA` | [View](https://apescan.io/address/0x3D1151Dc590ebF5C04501a7d4E1f8921546774eA) |
| Royalty Engine | - | Ethereum Mainnet | `0xEf770dFb6D5620977213f55f99bfd781D04BBE15` | [View](https://etherscan.io/address/0xEf770dFb6D5620977213f55f99bfd781D04BBE15) |
| Royalty Engine | - | Sepolia | `0xEf770dFb6D5620977213f55f99bfd781D04BBE15` | [View](https://sepolia.etherscan.io/address/0xEf770dFb6D5620977213f55f99bfd781D04BBE15) |
| Royalty Engine | - | Optimism | `0xEf770dFb6D5620977213f55f99bfd781D04BBE15` | [View](https://optimistic.etherscan.io/address/0xEf770dFb6D5620977213f55f99bfd781D04BBE15) |
| Royalty Engine | - | Base | `0xEf770dFb6D5620977213f55f99bfd781D04BBE15` | [View](https://basescan.org/address/0xEf770dFb6D5620977213f55f99bfd781D04BBE15) |
| Royalty Engine | - | Shape | `0xEf770dFb6D5620977213f55f99bfd781D04BBE15` | [View](https://explorer.shape.network/address/0xEf770dFb6D5620977213f55f99bfd781D04BBE15) |
| Royalty Engine | - | Apechain | `0xEf770dFb6D5620977213f55f99bfd781D04BBE15` | [View](https://apescan.io/address/0xEf770dFb6D5620977213f55f99bfd781D04BBE15) |
| Royalty Registry | - | Ethereum Mainnet | `0xad2184fb5dbcfc05d8f056542fb25b04fa32a95d` | [View](https://etherscan.io/address/0xad2184fb5dbcfc05d8f056542fb25b04fa32a95d) |
| Royalty Engine | - | Ethereum Mainnet | `0x0385603ab55642cb4dd5de3ae9e306809991804f` | [View](https://etherscan.io/address/0x0385603ab55642cb4dd5de3ae9e306809991804f) |

## Supported ERC20 Tokens

These ERC20 tokens are supported as payment methods in Manifold Claim extensions on **Ethereum Mainnet**:

| Contract | Version | Network | Address | Explorer |
|----------|---------|---------|---------|----------|
| USD Coin (USDC) | - | Ethereum Mainnet | `0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48` | [View](https://etherscan.io/address/0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48) |
| Tether USD (USDT) | - | Ethereum Mainnet | `0xdAC17F958D2ee523a2206206994597C13D831ec7` | [View](https://etherscan.io/address/0xdAC17F958D2ee523a2206206994597C13D831ec7) |
| Dai Stablecoin (DAI) | - | Ethereum Mainnet | `0x6B175474E89094C44Da98b954EedeAC495271d0F` | [View](https://etherscan.io/address/0x6B175474E89094C44Da98b954EedeAC495271d0F) |
| Wrapped Ether (WETH) | - | Ethereum Mainnet | `0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2` | [View](https://etherscan.io/address/0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2) |
| ApeCoin (APE) | - | Ethereum Mainnet | `0x4d224452801ACEd8B2F0aebE155379bb5D594381` | [View](https://etherscan.io/address/0x4d224452801ACEd8B2F0aebE155379bb5D594381) |
| LooksRare (LOOKS) | - | Ethereum Mainnet | `0xf4d2888d29D722226FafA5d9B24F9164c092421E` | [View](https://etherscan.io/address/0xf4d2888d29D722226FafA5d9B24F9164c092421E) |
| SuperRare (RARE) | - | Ethereum Mainnet | `0xba5BDe662c17e2aDFF1075610382B9B691296350` | [View](https://etherscan.io/address/0xba5BDe662c17e2aDFF1075610382B9B691296350) |
| Art Gobblers Goo (GOO) | - | Ethereum Mainnet | `0x600000000a36F3cD48407e35eB7C5c910dc1f7a8` | [View](https://etherscan.io/address/0x600000000a36F3cD48407e35eB7C5c910dc1f7a8) |
| Ash (ASH) | - | Ethereum Mainnet | `0x64D91f12Ece7362F91A6f8E7940Cd55F05060b92` | [View](https://etherscan.io/address/0x64D91f12Ece7362F91A6f8E7940Cd55F05060b92) |
| IYKYK (IYKYK) | - | Ethereum Mainnet | `0x7CB683151a83C2b10A30Cbb003CDA9996228A2Ba` | [View](https://etherscan.io/address/0x7CB683151a83C2b10A30Cbb003CDA9996228A2Ba) |
| Pepe (PEPE) | - | Ethereum Mainnet | `0x6982508145454Ce325dDbE47a25d4ec3d2311933` | [View](https://etherscan.io/address/0x6982508145454Ce325dDbE47a25d4ec3d2311933) |
| Turbo (TURBO) | - | Ethereum Mainnet | `0xA35923162C49cF95e6BF26623385eb431ad920D3` | [View](https://etherscan.io/address/0xA35923162C49cF95e6BF26623385eb431ad920D3) |

## Deprecated Contracts

These contracts are no longer actively used but are maintained for historical reference. See version history in sections above for older contract versions.

## Contributing

To report incorrect addresses or request updates, please:
1. Open an issue in the [Manifold GitHub repository](https://github.com/manifoldxyz)
2. Contact the Manifold team directly
3. Submit a pull request with corrections

---

*Last Updated: November 2024*

*This document is maintained by Manifold and serves as the authoritative source for all Manifold contract addresses.*