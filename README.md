# artcraft-minimals

A minimal fork of [ArtCraft Launcher](https://github.com/storytold/craft-launcher) with a single app: **FilmCraft**.

- Install and update go to the FilmCraft fork: <https://github.com/kintil555/filmcraft> (latest GitHub release).
- ArtCraft's release feed is off, and the launcher doesn't check upstream for its own updates.
- Assets in the fork's releases must keep the upstream naming: `filmcraft-<version>-<os>-<arch>.<ext>` (plus `SHA256SUMS.txt`).

Build (Rust 1.95+): `cargo build --release -p artcraft-launcher`

Licensed under MIT OR Apache-2.0, as upstream (see `LICENSE-*`, `NOTICE`, `ATTRIBUTION.md`).
