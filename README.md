# zed-just-ls

[Zed](https://zed.dev) extension for [`just-lsp`](https://github.com/terror/just-lsp).

## Installation

As long as `zed-just-ls` has not been published to [Zed extensions](https://zed.dev/extensions) just do the following. That's very similar to [develop an extension locally](https://zed.dev/docs/extensions/developing-extensions#developing-an-extension-locally) for `Zed`.

### Requirements

- [Rust](https://www.rust-lang.org/tools/install)
- [`wasm32-wasip1`](https://doc.rust-lang.org/nightly/rustc/platform-support/wasm32-wasip1.html) target
- [zed-just](https://zed.dev/extensions?query=just) extension is **required** to detect any `justfile`. Needed to make `zed-just-ls` work properly.

### Steps

1. Clone the repository `git clone https://github.com/sectore/zed-just-ls`

2. In `Zed` open the extension page (`Ctrl-Shift-X`).
3. Click `Install Dev Extension` button. Select the root folder of `zed-just-ls` you have cloned before. Building the extension for the first time might take some time, follow the process by checking logs in `Zed` command `zed: open log`).

# License

[MIT License](./LICENSE)
