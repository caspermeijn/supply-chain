# Rust Crate Audits

This repository contains the audit results performed by me. Using 
[cargo-vet](https://mozilla.github.io/cargo-vet/) can ensure your third-party 
Rust dependencies have been audited by trusted entities.

To import these audits into another cargo-vet instance, run the following import command:

```bash
cargo vet import caspermeijn https://raw.githubusercontent.com/caspermeijn/supply-chain/master/supply-chain/audits.toml
```
