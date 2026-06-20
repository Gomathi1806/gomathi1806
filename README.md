# Gomathi T

**UHI alum · Founder, Lexifi · Founder, newsie.tech**

I build pool-level compliance infrastructure and AI-augmented safety tooling for on-chain capital.

---

## Currently building

### 🔐 [Lexifi](https://lexifi.vercel.app) — V4 compliance infrastructure

- Live on Base Mainnet
- LexifiHook: [`0xb8ab80d8...d92880`](https://basescan.org/address/0xb8ab80d89620c29E71563779111b9cb1d4d92880)
- SDK: [`@lexifi/sdk@1.0.0`](https://www.npmjs.com/package/@lexifi/sdk)
- 5 verified contracts · 58 Foundry tests
- Source: [Lexifi_uniswap_v4hook_compliance](https://github.com/gomathi1806/Lexifi_uniswap_v4hook_compliance)
- `BEFORE_REMOVE_LIQUIDITY` hard-coded `false` at the CREATE2 address — funds cannot be trapped, encoded immutably in the contract address

### 🛡️ [newsie.tech](https://newsie.tech) — AI-augmented DeFi safety scorer

- Live, Stripe-billed Pro tier
- 0–100 protocol safety score, proprietary 5-factor weighted formula
- Stack: Next.js 16 + AI SDK 6 + Anthropic + Neon + Stripe
- Farcaster AI agent + frames also live

### pico — pennies of AI, settled inline

A Farcaster Mini App that runs AI tools and charges a few cents of USDC per call over the x402 protocol. Distribution is via casts: every output gets posted back as a cast, branded made with pico. Users pick a tool (image gen, scrape, ask, summarize thread), pay a few cents of USDC via the x402 protocol, and post the result back as a cast — without leaving the app.

The Mini App is a thin distribution layer on top of upstream APIs (fal.ai, Firecrawl, Anthropic via the Vercel AI Gateway, Neynar). It collects USDC from users via x402, calls the upstream, and returns the result. The operator's take rate is the difference between what the user pays and the upstream cost.

Live @farcaster

### Pico (celo-pico.vercel.app, )
is a MiniPay-native mini app that brings true x402 micropayments to AI tools on Celo — users pay a few cents of cUSD per call to generate images, ask AI, scrape URLs, summarize content, or get DeFi signals, settled atomically via thirdweb's x402 facilitator, slotting directly into MiniPay's "stablecoins for everyday use" thesis.

Live

### Pico_bio_link like buy me a coffe --> pico-celo-bio-link.vercel.app

Pico lets creators in Africa and beyond get paid by their fans using Celo MiniPay — no bank account, no Stripe, no middleman. Create a free bio link page in 30 seconds, set your price, and share it. Fans tap your link, confirm payment in MiniPay, and cUSD goes directly into your wallet. Built for mobile-first creators who want to sell tips, digital guides, or 1:1 calls using the money they already have on Celo.

Live

## Background

- **Uniswap Hook Incubator (UHI)** alum
- UHI capstone proof tx: [`0x0821b530…58f657d6c`](https://basescan.org/tx/0x0821b530f7f973b8d8de5aeeba642985009b24c9f0c57f5ae06f1af58f657d6c)
- Multi-chain shipping: Base, Celo, Farcaster, Uniswap V4

## Reach out

- 🐦 Twitter: [@gomathit4](https://twitter.com/gomathit4)
- 🟣 Farcaster: [@goms](https://farcaster.xyz/goms)
- 💼 LinkedIn: [defidataanalystgomathit](https://www.linkedin.com/in/defidataanalystgomathit/)
- 🌐 [lexifi.vercel.app](https://lexifiio.vercel.app/) · [newsie.tech](https://newsie.tech)
