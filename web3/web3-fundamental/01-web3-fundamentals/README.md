# Module 01 — From Web 1 to Web 3 & Your First Web3 Identity

## Learning Goals

By the end of this module, you will be able to:

- **Trace the evolution** of the internet from static pages to user-owned networks
- **Explain why Web3's "read-write-own" model** is a breakthrough for digital life
- **Set up a wallet** in test-net mode and understand seed-phrase safety
- **Claim a human-readable** on-chain handle (ENS/Lens/Farcaster)
- **Describe smart-account wallets** & account-abstraction (ERC-4337 / EIP-7702)

---

## Getting Started: Your Web3 Journey Begins Here

Welcome to your first step into Web3! This module is designed as a bridge—we'll start with the familiar (the internet you know) and gradually introduce you to the revolutionary concepts that make Web3 unique.

**Why start with history?** Understanding where we came from helps us appreciate where we're going. The evolution from Web1 to Web3 isn't just technical progress—it's a fundamental shift in who controls the digital world.

Let's begin by exploring how the internet has transformed over the past three decades...

## 1. The Internet's Three Ages

### 1.1 Flash-Timeline

| Era | Tagline | What changed? | Example services |
|-----|---------|---------------|------------------|
| **Web 1** (≈1990-2004) | **Read-only** | Static HTML, dial-up, no log-ins | GeoCities, Yahoo! Directory |
| **Web 2** (≈2004-2020) | **Read-write** | User-generated content, APIs, social graphs—but data stored in corporate silos | Facebook, Airbnb, PayPal |
| **Web 3** (≈2020-→) | **Read-write-own** | Blockchains for open data + token incentives + composability; users control keys & identity | Uniswap, OpenSea, Lens, Farcaster |

### 🛠️ Activity – Sketch Your Internet Timeline

In a notebook, mark the first time you used:
- **Email**
- **Social media** 
- **A blockchain app**

Notice how control over your data shifted at each step.

---

**🔄 From Timeline to Impact**

Now that you've mapped your personal internet journey, let's dive deeper into *why* this evolution matters. Web3 isn't just the "next version" of the internet—it represents a fundamental reimagining of digital relationships.

Think about it: In Web2, you might have thousands of photos on Instagram, a rich professional network on LinkedIn, or years of conversations on Discord. But what happens if these platforms disappear or ban your account? You lose everything because you never truly owned it.

Web3 changes this dynamic completely...

### 1.2 Why Web 3 Matters

**🔐 Digital ownership**: Wallets sign transactions that prove you own an asset or reputation badge—no password resets.

**🧩 Composability**: Anyone can plug new apps into public smart-contract rails.

**💰 Open incentives**: Tokens let users share upside instead of being monetized as the product.

**🆔 Self-sovereign identity**: Names like `yourname.eth` or `@alice.lens` travel across every dApp.

**🌍 Real-world splash**: Brands such as Starbucks Odyssey blend loyalty points with NFTs and on-chain wallets, creating "phygital" experiences. *[Source: voguebusiness.com]*

### 🤔 Reflection Prompt
Which of your favorite Web2 apps would benefit from user-owned data? Jot down two concrete improvements (e.g., exportable social graph, portable in-game purchases).

---

## 🔑 Making It Real: Your Web3 Toolkit

Excellent! You now understand *why* Web3 matters and can envision how user ownership could transform digital experiences. But how do you actually *participate* in this new internet?

**This is where we shift from theory to practice.** Just as you needed an email address to fully participate in early internet communication, and social media accounts for Web2, you need specific tools to interact with Web3.

The most fundamental tool? **Your wallet.** But as you'll discover, a Web3 wallet is much more than a place to store digital money—it's your entire digital identity, your key to the decentralized web, and your gateway to true digital ownership.

Ready to set up your Web3 identity? Let's dive in...

## 2. Wallets, Keys & On-Chain Identity

### 2.1 What is a Wallet?

A wallet is software or hardware that stores your private keys and builds transactions. Think of it as:

```
Private Key → Digital Signature → Blockchain Action
```

