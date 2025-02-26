---
title: Why Build With Axon
sidebar_position: 1
---

Axon facilitates the flow of assets and information between DApps built on different blockchains for a multi-chain future. With Axon, web3 builders can easily transform their ideas into reality. Whatever your project is, whether it’s GameFi, DeFi, or NFT, Axon offers a scalable and cost-effective framework to deploy your applications.



### High TPS

Axon uses a new Byzantine Fault Tolerance (BFT) based consensus algorithm called [Overlord Consensus](https://github.com/nervosnetwork/overlord). It decouples transaction sequence from state consensus, so that execution and consensus process can be carried out simultaneously.

This parallel execution supports over 3000 TPS (Transactions Per Second) across hundreds of nodes, with a transaction delay of less than a few seconds.



### Easy-to-Deploy

Axon provides a full-fledged toolkit that enables web3 developers to start building right away without having to understand the fundamentals. Designed with a different approach than Relayers, Axon automates off-chain communication, thereby significantly reducing deployment costs.

The hands-on tutorial <b>[Zero to Axon with Axon-cli](/for-dapp-devs/Zero_To_Axon_With_Axon_Cli)</b> teaches you how to build a chain from scratch in less than 15 minutes.



### Highly Interoperable

Axon will soon be fully compatible with Inter-Blockchain Communication (IBC)—the gateway to the Cosmos ecosystem, and later with all EVM-based blockchains. In addition to these top two thriving networks, Axon will be continually onboarding more protocols.



### Here’s how we do it

- CKB-VM
- Overlord Consensus
- P2P Network
- Mempool



**CKB-VM**

CKB Virtual Machine (CKB-VM) is the software implementation of the RISC-V instruction set used as a scripting VM. CKB-VM can call contracts on CKB, allowing protocols to be upgraded along with the contracts without hard-coding. With a variety of algorithms precompiled, CKB-VM greatly lowers the barrier to writing EVM-compatible contracts.

- [Explore more](https://github.com/nervosnetwork/ckb-vm)



**Overlord Consensus**

Overlord is a BFT consensus algorithm that supports over 3000 TPS across hundreds of nodes, with a transaction delay of less than a few seconds. By decoupling transaction sequence from state consensus, Overlord Consensus enables the  execution and consensus process to run in parallel.

- [Explore more](https://github.com/nervosnetwork/overlord)



**P2P Network**

The network of Axon is developed on top of Tentacle, a multi-layered P2P protocol stack, where each layer functions in a relatively independent manner. This design provides maximum flexibility for developers and reduces the complexity of development.

- [Explore more](https://blog.cryptape.com/tentacle-the-network-layer-of-ckb)



**Mempool**

Axon's mempool performs multiple validations before committing transactions to the block. When an influx of transactions comes in, the mempool slices these transactions into 4 queues to avert TPS exceeding the block interval limits.

