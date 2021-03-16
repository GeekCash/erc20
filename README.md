# ERC20

### Setup

```
cargo install --force --features binaryen-as-dependency cargo-contract
```

```
rustup component add rust-src --toolchain nightly
rustup target add wasm32-unknown-unknown --toolchain stable
```

```
npm i wasm-opt -g
```

### Build

```
cargo +nightly contract build
```
