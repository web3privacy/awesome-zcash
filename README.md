# awesome-zcash

Awesome Zcash Ecosystem (exhaustive curated list with website links)

A structured, privacy-focused curated list of projects in the Zcash (ZEC) ecosystem, modeled on awesome-privacy style lists. Zcash enables optional strong privacy via zero-knowledge proofs (shielded pools: Sprout/Sapling/Orchard + Unified Addresses). 

Ddraws from official ecosystem pages, ZecHub, community trackers (e.g. eli5defi dashboard ~77 projects as of mid-2026), forum listings, and active sites as of late July 2026 (Ironwood/NU6.3 era; zcashd EOL; Zebra + Zakura dominant). 

Status change — always verify shielded support, audits, network upgrade compatibility, and security yourself. 

Prefer open-source, self-custody, and shielded-by-default tools. 

**Organizations / Core Stewards**
- ZODL (Zcash Open Development Lab) — Full-stack core protocol R&D, zcashd transition management, Zodl wallet, Zallet. https://zodl.com
- Zcash Foundation (ZF) — 501(c)(3); zebrad, FROST, governance, Zcon, z.cash stewardship. https://zfnd.org
- Shielded Labs — Donation-funded (Switzerland); Crosslink, Network Sustainability Mechanism, dynamic fees. https://shieldedlabs.net (or via z.cash/ecosystem)
- Zcash Community Grants (ZCG) — Community-elected funding for independent projects. https://zcashcommunitygrants.org
- Sovright — Nonprofit infrastructure (Argos recovery, mining pool, block relay; from former Bootstrap). mining.sovright.com · relay.sovright.com (forum/community announcements)
- ZecHub — Volunteer education hub, wiki, dashboards, content. https://zechub.wiki
- Valar Group / Project Tachyon — Scaling research, Zakura node, proof-carrying wallets. https://zakura.com (Zakura) · related Tachyon discussions
- QEDIT — Privacy systems; Zcash Shielded Assets (ZSA) lead. Via z.cash/ecosystem/qedit
- Financial Privacy Foundation (FPF) — Back-office support for decentralized teams. https://www.financialprivacyfoundation.org
- Zk Av Club — Privacy-first AV/events/recording. Via ZF / community Regional communities (Brazil, India, Arabia, Nigeria, Ghana, Türkiye, etc.) — Grant-funded local chapters (e.g. X/@ZcashArabia)
- Historical/related: Electric Coin Company (ECC) origins, Bootstrap.

**Full Nodes & Core Infrastructure**
- zebrad (Zebra) — Independent Rust full node (ZF); primary consensus post-zcashd. https://zfnd.org · https://github.com/ZcashFoundation/zebra
- Zakura — High-performance Rust full node (Zebra fork by Valar/Tachyon); fast sync, pruning, snapshots, zcashd RPC compat, Ironwood support; scale-oriented. https://zakura.com · https://github.com/zakura-core/zakura
- zcashd — Original C++ node (EOL ~July 2026; security patches only). https://github.com/zcash/zcash
- Zaino — Modern Rust indexer (replaces lightwalletd; Zingo Labs). https://zingolabs.org · GitHub zingolabs/zaino
lightwalletd — Legacy light-client backend. https://github.com/zcash/lightwalletd
- Zallet — New wallet/RPC daemon (ZODL; zcashd wallet successor; Z3 stack component). Via zodl.com
- Z3 Stack — Unified zebrad + Zaino + Zallet effort.
- Sovright Relay — Low-latency public block relay. https://relay.sovright.com
- ZEC.PRO — Open-source infra (explorers, lightwalletd endpoints, tools). https://zec.pro
Related: Nym Mixnet integration for network privacy.
- Zcash Warp Sync - Fast synchronization engine that significantly reduces initial wallet sync time: https://github.com/zingolabs/warp-sync
- zcash-sync - Synchronization utilities for Zcash wallets and services: https://github.com/zingolabs/zcash-sync 

**Wallets (prioritize shielded-by-default / Orchard + Unified Addresses)**

Flagship 

