# Fun side project to tweek Zed and create Rainiac
![alt text](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/fd52d3a7-16d5-4ae5-a900-2ddb238ff7fb/dbho2be-f0c3bb5d-2f8f-4d54-a294-c7431b333892.png/v1/fill/w_1600,h_1600/injustice_2_brainiac_symbol_by_deathcantrell_dbho2be-fullview.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTYwMCIsInBhdGgiOiJcL2ZcL2ZkNTJkM2E3LTE2ZDUtNGFlNS1hOTAwLTJkZGIyMzhmZjdmYlwvZGJobzJiZS1mMGMzYmI1ZC0yZjhmLTRkNTQtYTI5NC1jNzQzMWIzMzM4OTIucG5nIiwid2lkdGgiOiI8PTE2MDAifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.cqu3w7zmk8qsc-3w2SOwN6wUjzTgKbBLTb5akWmUl7g)



Welcome to Rainiac, a high-performance, multiplayer code creator

---



### Developing Rainiac

- [Building Rainiac for macOS](./docs/src/development/macos.md)
- [Building Rainiac for Linux](./docs/src/development/linux.md)
- [Building Rainiac for Windows](./docs/src/development/windows.md)
- [Running Collaboration Locally](./docs/src/development/local-collaboration.md)

### Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for ways you can contribute to Rainiac.


### Licensing

License information for third party dependencies must be correctly provided for CI to pass.

We use [`cargo-about`](https://github.com/EmbarkStudios/cargo-about) to automatically comply with open source licenses. If CI is failing, check the following:

- Is it showing a `no license specified` error for a crate you've created? If so, add `publish = false` under `[package]` in your crate's Cargo.toml.
- Is the error `failed to satisfy license requirements` for a dependency? If so, first determine what license the project has and whether this system is sufficient to comply with this license's requirements. If you're unsure, ask a lawyer. Once you've verified that this system is acceptable add the license's SPDX identifier to the `accepted` array in `script/licenses/zed-licenses.toml`.
- Is `cargo-about` unable to find the license for a dependency? If so, add a clarification field at the end of `script/licenses/zed-licenses.toml`, as specified in the [cargo-about book](https://embarkstudios.github.io/cargo-about/cli/generate/config.html#crate-configuration).
