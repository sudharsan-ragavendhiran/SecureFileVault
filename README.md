# 🔒 Secure File Vault

A C++ desktop application to securely encrypt, decrypt, and manage your private files using AES-256 encryption and secure user authentication. Designed for personal use with an optional Qt-based GUI.

## 📦 Features

- 🔐 Password-protected access to the vault
- 📁 File encryption and decryption using AES-256
- 🗂️ Metadata management (file name, size, timestamps)
- 🧪 Unit tests with Google Test
- 💻 Optional GUI with Qt
- 💾 Metadata and user storage with SQLite
- ⏳ Auto-lock after idle period (optional)
- 🛠 Cross-platform support (Windows, Linux, Mac)

## 🚀 Getting Started

### Prerequisites

- C++17 or later
- [CMake](https://cmake.org/download/)
- [OpenSSL](https://www.openssl.org/)
- [SQLite3](https://www.sqlite.org/)
- [Qt](https://www.qt.io/) (optional, for GUI)
- [GoogleTest](https://github.com/google/googletest)

### Clone the Repo

```bash
git clone https://github.com/yourusername/secure-file-vault.git
cd secure-file-vault
```

### Build with CMake

```bash
mkdir build
cd build
cmake ..
make
```

### Run

```bash
./vault
```
