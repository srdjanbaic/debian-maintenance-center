# Debian Maintenance Center

**A simple terminal-based system maintenance utility for Debian GNU/Linux.**

Debian Maintenance Center provides a convenient way to perform common system maintenance tasks through an interactive terminal interface.

## Features

- Update installed packages
- Remove unnecessary packages
- Clean the APT package cache
- Check package database health
- Check system package dependencies
- Clean old system journal entries
- Detect and run SSD/NVMe TRIM when supported
- Display disk usage and available storage space
- Check whether a system reboot is required
- Save maintenance logs

## Requirements

- Debian GNU/Linux
- Bash
- APT and dpkg
- systemd
- sudo for administrative operations
- A compatible terminal emulator for the desktop launcher

## Installation

Download the Debian package from the [GitHub Releases](https://github.com/srdjanbaic/debian-maintenance-center/releases) page.

Install the downloaded package with:

```bash
sudo apt install ./debian-maintenance-center_1.0.0_all.deb
```

## Usage

Launch Debian Maintenance Center from your desktop application menu or open a terminal and run:

```bash
debian-maintenance-center
```

Administrative operations require appropriate privileges.

## Maintenance Logs

Maintenance logs are stored in:

```text
~/.local/state/debian-maintenance-center/
```

## Source Code

The project source code is available in this repository.

The main application, desktop launcher and SVG icon are included.

## License

This project is distributed under the [MIT License](LICENSE).

Copyright (c) 2026 Debian Maintenance Center Team
