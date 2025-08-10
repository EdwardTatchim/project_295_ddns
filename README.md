Blockchain-Based Decentralized Domain Name System: https://d.phicoin.net/documentation.html


 A. Problem Statement
The modern internet’s Domain Name System (DNS) represents a critical infrastructure vulnerability that undermines both security and freedom of information. Two primary categories of threats have emerged as systemic challenges:
DNS Security Vulnerabilities: The centralized architecture of traditional DNS systems creates attractive targets for sophisticated attacks. Recent evidence includes the APT GroupStormBamboo attacks, which compromised ISP-level DNS infrastructure to redirect legitimate traffic to malicious endpoints [1]. These poisoning attacks exploit the inherent trust relationships in hierarchical DNS resolution, demonstrating how centralized control points become systemic weaknesses [35],

 C. Our Contribution
 This project presents a comprehensive blockchain-based decentralized DNS system (hereinafter referred to as DDNS) that addresses these fundamental limitations through:
1) DDNS Blockchain Infrastructure: The project code name is Phicoin, representing an acronym for Proof of Work High-performance Infrastructure, aimed at build
ing a fully decentralized blockchain network using PoW mechanism.
2) Cryptographic Trust Chain: End-to-end verification using elliptic curve digital signatures (ECDSA) for domain registration and modification, eliminating reliance
 on third-party trust
 3) Distributed Storage Integration: IPFS-based domain control file storage with content-addressable hashing for tamper-evident record management
 4) Anti-Censorship Architecture: Mesh network communication patterns and distributed resolver infrastructure that circumvents traditional blocking mechanisms
 5) Cross-chain Integration: We developed cross-chain bridges capable of connecting the DDNS blockchain to other smart contract-enabled blockchains such as Solana
 and Ethereum. We have deployed smart contracts on Solana, enabling the 15 million monthly active users (MAU) of Solana to directly utilize DDNS services for
 domain registration and updates without downloading node clients.
 6) Edge DDNS Resolution Services: We developed edge DDNS servers that enable DDNS resolution within organizations without relying on public DDNS services,
 while maintaining compatibility with traditional DNS resolution. This requires only deploying edge DDNS services within the organization and configuring them
 as the organization’s network DNS servers.
 7) Decentralized Web Protocol (D-WEB): We implemented a decentralized D-WEB protocol based on DDNS TXT records, which leverages IPFS’s capability to resolve static directories, using TXT records to resolve website IPFS hashes, enabling decentralized archiving/access of traditional websites
