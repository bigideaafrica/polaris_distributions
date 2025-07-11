# Polaris Distributions

This repository contains distribution packages for the Polaris Node Manager application, organized by version.

## 🚀 Latest Version: v2.0.4

**Polaris Node Manager v2.0.4** introduces critical security enhancements with updated server public keys and comprehensive endpoint security improvements, ensuring maximum protection for all mining operations and data communications.

### 🔒 What's New in v2.0.4
- **Updated Server Public Keys**: New cryptographic keys with enhanced RSA-4096 encryption
- **Endpoint Security Hardening**: Comprehensive security improvements for all API endpoints
- **Enhanced SSL/TLS Configuration**: Upgraded to TLS 1.3 with perfect forward secrecy
- **Certificate Pinning**: Added certificate pinning for all secure connections
- **API Authentication Strengthening**: Improved token validation and refresh mechanisms
- **Security Audit Compliance**: Implemented security measures based on professional audit
- **Encrypted Data Transmission**: All data now encrypted with AES-256-GCM
- **Rate Limiting**: Advanced rate limiting to prevent abuse and DDoS attacks

### Key Features from v2.0.0 (Still Included)
- **Multi-Machine Management**: Register and manage multiple mining rigs under a single UID
- **Self-Validation System**: Automated server authentication and performance benchmarking
- **Real-time Monitoring**: Live status tracking for all connected mining machines
- **Activity Logging**: Comprehensive logging of mining operations and system events
- **Modern React UI**: Clean, responsive interface built with React and Material-UI Joy
- **Enhanced Cross-platform Support**: Optimized for Windows, macOS, and Linux

## Available Platforms

- **Windows**: Universal ZIP build and traditional installer
- **Linux**: Universal ZIP build (containing AppImage) and direct AppImage
- **MacOS**: Universal ZIP build and traditional DMG installer

## Available Versions

- **[v2.0.4](./v2.0.4/) - Latest Release** ⭐
  - Updated server public keys with RSA-4096 encryption
  - Comprehensive endpoint security hardening and TLS 1.3 upgrade
  - Certificate pinning and enhanced API authentication
  - Security audit compliance and encrypted data transmission

- **[v2.0.3](./v2.0.3/) - Previous Release**
  - Advanced real-time monitoring system with four key monitoring components
  - Visual status dashboard with color-coded indicators and diagnostic tooltips
  - Automatic health checks and continuous monitoring
  - Performance tracking with tier qualification status

- **[v2.0.2](./v2.0.2/) - Previous Release**
  - API-based connection system for improved reliability
  - Simplified SSH key management with direct key input
  - Enhanced security and streamlined user interface

- **[v2.0.1](./v2.0.1/) - Previous Release**
  - SSH client overhaul for enhanced stability
  - Python-based automatic remote hardware detection
  - Verified compute resource deletion with Firebase API

- **[v2.0.0](./v2/) - Stable Release**
  - Multi-machine management with unified UID support
  - Advanced validation and benchmarking system
  - Modern React-based interface
  - Enhanced monitoring and logging capabilities

- [v1.0.0](./v1/) - Legacy Release
  - Single machine setup and basic monitoring
  - Initial Bittensor network integration

## Download Instructions

### Quick Download (Recommended)

