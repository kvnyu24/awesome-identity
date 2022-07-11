# Awesome Identity [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

This is a curated list of academic, engineering, and educational resources related to ***identity***, ***privacy***, and ***reputation***. It's audience includes researchers, developers, *enterprises*, investors, students, and anyone who's interested in these topics.

The highly *interoperable*, *composable*, and *user-owned* future of the Internet, around which "web3" is termed, is far away from maturity, despite large amounts of capital being poured into the space. In the meantime, *identity*, aside from blockchain tech, is emerging as a crucial new primitive that may eventually unlock the massive adoption of web3 applications (or as Jack Dorsey would like to term it, [web5](https://twitter.com/jack/status/1535314738078486533)). Since identities are centered around user behaviors, their *privacy* naturally becomes important. Similarly, a wide array of identity-based applications are built around user *reputation*, which measures and (sometimes) quantifies vanilla user behavior data.

With the above in mind, this repo keeps track of the latest academic research, project and framework development, and educational resources related to the field. We attempt to keep all the resources as approachable as possible by providing more context about them. For academic papers, it's recommended for additional explanatory resources like slides and videos to be added.

For contributions, please refer to [the contribution guidelines](https://github.com/kvnyu24/awesome-identity/blob/main/CONTRIBUTING.md).

# Identity

## IAM (Traditional)

### Papers

### Projects

- [OpenId](https://openid.net/) allows user authentication based on relying parties (RP) with third-party identity provider services.  

## Decentralized Identity | Self-sovereign Identity

### Papers
- **Methods for Decentralized Identities: Evaluation and Insights**
  *W. Fdhila, N. Stifter, K. Kostal, et al*
  BPM 2021, [eprint](https://eprint.iacr.org/2021/1087.pdf)

- **CanDID: Can-Do Decentralized Identity with Legacy Compatibility, Sybil-Resistance, and Accountability**
  *D. Maram, H. Malvai, F. Zhang, et al*
  SP 2021, [eprint](https://eprint.iacr.org/2020/934.pdf)
- **Decentralized Multi-authority Anonymous Authentication for Global Identities with Non-interactive Proofs**
  *H. Anada*
  BITS 19, [eprint](https://eprint.iacr.org/2019/701.pdf)
- **A Decentralized Public Key Infrastructure with Identity Retention**
  *C. Fromknecht, D. Velicanu, S. Yakoubov*
  Preprint, [eprint](https://eprint.iacr.org/2014/803.pdf)
- **zkKYC in DeFi: An approach for implementing the zkKYC solution concept in Decentralized Finance**
  *P. Pauwels, J. Pirovich, P. Braunz, et al*
  Preprint, [eprint](https://eprint.iacr.org/2022/321.pdf)
- **A Privacy-Preserving Distributed Identity Offline-First PoCP Blockchain Paradigm**
  *A. Nassief*
  Preprint, [eprint](https://eprint.iacr.org/2021/1186.pdf)
- **Decentralized Anonymous Credentials**
  *C. Garman, M. Green, I. Miers*
  NDSS 2014, [eprint](https://eprint.iacr.org/2013/622.pdf)

### Frameworks

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
- 
---

# Privacy

## MPC-based Solutions
### General Frameworks
- [Multi-Protocol SPDZ](https://github.com/data61/MP-SPDZ): Software to benchmark various SMPC protocols such as SPDZ, SPDZ2k, MASCOT, Overdrive, BMR garbled circuits, Yao's garbled circuits, and computation based on three-party replicated secret sharing as well as Shamir's secret sharing (with an honest majority).
- [Secretflow](https://github.com/secretflow/secretflow): SecretFlow is a unified framework for privacy-preserving data intelligence and machine learning


## ZKP-based Solutions

### Basic Zero-knowledge Proofs



## PSI-based Solutions

## TEE-based Solutions
- **Town Crier: An Authenticated Data Feed for Smart Contracts**
  *F. Zhang, E. Cecchetti, K. Croman, et al.*
  CCS 16, [eprint](https://eprint.iacr.org/2016/168.pdf)
  - [Website](https://www.town-crier.org/)
  - [GitHub](https://github.com/bl4ck5un/Town-Crier)

---

# Reputation 
- **A Decentralized Anonymity-Preserving Reputation System with Constant-time Score Retrieval**
  *R. Bazin, A. Schaub, O. Hasan et al*
  Preprint, [eprint](https://eprint.iacr.org/2016/416.pdf)


## Mechanism Design

### Quadratic Voting

### Negative Reputation

## Social Network Analysis

## Game System Design

---

# Other Educational Resources

## Cryptography

### Digital Signatures

## Legislation
