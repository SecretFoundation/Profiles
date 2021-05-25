### [bridge.scrt.network](https://bridge.scrt.network/)

# What is the Secret Bridge?

![image](https://user-images.githubusercontent.com/25411371/119445176-06f8ac80-bcf2-11eb-8e4f-28f5a45032df.png)

The Secret Ethereum Bridge is live on mainnet and ready for your use today. This immediately allows holders of ETH and certain ERC-20 assets to create "secret" versions of their assets as Secret Tokens and transact with them privately. Secret Tokens are powerful - they're programmable like ERC-20s, but private by default like Monero and similar coins.

The Secret Ethereum Bridge transfers between assets on the Ethereum network (ETH/ERC-20) and Secret Tokens, which are specified by the SNIP-20 spec. Secret Tokens combine the programmability of ERC-20s with the privacy of coins like Zcash or Monero. Interactions with Secret Token contracts are encrypted, viewable only to address owners or holders of their viewing key.

![image](https://user-images.githubusercontent.com/25411371/119445369-4fb06580-bcf2-11eb-9434-5c5a11deed6f.png)

Bridge operators are responsible for watching the chain for new events. Once a new event is found, one of the bridge operators proposes a transaction, which is then confirmed by other operators. This triggers an on-chain event to mint secretETH (or a secretERC-20) on Secret Network, or when the Secret Token is burned, to unlock ETH (or ERC-20s) from the lock/deposit contact on Ethereum.

![image](https://user-images.githubusercontent.com/25411371/119445394-5dfe8180-bcf2-11eb-8df1-a148dba04f15.png)

The bridge is located at: https://bridge.scrt.network



