# EthR&D Discord Guidebook
This is a guidebook of links for research topics in the Ethereum R&amp;D Discord, which follows the existing channel structure.
## General 
### Apprenticeship Program
The Core Dev Apprenticeship Program (CDAP) is an effort to onboard more contributors to Ethereum Core Development.
- [Core Dev Apprenticeship Program Repo](https://github.com/ethereum-cdap) - Updated frequently
- [Announcement Blog Post](https://blog.ethereum.org/2021/05/13/core-dev-apprenticeship/) - May 2021
### Specifications
The Consensus Layer (Beacon Chain) is defined by an executable python implementation of Ethereum that prioritizes readability and simplicity. There is a project underway to do the same for the Execution Layer.
- [Consensus Specs](https://github.com/ethereum/consensus-specs) - Work Ongoing
- [Execution Specs](https://github.com/ethereum/execution-specs) - Work Ongoing
### Merge
The Merge will unite the Execution and Consensus layers of Ethereum into a single unified system. At the transition, Proof of Work consensus will be hot swapped with the Proof of Stake Beacon Chain consensus, resulting in a more scalable, secure, and sustainable. 
- [Merge Interop Spec](https://hackmd.io/@n0ble/merge-interop-spec) - Oct 2021
- [EIP-3675: Upgrade consensus to Proof-of-Stake](https://eips.ethereum.org/EIPS/eip-3675) - July 2021
## Execution R&D
### Fee Market
EIP-1559 changed Ethereum's fee market to use elastic blocksizes and burnt Ether to smooth congestion and improve transaction inclusion UX.
- [EIP-1559 Resources 🔥](https://hackmd.io/@timbeiko/1559-resources) - Tim Beiko, others
- [PEEPanEIP #37: EIP-1559: Fee market change with Tim Beiko, Barnabe Monnot, Micah Zoltu](https://www.youtube.com/watch?v=AC1FS3LmoT4&list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) - Ethereum Cat Herders
- [Cheatsheet: 1559 for Wallets & Users](https://hackmd.io/4YVYKxxvRZGDto7aq7rVkg?view) - Trent Van Epps, Tim Beiko
### Account Abstraction 
Account abstraction (AA) allows a contract to be the top-level account that pays fees and starts transaction execution. Sometimes used as a general catchall term for delegated transaction validation.
- [Account Abstraction Link Tree: 2015 - 2020](https://hackmd.io/@matt/r1neQ_B38)
- [Proposal for account abstraction via alternative mempool](https://notes.ethereum.org/@vbuterin/alt_abstraction) - June 2021
- [🅰️🅰️ Account Abstraction Beyond EIP-2938 🧵🎉](https://hackmd.io/@SamWilsn/S1UQDOzBv#Read-write-Calls) - Nov 2020
- [Account Abstraction (EIP-2938): Why & What](https://our.status.im/account-abstraction-eip-2938/) - Nov 2020
- [EIP-2938: Account Abstraction - Magician's Discussion](https://ethereum-magicians.org/t/eip-2938-account-abstraction/4630) - Sept 2020
### Client Development
(Summary needed)
- [Ethereum Wire Protocol (ETH)](https://github.com/ethereum/devp2p/blob/master/caps/eth.md) - Ongoing
- [The State of Client Diversity in Ethereum](https://medium.com/ethereum-cat-herders/the-state-of-client-diversity-in-ethereum-2ca915a3d768) - August 2020
### State Expiry
"The Ethereum state size is growing quickly... In order to maintain the scalability and sustainability of Ethereum, we need some solutions."
**[Review tying state expiry, witnesses, verkle trees & the portal network, as of end of June 2021](state-expiry/README.md)**

- [State Expiry EIP](https://notes.ethereum.org/@vbuterin/state_expiry_eip) - June 2021
- [A state expiry and statelessness roadmap](https://notes.ethereum.org/@vbuterin/verkle_and_state_expiry_proposal) - June 2021
- [Verkle tree EIP](https://notes.ethereum.org/@vbuterin/verkle_tree_eip) - June 2021
- [A theory of state size management](https://hackmd.io/@vbuterin/state_size_management) - Feb 2021
- [A few paths to statelessness and state expiry](https://hackmd.io/@vbuterin/state_expiry_paths) - Feb 2021
- [Resurrection-conflict-minimized state bounding](https://ethresear.ch/t/resurrection-conflict-minimized-state-bounding-take-2/8739) - Feb 2021
- [ReGenesis](https://medium.com/@mandrigin/regenesis-explained-97540f457807) - Explication of Alexey Akhunov’s proposal, can be described as a form of state expiry + history expiry - June 2020
- [ASE (Address Space Extension) with Translation Map](https://notes.ethereum.org/@ipsilon/address-space-extension-exploration) - June 2020
- [Increasing address size from 20 to 32 bytes](https://ethereum-magicians.org/t/increasing-address-size-from-20-to-32-bytes/5485) - March 2020
- [The Stateless Client Concept, original ethresear.ch post](https://ethresear.ch/t/the-stateless-client-concept/172) (2017) 
- [State rent (precursor to state expiry), original proposal](https://github.com/ethereum/EIPs/issues/35) - 2015
- [Presentation on bounding witness sizes](https://www.youtube.com/watch?v=qQpvkxKso2E) - Jan 2021
### EVM
Research and initiatives related to improving the Ethereum Virtual Machine (EVM)
- [Everything about the EVM Object Format (EOF)](https://notes.ethereum.org/@ipsilon/evm-object-format-overview) - June 2021
- [Memory Copying in Contracts Deployed on Ethereum](https://notes.ethereum.org/@ipsilon/evm-mcopy-analysis) - June 2021
### Polynomial Commitments
(Summary needed)
- [Kate polynomial commitments](https://dankradfeist.de/ethereum/2020/06/16/kate-polynomial-commitments.html) - June 2020
- [PCS multiproofs using random evaluation](https://dankradfeist.de/ethereum/2021/06/18/pcs-multiproofs.html) - June 2021
- [Fast Amortized Kate Proofs](https://github.com/khovratovich/Kate/blob/master/Kate_amortized.pdf) - March 2020
- [Understanding PLONK](https://vitalik.ca/general/2019/09/22/plonk.html) - Sep 2019
- [Ethresear.ch posts on kate](https://ethresear.ch/search?q=kate) - Ongoing
- [KZG Commitments in C](https://github.com/benjaminion/c-kzg) - Ongoing
### Witnesses
(Summary Needed)
- [Ethereum Witness Protocol (wit)](https://github.com/ethereum/devp2p/blob/master/caps/wit.md) - February 2021
- [The Formal Witness Spec: An Illustrated Primer](https://notes.ethereum.org/bjRBM5IxQQOgqp7bez15xQ) - October 2020
- [Block Witness Formal Specification](https://github.com/ethereum/portal-network-specs/blob/change-goals-structure/witness.md) - April 2020
### Verkle Trie Migration
An ongoing project to "Introduce a new Verkle state tree alongside the existing hexary Patricia tree. After the hard fork, the Verkle tree stores all edits to state and a copy of all accessed state, and the hexary Patricia tree can no longer be modified." This effort often considered a prerequisite for some degrees of Statelessness.
- [Verkle Tree EIP Notes](https://notes.ethereum.org/@vbuterin/verkle_tree_eip#Verkle-tree-definition) - September 2021
- [Verkle Trees](https://vitalik.ca/general/2021/06/18/verkle.html) - June 2021
- [Verkle Tree for Eth1 State](https://dankradfeist.de/ethereum/cryptography/2021/06/18/verkle-trie-for-eth1.html) - June 2021
- [Verkle Trees Paper](https://math.mit.edu/research/highschool/primes/materials/2018/Kuszmaul.pdf) - 2018
### Typed Transactions
(Summary Needed)
- [SSZ and Typed Transactions](https://notes.ethereum.org/71-fSPtGRi-ab-npDf2oIA) - January 2021
- [Typed Transactions](https://notes.ethereum.org/Ck-KDLVaQgCHBMfeIhZTcQ) - December 2020
- [EIP-2976: Typed Transactions over Gossip](https://eips.ethereum.org/EIPS/eip-2976) - September 2020
### 3074 & Meta Transactions
(Summary needed)
- [EIP-2718: Typed Transaction Envelope](https://eips.ethereum.org/EIPS/eip-2718) - June 2020
### Cryptography
(Summay Needed)
- LINK 1
- LINK 2
### Attack Vectors
(Summay Needed)
- LINK 1
- LINK 2
### Address Space Extension
(Summay Needed)
- LINK 1
- LINK 2
### Block Construction
(Summay Needed)
- LINK 1
- LINK 2
## Consensus R&D
### Portal Network
- [Introducing Fluffy - an ultra-light client for Ethereum](https://our.status.im/nimbus-fluffly/)
- [The Portal Network](https://github.com/ethereum/stateless-ethereum-specs/blob/master/portal-network.md)
### Pos Consensus
(Summary Needed)
- [Ethereum Proof-Of-Stake Consensus Specifications](https://github.com/ethereum/consensus-specs) - Ongoing
### Sharded Data
(Summary Needed)e
- [Sharding FAQs](https://eth.wiki/sharding/Sharding-FAQs) - Ongoing
- [Consensus Specs - Sharding](https://github.com/ethereum/consensus-specs/tree/dev/specs/sharding) - Ongoing
- [Why Sharding is Great: demystifying the technical properties](https://vitalik.ca/general/2021/04/07/sharding.html) - April 2021
- [An explanation of the sharding and DAS proposal](https://hackmd.io/@vbuterin/sharding_proposal) - January 2021
- [ETH2 Shard Chain Simplification Proposal](https://notes.ethereum.org/@vbuterin/HkiULaluS) - October 2019
### Light Clients
- LINK 1
- LINK 2
### Withdrawal Methods
- LINK 1
- LINK 2
### Secret Shared Validators
(Summary Needed)
- [Preventing Eth2 Validator Failure](https://notes.ethereum.org/@adiasg/preventing-eth2-validator-failure) - October 2020
### Formal Methods
(Summary Needed)
- [Formal Verification Blog](https://fv.ethereum.org/) - Ongoing
