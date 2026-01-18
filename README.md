<!--
SPDX-FileCopyrightText: Copyright © 2025 hashcatHitman

SPDX-License-Identifier: Apache-2.0 OR MIT
-->

# hashcatHitman's Rust Crate Audits

I use [`cargo-vet`] to ensure third-party Rust dependencies I use have been
audited by myself or other trusted entities.

This repository is an aggregation of my audits from various repositories to make
them easily reusable by myself and others.

> [!WARNING]
> Please do not use these audits blindly - I am not an expert and do these
> audits primarily for myself.

To import my audits into another `cargo-vet` instance, add the following lines
to your `config.toml`:

```toml
[imports.hashcatHitman]
url = "https://raw.githubusercontent.com/hashcatHitman/supply-chain/main/audits.toml"
```

[`cargo-vet`]: https://mozilla.github.io/cargo-vet/
