# Axiom Rust SDK Quickstart

This is a starter repo to help you write a circuit using the [Axiom Rust SDK](https://github.com/axiom-crypto/axiom-sdk-rs). To learn more about Axiom, check out the developer docs at [docs.axiom.xyz](https://docs.axiom.xyz) or join our developer [Telegram](https://t.me/axiom_discuss).

For full documentation of the Axiom Rust SDK, see the [docs](https://docs.axiom.xyz/sdk/rust-sdk/axiom-rust).

## Development

To build, run:

```
cargo build
```

For circuit keygen and proving commands, see the instructions in the [Rust SDK docs](https://github.com/axiom-crypto/axiom-sdk-rs?tab=readme-ov-file#running-the-circuit). Note that the sample commands there need to be adjusted for the directory structure of this repo, meaning that you should use:

```
cargo run -- --input data/input.json -k 12 -p <PROVIDER_URI> <CMD>
```

where `<CMD>` is `mock`, `prove`, `keygen`, or `run`.