**Latest v2.0.4**: Visit the [Releases](https://github.com/bigideaafrica/polaris_distributions/releases) page and download the latest version for your platform.

### Version-Specific Download

Navigate to the specific version folder:
- **v2.0.4** (Latest): [v2.0.4/](./v2.0.4/)
  - Windows: [v2.0.4/windows](./v2.0.4/windows/)
  - Linux: [v2.0.4/linux](./v2.0.4/linux/)
  - MacOS: [v2.0.4/macos](./v2.0.4/macos/)

- **v2.0.3**: [v2.0.3/](./v2.0.3/)
  - Windows: [v2.0.3/windows](./v2.0.3/windows/)
  - Linux: [v2.0.3/linux](./v2.0.3/linux/)
  - MacOS: [v2.0.3/macos](./v2.0.3/macos/)

- **v2.0.2**: [v2.0.2/](./v2.0.2/)
  - Windows: [v2.0.2/windows](./v2.0.2/windows/)
  - Linux: [v2.0.2/linux](./v2.0.2/linux/)
  - MacOS: [v2.0.2/macos](./v2.0.2/macos/)

- **v2.0.1**: [v2.0.1/](./v2.0.1/)
  - Windows: [v2.0.1/windows](./v2.0.1/windows/)
  - Linux: [v2.0.1/linux](./v2.0.1/linux/)
  - MacOS: [v2.0.1/macos](./v2.0.1/macos/)

- **v2.0.0**: [v2/](./v2/)
- **v1.0.0** (Legacy): [v1/](./v1/)

### Clone Repository

Clone this repository for offline access:
```bash
git clone https://github.com/bigideaafrica/polaris_distributions.git
```

## Large Files Note

This repository uses Git Large File Storage (Git LFS) to manage the installer files. If you want to clone the entire repository including the large installer files:

1. **Install Git LFS**: If you haven't installed Git LFS, do so first:
   ```
   # For Windows (using Chocolatey)
   choco install git-lfs
   
   # For Linux (Debian/Ubuntu)
   sudo apt install git-lfs
   
   # For macOS (using Homebrew)
   brew install git-lfs
   ```

2. **Clone with LFS**: Then clone the repository:
   ```
   git lfs install
   git clone https://github.com/bigideaafrica/polaris_distributions.git
   ```

3. **Pull Large Files**: If you've already cloned, run:
   ```
   git lfs pull
   ```

## Distribution Structure

Each version folder contains:
- Platform-specific installers
- README with version-specific information
- Requirements and dependency information
- Release notes and key features

## System Requirements

### Minimum Requirements
- **RAM**: 4GB minimum (8GB recommended for multi-machine management)
- **Storage**: 500MB disk space (increased for v2 features)
- **Network**: Stable internet connection
- **Permissions**: Administrator/sudo privileges for installation

### Platform-Specific Requirements

#### Windows
- Windows 10 or later (64-bit)
- .NET Framework 4.8+ (included in installer)
- Windows PowerShell 5.0+

#### Linux
- Modern Linux distribution (Ubuntu 20.04+, Fedora 35+, Debian 11+)
- systemd support (for service management)
- GTK3+ libraries (for GUI)

#### MacOS
- macOS 10.15 (Catalina) or later
- Apple Silicon (M1/M2) and Intel processors supported

### Mining Performance Requirements
- **CPU**: Multi-core processor (4+ cores recommended for v2)
- **RAM**: 8GB+ for optimal multi-machine management
- **GPU**: Optional but recommended (NVIDIA/AMD with current drivers)
- **Network**: Low-latency connection for real-time monitoring

## Key Features Comparison

| Feature | v1.0.0 | v2.0.0 |
|---------|--------|--------|
| Machine Management | Single machine | Multiple machines under one UID |
| User Interface | Basic GUI | Modern React + Material-UI |
| Validation System | Manual setup | Automated self-validation |
| Real-time Monitoring | Basic stats | Live status + activity logs |
| Performance Benchmarking | None | Built-in CPU/GPU scoring |
| Cross-platform | Windows/Linux | Windows/Linux/MacOS |
| Network Monitoring | Basic | Advanced with response times |

## Roadmap

- **v2.0.4** ✅ - Updated server public keys, comprehensive endpoint security hardening, TLS 1.3 upgrade
- **v2.0.3** ✅ - Advanced real-time monitoring system, visual status dashboard, automatic health checks
- **v2.0.2** ✅ - API-based connection system, enhanced SSH key management, streamlined UI
- **v2.0.1** ✅ - SSH overhaul, Python-based hardware detection, resource deletion verified
- **v2.0.0** ✅ - Multi-node management with self-validation
- **v2.1.0** 🔄 - Advanced analytics and reporting dashboard (Planned)
- **v2.2.0** 📋 - Enhanced API integration and remote management (Planned)
- **v3.0.0** 🚀 - Cloud-based management and mobile app (Planned)

## Build Information

All releases are built using PyInstaller and include necessary dependencies. The Windows installers are created using NSIS, while Linux packages are provided as DEB, RPM, and tar.gz formats.

## License

Polaris Installer is distributed under the [MIT License](https://opensource.org/licenses/MIT).

- 🐛 Issues: [GitHub Issues](https://github.com/bigideaafrica/polaris_distributions/issues) 

## 📋 Version History

| Version | Release Date | Key Features |
|---------|-------------|--------------|
| **v2.0.4** | Latest | Updated server public keys, endpoint security hardening, TLS 1.3 upgrade, certificate pinning |
| v2.0.3 | Previous | Advanced real-time monitoring system, comprehensive health checks, visual status dashboard |
| v2.0.2 | Previous | API-based connection system, enhanced SSH key management, streamlined UI |
| v2.0.1 | Archive | SSH overhaul, automated hardware detection, enhanced connection flow |
| v2.0.0 | Archive | Multi-machine management, Bittensor integration, modern UI |
