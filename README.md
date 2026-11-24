
# Debian Maintenance Center

A simple terminal-based system maintenance utility for Debian GNU/Linux.

## Features

- Update installed packages
- Remove unnecessary packages and clean APT cache
- Check package database health
- Check system package dependencies
- Clean old system journal entries
- Detect and run SSD/NVMe TRIM when supported
- Report disk usage and available space
- Check whether a system reboot is required
- Save maintenance logs

## Requirements

- Debian GNU/Linux
- Bash, APT and dpkg
- systemd
- sudo for administrative operations
- A desktop terminal emulator for the desktop launcher

## Installation

Download the Debian package from the [Releases](https://github.com/srdjanbaic/debian-maintenance-center/releases) page.

Install it with:

```bash
sudo apt install ./debian-maintenance-center_1.0.0_all.deb
```

Launch Debian Maintenance Center from your desktop application menu or run:

```bash
debian-maintenance-center
```

## License

This project is distributed under the MIT License.

Copyright (c) 2026 Debian Maintenance Center Team
