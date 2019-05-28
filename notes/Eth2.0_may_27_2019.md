# Ethereum 2.0
> A way to bring technical improvements, like PoS and sharding, together to improve the Virtual Machine, Merkle Trees, the efficiency of the protocol, and a whole bunch of small technical things that you have never heard of to create a next-generation blockchain

For this meetup we've decided to learn about Ethereum 2.0 the bigger better faster stronger :muscle: and very unclear upgrade of ether. 

## Resources

### Readings :books:
 - [An Eli5 Eth 2.0 blog post ](https://www.tokendaily.co/blog/eli5-explanation-of-the-ethereum-2-0-testnet):sparkles: good starting point
 - [Formal specification of ETH 2.0](https://github.com/ethereum/eth2.0-specs) :sparkles: good starting point
 - [What's New in Eth2 - 29 March 2019](https://notes.ethereum.org/c/Sk8Zs--CQ/https%3A%2F%2Fbenjaminion.xyz%2Fnewineth2%2F20190329.html)
 - [Ethereum phases](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth-2.0-phases/)
 - [Casper Protocol](https://vitalik.ca/general/2018/12/05/cbc_casper.html)
 - [Sharding](https://github.com/ethereum/wiki/wiki/Sharding-FAQ#how-can-we-facilitate-cross-shard-communication)

### Talks and other videos :tv:
 - [Justin Drake - randomness in ETH 2.0](https://www.youtube.com/watch?v=rUOBPu4W28c) 
 - [Implementers Call (1st of many)](https://www.youtube.com/watch?v=Ynqrka5DQOI)
 - [Prysmatic labs client update (Dec, 2018)](https://www.youtube.com/watch?v=91ZAFIoha2w)
 - [Unconfirmed: Insights and Analysis From the Top Minds in Crypto](https://unconfirmed.libsyn.com/why-ethereum-20-could-fail-and-how-it-could-be-fixed-ep065):microphone: Podcast

## Discussion
**After reading the spec and the ELI5 post, still a bit confused about the relation of the beacon chain, shards (1024 of them), the 'canonical chain'?**

The _beacon :bacon: chain_'s primary function is to manage validators on ethereum. It does this by having a store of all current validators. The beacon node will assign a group of validators to create a _committee_. 

The beacon chain is also in charge of running the protocol to chose which fork is the true fork (using GHOST).

The beacon chain also provides _safe_ **randomness** to the validators. 

The beacon chain communicates to the shards through **crosslinks**.

**In Ethereum2.0 lingo, what is a _slot_?**

A slot is an 8 second interval of time


