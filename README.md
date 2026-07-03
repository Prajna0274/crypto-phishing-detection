# Crypto Phishing Detection & Awareness

Phishing didn't stop at fake bank emails — it moved into crypto. Wallet-drainer scams, fake airdrops, and impersonated support accounts now cost users millions every year, often because the victim never knew what red flags to look for.

As part of my cybersecurity work, I analyzed common crypto phishing patterns, broke down how each one tricks users, and put together practical guidelines to help people avoid them.

## What I did
- Researched real-world crypto phishing patterns (fake airdrops, fake wallet alerts, fake support accounts)
- Identified the specific red flags for each — spoofed URLs, urgency tactics, malicious transaction approvals, impersonation
- Classified each pattern by risk level based on potential impact (info theft vs. partial loss vs. full wallet drain)
- Wrote practical, easy-to-follow safety guidelines for everyday crypto users

## Findings

| # | Scam Type | What It Pretends to Be | Red Flag | Risk Level |
|---|-----------|------------------------|----------|------------|
| 1 | Fake Airdrop | A token giveaway from a known project (e.g., "Claim your Uniswap airdrop") | Slightly misspelled URL, countdown timer creating urgency, asks you to "connect wallet" to claim | Medium |
| 2 | Fake Wallet Security Alert | A popup or email from "MetaMask"/"Trust Wallet" asking you to "re-verify" your wallet | Asks for your seed phrase or private key directly — legitimate wallets never do this | High |
| 3 | Fake Exchange Support | A DM on Twitter/Telegram claiming to be "Binance/Coinbase Support" | Unsolicited contact, asks you to share your screen or send funds to "verify" your account | High |
| 4 | Malicious Token Approval | A dApp or site asking you to "approve" a transaction to continue | The approval grants unlimited access to your tokens, allowing silent draining later | High |
| 5 | Fake Browser Extension | A wallet extension listed in a browser store impersonating MetaMask/Trust Wallet | Low install count, recently published, near-identical branding to the real extension | Medium |

## Key Learnings
- Most crypto phishing doesn't rely on hacking — it relies on **urgency and impersonation**, the same way traditional email phishing does.
- The single most dangerous action a user can take is entering their **seed phrase** anywhere outside their own wallet app — this is the one red flag that should always trigger suspicion.
- "Approving" a transaction is not the same as "receiving" something — many victims don't realize an approval can grant ongoing access to their funds.

## Safety Guidelines
1. Never enter your seed phrase or private key on any website, popup, or in a DM — no legitimate wallet or exchange will ever ask for it.
2. Always double-check a website's URL character by character before connecting your wallet.
3. Be suspicious of any unsolicited urgency ("claim before it expires," "verify now or lose access").
4. Regularly review and revoke unused token approvals using a tool like revoke.cash.
5. Treat unsolicited DMs from "support accounts" as scams by default — real support rarely initiates contact.

## Tools & Sources
- Chainabuse.com — public database of reported crypto scams
- r/CryptoScams — community-reported real-world cases
- MetaMask phishing detection blocklist (public GitHub resource)

---
*This project is part of my ongoing cybersecurity learning, applying phishing-analysis methodology to the crypto/Web3 space.*
