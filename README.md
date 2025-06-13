# Niri: A Scrollable-Tiling Wayland Compositor 🖥️✨

Welcome to **Niri**, a scrollable-tiling Wayland compositor designed to enhance your desktop experience. This project aims to provide a simple, efficient, and visually appealing way to manage your windows using the Wayland protocol.

[![Releases](https://img.shields.io/badge/Releases-v1.0.0-blue.svg)](https://github.com/fahrifaisal651/niri/releases)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Niri is built with Rust and leverages the Smithay library to create a smooth and responsive tiling window management experience. By focusing on simplicity and usability, Niri aims to provide a unique approach to managing windows on Wayland.

## Features

- **Scrollable Tiling**: Easily navigate through your open windows with a scrollable layout.
- **Wayland Support**: Fully compatible with the Wayland protocol for modern Linux environments.
- **Lightweight**: Minimal resource usage ensures your system runs smoothly.
- **Customizable**: Tailor the compositor to fit your workflow and preferences.

## Installation

To get started with Niri, you can download the latest release from our [Releases page](https://github.com/fahrifaisal651/niri/releases). Simply download the appropriate file for your system and execute it to install.

### Prerequisites

Before installing Niri, ensure you have the following:

- A Linux distribution with Wayland support.
- Rust installed on your system. You can install Rust using [rustup](https://rustup.rs/).

### Building from Source

If you prefer to build Niri from source, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/fahrifaisal651/niri.git
   cd niri
   ```

2. Build the project:
   ```bash
   cargo build --release
   ```

3. Run Niri:
   ```bash
   ./target/release/niri
   ```

## Usage

Once you have Niri running, you can start managing your windows. Here are some basic commands to get you started:

- **Open a Terminal**: Use your preferred method to open a terminal window.
- **Open Applications**: Launch applications from the terminal or your application launcher.
- **Switch Between Windows**: Use keyboard shortcuts to switch between open windows.

### Keyboard Shortcuts

| Action               | Shortcut       |
|----------------------|----------------|
| Switch to next window| `Mod + j`      |
| Switch to previous window| `Mod + k`  |
| Open a new terminal  | `Mod + Enter`  |
| Close the focused window| `Mod + q`   |

*Note: Replace `Mod` with your chosen modifier key (e.g., `Super` or `Alt`).*

## Configuration

Niri offers a configuration file to customize its behavior. The configuration file is located at `~/.config/niri/config.toml`. You can modify this file to change keybindings, window rules, and more.

### Example Configuration

```toml
[general]
mod_key = "Super"

[keybindings]
switch_next = "j"
switch_previous = "k"
open_terminal = "Return"
close_window = "q"
```

After editing the configuration file, restart Niri to apply the changes.

## Development

If you are interested in contributing to Niri, we welcome your input! Here are some ways you can help:

- **Report Issues**: If you encounter bugs or have suggestions, please open an issue on GitHub.
- **Submit Pull Requests**: If you have improvements or new features, feel free to submit a pull request.

### Development Setup

To set up a development environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/fahrifaisal651/niri.git
   cd niri
   ```

2. Install dependencies:
   ```bash
   cargo build
   ```

3. Run tests:
   ```bash
   cargo test
   ```

## Contributing

We appreciate contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your fork and create a pull request.

Please ensure your code adheres to our coding standards and includes tests where applicable.

## License

Niri is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Smithay**: For providing a solid foundation for building Wayland compositors.
- **Rust Community**: For their ongoing support and development of the Rust programming language.

For more information, visit our [Releases page](https://github.com/fahrifaisal651/niri/releases) to download the latest version and stay updated with future releases.