**Types of Accounts:**
- **EOA (Externally Owned Account)**: Classic MetaMask address, controlled by a single key
- **Smart Account (Contract Wallet)**: Programmable logic, multi-sig, session keys—enabled by account abstraction *[Sources: docs.safe.global, blog.thirdweb.com]*

---

**📱 Choosing Your First Wallet**

Now that you understand what a wallet fundamentally does, you might be wondering: "Which type should I choose?" The good news is that you're not locked into one choice forever—many users eventually use multiple wallets for different purposes.

For beginners, we recommend starting with a **browser extension wallet** like MetaMask because it offers the best balance of usability and dApp compatibility. As you become more comfortable, you can always explore other options.

Let's look at your choices...

### 2.2 Types of Wallets

| Category | Examples | Pros | Trade-offs |
|----------|----------|------|------------|
| **Browser extension** | MetaMask, Rabby | Fast onboarding, rich dApp support | Phishing risk, key in hot storage |
| **Mobile** | Rainbow, Trust, Coinbase Wallet | Touch-ID UX, NFC signing | Same hot-wallet risks |
| **Smart-contract** | Safe, Argent | Social recovery, batched tx, gas sponsorship | Slightly higher network fees; not on every chain yet |
| **Hardware** | Ledger, Keystone | Keys offline | Cost, extra steps |

---

**🎯 Time to Get Your Hands Dirty**

Theory is great, but Web3 is all about doing! You're about to take a major step: creating your first Web3 wallet. This isn't just an academic exercise—you're creating a real digital identity that could potentially be worth something someday.

**Important:** We'll be using **testnets** (practice networks) that use fake money, so there's zero financial risk. Think of this as a "driving simulator" for Web3—you'll learn all the mechanics without any danger.

**What you'll accomplish:** By the end of this section, you'll have a working wallet, some test cryptocurrency, and the confidence to send your first blockchain transaction. You'll also understand why security matters so much in Web3.

Let's build your Web3 identity step by step...

### 2.3 Hands-on 🛠️ — Set Up a Testnet Wallet

