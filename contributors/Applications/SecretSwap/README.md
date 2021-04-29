![Capture](https://user-images.githubusercontent.com/25411371/116608326-ae9fdc00-a8f8-11eb-9f19-22e90c1a5a4f.PNG)

### [secretswap.io](https://www.secretswap.io/)

# What is SecretSwap?

Secret Swap is a protocol for creating liquidity and trading SNIP-20 tokens on Secret Network. Leveraging secret contracts, Secret Swap protects users against malicious front-running and privacy threats, provides access to cross-chain liquidity, and reduces fees relative to Ethereum.

![Swap](https://user-images.githubusercontent.com/25411371/116608908-59b09580-a8f9-11eb-8367-f8cc2bbcdfe2.PNG)

# Why SecretSwap

Built on the principles of usability and privacy, SecretSwap provides a foundation for the open accessible financial system of the future. Our primary focus is to protect our users from value extracting players by focusing on privacy, a basic human right. SecretSwap is a liquidity hub that connects to other ecosystems for maximum user protection and access to assets.

[![SecretSwap](https://user-images.githubusercontent.com/25411371/116608626-0d655580-a8f9-11eb-86ad-3b1be6898d8c.PNG)](https://www.youtube.com/watch?v=CqkOUNvDIx8)



# Front-running Resistant
Solving [~$1bn](https://explore.flashbots.net/) problem crippling DeFi users

# Cross-Chain Liquidity
[Bridging](https://bridge.scrt.network/) Secret Network to Ethereum, Binance Smart Chain (soon), Cosmos (soon), and beyond.

# Privacy-First
Encrypted nature of secret contracts provide [enhanced privacy](https://scrt.network/blog/secret-tokens-programmable-privacy-for-defi/) to users

# About SEFI
SEFI is the native governance token for SecretSwap and Secret DeFi more generally. Earn SEFI and shape the future of the front-running resistant, privacy-first open finance ecosystem

![SEFI](https://user-images.githubusercontent.com/25411371/116608420-c70ff680-a8f8-11eb-88b5-a094084a8554.PNG)

-----------------------------------------------------------------
# FAQ

### What is Front-running?

Front-running is an arbitrage strategy to make profit at someone else’s expense based on an information advantage. Front-running issue is not limited to DeFi, however the scale of the problem is amplified given the public nature of blockchains. Miners and arbitrage bots can see an order on the mempool before the order makes its way into the ledger and insert their orders with higher gas fees to be processed first. This means that the miner or the arbitrage bot can profit at the expense of a regular user. Furthermore, this arbitrage opportunity increases the gas fees of the underlying network, hurting users even more. [Front-running problem on Ethereum DeFi costs users ~$1bn per year and millions of dollars in lost gas fees](https://explore.flashbots.net/).

### How does Secret Swap achieve front-running resistance?

SecretSwap is a protocol to swap secret contract based tokens (SNIP-20s) on Secret Network. Given the encrypted nature of SNIP-20s. Given the encrypted nature of secret contracts, inputs to a transaction/contract are encrypted while they are on the mempool and cannot be frontrun by any adversary. This ensure SecretSwap protects its users and their money from front-running attacks.

### How do I use Secret Swap?

First, you’ll need a Keplr wallet and some $SCRT. Once completed, head over to SecretSwap to start using the protocol to provide liquidity or swap tokens. Since [SecretSwap](https://bridge.scrt.network/swap#Swap) is built on Secret Network, each transaction and interaction costs $SCRT (the native coin of the network). This is called the “gas fee” and it’s paid to network validators to keep the network running.

### How does Secret Swap work?

Secret Swap is an automated market maker (AMM) liquidity protocol. There is no orderbook, no centralized party, and no central facilitator of trade. Using Secret Contracts, the mempool of potential Secret Swap transactions are kept entirely encrypted - protecting users from front-running attacks and providing an increased level of privacy compared to traditional AMMs.

Each pool within Secret Swap is defined by a secret contract that includes a few functions to enable swapping tokens, adding liquidity and more. At its core each pool uses the function x*y=k to maintain a curve along which trades can happen.

The pools keep track of reserves (liquidity) and updates those reserves every single time someone trades. Because the reserves are automatically rebalanced, a Secret Swap pool can always be used to buy or sell a token without requiring a counterparty on the other side of your trade.

Note: Given the requirement to publicly update pool reserves to determine the price, an observer can see a consolidated view of changes (swaps, provide / remove liquidity) in a given block. As a result, if there’s a single transaction with the pool in a given block, it is not possible to have privacy on that transaction. With more transactions per pool in a given block, SecretSwap provides additional privacy to users.

For a more in depth description, check out how SecretSwap works in this [blog post](https://scrt.network/blog/secret-markets-front-running-prevention) outlining the theory behind an AMM using secret contracts.

### How are prices determined?

Prices are determined by the amount of each secret token in a pool. The secret contract maintains a constant using the following function: x*y=k.

In this case x = secret_token_0, y = secret_token_1, k = constant. For each trade, a certain amount of secret tokens are removed from the pool in exchange for adding an amount of the other secret token. To maintain k, the balances held by the secret contract are adjusted during the execution of the trade, therefore changing the price.

I saw a token was trading at X value, but when I traded on Secret Swap I got a much lower value?
There are 2 fees involved with a SecretSwap transaction: SecretSwap fees and Secret Network fees. SecretSwap fees are 0.3% of each swap deducted across the pairs. The fees are put back in the liquidity pool providing income for LPs of that pair. The fees can be changed in the future with decentralized governance enabled by $SEFI.

Secret Network requires $SCRT as gas to execute each transaction. Depending on the market price of $SCRT, transaction costs can increase or decrease.

### Why does my transaction cost X?

Secret Network requires $SCRT as gas to execute each transaction. Depending on the market price of $SCRT transaction costs can increase or decrease.

# SEFI Token

### What is the total supply of SEFI?

Total supply of SEFI is set at 1,000,000,000. This amount is a non-inflationary fixed supply set at launch. 10% of the SEFI supply will be distributed at the genesis event to SecretSwap LPs during the soft-launch, SCRT stakers who secure Secret Network, users (depositors) of Secret Network-Ethereum bridge and UNI holders (above 400 UNI). The remaining 90% of the supply will be distributed over 4 years with a deflationary schedule. For more on SEFI tokenomics.

### How can I claim my SEFI?

Users will be able to claim SEFI both on Secret Network with their Keplr Wallet and on Ethereum with their Metamask wallet. Users can claim their SEFI airdrop on the SecretSwap application. After you’ve claimed your SEFI, you can provide liquidity to sSCRT/SEFI pool or stake your SEFI and continue to earn SEFI after genesis.

### Who else can earn SEFI after genesis?

SecretSwap LPs and SEFI stakers will begin earning SEFI after genesis. Traders on SecretSwap will also earn SEFI, though not immediately at genesis. Currently eligible pools for LP rewards are sSCRT/SEFI, sSCRT/sETH, sSCRT/sWBTC, sSCRT/sUSDT, sETH/sWBTC.

### Will you be able to stake SEFI at launch?

Yes, you can use this link to stake SEFI and participate in SecretSwap governance. Staking SEFI provides impermanent loss free yield. SEFI staking is done through a secret contract, using the SecretSwap application.

### What is the difference between an LP token and SEFI?

LP tokens are crypto-assets (secretTokens)mathematical proof that represents your ownership of a pool. When Alice provides provided assets to a pool, she receives LP tokens. Hand holding LP tokens means holding the claim to getting those assets back. This is in contrast to SEFI, which is the SecretSwap governance token used for managing application layer changes. Staking LP tokens allows you to earn SEFI.

### Are rewards for SecretSwap LPs in SEFI or also in SCRT?

All SecretSwap rewards and governance are based on SEFI.

### What is the difference between SEFI and SCRT when it comes to governance?

SEFI is used as an application layer governance token specifically for Secret Swap parameters, developer fund spending, and application related changes. This is in contrast to SCRT, which is the native governance token of the Secret Network protocol layer.

### How is the price of SEFI determined at the beginning?

The price of SEFI will be determined by market forces of demand and supply.

# Support

I accidentally transferred my tokens to a pair contract, is there anyway I can get them back?
SecretSwap token pair secret contracts are ownerless. We have no special control over the pair secret contracts’ functionality; because of this, any tokens accidentally transferred to the token contract itself are lost forever. Please be careful!

### How can I get support for SecretSwap?

You can use this chat to get support for all SecretSwap related issues.

### Will Keplr support SEFI staking at launch?

SEFI is a SNIP-20 (secret token) and supported by Keplr like all other SNIP-20s.
