# <img src="https://raw.githubusercontent.com/LiveSplit/LiveSplit/master/res/Icon.svg" alt="LiveSplit" height="42" width="45" align="top"/> asr-lso-bridge

Script to bridge the AutoSplitter Runtime with LiveSplit One.

## Usage

>[!IMPORTANT] Rust required
> Install Rust: https://www.rust-lang.org

### Settings

If the autosplitter has settings, create a `toml` file with top-level key-value pairs.
Pass the path to the file with `--settings`

### Running

```bash
cargo run --release -- [--settings SETTINGS.toml] path/to/autosplitter.wasm
```

## Credit

This is based of the asr-debugger tools and retains their copyright and license.
