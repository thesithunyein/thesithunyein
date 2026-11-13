<div align="center">

# Sithu Nyein

**Founder of [SeedlessPay](https://seedlesspay.com) · Web3 & AI engineer · Yangon, Myanmar**

I'm building SeedlessPay so freelancers anywhere get paid safely: the client pays USDC into escrow before the work starts, and the money is released as they approve it.

[![SeedlessPay](https://img.shields.io/badge/seedlesspay.com-1a7a50?style=for-the-badge)](https://seedlesspay.com)
[![Website](https://img.shields.io/badge/sithunyein.com-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://sithunyein.com)
[![X](https://img.shields.io/badge/@thesithunyein-111827?style=for-the-badge&logo=x&logoColor=white)](https://x.com/thesithunyein)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111827?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sithunyein)

</div>

---

## SeedlessPay

<a href="https://seedlesspay.com"><img src="https://raw.githubusercontent.com/SeedlessPay/seedlesspay/main/docs/screenshot-home.png" alt="SeedlessPay: Get paid safely" width="100%"></a>

**Get paid safely.** Freelancers paid by clients in other countries lose money to late payers and non-payers, and I have had this problem myself for years. Sending a wallet address protects nobody. Marketplaces protect you by holding your money and taking 5% to 20% of it.

SeedlessPay commits the money before the work starts:

1. The freelancer sends an invoice link with up to 5 milestones.
2. The client pays the full amount in USDC into an escrow contract on Avalanche that nobody owns.
3. Each milestone is released when the client approves it, or automatically after a 7-day review. Undelivered milestones go back to the client.

The freelancer's wallet opens with a passkey (Face ID), with no seed phrase, and network fees are sponsored.

**Status:** public beta on Avalanche Fuji · contracts source-verified · 52 tests passing · next: independent security review, then mainnet.

[Try the beta](https://seedlesspay.com/app) · [Code](https://github.com/SeedlessPay/seedlesspay) · [@seedlesspay](https://x.com/seedlesspay)

## Track record

- 🏆 **Circle Arc Microgrants winner**: [Olinea](https://sithunyein.com/work/olinea), a post-quantum USDC vault on Arc mainnet
- 🏆 **Superteam Agentic Engineering Grant**: [Equxi](https://sithunyein.com/work/equxi), slashable bonds for AI agents on Solana
- 🥉 **Pollar 3rd place**: [Susunaku](https://sithunyein.com/work/susunaku), rotating USDC savings on Stellar
- 🔧 **Open source**: end-to-end latency instrumentation with correlation IDs in [KeeperHub v3.12.0](https://github.com/KeeperHub/keeperhub/releases/tag/v3.12.0)

## Payment and trust contracts I've shipped

| Project | What it does | Where | Proof |
| :--- | :--- | :--- | :--- |
| **[Olinea](https://sithunyein.com/work/olinea)** | USDC vault that releases funds only when a post-quantum signature verifies on-chain. No owner, no admin, no upgrade path. | Arc mainnet | Arc Microgrants winner |
| **[Equxi](https://sithunyein.com/work/equxi)** | Agent operators lock a bond, rules live on-chain, misbehavior gets slashed and victims compensated. | Solana | Superteam grant |
| **[Kyrona](https://sithunyein.com/work/kyrona)** | Spending limits for a NEAR account, enforced by a contract: payee list, per-payment and daily caps, a lock. | NEAR mainnet | [Refused a prompt-injected agent payment](https://nearblocks.io/txns/Dz7GpQ9bBKzuuHXPDZ6H4F15qfAqBu9VExzANT2wzTCK) |
| **[Hasp](https://sithunyein.com/work/hasp)** | One-script-tag checkout: the buyer pays in almost any coin, the seller gets the exact USDC price. | NEAR Intents | Live mainnet quotes, 17 tests |
| **[HireWif](https://sithunyein.com/work/hirewif)** | Bonded agent market: no answer in 10 minutes and the agent's bond pays the hirer back. | Robinhood Chain mainnet | [Verified contract](https://robinhoodchain.blockscout.com/address/0xadf0244fEE999B019EDc712Ec5345c65C8506c31), 31 tests |
| **[Witness](https://sithunyein.com/work/witness)** | A human approves one exact agent action with a device passkey; the contract rejects anything over the ceiling. | Mezo · Monad | 41 contract tests |
| **[Meter](https://sithunyein.com/work/meter)** | Pay-per-call API gateway: any HTTP endpoint charges USDC per request, no API keys or accounts. | Arc mainnet | 22 tests, replay blocked per receipt |

<details>
<summary><b>More builds</b></summary>

<br>

- **[bill402](https://sithunyein.com/work/bill402)**: create an invoice, get an x402 URL, settle in USDC on Base mainnet
- **[Susunaku](https://sithunyein.com/work/susunaku)**: savings circles where members pay each other wallet to wallet (Pollar 3rd place)
- **[Swiposaur](https://sithunyein.com/work/swiposaur)**: 3D voxel browser runner with procedural meshes and synthesized audio
- **[Spark](https://sithunyein.com/work/spark)**: Attestcoin proves a Sepolia payment, then credit opens on Creditcoin
- **[pi River](https://sithunyein.com/work/pi-river)**: confidential Hold'em with Inco Lightning-encrypted hole cards (Inco × Megapot honorable mention)
- **[Consensus](https://sithunyein.com/work/consensus)**: N-of-M multisig trading desk from Telegram (Zerion honorable mention)
- **[Vectra](https://github.com/thesithunyein/vectra)**: operator downtime briefs with Solana-attested shift handoffs (ChainHack 2026 top 6)
- **[DeleGate](https://github.com/thesithunyein/delegate)**: ERC-7710 delegated agents that trade under per-day spending caps

</details>

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-111827?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

![Avalanche](https://img.shields.io/badge/Avalanche-E84142?style=flat-square&logo=avalanche&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![NEAR](https://img.shields.io/badge/NEAR-000000?style=flat-square&logo=near&logoColor=white)
![Base](https://img.shields.io/badge/Base-0052FF?style=flat-square&logo=coinbase&logoColor=white)
![Stellar](https://img.shields.io/badge/Stellar-111827?style=flat-square&logo=stellar&logoColor=white)
![ERC-4337](https://img.shields.io/badge/ERC--4337-111827?style=flat-square)
![x402](https://img.shields.io/badge/x402-111827?style=flat-square)

## Writing

- [Why Failed Solana Transactions Need a Diagnosis Layer](https://sithunyein.com/blog/solana-tx-diagnosis)
- [Why I'm Betting on Solana from Myanmar](https://sithunyein.com/blog/web3-from-myanmar)
- [From English Literature to Computer Science](https://sithunyein.com/blog/english-to-code)

## Now

Building SeedlessPay toward a security review and Avalanche mainnet, while studying CS at [University of the People](https://www.uopeople.edu/).

---

<div align="center">

[seedlesspay.com](https://seedlesspay.com) · [sithunyein.com](https://sithunyein.com) · [Email](mailto:sithunyein.mailto@gmail.com) · [X](https://x.com/thesithunyein)

</div>
