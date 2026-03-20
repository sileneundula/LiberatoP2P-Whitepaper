# LiberatoP2P: A Novel, Decentralized, Peer To Peer Network That Uses Block Lattices and Ephermal States For Communication

## Abstract

This paper introduces a new, novel peer to peer network for interacting with various clients using robust security measurements.

## 1. Identity

Implemented:
- [ ] Hybrids
  - [X] ShulginSigning (ED25519 & SPHINCS+ (SHAKE256))
    - [X] Info: Uses X59 Format, is classical and post-quantum secure, and the public key is under 200 bytes. Relies on robust security.
  - [ ] EsphandSigning (ED25519 & FALCON1024)
  - [ ] AbsolveSigning (ED25519 & ML-DSA)

The identity is defined as a `ShulginSigning` keypair in X59 format. This is a hybrid ED25519 and SPHINCS+ scheme, offering robust security.
