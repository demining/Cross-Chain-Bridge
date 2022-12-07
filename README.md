# Cross-Chain Bridges as the value of the Blockchain becomes attractive for various attacks


---
---



<figure class="wp-block-image"><img decoding="async" src="./Cross-Chain Bridges as the value of the Blockchain becomes attractive for various attacks CRYPTO DEEP TECH_files/025-1-1024x576.png" alt="Cross-chain bridges as the value of the blockchain becomes attractive for various attacks" class="wp-image-1745"></figure>



---
---



<p>This article will focus on a vulnerability in inter-network bridge protocols, which is a big security threat to smart contracts between different blockchains.</p>



<p>Cross bridges are an attractive target for hackers because they often represent a central storage point for the funds that support the “bridge” assets on the receiving blockchain.</p>



<p><strong><a href="https://cryptodeep.ru/cross-chain-bridge" target="_blank" rel="noreferrer noopener">What are Internet Bridge Protocols?</a></strong></p>



<p>Bridges are designed to solve the problem of interoperability between different blockchains.&nbsp;<a href="https://cryptodeep.ru/cross-chain-bridge" target="_blank" rel="noreferrer noopener">A bridge</a>&nbsp;is a protocol that allows a user to transfer digital assets from one blockchain to another.&nbsp;One of the most famous examples&nbsp;<code>Wormhole</code>is the bridging protocol, which allows users to move cryptocurrencies&nbsp;<code>NFT</code>between different smart contract blockchains such as Solana and Ethereum.&nbsp;In February&nbsp;<code>2022</code>of the year, there was a case when an unknown hacker found an exploit in the smart contract code&nbsp;<code>Wormhole</code>that allowed him to create&nbsp;<code>120 000</code>&nbsp;<code>Wrapped Ethereum</code>on&nbsp;<code>Solana (WeETH)</code>without providing the necessary equivalent collateral&nbsp;<code>Ethereum</code>.&nbsp;</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Cross-Chain Bridges as the value of the Blockchain becomes attractive for various attacks CRYPTO DEEP TECH_files/image-64.png" alt="Cross-chain bridges as the value of the blockchain becomes attractive for various attacks" class="wp-image-1715"></figure></div>


<p class="has-text-align-center" style="font-size:24px"><a href="https://techcrunch.com/2022/02/03/blockchain-bridge-wormhole-confirms-that-exploiter-stole-320-million-worth-of-crypto-assets/?guccounter=1&amp;guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&amp;guce_referrer_sig=AQAAAIosYdwRxjX5NdBm8j9DLXZREVBZaGegO8QyHCuIXB6BesYIrbH0US3Ffwjkra9ZXYCxSiIlXuzzJ9HrzcZY_-f8uddOB8dC09tpJAvvt7lTLVg3w-eE_WGQnAGHbhHk-TCk3IHTVG0A_z3-fTnZtyMu1KXB48-nbs1o-BP7RR8A" target="_blank" rel="noreferrer noopener">The Wormhole blockchain bridge confirms that the exploit stole US$320 million worth of crypto assets.</a></p>



<p>To understand why this incident was more serious than a normal hack, we need to know how cross bridges work.&nbsp;Users interact with bridges by sending funds in one asset to the bridge protocol, where the funds are then fixed in a contract.&nbsp;The user is then given the equivalent funds of the parallel asset on the chain to which the protocol is connected.&nbsp;In the case of Wormhole, users typically send ether&nbsp;<code>(ETH)</code>to the protocol, where it is stored as collateral, and issued&nbsp;<code>WeETH</code>to&nbsp;<code>Solana</code>, backed by the collateral locked in the contract&nbsp;<code>Wormhole</code>to&nbsp;<code>Ethereum</code>.</p>



<p>This high-profile hack meant that&nbsp;<code>WeETH</code>$&nbsp;<code>Solana</code>320 million was not secured within a certain period of time.&nbsp;If Ethereum&nbsp;<code>WeETH</code>was not secured, this would mean that a number of platforms on the basis of&nbsp;<code>Solana</code>accepting&nbsp;<code>WeETH</code>as collateral could become insolvent.&nbsp;We could see users rush to sell their WeETH, causing its value to drop, with major implications for the blockchain&nbsp;<code>Solana</code>and the vast ecosystem&nbsp;<code><a href="https://cryptodeep.ru/defi-attacks" target="_blank" rel="noreferrer noopener">DeFi</a></code>built on top of it, as many of these protocols also rely on&nbsp;<code>WeETH</code>to back issued assets.&nbsp;users.&nbsp;Indeed, last night we saw the price&nbsp;<code>Solana</code>of&nbsp;<code>13,5%</code>, which many attribute to fears of a hack.</p>



