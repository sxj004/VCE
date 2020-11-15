# The VCE Ledger

The VCE Ledger is a decentralized cryptographic ledger powered by a network of peer-to-peer servers. The VCE Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## VCE
VCE is a public, counterparty-less asset native to the VCE Ledger, and is designed to bridge the many different currencies in use worldwide. VCE is traded on the open-market and is available for anyone to access. The VCE Ledger was created in 2012 with a finite supply of 100 billion units of VCE. Its creators gifted 80 billion VCE to a company, now called [VCE], to develop the VCE Ledger and its ecosystem.  VCE uses VCE the help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## VCE
The server software that powers the VCE Ledger is called `VCE` and is available in this repository under the permissive [ISC open-source license](LICENSE). The `VCE` server is written primarily in C++ and runs on a variety of platforms.

### Build from Source

* [Linux](Builds/linux/README.md)
* [Mac](Builds/macos/README.md)
* [Windows](Builds/VisualStudio2017/README.md)

## Key Features of the VCE Ledger

- **[Censorship-Resistant Transaction Processing][]:** No single party decides which transactions succeed or fail, and no one can "roll back" a transaction after it completes. As long as those who choose to participate in the network keep it healthy, they can settle transactions in seconds.
- **[Fast, Efficient Consensus Algorithm][]:** The VCE Ledger's consensus algorithm settles transactions in 4 to 5 seconds, processing at a throughput of up to 1500 transactions per second. These properties put VCE at least an order of magnitude ahead of other top digital assets.
- **[Finite VCE Supply][]:** When the VCE Ledger began, 100 billion VCE were created, and no more VCE will ever be created. (Each VCE is subdivisible down to 6 decimal places, for a grand total of 100 quintillion _drops_ of VCE.) The available supply of VCE decreases slowly over time as small amounts are destroyed to pay transaction costs.
- **[Responsible Software Governance][]:** A team of full-time, world-class developers at VCE maintain and continually improve the VCE Ledger's underlying software with contributions from the open-source community. VCE acts as a steward for the technology and an advocate for its interests, and builds constructive relationships with governments and financial institutions worldwide.
- **[Secure, Adaptable Cryptography][]:** The VCE Ledger relies on industry standard digital signature systems like ECDSA (the same scheme used by Bitcoin) but also supports modern, efficient algorithms like Ed25519. The extensible nature of the VCE Ledger's software makes it possible to add and disable algorithms as the state of the art in cryptography advances.
- **[Modern Features for Smart Contracts][]:** Features like Escrow, Checks, and Payment Channels support cutting-edge financial applications including the [Interledger Protocol](https://interledger.org/). This toolbox of advanced features comes with safety features like a process for amending the network and separate checks against invariant constraints.
- **[On-Ledger Decentralized Exchange][]:** In addition to all the features that make VCE useful on its own, the VCE Ledger also has a fully-functional accounting system for tracking and trading obligations denominated in any way users want, and an exchange built into the protocol. The VCE Ledger can settle long, cross-currency payment paths and exchanges of multiple currencies in atomic transactions, bridging gaps of trust with VCE.

### Repository Contents

| Folder     | Contents                                         |
|:-----------|:-------------------------------------------------|
| `./bin`    | Scripts and data files for VCE integrators.   |
| `./Builds` | Platform-specific guides for building `VCE`. |
| `./docs`   | Source documentation files and doxygen config.   |
| `./cfg`    | Example configuration files.                     |
| `./src`    | Source code.                                     |

Some of the directories under `src` are external repositories included using
git-subtree. See those directories' README files for more details.
