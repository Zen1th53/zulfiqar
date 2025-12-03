# Table of Contents
- [Description](#description)
- [Overview](#overview)
- [Download and Installation](#download-and-installation)
- [Key Features](#key-features)
- [Installation Instruction](#installation-instruction)
- [Usage](#usage)
- [Get Involved](#get-involved)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)
- [Disclaimer](#disclaimer)
- [Conclusion](#conclusion)

---

# Description
**Zulfiqar OS Linux** is an Arch Linux–based penetration testing distribution for
penetration testers and security researchers. The repository contains [2880
tools](https://www.zulfiqar.org/tools.html). You can install tools individually
or in groups. Zulfiqar OS Linux is compatible with existing Arch installations.
For more information, see the installation instructions.

---

# Overview
To report bugs and request new tools, visit the issue tracker on
[GitHub](https://github.com/Zulfiqar OS/zulfiqar/issues), stop by
[Matrix](https://matrix.to/#/#Zulfiqar OS:matrix.org), or [email
us](mailto:team@zulfiqar.org).

**Zulfiqar OS Linux** is specifically designed for **penetration testers** and
**security researchers**. The repository contains over **2,800 tools**,
organized by category, allowing users to install them individually or in
**groups**.

**Zulfiqar OS** is fully compatible with existing Arch Linux installations, making
it a versatile choice for those who want to enhance their existing systems with
security tools.

---

# Download and Installation
Whether you're a cybersecurity professional, enthusiast, or researcher,
**Zulfiqar OS** offers the tools you need for a variety of tasks, such as
**penetration testing**, **forensics**, **reverse engineering**, **network
analysis**, and more.

Zulfiqar OS Linux only takes a moment to set up.

---

# Key Features
- **Over 2,800 Tools** – categorized for different testing scenarios
- **Arch Linux–based** – benefits from Arch’s rolling release updates
- **Compatibility** – integrates seamlessly with existing Arch setups
- **Customizable Installation** – Full, Slim, or Repo-based options
- **Live ISO** – test Zulfiqar OS without installing it

---

# Installation Instruction
Setting up **Zulfiqar OS Linux** is quick and easy. There are three primary
installation methods depending on your preference.

To start developing for Zulfiqar OS, refer to the [Developer
Guide](./docs/HOWTO-DEV.md).

## 1. Install on an Existing Arch Machine
If you're running **Arch Linux**, you can install **Zulfiqar OS tools** directly
onto your system using the Zulfiqar OS repository.

**Website:** https://www.zulfiqar.org/

```bash
# Sync the Zulfiqar OS repository
curl -s https://zulfiqar.org/strap.sh | sudo bash

# Install all Zulfiqar OS tools or specific ones
sudo pacman -S zulfiqar
```
## 2. Live ISO Installation

The Live ISO allows you to try Zulfiqar OS without installation.

Download the Live ISO from the official website and boot from it to start
penetration testing immediately.

## 3. Full, Netinstall, or Slim ISOs

Full ISO – complete set of tools with a text-based installer (zulfiqar-install)

Netinstall ISO – minimal installer (requires internet)
Slim ISO – lightweight version with GUI-based installer
For detailed steps, see the installation documentation.

---

# Usage

## Once installed, you can add or remove tools.

```bash
# Install all Zulfiqar OS tools
sudo pacman -S zulfiqar
```

## Install Specific Tool Groups

```bash
# Example: Web Application Security tools
sudo pacman -S zulfiqar-webapp
```

For a complete list of available tools, visit the official tools page.

### Running Tools

After installation, you can run tools directly from the terminal or application
menu. Most tools are command-line based, ideal for automation and scripting.

# Get Involved

Zulfiqar OS is open source and welcomes contributions from the community.
Whether you're a developer, researcher, or user, you can help in several ways.
Report Bugs or Request Tools

If you encounter a bug or have suggestions:

GitHub Issues: [Zulfiqar OS Issues](https://github.com/Zulfiqar OS/zulfiqar/issues)

Matrix Chat: [#Zulfiqar OS:matrix.org](https://matrix.to/#/#Zulfiqar OS:matrix.org)

---

# Contributing

We Encourage contributions in various forms:

* Bug fixes
* Documentation
* New tools
* tool groups

Before contributing, Review our Contributor Covenant Code of Conduct.

Refer to the Developer Guide for detailed steps.
Pull Requests
Fork the repository, make your changes, and submit a PR following our
contribution guidelines.

---

# Contact

Email: team@zulfiqar.org

Matrix: [#Zulfiqar OS:matrix.org](https://matrix.to/#/#Zulfiqar OS:matrix.org)

For news and updates, visit our official blog.

---

# License

## License: [![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD--3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)


Zulfiqar OS Linux is released under the BSD-3-Clause license. See the COPYING file
for details.

---

# Disclaimer

Zulfiqar OS Linux is intended for ethical hacking, penetration testing, and
security research only. Use it only on systems you own or have permission to
test.

---

# Conclusion

Zulfiqar OS Linux is a powerful, flexible, and comprehensive penetration testing
platform built on Arch Linux.

Whether you're conducting a security audit, performing vulnerability
assessments, or learning cybersecurity, Zulfiqar OS provides all the tools you
need to succeed.
# zulfiqar
# zulfiqar
