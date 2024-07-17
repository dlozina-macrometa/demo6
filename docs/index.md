This page explains how to install the PhotonIQ FaaS command line interface (CLI).

To update the CLI, follow the same procedure to install the new version over the old.

### Linux

1) Install the Rust compiler and WebAssembly libraries by executing the following commands. This is required for creating Rust functions:

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup target add wasm32-wasi
```

2) Download the FaaS CLI package to your machine from link below:

[FaaS Linux GNU CLI package](https://macrometacorp.github.io/photoniq-faas-cli-docs/faas-1.0.0-aarch64-unknown-linux-gnu.tar.gz)

[FaaS Linux MUSL CLI package](https://macrometacorp.github.io/photoniq-faas-cli-docs/faas-1.0.0-x86_64-unknown-linux-musl.tar.gz)

3) Navigate into the CLI directory, and then launch the `faas` CLI tool

```shell
./faas help
```

You can now run [FaaS CLI Commands](faas-cli-commands.md).
