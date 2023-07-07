# BTP2-TestNet


## Introduction
This document provides information on the BTP network connected to the ICON Berlin TestNet.

* [BTP2 Network Status Monitor](https://testnet.btp2.24x365.online/)

## Relay
* Repository URL : [BTP2 Repository](https://github.com/icon-project/btp2/tree/v1.0.2)
* Version : v1.0.2
## ICON Berlin TestNet

### Domain
* RPC URL : `https://berlin.net.solidwallet.io/api/v3/icon_dex`
* Network : `0x7.icon`
* BTP NetworkId : 
  * BSC : `0x4`
  * Eth2 : `0x6`
  * Havah : `0x7`
* StartHeight 
  * BSC : 9929680
  * Eth2 : 10349992
  * Havah : 10361781

### Contract
| Contract  | Address |                   Note                    |
|:----------|:-------:|:-----------------------------------------:|
| BMC       |   cxf1b0808f09138fffdb890772315aeabb37072a8a   |                                           |
| BSC BMV   |   cx6810e0a7d6c0bc53eef006c221dcd731c8903a95   |                Bridge Mode                |
| Eth2 BMV  |   cxdd91f194673553097745f33dd464a39740075735   |   Trustless Mode<br /> Supports Capella   |
| Havah BMV |   cx90b6dca89aa45388b24a6c158eb9d21d51263037   |              Trustless Mode               |
| XCALL     |   cxf4958b242a264fc11d7d8d95f79035e35b21c1bb   |                                           |
| Demo DAPP |   cx92283a47a95164bd3d604da08128886125593545   |                                           |


## BSC TestNet TestNet

### Domain
* RPC URL : `https://data-seed-prebsc-1-s1.binance.org:8545`
* Network : `0x61.bsc`
* StartHeight : 31022641

### Contract
| Contract  | Address | Note |
|:----------|:-------:|:----:|
| BMCM      |   0x41CD95F16f9bbF2bEB5479C00CF249A8b0A076bF   |      |
| BMCS      |   0xCC98F0736ec2ef32B8A64251BB89aF14E27043b6   |      |
| BMC       |   0x9Fd9e050682A8795dEa6eE70870A82a513d390Ac   |      |
| BMCP      |   0x8E3eb11031b6316C2A8e85040ecb204040Dc2A69   |      |
| BMV       |   0x0a42d5c21EF16aec1c31c4511EdCaA9648a9538C   |   Trustless Mode  |
| XCALL     |   0x5Ebb7aCB7bCaf7C1ADeFcF9660D39AC07d432904   |      |
| Demo DAPP |   0x4EaC1CDBE8131de10FE1AE969397d02d47D21082   |      |


## ETH2 Sepolia TestNet

### Relay
* Repository URL : [BTP2-eth2 Repository](https://github.com/icon-project/btp2-eth2)

### Domain
* RPC URL : `https://sepolia.infura.io/v3/ffbf8ebe228f4758ae82e175640275e0`
* Network : `0xaa36a7.eth2`
* StartHeight : 3813345

### Contract
| Contract  | Address | Note |
|:----------|:-------:|:----:|
| BMCM      |   0x9fb595461023f9A920B276A4b289972c4aFF114F   |      |
| BMCS      |   0xEe94cBA4C4d138fb4de1F4bcfA1CEeF062eE8251   |      |
| BMC       |   0xE602326106f5E1d436a3CCEB2A408759925f81ff   |      |
| BMCP      |   0x23810745feC53c8D80E9A3E30508458E408d3EB7   |      |
| BMV       |   0x1592F432Dde573341BaFe14d5FAbe4A299b2E721   | Trustless Mode |
| XCALL     |   0x694C1f5Fb4b81e730428490a1cE3dE6e32428637   |      |
| Demo DAPP |   0x597F73bfb3124B6145151E7a8A30b781C41FF2B0   |      |


## HAVAH TestNet

### Domain
* RPC URL : `https://ctz.altair.havah.io/api/v3/icon_dex`
* Network : `0x111.icon`
* BTP NetworkId :
  * Berlin : `0x1`
* StartHeight
  * Berlin : 9443

### Contract
| Contract  | Address |                   Note                    |
|:----------|:-------:|:-----------------------------------------:|
| BMC       |   cxf36efc770627067c41949a16688a0246ea6428e8   |                                           |
| BMV |   cx90f9d84e0b757ba02599fabcbda30e46105cb89c   |              Trustless Mode               |
| XCALL     |   cxce3a72cc1defaf07b23e05b595840c00d5a80b0c   |                                           |
| Demo DAPP |   cxc9f0ba03c4a39a43c5dc0a5ae5d2d1327a065d62   |                                           |
