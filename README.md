# Tessera Node Binary Releases

[![Release Status](https://img.shields.io/github/v/release/Chainscore/tessera-releases?label=latest)](https://github.com/Chainscore/tessera-releases/releases)

> **Automated binary releases for [Tessera Node](https://github.com/Chainscore/tessera)**  
> For support or issues, contact [prasad@chainscore.finance](mailto:prasad@chainscore.finance)

---

## 🚀 Latest Release

Find the latest binaries in the [Releases](https://github.com/Chainscore/tessera-releases/releases) section.

| Platform                | Download Name                       |
|-------------------------|-------------------------------------|
| Linux x86_64            | `tessera-node-Linux-x64.tar.gz`     |
| macOS Apple Silicon     | `tessera-node-Darwin-arm64.tar.gz`  |
| macOS Intel             | `tessera-node-Darwin-x64.tar.gz`    |

---

## 📦 Quick Start

```sh
# Extract the binary
tar -xzf tessera-node-*.tar.gz

# Run node
./tessera-node --help
./tessera-node --env <environment>

# Run fuzzer target
./tessera-node --fuzzer --socket /tmp/jam_conformance.sock
```

---

## 🔍 Build Info

- **Python**: 3.12
- **PyInstaller**: Latest
- **Automated Build**: [build-binaries.yml](.github/workflows/build-binaries.yml)
- **Release Date**: See individual release notes
