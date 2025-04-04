# MonkeyZoo Implemented Technologies

This is the documentation on blockchain technologies that MonkeyZoo Ltd. have directly Developed, sponsored or have implemented.

Royalty Splitting puzzle

Token Gifting System

Auto-burn offer file generator

FusionZoo (combining and serrating re-combined NFTs)

## Royalty Splitting puzzle

[Link to Source](https://github.com/trgarrett/chialisp/tree/main/royalty_share)

### Description

This a special puzzle originally developed by [trgarret](https://github.com/trgarrett). This puzzle allows a coin to be shared in a predefined percentage between 2 or more XCH addresses.

The custom puzzle allows you to add in 2 or more addresses and their the percentage of the total coin value that you would like to send to these two addresses. This generates a specific address to send the coin to be split.

The second part allows the user to ask the blockchain to activate the puzzle and action the split this creates two or more transactions and sends the predefined percentages to the predefined addresses.

### Implementation

Monkey Zoo has this implemented on all of our nfts to manage the royalty distribution onto two different wallets.

This can clearly be seen at wallet address [xch1aze9xrf4thau2lejnn0qt4wgw9ynfkynlxs2faq5rkm9nw3w26uq38509h](https://spacescan.io/address/xch1aze9xrf4thau2lejnn0qt4wgw9ynfkynlxs2faq5rkm9nw3w26uq38509h?tab=Transactions&type=standard&page=1) 

These coins can then be spent and the internal puzzles activated which splits the coin to the two separate coins to 2 predetermined addresses with any remainder value going to the primary address.

### Other use cases

## Token Gifting System

[Link to Source](https://github.com/monkeyzoo-metaverse/token-gifting-system)

### Description

From the beginning, MonkeyZoo always wanted to reward its NFT collectors for holding the MonkeyZoo NFTS with MZ token. This is MonkeysZoos own token ecosystem these tokens can be used to make NFT purchases.

### Implementation

Details on how Monkey Zoo has implemented the Token Gifting System.

## Inferno Auto-burn offer file generator.

[Link to Source](https://github.com/monkeyzoo-metaverse/chialisp/tree/main/misc)

### Description

Inferno is an offer file generator that allows and NFT to be traded with another NFT and the original NFT to be Burned so that it is no longer usable. The offer file allows this to be done in a trustless non-interactive way. 

### Implementation

MonkeyZoo used this method for their Valentines 2024 NFT sale where Ticket NFTs were sold and auto-burn offer files were generated. The Ticket holders could use the offer file to gain a black, red or gold Valentines NFT and their ticket was burnt as part of the exchange.

[This is one of the mentioned trades](https://dexie.space/offers/51unopZU8EjmV328EK1d4UzofzCCmvMo5TA9YMjB6hTB)

[Here you can see the Burned Placeholder ticket](https://www.spacescan.io/nft/nft18zz56wtxvszekp997a5c0v6w4fs7n7y8f8q6zu88cxmwmqqzh6aq3shz2e)

### Other use cases

Lottery system and ticketing are some of the use cases for this technology.

## NFT Fusion (FusionZoo)

[Link to Source](https://github.com/monkeyzoo-metaverse/fusion-clsp)

### Description

NFT Fusion is a sophisticated technology developed by the MonkeyZoo project that allows for a trustless and decentralized way of combining, updating, and upgrading NFTs while maintaining on-chain provenance and the non-fungible nature of the source NFTs. This technology leverages the unique features of the Chia blockchain and introduces a new level of flexibility and functionality to NFTs. Think of NFTs being stored inside other NFTs.

Lots more information on NFT Fusion can be found [here.](https://monkeyzoo.net/fusion/what-is-nft-fusion/)

### Implementation

SOON(tm)  

### Other use cases

Upgradeable game assets are a good alternative use case for this technology.

## Glossary

| Term | Definition |
| --- | --- |
| Chia Blockchain | The Chia Blockchain is an eco-friendly, decentralized blockchain that uses proof of space and time to secure its network.  |
| Royalty | A percentage of the sale price paid to the original creator each time an NFT is resold. |
| Puzzle | A cryptographic challenge that needs to be solved to achieve a specific outcome in a blockchain system. |
| Offer File | A file that contains the details of an offer, including the terms and conditions, for a transaction on the blockchain. |
| Burn | The process of permanently removing assets from circulation, reducing the total supply. |
