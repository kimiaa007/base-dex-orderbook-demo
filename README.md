# base-dex-orderbook-demo

Order-book DEX demo on Base. Users can place limit orders and match them onchain or offchain.

## Stack
- Solidity (order book logic)
- Kotlin client
- Base (L2)

## Structure
- `contracts/` — Solidity contracts
- `clients/kotlin/` — Kotlin client

## Notes
- Demo can use simple onchain matching or offchain matcher + settlement.
- Extend with fees, cancel/replace, and multiple pairs.

## License
MIT
