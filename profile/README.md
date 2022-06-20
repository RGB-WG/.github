RGB is a system of private & scalable client-validated smart contracts on Bitcoin & Lightning developed 
by [LNP/BP Standards Association](https://lnp-bp/org). You can read more about GRGB on 
[FAQ website](https://rgbfaq.com) and in [Technical Blueprint](https://rgb.network).

- Standards defining RGB are part of [LNPBP standards](https://github.com/LNP-BP/LNPBPs)
- Reference implementation of consensus/validation code is [RGB Core Lib](/RGB-WG/rgb-core)
- High-level API to RGB contracts is provided by [RGB Standard Lib](/RGB-WG/rgb-std)
- To run RGB, you can use [RGB Node](/RGB-WG/rgb-node), which is integratable with lightning
  [LNP Node](/LNP-WG/lnp-node). Alternatively, you can use [MyCitadel Node](/mycitadel/mycitadel-node),
  which already contains lightning, wallet functionality and decentralized storage integrated.
- To use RGB fungible assets (RGB20) developers working directly with RGB Node will need to
  use [RGB20 Lib](/RGB-WG/rust-rgb20) API for simplified processing of asset contracts.
- RGB uses [universal bitcoin invoices format][invoices], which is also can be used for 
  lightning and onchain bitcoin invoicing. The invoices can be created and parsed using 
  [LNP/BP invoice libraries](/LNP-BP/invoices).
  
  [invoices]: https://github.com/LNP-BP/presentations/blob/master/Presentation%20slides/Universal%20LNP-BP%20invoices.pdf
