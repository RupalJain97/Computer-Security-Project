# Security Analysis of Cryptocurrency Exchanges
#### Computer-Security-Project

## Introduction

Cryptocurrency has taken the world by a storm. Over 180 million people use Bitcoin, the most popular cryptocurrency blockchain [4]. Owing to its decentralised and immutable nature, blockchain based cryptocurrency has benefits over regular currency. This means that no single entity has control over the transactions made in a blockchain, and a user does not need to trust a singular entity as in the case of banks. The trust is divided on all the nodes of the blockchain network. Many people use third party cryptocurrency exchanges as a means to make transactions on the blockchain. This is so because of the convenience provided by these exchanges as running one’s own client node is a lengthy and complex process for an average user. In addition, these exchanges also provide features such as buying and selling of coins of a particular blockchain and across multiple blockchains. Exchanges act as a ‘dealer' by allowing its users to perform inter-blockchain transactions. They also charge a certain amount of fee for different transactions.
 
## Problem

Trusting the cryptocurrency exchanges to make transactions on the behalf of a user has its own caveats. These exchanges manage the wallet of users which includes the private keys of users. These keys could be used to make arbitrary transactions. It is unclear what security mechanisms exchanges employ to protect the data of its users. There are numerous cases of attacks on these exchanges in which the attackers steal millions of dollars worth of coins from such exchanges [5]. This fuels the motivation to investigate these third-party exchanges and study the underlying mechanisms. It is also imperative to study the causes of these attacks so mitigations could be formulated to prevent them.

## Related work

There is some work that focuses on the attacks launched into cryptocurrency exchanges[1]:  performs a study of cryptocurrency exchange scams[2], looks into an attack in which negative news is used to influence exchange rates[3], proposes a new cryptocurrency exchange that provides robust security guarantees. Our study will be a first of its kind work that focuses specifically on investigating the security mechanisms underlying cryptocurrency exchanges.

## Approach

We aimed to perform a study of the cryptocurrency exchanges from the lens of security. For this, we analysized the most popular exchanges which include Binance, FTX, Coinbase, Kraken, and BitFinex [5]. Studied the front end of these exchanges by investigating their mobile applications from Google PlayStore. Apart from this, we have also used CyrptoGuard software for the vulnerability detections and then try to propose security measures for these vulnerabilities. Our study will dive into the following questions.

* What data do these exchanges collect from the users?
* With which entities is this data shared?
* How do these exchanges manage the private keys of users? 
* What are the tradeoffs when users try to offload their transactions to these exchanges?
* What are the causes behind coin stealing attacks on these exchanges?

## Snapshots

![CryptoGuard running for Bitfinex](/image1.jpg)
*Fig. 1*: *CryptoGuard running for Bitfinex*.

![CryptoGuard running for Binance](/image2.jpg)
*Fig. 2*: *CryptoGuard running for Binance*.

## References

1. Pengcheng Xia, Haoyu Wang, Bowen Zhang, Ru Ji, Bingyu Gao, Lei Wu, Xiapu Luo, Guoai Xu, Zhang, S., Zhou, X., Pan, H. and Jia, J. (2019), Cryptocurrency, confirmatory bias and news readability – evidence from the largest Chinese cryptocurrency exchange. Account Finance, 58: 1445-1468.
2. Iddo Bentov, Yan Ji, Fan Zhang, Lorenz Breidenbach, Philip Daian, and Ari Juels. 2019. Tesseract: Real-Time Cryptocurrency Exchange Using Trusted Hardware. In Proceedings of the 2019 ACM SIGSAC Conference on Computer and Communications Security (CCS '19). Association for Computing Machinery, New York, NY, USA, 1521–1538.
3. How Many People Own Bitcoin? 95 Blockchain Statistics (2022). https://explodingtopics.com/blog/blockchain-stats
4. Kevin Groves, Cryptocurrency Exchange Hacks (Updated 2022 List). https://www.hedgewithcrypto.com/cryptocurrency-exchange-hacks/
5. Top Cryptocurrency Spot Exchanges. https://coinmarketcap.com/rankings/exchanges/