<p class="has-text-align-center">Jump Trading, the parent company of Wormhole and a major player in the Solana ecosystem, tweeted:</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./Cross-Chain Bridges as the value of the Blockchain becomes attractive for various attacks CRYPTO DEEP TECH_files/image-65.png" alt="Cross-chain bridges as the value of the blockchain becomes attractive for various attacks" class="wp-image-1719"></figure></div>


<p class="has-text-align-center"><code>Jump Trading</code>provided coins to&nbsp;<code>ETH</code>replace stolen funds after attempts to pay the hacker a reward for the stolen funds were ignored.</p>



<h2>Bridge construction</h2>



<p>Bridge designs vary, users typically interact with bridges by sending funds in one asset to the bridge protocol, where the funds are then fixed in a contract.&nbsp;The user is then given the equivalent funds of the parallel asset on the chain to which the protocol is connected.&nbsp;In the case of a wormhole, users typically send ether&nbsp;<code>(ETH)</code>to the protocol, where it is stored as collateral, and released&nbsp;<code>ETH</code>wormhole-wrapped to , backed&nbsp;<code>Solana</code>by the collateral locked in the wormhole’s contract to&nbsp;<code>Ethereum</code>.</p>



<h2>Vulnerable cross bridges</h2>



<p>Bridges are an attractive target because they often represent a central storage point for the funds that support “bridge” assets on the host blockchain.&nbsp;Whether these funds are stored in a smart contract or in a centralized custodian, this storage point becomes the target.&nbsp;In addition, efficient bridge design is still an unresolved technical issue, with many new models being developed and tested.&nbsp;These various schemes represent new attack vectors that could be exploited by attackers as best practices improve over time.</p>



<p>Just a few years ago, centralized exchanges were the most common target for hacks in the industry.&nbsp;Today, successful hacks of centralized exchanges are rare.&nbsp;This is because these organizations prioritize their security, and also because hackers are always on the lookout for the latest and most vulnerable services to attack.&nbsp;</p>



<p>While not reliable, a valuable first step to solving problems like this could be extremely rigorous code auditing, which would become the gold standard&nbsp;<a href="https://cryptodeep.ru/defi-attacks" target="_blank" rel="noreferrer noopener"><code>DeFi</code></a>for both these build protocols and the investors who evaluate them.&nbsp;Over time, the most reliable and secure smart contracts can serve as templates for developers.&nbsp;Cryptocurrency services, including but not limited to bridges, must invest in security measures and training.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2>Conclusion:</h2>



<p class="has-background" style="background-color:#f78da812">At the moment, all these modern attacks on bridges account for&nbsp;<code>69%</code>all the funds stolen in a&nbsp;<code>2022</code>year.&nbsp;This poses a serious threat to blockchain technology.&nbsp;As more value passes through&nbsp;<a href="https://cryptodeep.ru/cross-chain-bridge" target="_blank" rel="noreferrer noopener">cross-chain bridges</a>&nbsp;, they become more attractive to hackers.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong><a href="https://github.com/demining/Cross-Chain-Bridge" target="_blank" rel="noreferrer noopener">GitHub</a></strong></p>



<p><strong><a href="https://t.me/cryptodeeptech" target="_blank" rel="noreferrer noopener">Telegram: https://t.me/cryptodeeptech</a></strong></p>



<p><strong><a href="https://youtu.be/9rDEepQOyaM" target="_blank" rel="noreferrer noopener">Video: https://youtu.be/9rDEepQOyaM</a></strong></p>



<p><strong><a href="https://cryptodeeptech.ru/cross-chain-bridge" target="_blank" rel="noreferrer noopener">Source: https://cryptodeeptech.ru/cross-chain-bridge</a></strong></p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><img decoding="async" src="./Cross-Chain Bridges as the value of the Blockchain becomes attractive for various attacks CRYPTO DEEP TECH_files/025-1024x576.png" alt="Cross-chain bridges as the value of the blockchain becomes attractive for various attacks" class="wp-image-1743"></figure>




---




|  | Donation Address |
| --- | --- |
| ♥ __BTC__ | 1Lw2gTnMpxRUNBU85Hg4ruTwnpUPKdf3nV |
| ♥ __ETH__ | 0xaBd66CF90898517573f19184b3297d651f7b90bf |
