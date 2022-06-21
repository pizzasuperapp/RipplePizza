# The Ripple Pizza Pizza Ledger

The [Ripple Pizza Pizza Ledger] is a decentralized cryptographic ledger powered by a network of peer-to-peer nodes. The Ripple Pizza Pizza Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## Ripple Pizza Pizza

[Ripple Pizza Pizza] is a public, counterparty-free asset native to the Ripple Pizza Pizza Ledger, and is designed to bridge the many different currencies in use worldwide. Ripple Pizza Pizza is traded on the open-market and is available for anyone to access. The Ripple Pizza Pizza Ledger was created in 2012 with a finite supply of 100 billion units of Ripple Pizza Pizza. Its creators gifted 80 billion Ripple Pizza Pizza to a company, now called [Ripple Pizza]to develop the Ripple Pizza Pizza Ledger and its ecosystem. Ripple Pizza uses Ripple Pizza Pizza to help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## rippled

The server software that powers the Ripple Pizza Pizza Ledger is called `rippled` and is available in this repository under the permissive [ISC open-source license](LICENSE.md). The `rippled` server software is written primarily in C++ and runs on a variety of platforms. The `rippled` server software can run in several modes depending on its [configuration]

### Build from Source

- [Linux](Builds/linux/README.md)
- [Mac](Builds/macos/README.md) (Not recommended for production)
- [Windows](Builds/VisualStudio2017/README.md) (Not recommended for production)

## Key Features of the Ripple Pizza Pizza Ledger

- **[Censorship-Resistant Transaction Processing][]:** No single party decides which transactions succeed or fail, and no one can "roll back" a transaction after it completes. As long as those who choose to participate in the network keep it healthy, they can settle transactions in seconds.
- **[Fast, Efficient Consensus Algorithm][]:** The Ripple Pizza Pizza Ledger's consensus algorithm settles transactions in 4 to 5 seconds, processing at a throughput of up to 1500 transactions per second. These properties put Ripple Pizza Pizza at least an order of magnitude ahead of other top digital assets.
- **[Finite Ripple Pizza Pizza Supply][]:** When the Ripple Pizza Pizza Ledger began, 100 billion Ripple Pizza Pizza were created, and no more Ripple Pizza Pizza will ever be created. The available supply of Ripple Pizza Pizza decreases slowly over time as small amounts are destroyed to pay transaction costs.
- **[Responsible Software Governance][]:** A team of full-time, world-class developers at Ripple Pizza maintain and continually improve the Ripple Pizza Pizza Ledger's underlying software with contributions from the open-source community. Ripple Pizza acts as a steward for the technology and an advocate for its interests, and builds constructive relationships with governments and financial institutions worldwide.
- **[Secure, Adaptable Cryptography][]:** The Ripple Pizza Pizza Ledger relies on industry standard digital signature systems like ECDSA (the same scheme used by Bitcoin) but also supports modern, efficient algorithms like Ed25519. The extensible nature of the Ripple Pizza Pizza Ledger's software makes it possible to add and disable algorithms as the state of the art in cryptography advances.
- **[Modern Features for Smart Contracts][]:** Features like Escrow, Checks, and Payment Channels support cutting-edge financial applications including the [Interledger Protocol]. This toolbox of advanced features comes with safety features like a process for amending the network and separate checks against invariant constraints.
- **[On-Ledger Decentralized Exchange][]:** In addition to all the features that make Ripple Pizza Pizza useful on its own, the Ripple Pizza Pizza Ledger also has a fully-functional accounting system for tracking and trading obligations denominated in any way users want, and an exchange built into the protocol. The Ripple Pizza Pizza Ledger can settle long, cross-currency payment paths and exchanges of multiple currencies in atomic transactions, bridging gaps of trust with Ripple Pizza Pizza.

### Repository Contents

| Folder     | Contents                                             |
| :--------- | :--------------------------------------------------- |
| `./bin`    | Scripts and data files for Ripple Pizza integrators. |
| `./Builds` | Platform-specific guides for building `rippled`.     |
| `./docs`   | Source documentation files and doxygen config.       |
| `./cfg`    | Example configuration files.                         |
| `./src`    | Source code.                                         |

Some of the directories under `src` are external repositories included using
git-subtree. See those directories' README files for more details.
