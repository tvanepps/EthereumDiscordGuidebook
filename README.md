# EthR&D Discord Guidebook
This is a guidebook of links for research topics in the Ethereum R&amp;D Discord, which follows the existing channel structure.

### Fee Market
This is a change to Ethereum's fee market which uses elastic blocksizes and burnt Ether to smooth congestion, in addition to many other benefits.
- [EIP-1559 Resources 🔥](https://hackmd.io/@timbeiko/1559-resources) - Tim Beiko, others
- [PEEPanEIP #37: EIP-1559: Fee market change with Tim Beiko, Barnabe Monnot, Micah Zoltu](https://www.youtube.com/watch?v=AC1FS3LmoT4&list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) - Ethereum Cat Herders
- [Cheatsheet: 1559 for Wallets & Users](https://hackmd.io/4YVYKxxvRZGDto7aq7rVkg?view) - Trent Van Epps, Tim Beiko
---
### Account Abstraction 
(Summary needed)
- [Account Abstraction Link Tree: 2015 - 2020](https://hackmd.io/@matt/r1neQ_B38)
- [Proposal for account abstraction via alternative mempool](https://notes.ethereum.org/@vbuterin/alt_abstraction) - June 2021
- [🅰️🅰️ Account Abstraction Beyond EIP-2938 🧵🎉](https://hackmd.io/@SamWilsn/S1UQDOzBv#Read-write-Calls) - Nov 2020
- [Account Abstraction (EIP-2938): Why & What](https://our.status.im/account-abstraction-eip-2938/) - Nov 2020
- [EIP-2938: Account Abstraction - Magician's Discussion](https://ethereum-magicians.org/t/eip-2938-account-abstraction/4630) - Sept 2020
---
### Client Development
(Summary needed)
- [Ethereum Wire Protocol (ETH] (https://github.com/ethereum/devp2p/blob/master/caps/eth.md) - Ongoing
- [The State of Client Diversity in Ethereum](https://medium.com/ethereum-cat-herders/the-state-of-client-diversity-in-ethereum-2ca915a3d768) - August 2020
---
### Polynomial Commitments
(Summary needed)
- [Kate polynomial commitments](https://dankradfeist.de/ethereum/2020/06/16/kate-polynomial-commitments.html) - June 2020
- [PCS multiproofs using random evaluation](https://dankradfeist.de/ethereum/2021/06/18/pcs-multiproofs.html) - June 2021
- [Fast Amortized Kate Proofs](https://github.com/khovratovich/Kate/blob/master/Kate_amortized.pdf) - March 2020
- [Understanding PLONK](https://vitalik.ca/general/2019/09/22/plonk.html) - Sep 2019
- [Ethresear.ch posts on kate](https://ethresear.ch/search?q=kate) - Ongoing
- [KZG Commitments in C](https://github.com/benjaminion/c-kzg) - Ongoing
- 
---
### EVM
Research and initiatives related to improving the Ethereum Virtual Machine (EVM)
- [Everything about the EVM Object Format (EOF)](https://notes.ethereum.org/@ipsilon/evm-object-format-overview) - June 2021
- [Memory Copying in Contracts Deployed on Ethereum](https://notes.ethereum.org/@ipsilon/evm-mcopy-analysis) - June 2021
---
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

---
### Witnesses
(Summary Needed)

- [Ethereum Witness Protocol (wit)](https://github.com/ethereum/devp2p/blob/master/caps/wit.md) - February 2021
- [The Formal Witness Spec: An Illustrated Primer](https://notes.ethereum.org/bjRBM5IxQQOgqp7bez15xQ) - October 2020
- [Block Witness Formal Specification](https://github.com/ethereum/portal-network-specs/blob/change-goals-structure/witness.md) - April 2020

---
### Sync
- [Geth v1.10.0](https://blog.ethereum.org/2021/03/03/geth-v1-10-0/) Snap Sync - March 2021
---
### Verkle Trie Migration
(Summary Needed)

- [Verkle Tree EIP Notes](https://notes.ethereum.org/@vbuterin/verkle_tree_eip#Verkle-tree-definition) - September 2021
- [Verkle Trees](https://vitalik.ca/general/2021/06/18/verkle.html) - June 2021
- [Verkle Tree for Eth1 State](https://dankradfeist.de/ethereum/cryptography/2021/06/18/verkle-trie-for-eth1.html) - June 2021
- [Verkle Trees Paper](https://math.mit.edu/research/highschool/primes/materials/2018/Kuszmaul.pdf) - 2018

---
### Typed Transactions
(Summary Needed)

- [SSZ and Typed Transactions] (https://notes.ethereum.org/71-fSPtGRi-ab-npDf2oIA) - January 2021
- [Typed Transactions](https://notes.ethereum.org/Ck-KDLVaQgCHBMfeIhZTcQ) - December 2020
- [EIP-2976: Typed Transactions over Gossip](https://eips.ethereum.org/EIPS/eip-2976) - September 2020

---
### 3074 Meta Transactions
(Summary needed)

- [EIP-2718: Typed Transaction Envelope](https://eips.ethereum.org/EIPS/eip-2718) - June 2020

---
### Portal Network
- [Introducing Fluffy - an ultra-light client for Ethereum](https://our.status.im/nimbus-fluffly/)
- [The Portal Network](https://github.com/ethereum/stateless-ethereum-specs/blob/master/portal-network.md)
- 
---
### Cryptography
- LINK 1
- LINK 2
---
### Gas Bomb
- LINK 1
- LINK 2
---
### Pos Consensus
(Summary Needed)

- [Ethereum Proof-Of-Stake Consensus Specifications](https://github.com/ethereum/consensus-specs) - Ongoing

---
### Sharded Data
(Summary Needed)

- [Sharding FAQs] (https://eth.wiki/sharding/Sharding-FAQs) - Ongoing
- [Consensus Specs - Sharding](https://github.com/ethereum/consensus-specs/tree/dev/specs/sharding) - Ongoing
- [Why Sharding is Great: demystifying the technical properties](https://vitalik.ca/general/2021/04/07/sharding.html) - April 2021
- [An explanation of the sharding and DAS proposal](https://hackmd.io/@vbuterin/sharding_proposal) - January 2021
- [ETH2 Shard Chain Simplification Proposal](https://notes.ethereum.org/@vbuterin/HkiULaluS) - October 2019

---
### Light Clients
- LINK 1
- LINK 2
---
### Withdrawal Methods
- LINK 1
- LINK 2
---
### Networking
(Summary Needed)

- [Phase 0 -- Networking](https://github.com/ethereum/consensus-specs/blob/dev/specs/phase0/p2p-interface.md) - Ongoing

---
### Secret Shared Validators
(Summary Needed)

- [Preventing Eth2 Validator Failure](https://notes.ethereum.org/@adiasg/preventing-eth2-validator-failure) - October 2020

---
### Phase2
- LINK 1
- LINK 2
---
### Formal Methods
(Summary Needed)

- [Formal Verification Blog](https://fv.ethereum.org/) - Ongoing

---
