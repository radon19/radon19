```text
                        -`                     
                       .o+`                            radon@archlinux @github
                      `ooo/                            -----------------------
                     `+oooo:                           OS: Arch Linux 
                    `+oooooo:                          Role: Fullstack , Blockchain , Web3 Engineer
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
        `/ossssso+/:-        -:/+osssso+-              Frontend: .... Next js , React js, Tailwind Css
       `+sso+:-`                 `.-/+oso:             Backend: .... Rust, Node.js, Express, PostgreSQL
      `++:.                           `-/+/            Web3/EVM: ... Solidity, Foundry, viem, ethers.js, wagmi
      .`                                 `/            Systems: .... Linux, Docker, Kubernetes, Git
```
<div align="center">

# Kedar Singh Naikane

**Full-stack developer · Rust · Blockchain · Linux**

I build full-stack applications and blockchain infrastructure with Rust, TypeScript, React and Next.js—from the interface to the systems underneath it.

[LinkedIn](https://www.linkedin.com/in/kedar-sn/) · [Email](mailto:ks.naikane@gmail.com) · [LeetCode](https://leetcode.com/u/kedar2005/) · [Codeforces](https://codeforces.com/profile/Kedar2005)

```text
radon@linux ~ $ whoami
Full-stack developer. Computer Science student. Linux enthusiast.

radon@linux ~ $ cat approach.txt
Understand the system. Question the assumptions. Make it better.
```

## Selected work

### [Solana DEX Indexer](https://github.com/radon19/solana-indexer)

**Rust · Tokio · Yellowstone gRPC · Carbon · PostgreSQL · SQLx**

A transaction-processing pipeline that turns Solana DEX activity into structured events, with live ingestion and offline capture replay.

- **10 protocol parsers across five ecosystems:** Jupiter, Pump.fun, Raydium, Orca and Meteora. Coverage is instruction-specific.
- **Correct event identity:** preserves parent instruction identity through nested cross-program invocations, database keys and route hops to prevent storage collisions.
- **Explicit failure handling:** bounded channels propagate backpressure; complete finalized blocks and their checkpoints commit atomically. Batched writes, versioned dead-letter recovery and graceful shutdown handle accepted work.
- **Reproducible checks:** recorded verification includes **85 passing unit tests** and a reference replay storing **5,969 transactions and 2,471 swap events**. Replaying again preserved row counts and transaction/slot checksums.

The replay figures describe one reference capture, not sustained mainnet throughput. See the linked verification and supported scope for details.

[Code](https://github.com/radon19/solana-indexer) · [Demo](https://github.com/radon19/solana-indexer/blob/main/demo/demo_indexer.mp4) · [Verification](https://github.com/radon19/solana-indexer/blob/main/docs/validation.txt) · [Scope & limitations](https://github.com/radon19/solana-indexer/blob/main/docs/limitations.md)

### [Indenture](https://github.com/radon19/Indenture)

**Solidity · Foundry · TypeScript · Bun · Next.js · PostgreSQL · Prisma**

A cross-chain credit protocol that turns Ethereum repayment history into a portable on-chain score.

- Integrates Aave V3, Spark and Compound V3 repayment evidence with Merkle and continuity attestations.
- Connects a proving worker, evidence deduplication, tier-based lending and verifiable credit receipts.
- Recorded checks include **112 contract tests and 12 worker tests passing**.

[Code](https://github.com/radon19/Indenture) · [Demo](https://indenture.vercel.app/)

### [StorEx — Wallet-as-a-Service](https://github.com/radon19/StorEx-Waas)

**TypeScript · React · Next.js · Solana · PostgreSQL · Prisma · Tailwind CSS**

A Solana wallet platform with Google sign-in, token balances, transfers and Jupiter swaps.

- Generates wallets server-side, encrypts keys at rest with **AES-256-GCM**, and signs transactions on the server.
- Uses session checks and Zod validation for wallet operations, with configurable swap slippage and USD pricing.

[Code](https://github.com/radon19/StorEx-Waas) · [Demo](https://storex-waas.vercel.app/)

### [AdiJey Engineering Solutions](https://github.com/radon19/adijey)

**Freelance client work · Next.js · TypeScript · Tailwind CSS · Supabase · Vercel**

Delivered the company's website from architecture to deployment: **18 product and service categories**, a PostgreSQL-backed enquiry workflow, Row Level Security and an authenticated admin dashboard.

[Website](https://adijey.com) · [Public site code](https://github.com/radon19/adijey) · [Admin code](https://github.com/radon19/adijey-admin)

## Toolkit

| Area | Technologies |
| --- | --- |
| Full-stack | TypeScript, React, Next.js, Tailwind CSS, Node.js, Express, REST APIs, Zod |
| Systems & data | Rust, Tokio, gRPC, PostgreSQL, SQLx, Prisma, Supabase, MongoDB |
| Blockchain | Solana, Ethereum/EVM, Solidity, Carbon, Foundry, Hardhat, viem, ethers.js, wagmi |
| Environment | Linux, Git, Docker |
| Other languages | Python, SQL, C++, Java |

## Currently exploring

- Linux internals, networking and computer architecture.
- Rust concurrency, data consistency and failure recovery.
- Execution-aware blockchain indexing and smart-contract security.

**B.Tech. in Computer Science and Engineering · Ramdeobaba University, Nagpur · 2024–2028**
