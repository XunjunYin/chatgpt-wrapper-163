# ChatGPT Wrapper

A desktop application wrapper for ChatGPT website (https://chatgpt.nie.netease.com/) built with Rust and Tauri.

## Features

- Native desktop application for Windows, macOS, and Linux
- Modern and clean user interface
- System tray support
- Automatic updates support
- Cross-platform builds via GitHub Actions

## Development Prerequisites

- Rust (latest stable version)
- Node.js (v16 or later)
- Tauri CLI
- Cargo

## Development Setup

1. Install Rust from https://rustup.rs/
2. Install Node.js from https://nodejs.org/
3. Install Tauri CLI:
```bash
cargo install tauri-cli
```

4. Clone the repository:
```bash
git clone [your-repo-url]
cd chatgpt-wrapper
```

5. Install dependencies:
```bash
npm install
```

6. Run development build:
```bash
cargo tauri dev
```

## Building

To build for your current platform:
```bash
cargo tauri build
```

## Release Process

The project uses GitHub Actions for automated builds. When you push a tag starting with 'v' (e.g., v1.0.0), it will automatically:
1. Build the application for Windows, macOS, and Linux
2. Create a GitHub release
3. Upload the built artifacts to the release

## License

MIT
