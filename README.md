# GraphDC

Decentralized GraphQL is an implementation of GraphQL running on blockchain virtual machines. Its code literally runs directly on the blockchain. The goal is to create an unstoppable GraphQL backend with 100% uptime, infinite scalability, amazing security and privacy, and extremely simplified infrastructure and maintenance.

## Vision

The goal is to allow for decentralized GraphQL backends that have all of the properties that scalable blockchains promise to provide, including 100% uptime, infinite scalability, and extremely low maintenance. All of the complicated hardware and software infrastructure related to scaling backends need not be, because of past and future innovations in blockchain technologies. No more complicated infrastructure, no more scaling and uptime issues, just pure client-side GraphQL queries that resolve against an unstoppable decentralized backend.

This project will start with a GraphQL implementation running on the EVM, allowing GraphQL queries to resolve against state stored through the Ethereum blockchain. The interface will most likely be implemented as a smart contract. The contract will receive GraphQL queries, and will automatically parse and execute the underlying read or write, storing or reading from the Ethereum blockchain. The contract will allow custom schemas to be uploaded, and will respond by generating queries for all basic CRUD operations. This behavior will be very similar to the [Prisma](https://github.com/prismagraphql/prisma) project, but running as a smart contract.

The final product will give developers entirely decentralized backends (100% uptime, infinite scalability, excellent security and privacy), without having to worry about databases, infrastructure, and scaling. This will be a complete replacement for a GraphQL backend, allowing the user to move their entire database business logic to the Ethereum blockchain. Most of the development time that went into worrying about scaling, security, and managing databases and software and hardware infrastructure that doesn't directly deal with the business logic of applications will be removed. Developers will be free to focus almost entirely on writing the business logic of their applications, codifying their data types and operations in GraphQL schemas and custom resolvers, and then simply deploying the results to the blockchain. The final product will pave the way for Decentralized GraphQL to become the main development platform for all GraphQL applications (and by the way GraphQL will replace REST in most cases).

## Roadmap

The order is intended to be prioritized and chronological, but is subject to change.

- [ ] Minimum viable GraphQL implementation running on the EVM
- [ ] Full GraphQL implementation running on the EVM
- [ ] Minimum viable auto-generating data access layer running on the EVM (see [Prisma](https://github.com/prismagraphql/prisma))
- [ ] Full auto-generating data access layer running on the EVM (see [Prisma](https://github.com/prismagraphql/prisma))
- [ ] Authentication and authorization of data stored on the blockchain
- [ ] Simple yet powerful developer tooling
- [ ] Optimization

## Justification

### The Internet is decentralized

The exchange of data across the internet is decentralized, which brings a host of benefits. As a whole it has 100% uptime, it has scaled incredibly to handle most every application we’ve thrown at it, and it is extremely fault-tolerant. It was built to survive disasters, and it has.

### The Web is not decentralized

The storage of data across the internet’s greatest domain of applications, the Web, is not decentralized. Content hosted on the Web is most often stored behind the proprietary infrastructure of large companies. This centralization brings a host of issues. Uptime, scalability, and fault-tolerance is subject to their limitations. You may trust them, but in the end that’s all you can rely on. They are a central point of failure.

### Decentralize the Web

New decentralized technologies are coming out to solve these problems. Using worldwide peer-to-peer networks, these technologies will democratize the world’s resources to create large decentralized and distributed virtual machines, file systems, and databases. These technologies offer applications the possibility of 100% uptime, infinite scalability, and extremely low maintenance.

### Decentralize GraphQL

GraphQL is perfectly poised to capitalize on these innovations. With its simple client syntax and its ability to resolve queries across arbitrary data sources, it is possible to plug these decentralized computation and storage solutions into GraphQL. This will offer a seamless entry point for GraphQL applications into the world of decentralized computing and storage. No more complicated infrastructure, no more scaling and uptime issues, just pure client-side GraphQL queries that resolve against an unstoppable decentralized backend.
