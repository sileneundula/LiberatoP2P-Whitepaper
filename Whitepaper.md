# LiberatoP2P: A Novel, Decentralized, Peer To Peer Network That Uses Block Lattices and Ephermal States For Communication

## Abstract

This paper introduces a new, novel peer to peer network for interacting with various clients using robust security measurements. It introduces several components detailed below

- [X] MuscarineP2P/LiberatoP2P
  - [X] Networking Functionality
  - [ ] Command-Line Interface
  - [ ] Protocols
    - [ ] Authorativie Assignment Protocol (AAP): A Protocol to assign a role/service to a certificate using cryptography and digital signatures.
    - [ ] Sumatra Worker Protocol
- [X] Sumatra DAG
  - [X] Account Ledger Manager (ALMAC)
    - [X] Synthchains
    - [ ] 
- [ ] Immutable-Storage-Solution-Standard (Standardized)

## 1. Identity

Implemented:
- [ ] Hybrids
  - [X] ShulginSigning (ED25519 & SPHINCS+ (SHAKE256))
    - [X] Info: Uses X59 Format, is classical and post-quantum secure, and the public key is under 200 bytes. Relies on robust security.
  - [ ] EsphandSigning (ED25519 & FALCON1024)
  - [ ] AbsolveSigning (ED25519 & ML-DSA)

The identity is defined as a `ShulginSigning` keypair in X59 format. This is a hybrid ED25519 and SPHINCS+ scheme, offering robust security.
