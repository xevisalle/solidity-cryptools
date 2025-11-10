# Solidity ECC: Elliptic Curves Cryptography Solidity Libraries

This repository contains a bunch of libraries on elliptic curves and related cryptographic primitives coded in Solidity. At the moment, we support:

- [Twisted Edwards elliptic curves](src/TwistedEdwards.sol): implementation of some basic EC operations.
- [BLS signatures over BLS12-381](src/BlsSignatures.sol): implementation of BLS signatures verification, using the BLS12-381 elliptic curve.

**DISCLAIMER:** the code in this repository has NOT been audited. Use at your own risk.
