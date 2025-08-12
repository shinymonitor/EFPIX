# EFPIX (Encrypted Flood Protocol for Information eXchange)

EFPIX is a **zero-trust, encrypted flood-based relay communication protocol** designed for privacy, resilience, and metadata protection. It enables **end-to-end encryption**, **plausible deniability**, and **untraceable messaging**, even in hostile or degraded network environments.

## Features

- **Topology-Agnostic**: Works over any network structure and survives infrastructure loss, censorship, and dynamic topology changes.
- **End-to-End Encryption**: Protects both content and metadata from unauthorized parties.
- **Untraceable messages**: Receiver or sender cannot be traced.
- **Spam Resistance**: Proof-of-Work and deduplication limit flooding abuse.
- **Optional Enhancements**: HMAC-based signatures, verifiable delay functions (VDF), tagged decryption, dummy traffic, sector-based routing, and more.

## Use Cases

- Secure whistleblower and journalist communication  
- Activism and censorship-resistant messaging  
- Disaster recovery and infrastructure-loss scenarios  
- Space/research/military communication where central servers are infeasible  
- General-purpose privacy-first peer-to-peer communication

## Designed For
EFPIX is **not** optimized for high-bandwidth or ultra-low-latency applications

It is best suited for **asynchronous, privacy-critical communication** such as secure email, file drops, offline messaging, and distributed alerts.

“0% performance, 100% security”: EFPIX prioritizes anonymity and resilience over speed. Choose optional features to balance your needs.

## Whitepaper

The complete technical specification, threat model, and example instantiation are available here:  
[EFPIX Whitepaper (PDF)](./EFPIX.pdf)
