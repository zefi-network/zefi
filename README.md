# Zefi
Decentralized Finance extension of Zclassic

# Bridging Zclassic Bitcoin and Ethereum
The Zefi network brings Zclassic to ethereum as a wrapped erc-20 token

The first stage of the bridge is bringing the ZCL token to the Zefi network via [IBC](https://cosmos.network/ibc)
Additionally, Zefi wraps Bitcoin (BTC), and possibly other assets via the Cosmos IBC specification

After ZCL has migrated to the Zefi network as a wrapped IBC asset, and security audit is complete, a second two-way trustless peg will be implemented to the Ethereum network, migrating ZCL as an erc-20 (or erc-223) token.  See [peggy](https://github.com/cosmos/peggy)

# Zefi Network Governance DAO

The Zefi Network includes an on-chain governance system, powered by the [Cosmos SDK governance module](https://docs.cosmos.network/master/modules/gov/
).  Participants can submit proposals and vote on them using the native ZEFI token on a 1 token 1 vote basis
