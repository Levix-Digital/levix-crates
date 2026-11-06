# levix-crates

Open source Rust crates from Levix Digital: generic building blocks (formats,
signature primitives, parsers and similar) shared by the Levix projects and usable
by anyone. Every crate is published to [crates.io](https://crates.io) under the
`levix-` prefix and licensed MIT OR Apache-2.0.

## Features

- Small, focused crates: each one does one thing and has its own version.
- Permissive license (MIT OR Apache-2.0) for the crates and every dependency.
- Dependencies from crates.io only, checked in CI with `cargo deny`.

## Requirements

- Rust stable (edition 2024).

## Installation

Add the crate you need from crates.io:

```bash
cargo add levix-<name>
```

No crate is published yet; the list below grows as crates are released.

## Usage

Each crate documents its API in its own `README.md` and on docs.rs.

| Crate | Purpose |
|---|---|
| none yet | |

## Configuration

Crates expose their options through Cargo features, listed in each crate's README.

## Troubleshooting

- **A feature is missing or the build fails on your target:** open an issue with the
  crate name, version, target and the full error.
- **A security problem:** follow [`SECURITY.md`](SECURITY.md), never a public issue.

## Documentation

- Contributing and crate rules: [`CONTRIBUTING.md`](CONTRIBUTING.md)
- Security policy: [`SECURITY.md`](SECURITY.md)

## License

Licensed under either of [Apache License, Version 2.0](LICENSE-APACHE) or
[MIT license](LICENSE-MIT) at your option.
