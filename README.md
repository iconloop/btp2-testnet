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
  * Eth2 : `0x5`
  * Havah : `0x3`
* StartHeight 
  * BSC : 9929680
  * Eth2 : 6229184
  * Havah : 8582402

### Contract
| Contract  | Address |                   Note                    |
|:----------|:-------:|:-----------------------------------------:|
| BMC       |   cxf1b0808f09138fffdb890772315aeabb37072a8a   |                                           |
| BSC BMV   |   cx6810e0a7d6c0bc53eef006c221dcd731c8903a95   |                Bridge Mode                |
| Eth2 BMV  |   cx506970c5a98fce3a8b29a5a8436ed691e1fdbcda   |   Trustless Mode<br /> Supports Capella   |
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
* StartHeight : 3774860

### Contract
| Contract | Address | Note |
|:---------|:-------:|:----:|
| BMCM     |   0xee89840B024C570313D3540029A242c1b4E0E0A5   |      |
| BMCS     |   0xf04859b44Accae55D92510C4CC77F1dB41503DF5   |      |
| BMC      |   0xb31057dA7d24216E16e270e15CdbE537F472caEF   |      |
| BMV      |   0x73cCDBF447c8BbED10457A65F04DC4547d3071C1   | Trustless Mode |
| XCALL    |   0x232dd167F4141d4313C29b5ea264aa98f9c339d4   |      |
| Demo DAPP   |   0x52D0A13ABD0B949FF840de7F953545BBB9259A9c   |      |


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