#### Step 1: Install MetaMask
1. **Install MetaMask** (Chrome / Firefox). Follow the [official guide](https://support.metamask.io), create a new wallet
2. **Write down the Secret Recovery Phrase** on paper—**never in screenshots or cloud notes**
3. Store your seed phrase in multiple secure physical locations

#### Step 2: Configure Testnet
1. **Switch network** → Sepolia (Ethereum testnet)
2. **Visit a public Sepolia faucet** and request 0.1 tETH
3. **Send a tiny amount** to a friend's test address to see gas in action

#### Step 3: Explore Alternative Wallets
- **Optional**: Try [Rabby extension](https://rabby.io); import the same address and notice automatic chain switching

#### ⚠️ Security Tip
**If anyone asks for your recovery phrase, they are scamming you.**

---

**🚀 Beyond Basic Wallets: The Future is Here**

Congratulations! You now have a working Web3 wallet and have sent your first transaction. You've experienced what most of the crypto world uses today—but what if I told you that wallets are about to get *much* better?

**Here's the thing:** The wallet you just set up, while functional, has some limitations. You can't batch multiple transactions, you always need to pay gas fees yourself, and if you lose your seed phrase, your funds are gone forever.

But there's a revolution happening right now called **Account Abstraction** that's solving these problems. Think of it as "Wallets 2.0"—programmable, user-friendly, and much more powerful.

This might seem advanced for a beginner lesson, but understanding where wallets are heading will help you make better choices as you grow in Web3...

### 2.4 Account Abstraction 101

**Current Limitations of EOAs:**
- Can't batch transactions
- Can't sponsor gas fees  
- Can't enforce 2-factor keys

**Solutions:**

**🔧 ERC-4337**: Introduces UserOperations, Bundlers & Paymasters—smart accounts work on any EVM chain

**⚡ Native AA**: zkSync, Starknet bake smart accounts into the protocol

**🔄 EIP-7702**: Lets existing EOAs temporarily behave like smart accounts, giving wallets a gentle upgrade path

*[Sources: gelato.network, blog.thirdweb.com]*

#### 🛠️ Try It: Smart Account Demo
Head to [thirdweb's AA sandbox](https://thirdweb.com) and create a demo smart account. Observe a gas-sponsored mint.

---

**🏷️ Making Your Address Human-Friendly**

You now have a wallet address that looks something like `0x742d35Cc6...`—not exactly memorable, right? Imagine if every website had IP addresses instead of domain names, or if phone numbers had no area codes. That's essentially where we are with Web3 addresses today.

**But here's the exciting part:** Just as the early internet developed domain names to make addresses human-readable, Web3 has created several systems to give you a memorable, portable identity that works across applications.

**Why does this matter?** Your Web3 handle becomes your universal username across the entire decentralized internet. Whether you're trading NFTs, participating in DAOs, or socializing on decentralized platforms, your identity follows you everywhere.

Ready to claim your piece of the decentralized internet? Let's explore your options...

### 2.5 Claiming Your Web3 Handle

| System | What you get | How to try (free or low-cost) |
|--------|--------------|-------------------------------|
| **ENS (.eth name)** | Universal domain → resolves to any address | On testnet: go to the [ENS App](https://app.ens.domains), switch to Sepolia, register a sub-name under example.eth *[docs.ens.domains]* |
| **Lens Protocol** | Social graph handle (@you.lens) usable in clients like Orb | Request a testnet profile in Lenster staging or use the Polygon Mumbai faucet demo *[youtube.com]* |
| **Farcaster** | Decentralized social username (@you) plus custody address | Install Warpcast, create an account, then verify an ETH address under Settings → Identity *[forbes.com]* |

#### 🛠️ Mini-project: Complete Web3 Identity Setup

1. **Register a free test ENS sub-domain**
2. **Set a custom avatar** (NFT or off-chain image)
3. **Post your new name** in a Farcaster frame or Lens post

**Voilà, cross-app identity!**

---

**🛡️ Protecting Your Digital Future**

You've come so far! You have a wallet, you've sent transactions, maybe even claimed a Web3 handle. But with great power comes great responsibility—and in Web3, **you are your own bank and identity provider.**

**Here's the reality:** In Web2, if you forget your password, you click "forgot password" and reset it. In Web3, if you lose your seed phrase, your funds and identity can be gone forever. No customer service can help you.

**But don't worry!** Millions of people safely manage their Web3 identities every day. The key is building good habits from the start. These best practices aren't just suggestions—they're your shield against the most common ways people lose access to their Web3 assets.

Let's make sure you're protected...

### 2.6 Best-Practice Checklist

✅ **Back up seed phrases offline** (steel plate or paper in safe)

✅ **Enable biometric unlock** on mobile and a separate passcode for the wallet

✅ **Verify contract addresses** on etherscan.io before signing

✅ **Use a burner wallet** for unfamiliar mints or airdrops

✅ **For larger sums**, move to a hardware wallet or a multi-sig Safe

---

## 📖 Expanding Your Web3 Knowledge

Outstanding work! You've completed the hands-on portions of this module and now have real Web3 experience under your belt. But this is just the beginning of your journey.

**What's next?** Web3 is a rapidly evolving space with new protocols, tools, and opportunities emerging constantly. The fundamentals you've learned here—understanding wallets, transactions, and digital identity—form the foundation for everything else you'll explore.

**Learning mindset:** In Web3, even experts are constantly learning. The space moves fast, and curiosity is your best asset. The resources below will help you deepen your understanding and stay current with developments.

**Choose your own adventure:** You don't need to consume all these resources immediately. Bookmark what interests you and return to it as you encounter related concepts in your Web3 journey.

## 3. Further Learning 📚

| Topic | Resource |
|-------|----------|
| **Intro video — "Web 3 in 10 mins"** | [Finematics YouTube](https://youtube.com/finematics) |
| **ERC-4337 deep dive** | [Gelato Blog — "Guide to Account Abstraction"](https://gelato.network) |
| **Smart-wallet SDK** | [thirdweb Account Abstraction docs](https://blog.thirdweb.com) |
| **ENS Quick-start** | [docs.ens.domains → Quickstart](https://docs.ens.domains) |
| **Lens tutorial** | [YouTube guide by devrel_eth](https://youtube.com) |
| **Farcaster ecosystem** | [forbes.com feature article](https://forbes.com) |
| **Safe Smart Accounts** | [docs.safe.global overview](https://docs.safe.global) |
| **Security 101** | MetaMask "Staying Safe" KB article |

---

## 📚 Your Web3 Dictionary

As you dive deeper into Web3, you'll encounter many specialized terms. This glossary covers the essential vocabulary from this module, but don't feel pressured to memorize everything immediately.

**How to use this:** Treat this as a reference tool. When you see a term in other Web3 content and can't quite remember what it means, come back here for a quick refresh. Over time, these concepts will become second nature.

**Living vocabulary:** Web3 terminology is still evolving. New terms emerge regularly, and existing ones sometimes change meaning. What matters most is understanding the core concepts behind the words.

## 4. Glossary 🗂️

| Term | Plain-English meaning |
|------|----------------------|
| **Block** | A batch of verified transactions added to a blockchain |
| **dApp** | Decentralized application running on a blockchain |
| **EOA** | Externally Owned Account (normal wallet address) |
| **Gas** | Small ETH fee paid to miners/validators for executing a tx |
| **NFT** | Non-Fungible Token—unique digital item or credential |
| **Seed Phrase** | 12- or 24-word master key that can regenerate your wallet |
| **Smart Account** | Wallet implemented as a smart contract (multi-sig, social recovery) |
| **Account Abstraction** | Turning every wallet into programmable code (ERC-4337, native, EIP-7702) |
| **ENS** | Ethereum Name Service—yourname.eth domains |
| **Lens** | Composable, on-chain social graph protocol |
| **Faucet** | Web service that drips free testnet coins |

---

## 🎯 Reflecting on Your Progress

Take a moment to appreciate how far you've come! When you started this module, concepts like "seed phrases" and "account abstraction" might have seemed foreign. Now you have practical experience with these tools.

**This checkpoint isn't a test**—it's a moment of reflection to consolidate your learning and build confidence for what's ahead. Can you explain these concepts to a friend? Can you perform these tasks independently? If so, you're ready for the next phase of your Web3 journey.

**Remember:** Everyone learns at their own pace. If any of these checkpoints feel unclear, it's perfectly normal to revisit the relevant sections or practice more with testnets.

## 📌 Checkpoint

**You've completed Module 01 if you can:**

✅ **Explain the difference between Web1/2/3** in one tweet

✅ **Send test ETH from MetaMask** to a friend

✅ **Show an ENS or Farcaster handle** linked to your address

---

## 🌟 Ready for the Next Adventure?

Excellent! You've mastered the foundations of Web3—you understand the big picture, you have the tools (wallet + identity), and you know how to navigate safely. But having a wallet is just the beginning. 

**What can you actually *do* with Web3?** That's where things get really exciting. In the next module, we'll explore how Web3 enables new forms of finance, trading, and value creation that simply weren't possible in the Web2 world.

**You're about to discover** how anyone can become their own bank, how liquidity pools work, and why "DeFi" (Decentralized Finance) is revolutionizing money itself...

## 🚀 Up Next

**Module 02** dives into **DeFi & On-Chain Value Transfer**, where you'll swap tokens on a DEX and trace how liquidity pools work.

## Troubleshooting

**MetaMask won't install?**
- Try different browser
- Disable other wallet extensions temporarily

**Can't switch to testnet?**
- Look for "Show/Hide test networks" in settings
- Enable developer mode if needed

**Faucet not working?**
- Try different faucet websites
- Some require social verification
- Try multiple faucets if one is dry

**ENS registration failing?**
- Ensure you're on the correct testnet
- Check you have enough test ETH for gas
- Try a different subdomain name

**Smart account demo not working?**
- Clear browser cache and try again
- Ensure wallet is connected to correct network
- Try switching between different testnets

---

**Happy building & exploring! 🎉**

*Remember: This is your journey into Web3. Take your time, experiment safely on testnets, and don't hesitate to revisit concepts as you build your understanding.*
