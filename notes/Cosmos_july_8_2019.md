# Cosmos

## Questions
**Can Cosmos enable atomic swaps? (Bitcoin -> Ethereum)**
    *Not natively, but you can have a Cosmos connected chain that acts as a DEX
    which enables atomic swaps.*

**What is Inter Blockchain Communication (IBC)?**
    *protocol for reliable & secure inter-module communication protocol, where
    modules are deterministic processes that run on independent distributed
    ledgers (also referred to as blockchains).*

**Are ICS Relayer singletons - or application specific?**
    *not a singleton - relayers carry out application logic*

## Inter Blockchain Communication (IBC)
* The inter-blockchain communication protocol is a reliable & secure
inter-module communication protocol, where modules are deterministic processes
  * ie smart contracts on ethereum are a module
* IBC is not an application-layer protocol: it handles data transport,
  authentication, and reliability only.
* relayers responsible for reading on one chain and submitting to another
  * https://github.com/cosmos/ics/tree/master/spec/ics-018-relayer-algorithms

that run on independent distributed ledgers (also referred to as blockchains).
https://github.com/cosmos/ics
https://cosmos.network/docs/spec/ibc/
https://cosmos.network/docs/tutorial/#requirements

Tutorial:
https://cosmos.network/docs/tutorial/#requirements
