---
hip: 7
title: DID ICNS spec
author: DID Intern (https://github.com/didintern)
status: Draft
type: Standards Track
category: SDK, Core
created: 2022-12-12
---

## Simple Summary
A proposal for supporting ICNS in DID name space on Hypersign chain.

## Abstract
This proposal is for the deterministic generation of DIDs and DID Documents using name systems such as ICNS, Ens etc and a standard for verification of DIDs and DID Documents.

With zero transaction costs, users can easily create their own DIDs from ICNS. They will then be able to prove control over their DID and allow counterparties to find their public encryption key, signature verification key and public services. Those services can be used to interact with the user’s DID.

## Motivation
DIDs are not a replacement for Cosmos Accounts and ICNS. Instead, DIDs can be seen as an abstract representation of those which makes it easier for developers to build applications across different chains and platforms. Many developers in the Decentralized Identity Community are already building a lot of Open Source tooling/products and protocols facilitating trust, privacy, security and data sovereignty, to integrate with the Cosmos & Ethereum  ecosystem and vice versa. Some of the Open Source components include decentralized agents (e.g. Veramo), secure communication (i.e. DIDComm Messaging), capabilities-based authorization and delegation frameworks (e.g. ZCaps) or public storage (e.g. Ceramic) and more.

DID-based representations for Cosmos Accounts have been already defined and used. Examples include:

- did:hid:khq95kp898jekjurw828jjr7evfgrhyxv33wfh
- did:cheqd:khq95kp898jekjurw828jjr7evfgrhyxv33wfh

We would like to define a DID-representation for ICNS names such as:

 - did:icns:mainnet:sunny.osmo

This has two purposes:

- to wrap existing ICNS names as DIDs to facilitate interoperability of emerging technologies in the Decentralized Identity and Other community such as eTH,
- to define a canonical way to augment ICNS names with DID capabilities (e.g., encryption) as mentioned above.

## Usecases 
 - Encrypted File Storage using ICNS
 - Onchain Email system using ICNS
 - Onchain Notification
 - Delegation


## Specification

We will update this once ICNS commmunity decides we should go forward witht this.
#### sub topic:


This is still in draft stage. I will update this section once the proposal is finalized.


## Rationale

## Backwards Compatibility
This proposal is backward compatible. The current DID and DID Document generation and verification process will work even after the acceptance of this proposal.

## Reference Implementation




