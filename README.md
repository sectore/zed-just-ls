# zed-just-ls

[Zed](https://zed.dev) extension for [`just-lsp`](https://github.com/terror/just-lsp).

## Installation

1. In `Zed` open the extension page (`Ctrl-Shift-X`).
2. Search for `Just Language Server`.
3. Click `Install` button.

Note: In addition [zed-just](https://zed.dev/extensions?query=just) extension is **required** to detect a `justfile` and to make `zed-just-ls` work properly. If anyone know how to avoid this extra step, pls open an issue or PR.


## Development

### Requirements

- [Rust](https://www.rust-lang.org/tools/install)
- [`wasm32-wasip1`](https://doc.rust-lang.org/nightly/rustc/platform-support/wasm32-wasip1.html) target
- [zed-just](https://zed.dev/extensions?query=just) extension (see `Note` in chapter [Installation](./#installation))

### Steps

Steps are very similar to `Zed` docs chapter ["Developing an Extension Locally"](https://zed.dev/docs/extensions/developing-extensions#developing-an-extension-locally).

1. Clone the repository `git clone https://github.com/sectore/zed-just-ls`.
2. In `Zed` open the extension page (`Ctrl-Shift-X`).
3. Click `Install Dev Extension` button. Select the root folder of `zed-just-ls` you have cloned before. Building the extension for the first time might take some time. You might follow the process by checking logs in `Zed` command `zed: open log`).

# License

[MIT License](./LICENSE)
