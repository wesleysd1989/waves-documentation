# Waves Smart Contract

![master](https://img.shields.io/badge/TESTNET-available-4bc51d.svg) ![master](https://img.shields.io/badge/node->%3D0.12.0-4bc51d.svg)

Our realisation of smart contracts will contain two parts:

1. A **Smart Account** language implementation, It is an important property that the smart account does not store any data on the blockchain. A smart account will only have access to blockchain state values that can be retrieved and executed relatively fast, in a “constant” time. these smart accounts can be run for the price of normal transactions with a predefined fee, **without any additional “gas” or other costs**.
2. A **Foundational Layer** for developing various decentralised applications and smart contracts on the blockchain, with a built-in Turing-complete programming language.

We see the syntax of our language as functional, similar to F\#: strong and statically typed.

**Note.** [**Here**](https://wavesplatform.com/files/docs/white_paper_waves_smart_contracts.pdf) you can find our **White Paper** which describes Waves Smart Contract.

# Tutorials

1. [Waves Console Example](https://www.youtube.com/watch?v=QWaZjpiQtHA&feature=youtu.be)
2. [Multi Signature Example](https://www.youtube.com/watch?v=oRmnERIBKzY&feature=youtu.be)
3. [Escrow Example](https://youtu.be/0Ic--oQIQhU)



For More technical details, find the articles below:

1. [Approach and Capabilities](./waves-contracts-language-description/approach-and-capabilities.md)
2. [Language Description](waves-contracts-language-description/language-description.md)
3. [Standard Library Documentation](waves-contracts-language-description/standard-library.md)
4. [Syntax Processor and Executor Implementation Details](waves-contracts-language-description/implementation-details.md)
5. [Creating and Deploying a Script Manually](waves-contracts-language-description/creating-and-deploying-a-script-manually.md)
6. [Script Performance Tests](waves-contracts-language-description/script-performance-tests.md)



