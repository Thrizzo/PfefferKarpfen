# Projekt PfefferKarpfen

**Composite Identity-Based Zero Trust Enforcement at the Network Layer**

Projekt PfefferKarpfen is a blockchain-agnostic, device-agnostic identity enforcement system designed to implement zero trust at the host or network layer. It verifies composite identities—user + device—and denies unauthorized access *before* connections are made, like a cryptographic firewall.

## Features
- Decentralized, pluggable identity verification
- Composite identity binding via DIDs
- Host-level enforcement (iptables, WinFW, etc.)
- Modular DID resolution (supports any blockchain)
- Lightweight: suitable for Android, IoT, edge

## Status
MVP in progress — follow the `spec/` directory for early design docs.

## License
[MIT License](./LICENSE)
