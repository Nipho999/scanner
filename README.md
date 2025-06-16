## Advanced Domain Scanner 🔍

![Banner](https://raw.githubusercontent.com/Nipho999/scanner/refs/heads/main/IMG_20250616_212530.jpg)

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Node.js-≥18.0-yellow" alt="Node.js">
</p>

A high-performance domain scanning tool with proxy support, reverse proxy detection, and intelligent filtering.

## ✨ Features
- **Multi-mode scanning**
- **Progress visualization**
- **Error suppression**
- **UID authentication** 
- **export Results**

## 🛠 Installation
<small>
```bash
# Clone repository
git clone https://github.com/Nipho999/scanner.git
cd scanner

# Install dependencies
npm install chalk@4 readline

# Run the code
node tbk-scan.js ( it will use direct mode )
node tbk-scan.js --ssl your.ssh.server 443 ( it will use ssl mode )
node tbk-scan.js --ws your.ssh.server 443 ( it will use websocket mode )
</small>
