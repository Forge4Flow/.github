<a name="readme-top"></a>

<div align="center">

<!-- PROJECT LOGO -->
<br />
  <img src="../images/logo.png" alt="Logo" width="160" height="160">

  <h3>Forge4Flow</h3>

  <p>
    <a href="http://forge4flow.gitbook.io/docs"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://github.com/Forge4Flow/Forge4Flow-Core/issues">Report Bug</a>
    ·
    <a href="https://github.com/Forge4Flow/Forge4Flow-Core/issues">Request Feature</a>
  </p>

  <h3>Forge4Flow provides ecosystem and developer tools for the Flow Blockchain, including Identity and Access Management, Blockchain Event Monitoring, and SDKs to better integrate dApps with the ecosystem.</h3>

</div>

## The problem it solves

Developers face challenges in creating dApps due to issues like user authentication, access control, system monitoring, and third-party integration. Forge4Flow aims to address these problems with a developer infrastructure and tooling platform. We're excited to introduce three tool sets to advance the ecosystem:

### Auth4Flow:

> Blockchain-based authentication lacks comprehensive user verification, requiring custom solutions for advanced functionalities and role-based access control. Transitioning to a Web3 environment increases the complexity of achieving secure user access control, both within DApps and when interacting with Web2 technologies. Auth4Flow offers a simple, open-source Identity and Access Management platform that simplifies Web3 authentication. It supports various authorization schemes, including RBAC, FGAC, ReBAC, and NFT/FT gated access.

### Alerts4Flow:

> One of the biggest advanges of the Flow Blockchain is it's ability to emmit events from within contracts, thus allowing developers to react to changes as they occur. Unfortuantley tooling in this area has not been widely developed. With Alerts4Flow developers can easily setup Event Monitors to receive alerts in realtime using Websockets or Webhooks.

### Ecosystem SDKs:

> Lack of mobile resources is a huge factor for their being verry little Web3 Mobile apps. By releases ecosystem SDKs for multiple platofrms we can lower the barrier to entry for new developers. We have scoped several SDKs to target for Swift (iOS).

By providing these tool sets, we aim to empower developers to focus on delivering exceptional user experiences without worrying about complex authentication, access control, and other Web3 challenges.

<!-- GETTING STARTED -->

## Getting Started

To get started using Forge4Flow, follow the [deployment guide](https://github.com/Forge4Flow/Forge4Flow-Core/blob/main/deployment.md) to self host your own instance of Forge4Flow-Core. Once you have an instance started, follow one of our SDK quick start guides or check out or documentation for more information.

<!-- ROADMAP -->

## Roadmap

### Auth4Flow

- [x] Blockchain Native Login w/ Client & Server Sessions
- [ ] Walletless Onboarding w/ Client & Server Sessions
  - [ ] Transaction Signing APIs
  - [ ] Parent/Child Account Linking
  - [ ] Forced Hybrid Authentication (Creating Flow Child Accounts for Blockchain Native Accounts)
- [ ] NFT Gated Access Control
- [ ] .find Name and Profile Integration
- [ ] GO Server SDK
- [x] [JS SDK](https://github.com/Forge4Flow/Forge4Flow-JS)
- [x] [Node SDK](https://github.com/Forge4Flow/Forge4Flow-Node)
- [x] [React SDK](https://github.com/Forge4Flow/Forge4Flow-React)
- [x] [NextJS](https://github.com/Forge4Flow/Forge4Flow-NextJS)
- [ ] Swift SDK
- [ ] Kotlin SDK
- [x] Admin Dashboard
- [x] Multi-Tenant Support

### Alerts4Flow

- [x] Custom Event Monitors
- [x] Admin Dashboard

### Ecosystem SDKs

- Flow Ecosystem
  - FLOAT
    - [x] [Swift (iOS)](https://github.com/Forge4Flow/FLOAT-Swift-SDK)
    - [ ] JS, Node
    - [ ] Go
  - .find
    - [x] [Swift (iOS)](https://github.com/Forge4Flow/FIND-Swift-SDK)
    - [ ] JS, Node
    - [ ] Go
  - Flow NFT Catalog
    - [ ] Swift (iOS)
    - [ ] Go
- Mobile Platforms
  - Swift (iOS)
    - [x] [NFT.storage](https://github.com/Forge4Flow/NFT-Storage-Swift)
    - [x] [SwiftIPFS-Image]https://github.com/Forge4Flow/SwiftUI-IPFSImage
- General Purpose
  - [x] [GCP KMS authorizer (signer)](https://github.com/Forge4Flow/GCP-KMS-Flow-Authorizer)

See the [open issues](https://github.com/Forge4Flow/Forge4Flow-Core/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>
