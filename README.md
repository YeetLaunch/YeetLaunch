<div align="center">

# YeetLaunch

### Launch a token on Solana in minutes — with liquidity you can actually trust after it graduates.

*A fully self-contained launch stack: native bonding curve, native AMM, native aggregator & indexer. No third-party DEX in the path.*

[![Create a token](https://img.shields.io/badge/Create_a_token-39FF14?style=for-the-badge)](https://yeetlaunch.io/token-creator)
[![Website](https://img.shields.io/badge/yeetlaunch.io-0b0f14?style=for-the-badge&logo=firefox&logoColor=39FF14)](https://yeetlaunch.io)
[![Whitepaper](https://img.shields.io/badge/Whitepaper-v1.7.2-39FF14?style=for-the-badge)](https://yeetlaunch.io/YeetLaunch_Whitepaper_v1.7.2.pdf)
[![Docs](https://img.shields.io/badge/Docs-repo-14F195?style=for-the-badge)](https://github.com/YeetLaunch/docs)
[![SDK](https://img.shields.io/badge/TypeScript_SDK-repo-39FF14?style=for-the-badge&logo=typescript&logoColor=39FF14)](https://github.com/YeetLaunch/yeet-amm-sdk)

</div>

---

Most launch sites make it easy to start a token and hard to trust what happens next. **YeetLaunch is built around legibility** — fees you can reason about, post-graduation liquidity that's locked and vesting, and anti-dump mechanics documented in the open instead of hidden.

### What makes it different

- ⚡ **Atomic graduation** — the *same transaction* that fills the curve (48 SOL for tokens launched since 14 October 2026) flips the pool from bonding-curve to AMM in place. No waiting, no separate migration, no external venue.
- 💸 **One flat fee** — **1.00% per swap**, from the first trade. Creators earn **0.30% forever**. No hidden pre-skim.
- 🛡️ **Anti-dump, in the open** — a sell cap of at most 5% of reserves per slot (adaptive, with a 0.5% floor) and a 30% permanently locked / 70% creator-vesting LP model. Buys are never restricted. [Read the rules and their limits →](https://yeetlaunch.io/YeetLaunch_Whitepaper_v1.7.2.pdf)
- 🧱 **100% native stack** — the bonding curve, AMM (YeetAMM), aggregator, and indexer are all first-party. The program has been internally security-reviewed and tested; an independent external audit is pending.

### Read more

- 🚀 **[Create a token](https://yeetlaunch.io/token-creator)** — launch one on yeetlaunch.io
- 🔗 **[Launch from your own site](https://github.com/YeetLaunch/docs/blob/main/docs/LAUNCH_FROM_YOUR_SITE.md)** — signing links: your users launch on YeetLaunch from your site, with their own wallet
- 📄 **[Whitepaper (v1.7.2)](https://yeetlaunch.io/YeetLaunch_Whitepaper_v1.7.2.pdf)** — the full protocol design
- 🔀 **[Routing & Integration Guide](https://github.com/YeetLaunch/docs/blob/main/docs/YEETAMM_ROUTING_INTEGRATION.md)** — for aggregators integrating YeetAMM pools
- 🧰 **[YeetAMM TypeScript SDK](https://github.com/YeetLaunch/yeet-amm-sdk)** — PDA derivation, swap builders, account/error decoding, REST client
- 🛠️ **[Developer portal](https://yeetlaunch.io/dev)** — program IDs, official addresses, live JSON API, and the DEX integration spec
- 🌐 **[yeetlaunch.io](https://yeetlaunch.io)**

<div align="center">
<sub>The protocol and platform source is proprietary. Public documentation lives in <a href="https://github.com/YeetLaunch/docs">YeetLaunch/docs</a>.</sub>
</div>
