# Welcome to IceFireDB

<p align="center">
<img 
    src="https://raw.githubusercontent.com/IceFireDB/IceFireDB/main/icefiredb-bridge.png" 
     alt="icefiredb-bridge">
</p>

![test](https://github.com/IceFireDB/IceFireDB/actions/workflows/test.yml/badge.svg)
![build](https://github.com/IceFireDB/IceFireDB/actions/workflows/build.yml/badge.svg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FIceFireDB%2FIceFireDB.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FIceFireDB%2FIceFireDB?ref=badge_shield)

IceFireDB is a database built for web3 and web2. The core mission of the project is to help applications quickly achieve decentralization and data immutability. At present, the storage layer supports various storage methods such as disk, OSS, and IPFS. The protocol layer currently supports the RESP protocol, and will support the SQL and GraphQL protocols in the future. A blockchain fusion layer based on immutable transparent logs and Ethereum is under construction to support integration with higher-level decentralized computing platforms and applications as well as identity, financial assets, intellectual property and sidechain protocols. IceFireDB strives to fill the gap of the decentralized stack, making the data ecology of web3 applications more complete, and making it easier for web2 applications to achieve decentralization and data immutability.

<p align="center">
<img 
    src="https://raw.githubusercontent.com/IceFireDB/IceFireDB/main/imgs/project_purpose.png" 
     alt="project_purpose">
</p>

# Project composition

## [IceFireDB-SQLite](https://github.com/IceFireDB/IceFireDB/tree/main/IceFireDB-SQLite)
IceFireDB-SQLite database is a decentralized SQLite database. Provide a convenient mechanism to build a global distributed database system. Support users to write data to IceFireDB-SQLite using MySQL protocol. IceFireDB-SQLite stores the data in the SQLite database and synchronizes the data among the nodes in the P2P automatic network.

## [IceFireDB-SQLProxy](https://github.com/IceFireDB/IceFireDB/tree/main/IceFireDB-SQLProxy)

IceFireDB-SQLProxy is a decentralized SQL database networking system that helps web2 traditional SQL database data decentralization. Provide a convenient mechanism to build a globally distributed storage system with automatic networking. Commands are automatically synchronized between IceFireDB-SQLProxy in the network, and each IceFireDB-SQLProxy writes data to MySQL storage.

Decentralized networking through IceFireDB-SQLProxy provides web2 program read and write support for SQL, enabling decentralized data synchronization for MySQL database read and write scenarios commonly used in web2 applications.

## [IceFireDB-NoSQL](https://github.com/IceFireDB)
It supports distributed raft disk Redis database mode in web2 mode, and also supports decentralized IPFS storage mode.

# Project direction

IceFireDB originated from the distributed NoSQL database in the web2 scenario. We will continue to support the web2 distributed NoSQL database, while investing more energy in the direction of web3 and web2 decentralized databases. We are very grateful to our community partners for their continued interest, the community has been our driving force.
