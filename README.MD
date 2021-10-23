# Solana NFT

Make sure you have the following installed
- Rust
- Solana
## Compile contracts

Build the 

```bash
cargo build-bpf
```

## Deploy
Deploy all compiled contarcts

```python
solana program deploy /mnt/d/rust/target/deploy/nft_candy_machine.so -u devnet
```
Copy the program ID for all contracts
```python
Program Id: DpYitSMsJgVGVkYsr7YPXrtYvEZgQPfMsu7K7PcF6iox
```
Now paste the IDs in all the typescript client code (wherever needed)