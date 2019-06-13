# Tezos
> a blockchain that can evolve by upgrading itself

For this meetup we've decided to learn about Tezos the _malleable_ blockchain, so malleable that you could, in fact, implement Ether in Tezos :thinking:

## Resources

### Readings and websites :books:
 - [Official website](https://tezos.com/learn-about-tezos)
 - [Project paper](https://tezos.com/static/position_paper-841a0a56b573afb28da16f6650152fb4.pdf) :point_right: like a whitepaper but non technical :sparkles: good starting point
   - Here's the actual [whitepaper](https://tezos.com/static/white_paper-2dc8c02267a8fb86bd67a108199441bf.pdf) :scroll:
 - **Smart Contracts on Tezos**
   - Tezos uses a low-level smart contract language called the [Michelson Language](https://try-michelson.com)
   - [Liquidity](http://www.liquidity-lang.org/) is a higher level language which can compile to michelson
     - And michelson can _decompile_ to liquidity :clap: :clap:
     - Try using it with the online [editor](http://www.liquidity-lang.org/edit/?)
 - [Story of Tezos](https://www.wired.com/story/tezos-blockchain-love-story-horror-story/) An interesting Wired article about the founding of Tezos with a lot of the drama
 - [Block Explorer](https://tzscan.io/network?state=all)
 - [Mainet Docs](https://medium.com/tocqueville-group/lifecycle-of-an-operation-in-tezos-248c51038ec2)
 - [Eztz, the Web3 alternative](https://github.com/TezTech/eztz)
 - [Many more](https://tezos.rocks/)

### Talks and other videos :tv:
 - [Tezos Governance](https://m.youtube.com/watch?v=lKWNwIRC_Yc) :sunglasses: Quick animatated video about Tezos governance
 - [Tezos at Consensus 2019](https://youtu.be/PH8YQ1mr5ws?t=814) :sparkles: A good high level overview of Tezos

## Discussion
**What is Liquid proof of stake?**

Liquid proof of stake is mechanism in Tezos of _delegating_ your stake to a trusted node/address allowing them to act on your behalf.

**What is difference between PoS in Tezos and Ethereum 2.0**

The above mentioned Delegate/Liquid proof of stake is one main difference. However there aren't a set number of delegates so the system can still act completely decentralized.

**Is there an incentive to delegate to someone else?**

Combat potential bad entities by grouping stake together. No monetary gain. 


**How does gas work in Tezos?**

Using a similar system as ether except there is a hard limit on the gas you're willing to spend and you don't get a refund for unused gas.
