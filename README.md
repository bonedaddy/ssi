# SSI: Cross-Chain Instruction Execution for Solana

SSI (Solana Signed Instruction) enables secure cross-chain instruction execution on Solana and gasless transaction relaying. SSI is a lightweight protocol requiring only 129 bytes of data.

## Example Use Cases

* Execute Solana program instructions from Ethereum smart contracts
* Gasless transaction relaying on Solana
* Execute Solana program instructions without needing to hold SOL

## Universal Compatibility

Any wallet capable of secp256k1 signatures can be used with SSI, with out of the box support for any EVM blockchain.

## Reference Implementation

[ByteSignedIx](./src/byte_signed_ix.rs) is a reference implementation of the SSI specification. An example program using SSI for user authentication is located in [proxy_auth](./src/proxy_auth/mod.rs).
