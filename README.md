# Typst Desktop

<p align="center">
  <em>A standalone desktop application for [Typst](https://typst.app/) web editor, built with [Tauri](https://v2.tauri.app/)</em>
</p>

![App screenshot](https://raw.githubusercontent.com/lucaslrodri/typst-desktop/main/assets/screenshot.png)

# Features
- **Native Desktop Experience**: Interact with Typst's web editor directly from your desktop without needing open a browser.
- **Fast and Lightweight**: Built with Tauri, ensuring a minimal footprint and quick startup times.

# Installation

## Pre-built Binaries
- Download the latest release from the [Releases page](https://github.com/lucaslrodri/typst-desktop/releases).

## Building from source
1. Clone this repository:
```bash
git clone https://github.com/lucaslrodri/typst-desktop.git
```

2. Navigate to the project directory:
```bash
cd typst-desktop
```

3. Install tauri:
```bash
cargo install tauri-cli
```

4. Build the application:
```bash
cargo tauri build
```

# Usage
1. Launch the application.
2. Log in with your Typst account to access your documents.
3. Use the Typst editor as you would in a web browser.

# Cache folder

The cache folder on Windows is located at `%LOCALAPPDATA%\com.lucaslrodri.typst-desktop.app\cache`. You can clear it if you encounter any issues with the application.

# Contributing

Contributions are welcome! If you have suggestions for improvements or find bugs, please open an issue or submit a pull request.

For more details on how to install and use Tauri, refer to the [Tauri documentation](https://v2.tauri.app/).

# License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.