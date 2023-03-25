# Blog OS (Minimal Kernel)

[![Build Status](https://github.com/phil-opp/blog_os/workflows/Code/badge.svg?branch=post-3.1)](https://github.com/phil-opp/blog_os/actions?query=workflow%3A%22Code%22+branch%3Apost-3.1)

This repository contains the source code for the [Minimal Kernel][post] post of the [Writing an OS in Rust](https://os.phil-opp.com) series.

[post]: https://os.phil-opp.com/minimal-kernel

**Check out the [master branch](https://github.com/phil-opp/blog_os) for more information.**

## Building

- Install the `x86_64-unknown-none` target using rustup:
  ```
  rustup target add x86_64-unknown-none
  ```
- Build by running:
  ```
  cargo build --target x86_64-unknown-none
  ```

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

Note that this only applies to this git branch, other branches might be licensed differently.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
