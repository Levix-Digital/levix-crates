# Contributing

Contributions are welcome through pull requests on this repository.

## License of contributions

Unless you state otherwise, any contribution you submit for inclusion is licensed
as MIT OR Apache-2.0, the same terms as the rest of the repository, with no
additional terms or conditions (inbound = outbound).

Sign off every commit (`git commit -s`) to certify the
[Developer Certificate of Origin](https://developercertificate.org/).

## Rules for crates in this repository

- One crate does one thing. No grab-bag crates (`levix-common`, `levix-utils`).
- Every crate is named `levix-<name>`, inherits `license`, `edition` and
  `repository` from the workspace, has its own `README.md` and is published to
  crates.io.
- Dependencies come from crates.io only (enforced by `cargo deny`), under permissive
  licenses.
- Public APIs follow semantic versioning; a breaking change needs a major version.

## Before opening a pull request

```bash
cargo fmt --all --check
cargo clippy --workspace --all-targets --all-features -- -D warnings
cargo test --workspace --all-features
cargo deny check
```
