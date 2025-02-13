# Rust Seed Boilerplate

The Rust Seed Boilerplate is a boilerplate for developers who want to get started with Seed SPA applications faster.

## Dependency

* cargo
* rustup
* seed

## Setup

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup component add rls rust-analysis rust-src
cargo install cargo-edit cargo-make
cargo make build
cargo make serve

localhost:9090
```

## Troubleshooting

###  failed to run custom build command for `openssl-sys v0.9.xx`

on Ubuntu

```
    apt-get update -y
    apt-get install -y libssl-dev
    apt-get install -y pkg-config
```


## In progress

- [ ] Fetch API
- [ ] Many components
- [ ] Integration with background API [ActixWebBoilerplate](https://github.com/Norio4/rust_actixweb_boilerplate)
