## Advanced Domain Scanner 🔍

![Banner](https://raw.githubusercontent.com/Nipho999/scanner/refs/heads/main/IMG_20250616_212530.jpg)

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Node.js-≥18.0-yellow" alt="Node.js">
</p>

A high-performance HTTP/S domain scanning tool with SSL & WEBSOCKET support <b>☁️</b>🗝️

## ✨¨ Features
- **Multi-mode scanning**
- **Progress visualization**
- **Error suppression**
- **UID authentication**
- **Export results**
- **Proxy support**

##  🛠› Installation

### 🔹› Clone repository
```bash
git clone https://github.com/Nipho999/scanner.git
```

### 🔹› Go to directory
```bash
cd scanner
```

###  🛠› Install dependencies
```bash
npm install chalk@4 readline
```

### › Direct scan
```bash
node tbk-scan.js
```

### › SSL scan
```bash
node tbk-scan.js --ssl your.ssh.server 443
```

### › WebSocket scan
```bash
node tbk-scan.js --ws your.ssh.server 443
```

## › License

Licensed under the MIT License.
