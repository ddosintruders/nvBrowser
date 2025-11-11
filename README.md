<p align="center">
  <img src="Resources/Icons/nvBrowser Icon Version 1.png" alt="nvBrowser Logo" width=100>
</p>
  
<h1 align="center">nvBrowser</h1>

<p align="center">
  nvBrowser is a project aimed to make a fully-editable metadata environment based browser, focusing on research, testing, and privacy.
</p>

<div align="center">

[![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I5I0713E)

</div>

> [!CAUTION]  
> This browser is specifically designed for privacy and research/testing purposes.
> Use of the browser in illegal ways is **NOT** encouraged.
> The author(s) of this project are not liable for any misconduct performed using this project's contents.

## Overview

nvBrowser extends the privacy-hardened foundation of LibreWolf by adding powerful profile management and configurable fingerprinting capabilities. Each profile maintains its own metadata configuration, network routing preferences, and fingerprint resistance settings, enabling users to switch between different browsing identities seamlessly.

### Key Features

- **Multi-Profile Management**: Create, edit, and switch between named profiles with distinct configurations
- **Configurable Metadata**: Customize OS name, hostname, user-agent, ISP label, timezone, locale, and location per profile
- **Fingerprint Resistance Modes**: Choose between Minimal, Resist, or Dev modes for different levels of fingerprint protection
- **Network Routing Options**: Configure profiles to use direct connections, Tor, VPN, or custom proxies
- **Real-Time Provenance Panel**: Visual display showing active overrides and spoofed values
- **Profile Import/Export**: Share and backup profiles using JSON format
- **Audit Logging**: Track profile changes and browser actions with local logs
- **Privacy by Default**: Built on LibreWolf's telemetry-free, tracking-resistant foundation

---

## Use Cases

nvBrowser is designed for legitimate privacy and testing scenarios:

- **Privacy Research**: Study browser fingerprinting techniques and develop countermeasures
- **Web Development Testing**: Test applications across different user-agent, locale, and timezone configurations
- **Security Research**: Analyze how websites handle different browser identities
- **Personal Privacy**: Maintain separate browsing identities for different contexts
- **Cross-Platform Testing**: Simulate different operating systems and devices without virtual machines

---

## Project Status

**Current Version**: 1.01 - Genesys  
**Status**: Active Development

nvBrowser is currently in early development. The core profile management system and configuration interface are being implemented. This is a long-term project built iteratively with careful attention to privacy, security, and user experience.

---

## Built With

- **Base**: LibreWolf (Firefox ESR fork)
- **Languages**: JavaScript, C++, Rust, HTML, CSS
- **Build System**: Mozilla Build System (mach)
- **Installer**: NSIS (Nullsoft Scriptable Install System)

---

## Getting Started

### Prerequisites

- Windows 10/11 (current build target)
- 40-60GB free disk space
- 8GB RAM minimum (16GB recommended)
- Git for version control

### Building from Source

Detailed build instructions will be provided as the project progresses. The build process follows LibreWolf's compilation workflow with nvBrowser-specific modifications.

---

## Screenshots

Interface designs and screenshots will be added as features are implemented.

---

## Roadmap

### Phase 1: Foundation
- Set up build environment
- Successful LibreWolf compilation
- Basic branding changes

### Phase 2: Core Features
- Profile management system
- Metadata configuration interface
- Profile switching functionality

### Phase 3: Fingerprint Protection
- Fingerprint resistance modes implementation
- Canvas/WebGL protection
- Real-time provenance panel

### Phase 4: Network Integration
- Tor/VPN routing per profile
- Proxy configuration management
- Connection monitoring

### Phase 5: Polish & Distribution
- Audit logging system
- Profile import/export
- NSIS installer creation
- Documentation and guides

---

## Contributing

nvBrowser is currently in early development. Contribution guidelines will be established as the project matures.

---

## Disclaimer

nvBrowser is provided as-is for legitimate privacy research, testing, and personal use.

**User Responsibility**: You are solely responsible for how you use this software. Using nvBrowser to violate laws, terms of service, or engage in fraudulent activities is prohibited. The author(s) are not liable for misuse of this software.

**No Warranty**: This software is provided without warranty of any kind, either express or implied. Use at your own risk.

**Compliance**: Users must comply with all applicable laws and regulations in their jurisdiction.

---

## License

nvBrowser is licensed under the Mozilla Public License 2.0 (MPL 2.0), maintaining compatibility with the LibreWolf and Firefox codebases.

See [LICENSE](LICENSE) for full license text.

---

## Credits

**Design & Development**: Adnan Ahmed  
**Built with AI Collaboration**: Developed in partnership with Claude (Anthropic)  
**Usage Testing**: M. Janoowalla  
**Based on**: LibreWolf Project, Mozilla Firefox

---

## Links

- **Source Code**: [GitHub Repository](https://github.com/ddosintruders/nvBrowser)
- **Documentation**: Coming soon
- **Developer**: [Portfolio/Contact](https://adnan-ahmed.pages.dev)

---

## Acknowledgments

nvBrowser builds upon the excellent work of:
- The LibreWolf team for their privacy-focused Firefox fork
- The Mozilla Foundation for the Firefox browser and Gecko engine
- The Tor Project for pioneering browser fingerprint resistance techniques
- The open-source privacy community

---

**Note**: This project is under active development. Features, documentation, and interfaces are subject to change as development progresses.

Built with privacy, transparency, and user control as core principles.
