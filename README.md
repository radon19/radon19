```text
                        -`                     
                       .o+`                            radon@archlinux @github
                      `ooo/                            -----------------------
                     `+oooo:                           OS: Arch Linux 
                    `+oooooo:                          Role: Backend , Blockchain , Web3 Engineer
                    -+oooooo+:                         Uptime: 21 Years
                  `/:-:++oooo+:                        Focus: Low Level Programming, Distributed Systems
                 `/++++/+++++++:                       Languages: Rust, Solidity, TypeScript, Python, C++, Java
                `/++++++++++++++:              
               `/+++ooooooooooooo/`                    - Contact ---------------------
              ./ooosssso++osssssso+`                   GitHub: ...... github.com/radon19
             .oossssso-````/ossssss+`                  LinkedIn: .... /in/kkedarsinghnaikane
            -osssssso.      :ssssssso.                 LeetCode: .... leetcode.com/u/kedar2005
           :osssssss/        osssso+++.        
          /ossssssss/        +ssssooo/-                - Stack & Systems -------------
        `/ossssso+/:-        -:/+osssso+-              Backend: .... Node.js, Express, PostgreSQL
       `+sso+:-`                 `.-/+oso:             Web3/EVM: ... Hardhat, viem, ethers.js, wagmi
      `++:.                           `-/+/            Systems: .... Linux, Docker, Kubernetes, Git
      .`                                 `/    
```
<div align="center">

# Kedar Singh Naikane

### Backend & Blockchain Engineer | Systems-minded Developer

I build blockchain infrastructure, backend systems, and low-level software from first principles.

[![GitHub](https://img.shields.io/badge/GitHub-radon19-181717?style=flat&logo=github)](https://github.com/radon19)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/kkedar-singh-naikane/)
[![LeetCode](https://img.shields.io/badge/LeetCode-kedar2005-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/kedar2005/)
[![Codeforces](https://img.shields.io/badge/Codeforces-Kedar2005-1F8ACB?style=flat&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Kedar2005)

![Profile views](https://komarev.com/ghpvc/?username=radon19&style=flat-square&color=2563EB&label=Profile+views)

</div>

---

## About me

- I enjoy learning how technology works beneath the abstractions, from operating systems and networking to runtimes and distributed systems.
- I prefer building rather than only assembling: backend services, protocol integrations, data layers, and blockchain infrastructure.
- I work primarily with Linux and use Arch as my daily environment.
- I care about fundamentals, clear interfaces, correctness, security, and understanding trade-offs.
- I am constantly exploring new tools and ideas instead of following a single traditional stack.

## What I build

My strongest interests are:

- **Blockchain and Web3:** smart contracts, wallet infrastructure, EVM internals, Solana, transaction flows, and on-chain applications.
- **Backend systems:** APIs, authentication, databases, validation, service design, and production-minded architecture.
- **Low-level and systems programming:** Linux, memory, processes, networking, concurrency, runtimes, and how abstractions work underneath.
- **Developer infrastructure:** Docker, Kubernetes, observability-minded services, and reliable deployment workflows.

## Technical toolkit

<table>
<tr>
<td valign="top" width="50%">

### Backend & application

`TypeScript` `Node.js` `MongoDB` `Express` `Next.js` `PostgreSQL` `Prisma` `REST APIs` `Zod`

`Python` `NumPy` `Pandas` `Seaborn` `Matplotlib`

</td>
<td valign="top" width="50%">

### Blockchain & Web3

`Solidity` `Hardhat` `EVM` `Ethereum` `Solana` `viem` `ethers.js` `web3.js` `wagmi`

Smart contracts, wallet infrastructure, RPC interactions, transaction signing, and DeFi integrations.

</td>
</tr>
<tr>
<td valign="top">

### Systems & infrastructure

`Linux` `Arch Linux` `Docker` `Kubernetes` `Git` `Networking` `Concurrency`

Interested in operating systems, compilers, runtimes, memory, and low-level programming.

</td>
<td valign="top">

### Web interfaces

`Tailwind CSS` `HTML` `CSS`

I use web interfaces to make systems usable, while my deepest focus remains blockchain, backend, and infrastructure.

</td>
</tr>
</table>

## Engineering principles

```text
Understand the abstraction.
Respect the boundary.
Validate the input.
Make failure explicit.
Measure before optimizing.
Build the smallest correct system.
```

## Currently learning

- Rust for safe, performant systems and deeper blockchain development.
- Advanced smart contract security, protocol design, and production-grade blockchain infrastructure.
- Low-level programming, distributed systems, and production infrastructure.
- New tools and development patterns across the Ethereum and Solana ecosystems.

## Find me online

| Platform | Profile |
| --- | --- |
| GitHub | [@radon19](https://github.com/radon19) |
| LinkedIn | [Kedar Singh Naikane](https://www.linkedin.com/in/kedar-sn/) |
| LeetCode | [kedar2005](https://leetcode.com/u/kedar2005/) |
| Codeforces | [Kedar2005](https://codeforces.com/profile/Kedar2005) |

## Featured project

### [Indenture](https://github.com/radon19/Indenture)

**A cross-chain credit protocol that makes on-chain repayment history portable.**

A perfect repayment history on Ethereum counts for nothing the moment you touch a new chain — lenders can't tell a good borrower from a fresh wallet, so everyone gets pushed into the same over-collateralized terms. Indenture fixes that:

- Converts verified repayment history from **Aave V3, Spark, and Compound V3** into a portable **400–900 on-chain credit score**.
- Proves repayments with **Merkle and continuity attestations**, verified on-chain via precompile — no self-reported claims.
- Hardens scoring against Sybil and flash-loan attacks by capping stake credit at 35% of lifetime volume.
- Runs a **Bun-based proving** worker that pre-checks receipts, summarizes logs, and builds attestations, rejecting invalid input in 68ms before any external I/O.
- Verified by **124 automated tests** (112 contract + 12 worker) at a 100% pass rate.
- Built with Solidity, Next.js, TypeScript, Bun, PostgreSQL, Prisma, and Creditcoin for score and lending infrastructure.


### [StorEx-WaaS](https://github.com/radon19/StorEx-Waas)

**A wallet-as-a-service platform for crypto trading, built end to end.**

StorEx provisions Solana wallets through Google sign-in and provides a production-oriented trading pipeline:

- Generates real Solana keypairs on account creation.
- Encrypts private keys at rest with **AES-256-GCM**; keys never reach the browser.
- Reads live balances from Solana and prices assets through Jupiter.
- Quotes, signs, and executes swaps through **Jupiter Aggregator v2**.
- Uses **TypeScript, Next.js, PostgreSQL, Prisma, Zod, and Tailwind CSS** end to end.
- Keeps authentication, validation, wallet operations, and transaction signing on the server side.

This project reflects how I approach engineering: understand the underlying protocol, design around security boundaries, and build the complete path from user action to infrastructure.

<div align="center">

### Always learning. Always building. Always going deeper.

</div>
