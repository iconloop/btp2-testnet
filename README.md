# BTP2-TestNet


## Introduction
This document provides information on the BTP network connected to the ICON Berlin TestNet.

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
  * Havah : `0x3`
* StartHeight 
  * BSC : 9929680
  * Eth2 : 10349992
  * Havah : 8582402

### Contract
| Contract  | Address |                   Note                    |
|:----------|:-------:|:-----------------------------------------:|
| BMC       |   cxf1b0808f09138fffdb890772315aeabb37072a8a   |                                           |
| BSC BMV   |   cx6810e0a7d6c0bc53eef006c221dcd731c8903a95   |                Bridge Mode                |
| Eth2 BMV  |   cxdd91f194673553097745f33dd464a39740075735   |   Trustless Mode<br /> Supports Capella   |
| Havah BMV |   cxd1bd0add3c7707fa875bf5370da46875365f44cf   |              Trustless Mode               |
| XCALL     |   cxf4958b242a264fc11d7d8d95f79035e35b21c1bb   |                                           |
| Demo DAPP |   cx92283a47a95164bd3d604da08128886125593545   |                                           |


## BSC TestNet TestNet

### Domain
* RPC URL : `https://data-seed-prebsc-1-s1.binance.org:8545`
* Network : `0x61.bsc`
* StartHeight : 31022641

### Contract
| Contract | Address | Note |
|:---------|:-------:|:----:|
| BMCM     |   0x41CD95F16f9bbF2bEB5479C00CF249A8b0A076bF   |      |
| BMCS     |   0xCC98F0736ec2ef32B8A64251BB89aF14E27043b6   |      |
| BMC      |   0x9Fd9e050682A8795dEa6eE70870A82a513d390Ac   |      |
| BMV      |   0x0a42d5c21EF16aec1c31c4511EdCaA9648a9538C   |   Trustless Mode  |
| XCALL    |   0x908169ab780de828dCd014Dd9f3768BB65C46e37   |      |
| Demo DAPP   |   0xA77a7545Fb4e35bDB0D96144c0e771305Dc3D7fB   |      |


## ETH2 Sepolia TestNet

### Relay
* Repository URL : [BTP2-eth2 Repository](https://github.com/icon-project/btp2-eth2)

### Domain
* RPC URL : `https://sepolia.infura.io/v3/ffbf8ebe228f4758ae82e175640275e0`
* Network : `0xaa36a7.eth2`
* StartHeight : 3813345

### Contract
| Contract | Address | Note |
|:---------|:-------:|:----:|
| BMCM     |   0x9fb595461023f9A920B276A4b289972c4aFF114F   |      |
| BMCS     |   0xEe94cBA4C4d138fb4de1F4bcfA1CEeF062eE8251   |      |
| BMC      |   0xE602326106f5E1d436a3CCEB2A408759925f81ff   |      |
| BMV      |   0x1592F432Dde573341BaFe14d5FAbe4A299b2E721   | Trustless Mode |
| XCALL    |   0xfA23ED949E7c942C28eB730aAd979C3702101B11   |      |
| Demo DAPP   |   0xEB556AC6Ab28110914CCdb2c991Da369972195f3   |      |


## HAVAH TestNet

### Domain
* RPC URL : `https://ctz.altair.havah.io/api/v3/icon_dex`
* Network : `0x111.icon`
* BTP NetworkId :
  * Berlin : `0x3`
* StartHeight
  * Berlin : 1296519

### Contract
| Contract  | Address |                   Note                    |
|:----------|:-------:|:-----------------------------------------:|
| BMC       |   cx683a92f72cc2fe9a7a617019a8d6fcba6b6c06b7   |                                           |
| BMV |   cx8737236f65ef6d41ac33b328bc758e8663366caa   |              Trustless Mode               |
| XCALL     |   cx05b5f4e2cb80827d4b53d13549041c66442f327d   |                                           |
| Demo DAPP |   cxd1531ebfc81cb890810bc0e5603c1e27046174e3   |                                           |
