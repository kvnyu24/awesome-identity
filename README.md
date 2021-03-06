# Awesome Identity [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

This is a curated list of academic, engineering, and educational resources related to ***identity***, ***privacy***, and ***reputation***. It's audience includes researchers, developers, *enterprises*, investors, students, and anyone who's interested in these topics.

The highly *interoperable*, *composable*, and *user-owned* future of the Internet, around which "web3" is termed, is far away from maturity, despite large amounts of capital being poured into the space. In the meantime, *identity*, aside from blockchain tech, is emerging as a crucial new primitive that may eventually unlock the massive adoption of web3 applications (or as Jack Dorsey would like to term it, [web5](https://twitter.com/jack/status/1535314738078486533)). Since identities are centered around user behaviors, their *privacy* naturally becomes important. Similarly, a wide array of identity-based applications are built around user *reputation*, which measures and (sometimes) quantifies vanilla user behavior data.

With the above in mind, this repo keeps track of the latest academic research, project and framework development, and educational resources related to the field. We attempt to keep all the resources as approachable as possible by providing more context for them. For academic papers, it's recommended for additional explanatory resources like slides and videos to be added. In addition, I will gradually add in ***paper reading*** sections for listed papers for further explanation.

For contributions, please refer to [the contribution guidelines](https://github.com/kvnyu24/awesome-identity/blob/main/CONTRIBUTING.md).

# Identity

## IAM (Traditional)

### Papers

- **HIR-CP-ABE: Hierarchical Identity Revocable Ciphertext-Policy Attribute-Based Encryption for Secure and Flexible Data Sharing**   
  *Q. Dong, D. Huang, J. Luo*   
  Preprint, [eprint](https://eprint.iacr.org/2017/1101.pdf)
- **Privacy-preserving Identity Management System**   
  *J. Lee, J. Choi, H. Oh, et al.*   
  Preprint, [eprint](https://eprint.iacr.org/2021/1459.pdf)
- **Identity-Based Authenticated Asymmetric Group Key Agreement Protocol**   
  *L. Zhang, Q. Wu, B. Qin, et al.*   
  COCOON 2010, [eprint](https://eprint.iacr.org/2010/209.pdf)
- **Holistic Privacy-Preserving Identity Management System for the Internet of Things**   
*J. Bernabe, J. Ramos, A. Gomez*   
Mob. Inf. Syst. 2017, [hindawi](https://downloads.hindawi.com/journals/misy/2017/6384186.pdf)
- **Efficient Access Control of Sensitive Data Service in Outsourcing Scenarios**   
*Y. Zhang and J. Chen*   
Preprint, [eprint](https://eprint.iacr.org/2010/242.pdf)
- **A Framework for Secure Single Sign-On**   
*B. David, A. Nascimento, R. Tonicelli*   
Preprint, [eprint](https://eprint.iacr.org/2011/246.pdf)
- **Secure Decentralized Access Control Policy for Data Sharing in Smart Grid**   
*Y. Ye, L. Zhang, Y. Mu, et al.*   
INFOCOM 2021, [eprint](https://eprint.iacr.org/2020/1567.pdf)
- **Cross-Domain Identity-based Matchmaking Encryption**   
*A. Wu, J. Weng, W. Luo, et al.*   
Preprint, [eprint](https://eprint.iacr.org/2022/085.pdf)

### Projects

- [OpenId](https://openid.net/) allows user authentication based on relying parties (RP) with third-party identity provider services.  

## Decentralized Identity | Self-sovereign Identity

### Papers
- **Methods for Decentralized Identities: Evaluation and Insights**   
  *W. Fdhila, N. Stifter, K. Kostal, et al.*   
  BPM 2021, [eprint](https://eprint.iacr.org/2021/1087.pdf)
- **SIMS : Self Sovereign Identity Management System with Preserving Privacy in Blockchain**   
  *J. Lee, J. Hwang, J. Choi, et al.*   
  Preprint, [eprint](https://eprint.iacr.org/2019/1241.pdf)
- **CanDID: Can-Do Decentralized Identity with Legacy Compatibility, Sybil-Resistance, and Accountability**   
  *D. Maram, H. Malvai, F. Zhang, et al.*   
  SP 2021, [eprint](https://eprint.iacr.org/2020/934.pdf)
- **Decentralized Multi-authority Anonymous Authentication for Global Identities with Non-interactive Proofs**   
  *H. Anada*   
  BITS 2019, [eprint](https://eprint.iacr.org/2019/701.pdf)
- **A Decentralized Public Key Infrastructure with Identity Retention**   
  *C. Fromknecht, D. Velicanu, S. Yakoubov*   
  Preprint, [eprint](https://eprint.iacr.org/2014/803.pdf)
- **A Privacy-Preserving Distributed Identity Offline-First PoCP Blockchain Paradigm**   
  *A. Nassief*   
  Preprint, [eprint](https://eprint.iacr.org/2021/1186.pdf)
- **Decentralized Anonymous Credentials**   
  *C. Garman, M. Green, I. Miers*   
  NDSS 2014, [eprint](https://eprint.iacr.org/2013/622.pdf)
- **Studying Bitcoin Privacy Attacks and Their Impact on Bitcoin-Based Identity Methods**   
  *S. Ghesmati, W. Fdhila, Ed. Weippl*   
  BPM 2021, [Springer](https://link.springer.com/chapter/10.1007/978-3-030-85867-4_7)
  - [Research Summary](https://www.smartcontractresearch.org/t/research-summary-studying-bitcoin-privacy-attacks-and-their-impact-on-bitcoin-based-identity-methods/1790)

### Frameworks

- [**Sidetree Protocol**](https://identity.foundation/sidetree/spec/)  is a protocol for creating scalable *Decentralized Identifier networks* that can run atop any existing decentralized anchoring system (e.g. Bitcoin, Ethereum, distributed ledgers, witness-based approaches).
  - [GitHub](https://github.com/decentralized-identity/sidetree)
  - [REST API](https://identity.foundation/sidetree/api/)
  - [**Ion**](https://identity.foundation/ion/) is a permissionless DID network that implements Sidetree on top of Bitcoin
  - [**Sidetree Ethereuem**](https://github.com/decentralized-identity/sidetree-ethereum) is a REST API that supports anchoring of Sidetree Transactions to the Ethereum Blockchain

## Account-bound Tokens | Soulbound Tokens

### Interfaces

#### EIP4973

A standard interface for non-transferrable NFTs binding to an Ethereum account like a legendary World of Warcraft item binds to a character.

- [Discussion on Ethereum Forum](https://ethereum-magicians.org/t/eip-4973-account-bound-tokens/8825)
- [GitHub Submission](https://github.com/ethereum/EIPs/pull/4973)
- [Offical EIP Specification Document](https://eips.ethereum.org/EIPS/eip-4973)
- [Reference Implementation by Proposers](https://github.com/rugpullindex/ERC4973/)
- [Blog Post That Summarizes The Account-bound vs Soulbound Debates](https://timdaub.github.io/2022/05/30/what-are-account-bound-tokens/)
- [Core Contract Design Update Commit](https://github.com/rugpullindex/ERC4973/commit/27a62d1d61e4890542d941a7be7b314ab8e242d3)

#### Other Interfaces

- [ERC: Proxy standard #121](https://github.com/ethereum/EIPs/issues/121)
- [ERC: Claim Holder #735](https://github.com/ethereum/EIPs/issues/735)
- [ERC1238: Non-transferrable Non-Fungible Tokens (NTT) #1238](https://github.com/ethereum/EIPs/issues/1238)
- [Creates EIP-5114: Soulbound Token](https://github.com/ethereum/EIPs/pull/5114)
- [Add EIP-5192 - Minimal Soulbound NFTs #5192](https://github.com/ethereum/EIPs/pull/5192)

### Implementations
- [Sismo Protocol](https://www.sismo.io/): a modular Attestations Protocol focused on decentralization, privacy and usability.
  - [Sismo Protocol Contracts](https://github.com/sismo-core/sismo-protocol)
  - [Docs](https://docs.sismo.io/sismo-docs/)


## On-chain Key Management
### Social Recovery Wallets
- [Vitalik's Basic Explainer of Social Recovery Wallets](https://hackernoon.com/what-is-a-social-recovery-wallet) 
#### Implementations
- [Argent](https://www.argent.xyz/)
  - [Argent Recovery with Guardians](https://support.argent.xyz/hc/en-us/articles/360008828238)
- [Loopring Wallet](https://loopring.io/wallet#/)
  - [Loopring Interface to Assign Guardian](https://loopring.io/#/guardian)

---

# Privacy

## MPC-based Solutions
- **DECO: Liberating Web Data Using Decentralized Oracles for TLS**   
  *F. Zhang, D. Maram, H. Malvai*   
  CCS 2020, [arxiv](https://arxiv.org/pdf/1909.00938.pdf)
  - [Official Website](https://www.deco.works/)
  - [Ari Juels Presentation](https://www.youtube.com/watch?v=zWTx1iQOCDM)
  - [Chainlink Mixicles](https://assets.website-files.com/5f44d690acb168953e6181f6/5fa2f1616ac1b092226b3a86_mixicles.pdf)

### Basic MPC

- [The Awesome MPC Repo by *rdragos*](https://github.com/rdragos/awesome-mpc)
- [The Awesome Secure Computation Repo y *Jamie-Cui*](https://github.com/Jamie-Cui/awesome-secure-computation)

### General MPC Frameworks

- [Multi-Protocol SPDZ](https://github.com/data61/MP-SPDZ): Software to benchmark various SMPC protocols such as SPDZ, SPDZ2k, MASCOT, Overdrive, BMR garbled circuits, Yao's garbled circuits, and computation based on three-party replicated secret sharing as well as Shamir's secret sharing (with an honest majority).
- [Secretflow](https://github.com/secretflow/secretflow): SecretFlow is a unified framework for privacy-preserving data intelligence and machine learning


## ZKP-based Solutions
- **zkKYC in DeFi: An approach for implementing the zkKYC solution concept in Decentralized Finance**   
  *P. Pauwels, J. Pirovich, P. Braunz, et al.*   
  Preprint, [eprint](https://eprint.iacr.org/2022/321.pdf)

### Basic Zero-knowledge Proofs

- [The Awesome ZKP Repo by *matter-labs*](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
- [The Awesome ZK Repo by *ventali*](https://github.com/ventali/awesome-zk)
- [The Awesome ZKP Repo by *mattgstevens*](https://github.com/mattgstevens/awesome-zero-knowledge-proofs)
- [The Awesome ZKEVM Repo by *LuozhuZhang*](https://github.com/LuozhuZhang/Awesome-zkEVM)
- [The Awesome ZKP Starter Pack Repo by *paulrberg*](https://github.com/paulrberg/awesome-zkp-starter-pack)
- [The Awesome Plonk Repo by *fluidex*](https://github.com/fluidex/awesome-plonk)

## PSI-based Solutions

### PSI Frameworks

- [*OpenMined*'s PSI Implementation in Multiple Languages](https://github.com/OpenMined/PSI)
- [*encryptogroup*'s PSI Implementation in C++](https://github.com/encryptogroup/PSI)
- [*Microsoft*'s Asymmetric PSI Implementation in C++](https://github.com/microsoft/APSI)
- [*Google*'s Private Join and Compute Library in C](https://github.com/google/private-join-and-compute)

## TEE-based Solutions
- **Town Crier: An Authenticated Data Feed for Smart Contracts**   
  *F. Zhang, E. Cecchetti, K. Croman, et al.*   
  CCS 2016, [eprint](https://eprint.iacr.org/2016/168.pdf)
  - [Website](https://www.town-crier.org/)
  - [GitHub](https://github.com/bl4ck5un/Town-Crier)

## Secret Handshake 
- **Match Me if You Can: Matchmaking Encryption and its Applications**   
  *G. Ateniese, D. Francati, D. Nu??ez, et al.*   
  JOC 2021, [eprint](https://eprint.iacr.org/2018/1094.pdf)

---

# Reputation 
- **A Decentralized Anonymity-Preserving Reputation System with Constant-time Score Retrieval**   
  *R. Bazin, A. Schaub, O. Hasan et al.*   
  Preprint, [eprint](https://eprint.iacr.org/2016/416.pdf)


## Mechanism Design

### Quadratic Voting

- **Nash Equilbria for Quadratic Voting**   
  *S. Lalley, G. Weyl*   
  Preprint, [arXiv](https://arxiv.org/pdf/1409.0264)
- **Liberal Radicalism: A Flexible Design For Philanthropic Matching Funds**   
  *V. Buterin, Z.Hitzig, G. Weyl*   
  Preprint, [SSRN](https://deliverypdf.ssrn.com/delivery.php?ID=937027118025005094068064090066087002015011046006095011102005012125087125098070017112012063127057051019035114092110122081110087038047089019092071114001004018070001028055062004105115023115091071121015112123103094083127027026065065127020084070086093108105&EXT=pdf&INDEX=TRUE)
- **Implementation by Vote-Buying Mechanisms**   
  *J. Eguia, D. Xefteris*   
  Preprint, [SSRN](https://deliverypdf.ssrn.com/delivery.php?ID=037082122068091004075109079001098005123025053058021063112096087101085003024072084028096120057028116036040109026080009102007028039017049060086091116108080065100125126024083008073092094116107120001015080116064091074118107121070004087111118080115112101125&EXT=pdf&INDEX=TRUE)

### Negative Reputation

## Social Network Analysis

## Game System Design

---

# Other Educational Resources

## Cryptography

- [Awesome Cryptography by *sobolevn*](https://github.com/sobolevn/awesome-cryptography)
- [Collected Libraries & Packages about Cryptography in **Rust**](https://github.com/rust-cc/awesome-cryptography-rust)
- [The **Python** `cryptography` Library](https://github.com/pyca/cryptography)
- [The **Javascript** `crypto-js` Library](https://github.com/brix/crypto-js)
- [Supplementary Crypto Libraries in **Go**](https://github.com/golang/crypto)
- [Crypto++](https://www.cryptopp.com/)

## Compliance

- [Compliance Rank](https://compliancerank.com/)

### GDPR

- [Official Website](https://gdpr.eu/)
  - [What is GDPR](https://gdpr.eu/what-is-gdpr/)
  - [Checklist](https://gdpr.eu/checklist/)
- [GDPR Enforcement Tracker](https://www.enforcementtracker.com/)
- [GDPR Developer Guide](https://github.com/LINCnil/GDPR-Developer-Guide)

### CCPA

- [Official Legislation Document](https://oag.ca.gov/privacy/ccpa#:~:text=The%20California%20Consumer%20Privacy%20Act,how%20to%20implement%20the%20law.)
- [Technical Specifications to Support US Privacy Initiatives](https://github.com/InteractiveAdvertisingBureau/USPrivacy)