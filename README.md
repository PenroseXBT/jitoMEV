# mev-base

This repo is a starter template for Jito focused MEV bots on Solana. It is only opinionated on dependency structure, and leaves bot implementation up to the operator. The point of it is to do away with the boilerplate of setting up searcher and geyser protobufs for every new bot, and also to pin versions for the shared dependencies between the `searcher-client`, `geyser-client`, and `geyser-protos` crates.

All included crates are from the [Jito Labs](https://github.com/jito-labs) and [Jito Foundation](https://github.com/jito-foundation) GitHub orgs. All code belongs to them.

## Setting up

```base
git clone 
cd jitoMEV/
git submodule update --init --recursive
cargo build
```

