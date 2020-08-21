# rust-cli-template

A Rust template for a CLI crate.

Features:

- Decently filled out `Cargo.toml`
- Support for benchmarking with [Criterion]
- A bunch of useful default dependencies and dev-dependencies.
    - [pretty_assertions] and [indoc] for tests
    - [color_eyre] with [tracing], [tracing-subscriber], and [tracing-error]
      for error reporting and logging
    - [structopt] for command-line argument parsing (to be replaced with clap3
      whenever that's released)
- A lib target for doc tests and a bin target for the actual tool

[Criterion]: https://github.com/bheisler/criterion.rs
[pretty_assertions]: https://docs.rs/pretty_assertions
[indoc]: https://docs.rs/indoc
[color_eyre]: https://docs.rs/color_eyre
[tracing]: https://docs.rs/tracing
[tracing-subscriber]: https://docs.rs/tracing-subscriber
[tracing-error]: https://docs.rs/tracing-error
[structopt]: https://docs.rs/structopt
