## Advanced Domain Scanner ðŸ”

![Banner](https://raw.githubusercontent.com/cristina/scanner/refs/heads/main/IMG_20250616_212530.jpg)

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Node.js-â‰¥18.0-yellow" alt="Node.js">
</p>

A high-performance domain scanning tool with proxy support, reverse proxy detection, and intelligent filtering.

## âœ¨ Features
- **Multi-mode scanning**
- **Progress visualization**
- **Error suppression**
- **UID authentication**
- **Export results**
- **Proxy support**

## ðŸ›  Installation

### ðŸ”» Clone repository
```bash
git clone https://github.com/cristina/scanner.git
```

### ðŸ“ Go to directory
```bash
cd scanner
```

### ðŸ“¦ Install dependencies
```bash
npm install chalk@4 readline
```

### ðŸš€ Direct scan
```bash
node tbk-scan.js
```

### ðŸ” SSL scan
```bash
node tbk-scan.js --ssl your.ssh.server 443
```

### ðŸŒ WebSocket scan
```bash
node tbk-scan.js --ws your.ssh.server 443
```

## ðŸ“„ License

Licensed under the MIT License.
