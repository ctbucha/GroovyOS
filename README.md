# GroovyOS

Practice building an OS in Rust.

## Getting started

1. Install rust nightly. (Required for the `build-std` option in cargo)

```bash
rustup toolchain install nightly
```

1. Install several rustup components.

```bash
rustup component add rust-src
rustup component add llvm-tools-preview
```

1. Install bootimage.

```
cargo install bootimage
```

1. Install qemu.

```bash
brew install qemu
```

## Running the project

After set up, just run `cargo run` in the root directory.
