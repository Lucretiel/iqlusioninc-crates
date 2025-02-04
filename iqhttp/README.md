# iqhttp <a href="https://www.iqlusion.io"><img src="https://storage.googleapis.com/iqlusion-production-web/img/logo/iqlusion-rings-sm.png" alt="iqlusion" width="24" height="24"></a>

[![Crate][crate-image]][crate-link]
[![Docs][docs-image]][docs-link]
[![Apache 2.0 Licensed][license-image]][license-link]
![MSRV][rustc-image]
[![Build Status][build-image]][build-link]

iqlusion's HTTPS toolkit. Provides a high-level wrapper around [`hyper`], with
built-in SSL/TLS support based on [`rustls`].

[Documentation][docs-link]

## Minimum Supported Rust Version

- Rust **1.47**

## License

Copyright © 2021 iqlusion

**iqhttp** is distributed under the terms of either the MIT license
or the Apache License (Version 2.0), at your option.

See [LICENSE] (Apache License, Version 2.0) file in the `iqlusioninc/crates`
toplevel directory of this repository or [LICENSE-MIT] for details.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you shall be dual licensed as above,
without any additional terms or conditions.

[//]: # (badges)

[crate-image]: https://img.shields.io/crates/v/iqhttp.svg
[crate-link]: https://crates.io/crates/iqhttp
[docs-image]: https://docs.rs/iqhttp/badge.svg
[docs-link]: https://docs.rs/iqhttp/
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[license-link]: https://github.com/iqlusioninc/crates/blob/main/LICENSE
[rustc-image]: https://img.shields.io/badge/rustc-1.47+-blue.svg
[build-image]: https://github.com/iqlusioninc/crates/actions/workflows/iqhttp.yml/badge.svg
[build-link]: https://github.com/iqlusioninc/crates/actions/workflows/iqhttp.yml

[//]: # (general links)

[`hyper`]: https://github.com/hyperium/hyper
[`rustls`]: https://github.com/ctz/rustls
[LICENSE]: https://github.com/iqlusioninc/crates/blob/main/LICENSE
[LICENSE-MIT]: https://github.com/iqlusioninc/crates/blob/main/iqhttp/LICENSE-MIT
