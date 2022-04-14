# Welcome to IceFireDB

![test](https://github.com/IceFireDB/IceFireDB/actions/workflows/test.yml/badge.svg)
![build](https://github.com/IceFireDB/IceFireDB/actions/workflows/build.yml/badge.svg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FIceFireDB%2FIceFireDB.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FIceFireDB%2FIceFireDB?ref=badge_shield)


IceFireDB is a database built for web3 and web2. The storage layer supports disk,OSS,IPFS and other storage methods, the protocol layer currently supports RESP, and will support SQL and GraphQL in the future. A blockchain fusion layer based on Ethereum and EOS is being built, which can be used in fusion with higher-level decentralized computing platforms and applications as well as identity, financial assets, intellectual property, and sidechain protocols. IceFireDB strives to fill the gap of the decentralized stack, making web3 application data storage more convenient, and making web2 application easier to connect to the blockchain.

<p align="center">
<img 
    src="https://raw.githubusercontent.com/IceFireDB/IceFireDB/main/imgs/project_purpose.png" 
     alt="project_purpose">
</p>

1. High performance
2. Distributed consistency
3. Reliable LSM disk storage
4. Support OSS storage engine
5. Based on IPFS decentralized storage, build a persistent data distributed storage layer.（beta version）
6. Build a blockchain mechanism based on Ethereum and quorum.（Working hard）
7. Support kv metadata layer and mixed storage structure of hot and cold.
8. More advanced cache implementation, faster LSM persistent storage（Source of ideas: https://dl.acm.org/doi/10.1145/3448016.3452819 ）

# Architecture

<p align="center">
<img 
    src="https://raw.githubusercontent.com/IceFireDB/IceFireDB/main/IceFireDB_Architecture.png" 
     alt="IceFireDB_Architecture">
</p>
