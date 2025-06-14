# Configurations Repository

This repository contains configuration files for various development tools and environments, organized by platform and tool.

## Contents

- **maven/**: Maven configuration files (`settings.xml`, `settings-default.xml`).
- **ssh/**: SSH configuration files for different platforms:
  - `mac/config`: SSH config for macOS.
  - `windows/config`: SSH config for Windows.
  - `wsl/config`: SSH config for Windows Subsystem for Linux (WSL).
- **vim/**: Vim editor configuration files.
- **zsh/**: Zsh shell configuration files.

## Usage

Copy the relevant configuration files to your home directory or the appropriate location for your system or tool. For example:

- For Maven, copy `settings.xml` to `~/.m2/settings.xml`.
- For SSH, copy the appropriate `config` file to `~/.ssh/config`.
- For Vim and Zsh, copy the configuration files to your home directory.

## Notes

- The SSH configs are tailored for each platform and may include proxy settings (e.g., SOCKS proxy at 127.0.0.1:1080).
- Review and update identity files, proxy addresses, and other sensitive information as needed for your environment.
