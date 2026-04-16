# Decibri

Premium Voice AI infrastructure. Native audio capture, playback, and device management across Node.js, browsers, Rust, and the command line.

Built for developers who want to ship Voice AI applications, not wrestle audio drivers.

## What's here

**[decibri](https://github.com/decibri/decibri)** - the core audio library. Native bindings on four platforms, browser support via conditional exports, Silero VAD, sub-millisecond frame capture. Install via `npm install decibri` (Node.js/browser) or `cargo add decibri` (Rust). Zero system dependencies.

**[decibri-cli](https://github.com/decibri/decibri-cli)** - cross-platform audio CLI built on decibri. Capture, play, and list devices from any shell. One statically-linked binary, zero runtime dependencies. Install via `npm install -g decibri-cli` or `cargo install decibri-cli`.

**[mcp-listen](https://github.com/decibri/mcp-listen)** - give your AI agents the ability to listen. Microphone capture and speech-to-text tools for MCP-compatible agents. Install via `npm install -g mcp-listen`.

## What's next

Python support and ONNX-based VAD models are in development. See [decibri.com](https://decibri.com) for the latest.

## Links

[decibri.com](https://decibri.com) · [npm](https://www.npmjs.com/org/decibri) · [crates.io](https://crates.io/search?q=decibri)
