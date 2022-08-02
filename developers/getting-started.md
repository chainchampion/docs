---
description: Everything you need to build your first interchain application
---

# Getting started

Abacus makes interchain communication straightforward by providing a simple API for sending and receiving messages from smart contracts. You can build a new interchain application from the ground up or integrate messaging into your existing app.

Similar to single-chain dApp development, the high level approach is to:

1\. write/modify your contracts,&#x20;

2\. deploy them to the network(s), and&#x20;

3\. utilize contracts in your application.&#x20;

The Abacus SDK provides the utilities you'll need for all three steps.

### Installing the SDK Package

The SDK package can be added to you project using yarn or npm (yarn is recommended).

```shell
yarn add @abacus-network/sdk
```

The SDK includes other dependencies you may need, such as the `@abacus-network/app` package for extending Abacus contracts and the `@abacus-network/utils` package for various utility functions.

### **Building Interchain Apps**

_**Integrating contracts with Abacus?**_ See the [writing contracts](writing-contracts/) section to learn about writing and testing contracts.

_**Ready to deploy your contracts?**_ Use the SDK's [deployment tooling](writing-contracts/deploying-contracts/) to facilitate deployment across multiple chains.

_**Interacting with contracts?**_ Learn about [building an application](building-applications/) on top of interchain contracts.

### **Example Apps**

The [Hello World](https://github.com/abacus-network/abacus-app-template) app shows a contract that sends a 'hello' message to a set of destination chains, and has an examples of how to deploy and interact with that contract.

For more examples, take a look at the [example applications](examples/) page to see what you can build.

### Help and support

If you need help building your interchain applications, you can always reach out on [discord](https://discord.com/invite/KBD3aD78Bb) or [twitter](https://twitter.com/Abacus\_Network)!

