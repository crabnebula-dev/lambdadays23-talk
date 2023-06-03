# Tauri: Build Secure and Reliable Native Apps using Rust and Elm

This is the code accompanying the Lambda Days 2023 Talk. This repo also contains the slides.

## Prerequisites

1. Setup Tauri prerequisites for your OS (especially on Linux):
   https://tauri.app/v1/guides/getting-started/prerequisites/

2. Install the wasm32 Rust target

    ```
    rustup target install wasm32-unknown-unknown
    ```

3. Install the Tauri CLI

    ```
    cargo install tauri-cli
    ```

4. Install Elm

    Install Elm by downloading the installer [here]( https://guide.elm-lang.org/install/elm.html).

5. Clone this repo

    ```
    git clone https://github.com/crabnebula-dev/lambdadays23-talk
    ```

## Getting Started

You can run the checkpoint apps by navigating into their respective subfolders and running the command:

```
cargo tauri dev
```

To build production-ready bundles run

```
cargo tauri build
```

## License

<sup>
Licensed under either of <a href="LICENSE-APACHE">Apache License, Version
2.0</a> or <a href="LICENSE-MIT">MIT license</a> at your option.
</sup>