- Zodl (formerly Zashi) — Self-custody, shielded-by-default mobile (iOS/Android); Tor/Arti, CrossPay swaps. https://zodl.com
- Zingo! — Shielded-first mobile + desktop (Orchard/UA strong support; Zingo Labs). https://zingolabs.org
- Ywallet / Zkool — Multi-pool power-user (all pools, advanced features, multi-account; Ywallet successor elements). https://ywallet.app
- Cake Wallet — Multi-coin privacy wallet with active shielded ZEC. https://cakewallet.com
- Edge Wallet — Multi-asset non-custodial with shielded ZEC. https://edge.app
- Unstoppable Wallet — Multi-currency self-custody with shielded support. https://unstoppable.money
- Vizor — macOS/desktop (Keplr-related; shielded-by-default, Keystone). https://vizor.cash (or community)
- Ezcash, Nozy Wallet, Zafu Wallet (browser extension), Zipher (experimental/agents), others (community/GitHub).

**Hardware / Multi-sig / Browser**

- Keystone — Air-gapped open-source hardware with shielded support. https://keystonewallet.com
- Trezor / Ledger — Hardware (transparent primary; check current shielded status). https://trezor.io · https://ledger.com
- Vultisig — Seedless multi-factor multi-chain vault. https://vultisig.com
- Brave Wallet + MetaMask Snap / WebZJS — Browser/shielded integrations.
- Legacy/recovery: Zecwallet Lite (Sapling-era; use Argos for stuck funds via Sovright).

Note: Confirm NU6.x/Ironwood compatibility. Many multi-coin wallets have limited or transparent-only ZEC.

**Payments & Merchant Tools**

- CipherPay — Non-custodial “Stripe for Zcash”; direct shielded ZEC to merchant wallets (viewing keys); Shopify/WooCommerce, API, x402/agent support. https://cipherpay.app or https://www.cipherpay.app
- ZGo — Browser-based POS / any-device terminal. https://zgo.cash
- Flexa — Retail payments network (Zodl integration). Via flexa.network / ecosystem
- Free2z — Anonymous content + private donations. https://free2z.cash
- BTCPay Server (Zcash plugin) — Self-hosted open-source gateway.
- Zimppy — Machine-to-machine / AI agent payments (Orchard). https://zimppy.xyz
- Dizzy Wallet — Discord bot for Zcash txs.

**Custodial multi-coin**: NOWPayments, CoinGate, Plisio, Overpay.com, etc.
**Others**: Zapp (messenger + payments) https://www.justzappit.xyz

**Block Explorers & Analytics**

- zcashinfo.com — Network/mining data (Foundry). https://zcashinfo.com
- Zcash Block Explorer (Nighthawk / community) — https://mainnet.zcashexplorer.app
- CipherScan — Privacy-first explorer. https://cipherscan.app
- ZEC.PRO explorers — Mainnet/testnet. https://explorer.zec.pro · testnet variant
- Blockchair, Bitquery — Multi-chain with Zcash data.
- ZecStats — Real-time network/shielding metrics. https://zecstats.com
- OpenZcash — Dev Fund / Lockbox / grants transparency. https://openzcash.org
- Exblo (testnet), Zcash.Space (UA parser) https://zcash.space, ZECping, zecprice.com, etc.

**Developer Tools, Libraries & Specs**

- ZIPs — Protocol source of truth. https://zips.z.cash
- Zcash Protocol Specification, Halo 2, librustzcash, official Wallet SDKs.
- WebZJS + MetaMask Snap — Browser library.
- FROST for Zcash — Threshold signatures. https://zfnd.org/frost
- ZeWIF — Wallet interchange format (Zingo + Blockchain Commons).
- zecd — Alternative wallet-server style interface.

**GitHub orgs**: github.com/zcash, github.com/ZcashFoundation, github.com/zingolabs, zakura-core, etc.

- Ziggurat — Network test suite. https://github.com/runziggurat/zcash

**Developer Libraries**

