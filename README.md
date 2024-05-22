# EthR&D Discord Guidebook
A guidebook to the bleeding edge of research topics in the Ethereum R&D Discord, which should follow the existing channel structure.

Help wanted to get it up to date! Updating channel structure and links to the latest work in each area ensures this resource remains relevant. I have selected the channels which seem most active, related to research & development, or have discrete outputs (eg. documents). Links should be structured as below with most recent on top:

### Channel name
- Title of resource with link - Date created

---

## General 
### Testnets
- [Goerli Deprecation](https://blog.ethereum.org/2023/11/30/goerli-lts-update) - Nov 2023
### Specifications
The Consensus Layer (Beacon Chain) is defined by an executable python implementation of Ethereum that prioritizes readability and simplicity. There is a project underway to do the same for the Execution Layer.
- [Consensus Specs](https://github.com/ethereum/consensus-specs) - Work Ongoing
- [Execution Specs](https://github.com/ethereum/execution-specs) - Work Ongoing
### Protocol Fellowship
Ethereum Protocol Fellowship Program (EPF) is an effort to onboard more contributors to Ethereum Core Development.
- [EPF repositories](https://github.com/eth-protocol-fellows) - Updated frequently.
- [EPF Wiki](https://epf.wiki/#/) - A wiki maintained by the community formed around the EPF study group. Contributions are welcome!!
- [Fifth Cohort Announcement Blog Post](https://blog.ethereum.org/2024/05/13/epf-5-announcement) - May 2024
### Rollcall
- Link1
- Link2

## Sharding
### Sharded data
(Summary Needed)
- [Sharding FAQs](https://eth.wiki/sharding/Sharding-FAQs) - Ongoing
- [Consensus Specs - Sharding](https://github.com/ethereum/consensus-specs/tree/dev/specs/sharding) - Ongoing
- [Why Sharding is Great: demystifying the technical properties](https://vitalik.ca/general/2021/04/07/sharding.html) - April 2021
- [An explanation of the sharding and DAS proposal](https://hackmd.io/@vbuterin/sharding_proposal) - January 2021
- [ETH2 Shard Chain Simplification Proposal](https://notes.ethereum.org/@vbuterin/HkiULaluS) - October 2019
- [Dankrad's data sharding design](https://notes.ethereum.org/@dankrad/new_sharding) - December 2021
- ["Dude, what’s the Danksharding situation?" Workshop](https://www.youtube.com/watch?v=e9oudTr5BE4) - February 2022
- [EIP-4844: Shard Blob Transactions ("Proto-Danksharding")](https://eips.ethereum.org/EIPS/eip-4844) - February 2022
- [Proto-Danksharding FAQ](https://notes.ethereum.org/@vbuterin/proto_danksharding_faq) - March 2022
### KZG Ceremony
- [Wrapping up the KZG Ceremony](https://blog.ethereum.org/2024/01/23/kzg-wrap) - Jan 2024
- [KZG Ceremony Special Contributions](https://blog.ethereum.org/2023/08/02/kzg-special-contributions)  Aug 2023
- [Announcing the KZG Ceremony](https://blog.ethereum.org/2023/01/16/announcing-kzg-ceremony) Jan 2023
### 4844-testing
- Link1
- Link2

## Execution R&D
### Statelessness / State Expiry
"The Ethereum state size is growing quickly... In order to maintain the scalability and sustainability of Ethereum, we need some solutions."

- [Ethereum Statelessness Resource Page](https://notes.ethereum.org/@gballet/Sy-a6T5St) - Oct 2021
- [Review tying state expiry, witnesses, verkle trees & the portal network](state-expiry/README.md) - June 2021
- [State Expiry EIP](https://notes.ethereum.org/@vbuterin/state_expiry_eip) - June 2021
- [A state expiry and statelessness roadmap](https://notes.ethereum.org/@vbuterin/verkle_and_state_expiry_proposal) - June 2021
- [Verkle tree EIP](https://notes.ethereum.org/@vbuterin/verkle_tree_eip) - June 2021
- [A theory of state size management](https://hackmd.io/@vbuterin/state_size_management) - February 2021
- [A few paths to statelessness and state expiry](https://hackmd.io/@vbuterin/state_expiry_paths) - February 2021
- [Resurrection-conflict-minimized state bounding](https://ethresear.ch/t/resurrection-conflict-minimized-state-bounding-take-2/8739) - February 2021
- [Proposed Verkle tree scheme for Ethereum state](https://ethereum-magicians.org/t/proposed-verkle-tree-scheme-for-ethereum-state/5805) - March 2021
- [ReGenesis](https://medium.com/@mandrigin/regenesis-explained-97540f457807) - Explication of Alexey Akhunov’s proposal, can be described as a form of state expiry + history expiry - June 2020
- [ASE (Address Space Extension) with Translation Map](https://notes.ethereum.org/@ipsilon/address-space-extension-exploration) - June 2020
- [Increasing address size from 20 to 32 bytes](https://ethereum-magicians.org/t/increasing-address-size-from-20-to-32-bytes/5485) - March 2020
- [The Stateless Client Concept, original ethresear.ch post](https://ethresear.ch/t/the-stateless-client-concept/172) - 2017
- [State rent (precursor to state expiry), original proposal](https://github.com/ethereum/EIPs/issues/35) - 2015
- [Presentation on bounding witness sizes](https://www.youtube.com/watch?v=qQpvkxKso2E) - Jan 2021
## EVM
Research and initiatives related to improving the Ethereum Virtual Machine (EVM)
- [Everything about the EVM Object Format (EOF)](https://notes.ethereum.org/@ipsilon/evm-object-format-overview) - June 2021
- [Memory Copying in Contracts Deployed on Ethereum](https://notes.ethereum.org/@ipsilon/evm-mcopy-analysis) - June 2021
- [EOF Status Update 2023-10-12](EOF%20Status%20Update%202023-10-12.pptx)
## EPBS
Maximal Extractable Value (MEV) represents a centralization vector around block builder. Separating the responsibility of building blocks from proposing blocks helps mitigate centralization concerns and democratize access to the extractable value.
- [PBS-friendly fee market designs](https://ethresear.ch/t/proposer-block-builder-separation-friendly-fee-market-designs/9725) - June 2021
- [Two-slot PBS](https://ethresear.ch/t/two-slot-proposer-builder-separation/10980) - October 2021
- [Committee-driven MEV smoothing](https://ethresear.ch/t/committee-driven-mev-smoothing/10408) - August 2021
- [State of research on censorship resistance under PBS](https://notes.ethereum.org/s3JToeApTx6CKLJt8AbhFQ) - January 2022
- [Current crList proposal](https://notes.ethereum.org/Dh7NaB59TnuUW5545msDJQ) - February 2022
## Blockspace markets
## EVM graveyard
## polynomial commitments
(Summary needed)
- [Kate polynomial commitments](https://dankradfeist.de/ethereum/2020/06/16/kate-polynomial-commitments.html) - June 2020
- [PCS multiproofs using random evaluation](https://dankradfeist.de/ethereum/2021/06/18/pcs-multiproofs.html) - June 2021
- [Fast Amortized Kate Proofs](https://github.com/khovratovich/Kate/blob/master/Kate_amortized.pdf) - March 2020
- [Understanding PLONK](https://vitalik.ca/general/2019/09/22/plonk.html) - Sep 2019
- [Ethresear.ch posts on kate](https://ethresear.ch/search?q=kate) - Ongoing
- [KZG Commitments in C](https://github.com/benjaminion/c-kzg) - Ongoing
- [KZG Trusted Setup Ceremony specifications](https://github.com/ethereum/kzg-ceremony-specs) - Ongoing
## witnesses
(Summary Needed)
- [Ethereum Witness Protocol (wit)](https://github.com/ethereum/devp2p/blob/master/caps/wit.md) - February 2021
- [The Formal Witness Spec: An Illustrated Primer](https://notes.ethereum.org/bjRBM5IxQQOgqp7bez15xQ) - October 2020
- [Block Witness Formal Specification](https://github.com/ethereum/portal-network-specs/blob/change-goals-structure/witness.md) - April 2020
## verkle-trie migration
An ongoing project to "Introduce a new Verkle state tree alongside the existing hexary Patricia tree. After the hard fork, the Verkle tree stores all edits to state and a copy of all accessed state, and the hexary Patricia tree can no longer be modified." This effort often considered a prerequisite for some degrees of Statelessness.
- [Verkle.info] (https://verkle.info/) - Jan 2024
- [Verkle Tree Update](https://docs.google.com/presentation/d/1Hgke4EHtjHBaYrIA6WbToGip6eho6INBgvwG76BIw1M) - Aug 2023
- [Ethereum statelessness roadmap](https://notes.ethereum.org/Yn_mwNa2SeeQHnKsRgekKg) - Oct 2021
- [Verkle Tree EIP Draft](https://notes.ethereum.org/5HDhQXstTaKtVqVbS7S9yw) - Oct 2021
- [Verkle Tree EIP Notes](https://notes.ethereum.org/@vbuterin/verkle_tree_eip#Verkle-tree-definition) - September 2021
- [Verkle Trees](https://vitalik.ca/general/2021/06/18/verkle.html) - June 2021
- [Verkle Tree for Eth1 State](https://dankradfeist.de/ethereum/cryptography/2021/06/18/verkle-trie-for-eth1.html) - June 2021
- [Verkle Trees Paper](https://math.mit.edu/research/highschool/primes/materials/2018/Kuszmaul.pdf) - 2018
## typed transactions
(Summary Needed)
- [SSZ and Typed Transactions](https://notes.ethereum.org/71-fSPtGRi-ab-npDf2oIA) - January 2021
- [Typed Transactions](https://notes.ethereum.org/Ck-KDLVaQgCHBMfeIhZTcQ) - December 2020
- [EIP-2976: Typed Transactions over Gossip](https://eips.ethereum.org/EIPS/eip-2976) - September 2020
## future EOA
- [Account Abstraction Link Tree: 2015 - 2020](https://hackmd.io/@matt/r1neQ_B38)
- [Proposal for account abstraction via alternative mempool](https://notes.ethereum.org/@vbuterin/alt_abstraction) - June 2021
- [🅰️🅰️ Account Abstraction Beyond EIP-2938 🧵🎉](https://hackmd.io/@SamWilsn/S1UQDOzBv#Read-write-Calls) - Nov 2020
- [Account Abstraction (EIP-2938): Why & What](https://our.status.im/account-abstraction-eip-2938/) - Nov 2020
- [EIP-2938: Account Abstraction - Magician's Discussion](https://ethereum-magicians.org/t/eip-2938-account-abstraction/4630) - Sept 2020
- [EIP-2718: Typed Transaction Envelope](https://eips.ethereum.org/EIPS/eip-2718) - June 2020
## cryptography
## attack vectors
- [Responding to 51% attacks in Casper FFG](https://ethresear.ch/t/responding-to-51-attacks-in-casper-ffg/6363) - October 2019
## address space extension
## history expiry
## self-destruct removal

### Client Development
(Summary needed)
- [Ethereum Wire Protocol (ETH)](https://github.com/ethereum/devp2p/blob/master/caps/eth.md) - Ongoing
- [The State of Client Diversity in Ethereum](https://medium.com/ethereum-cat-herders/the-state-of-client-diversity-in-ethereum-2ca915a3d768) - August 2020

### EIP-6404 and EIP-6466 SSZification of Transaction and Receipt Roots
- [Study on the SSZification Impact on existing applications/protocol](EIP-6404_And_EIP-6466/Dedaub%20EF%20Receipts%20&%20Transactions%20SSZ%20Root%20Impact%20Study.odt)
- [Presentation on the SSZification Impact on existing applications/protocol](EIP-6404_And_EIP-6466/EF%20Study%20-%20RLP%20to%20SSZ%20migration.odp)
## Consensus R&D

## Pos Consensus
### data availability sampling
### Withdrawal Methods
- LINK 1
- LINK 2
### Light Clients
- LINK 1
- LINK 2
### Distributed Validators
(Summary Needed)
- [Preventing Eth2 Validator Failure](https://notes.ethereum.org/@adiasg/preventing-eth2-validator-failure) - October 2020
### Formal Methods
(Summary Needed)
- [Formal Verification Blog](https://fv.ethereum.org/) - Ongoing
### Secret Single Leader Election
- [Secret Single Leader Election (SSLE) in Eth2](https://notes.ethereum.org/@vbuterin/HJNJDTaVw) - September 2022
- [Provable Single Secret Leader Election](https://ethresear.ch/t/provable-single-secret-leader-election/7971) - September 2020
- [Secret non-single leader election](https://ethresear.ch/t/secret-non-single-leader-election/11789) - January 2022
- [Whisk: A practical shuffle-based SSLE protocol for Ethereum](https://ethresear.ch/t/whisk-a-practical-shuffle-based-ssle-protocol-for-ethereum/11763) - January 2022
- [Simplified SSLE](https://ethresear.ch/t/simplified-ssle/12315) - April 2022

---

## Archived
### Merge
The Merge united the Execution and Consensus layers of Ethereum into a single unified system. At the transition, Proof of Work consensus was hot-swapped with the Proof of Stake Beacon Chain consensus, resulting in a more scalable, secure, and sustainable network
- [Amphora Interop Milestone tracker](https://hackmd.io/_9XZIkDBTlqGJejVnOSOJg?view) - Oct 2021
- [Merge Interop Spec](https://hackmd.io/@n0ble/merge-interop-spec) - Oct 2021
- [EIP-3675: Upgrade consensus to Proof-of-Stake](https://eips.ethereum.org/EIPS/eip-3675) - July 2021
### Fee Market
[EIP-1559](https://eips.ethereum.org/EIPS/eip-1559) changed Ethereum's fee market to use elastic blocksizes and burnt Ether to smooth congestion and improve transaction inclusion UX.
- [EIP-1559 Resources 🔥](https://hackmd.io/@timbeiko/1559-resources) - Tim Beiko, others
- [PEEPanEIP #37: EIP-1559: Fee market change with Tim Beiko, Barnabe Monnot, Micah Zoltu](https://www.youtube.com/watch?v=AC1FS3LmoT4&list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) - Ethereum Cat Herders
- [Cheatsheet: 1559 for Wallets & Users](https://hackmd.io/4YVYKxxvRZGDto7aq7rVkg?view) - Trent Van Epps, Tim Beiko
- [EIP-4396: Time-Aware Base Fee Calculation](https://eips.ethereum.org/EIPS/eip-4396) - October 2021
- [Make EIP-1559 more like an AMM curve](https://ethresear.ch/t/make-eip-1559-more-like-an-amm-curve/9082) - April 2021
- [Multidimensional EIP-1559](https://ethresear.ch/t/multidimensional-eip-1559/11651) - January 2022
### Portal Network
- [Introducing Fluffy - an ultra-light client for Ethereum](https://our.status.im/nimbus-fluffly/)
- [The Portal Network](https://github.com/ethereum/stateless-ethereum-specs/blob/master/portal-network.md)