- zingolib - Rust library powering Zingo and other light wallets with Unified Address, Orchard, and lightwalletd support.
- librustzcash - Core Rust libraries implementing Zcash protocols, cryptography, wallet functionality, and transaction building: https://github.com/zcash/librustzcash
- ZcashLightClientKit - Swift SDK for building shielded Zcash wallets on Apple platforms : https://github.com/zcash/ZcashLightClientKit
- Zcash Android Wallet SDK - Android SDK for integrating shielded Zcash functionality into mobile applications: https://github.com/zcash/zcash-android-wallet-sdk
- zcash-localnet - Local multi-node Zcash network for development, testing, and integration: https://github.com/zcash/zcash-localnet
- Zcash DevTool - Utilities for testing, debugging, and developing Zcash applications: https://github.com/zcash/zcash-devtool
- zcash-testnet-wallet - One-command testnet wallet: prebuilt zcash-devtool, utest1 address + QR, funded from a faucet, plus a viewing-key payment watcher: https://github.com/anukulpandey/zcash-testnet-wallet

_Read the Docs / developer portals via z.cash and ZF._

**Protocol Research, Upgrades & Cryptography**

- Network upgrades (NU series, Ironwood/NU6.3 new pool mechanics, etc.).
- Project Tachyon — Scaling (proof-carrying wallets, oblivious sync, recursive proofs toward high TPS).
- Crosslink — Hybrid PoW/PoS finality (Shielded Labs).
- Zcash Shielded Assets (ZSA) — Private user-issued tokens (QEDIT).
- FROST, quantum recoverability, Network Sustainability Mechanism, block-time proposals, Ztarknet (STARK checker ideas), etc.
- Foundational: Zerocash paper, Halo recursive proofs.

**DeFi, Bridges & Cross-Chain**

- NEAR Intents, Maya Protocol, THORChain / THORSwap, SwapKit — Native/near-native ZEC swaps. (THORSwap via ecosystem; SwapKit integrated)
- Houdini Swap, LeoDex, Avalanche Redbridge, OmniBridge / wrapped ZEC (Solana, EVM variants like zenZEC, Universal).
- Emerging: Rhea Finance (NEAR), Hyperliquid (perps + BitFrost bridge), Project 0 (lending), etc.

_Privacy note: Prefer native/shielded paths where possible._

**Exchanges & On/Off-Ramps**

- Major CEX (check shielded deposit/withdrawal): Coinbase, Kraken, Binance, Gemini, KuCoin, etc.
- Non-custodial/instant: ChangeNOW, StealthEx, Changelly, Houdini Swap, etc.
- Regional/others: BitcoinVN, CoinDCX, Airtm.

_Always verify current privacy policies and support._

**Mining**

- Pools: Foundry (major + explorer), ViaBTC, F2Pool, 2Miners, Fortitude, Sovright (testnet→mainnet; shielded payouts, decentralization focus) — mining.sovright.com
- Equihash; monitoring via Miningpoolstats, zcashinfo.com.

**Education & Community Resources**

- z.cash — Official user site (wallets, learn, ecosystem). https://z.cash
- zcash.school — Structured resources/tutorials.
- ZecHub Wiki — Community education, projects, developer guides. https://zechub.wiki

**Forum**: https://forum.zcashcommunity.com
**Community**: r/zcash, Discord/Telegram (via ZF links), X (@Zcash, @ZcashFoundation, @zodl_app, @ZingoLabs, etc.)
**Media**: Zcash Media, Zk Av Club, regional content, “My First Zcash” workbook (GitHub massadoptionorg), ZK Radio, ZShieldHer (education for survivors) https://zshieldher.com, ZecForge, etc.

**Events**
- Zcon
- Arborist calls
- Dev Summits.
- Zodl Summit - https://x.com/jswihart/status/2079019957950771287

**Other community**: ZECPublish https://www.zecpublish.com, ZcashNames https://www.zcashnames.com, ZecMap https://zecmap.com, aftok https://aftok.com, ZK Global Credit, Zentat (browser extension), etc.

**Other Tools & Apps**
**Recovery**: Argos (Sovright, for legacy ZEC Wallet Lite).
**Messaging/social**: Zapp, ZECPublish.
**Identity**: ZcashNames.
**Merchant maps**: ZecMap.
**Misc**: Ziggurat, various GitHub tools, media kits (via z.cash).

**Starting points**

**Official ecosystem**: https://z.cash/ecosystem
**Community projects**: https://zechub.wiki/zcash-projects · https://zechub.wiki/zcash-community/community-projects
**Dashboard-style maps**: zcash.eli5defi.xyz (or similar community trackers) 
Specs/code: https://zips.z.cash · GitHub zcash / ZcashFoundation
