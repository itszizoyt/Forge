# ⚒️ FORGE

### Forge your ideas into reality.

**A lightweight, modern programming language built with C++.**

<p align="center">
  <img src="https://img.shields.io/badge/version-0.8.0-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/status-in%20development-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/source%20files-.forge-blue?style=for-the-badge" />
</p>

---

## 🔥 What is FORGE?

FORGE is a lightweight programming language designed to make coding straightforward, readable, and expressive.

With its own syntax, interpreter, and growing package ecosystem, FORGE aims to provide developers with a simple yet capable programming experience.

## ✨ Language Features

- Variables and data types
- Functions and return statements
- Conditional statements
- While loops
- Arithmetic operations
- Comparisons and logical operators
- Short-circuit logical evaluation
- Syntax checking
- Inline code execution

## 🚀 Your First Program

Create a file named `hello.forge`:

```forge
say "Hello from FORGE!"
```

Execute it using the FORGE interpreter:

```cmd
forge hello.forge
```

Output:

```text
Hello from FORGE!
```

## 📖 Language Example

```forge
let name: string = "FORGE"
let version: float = 0.8

fn greet(person):
    say "Hello," person
    return true

if version >= 0.8:
    greet(name)
else:
    say "Welcome!"
```

## ⚙️ Command Line

| Command | Description |
|---|---|
| `forge file.forge` | Run a FORGE program |
| `forge --help` | Display help |
| `forge --version` | Display version |
| `forge -c "CODE"` | Execute inline code |
| `forge --check file.forge` | Check syntax |
| `forge --tokens file.forge` | Display tokens |

## 📦 FPM — Forge Package Manager

FPM is the official package management tool for the FORGE ecosystem.

Available commands:

| Command | Description |
|---|---|
| `fpm --help` | Display help |
| `fpm --version` | Display version |
| `fpm init` | Initialize a project |
| `fpm list` | List packages |

More package management capabilities are planned.

## 🌐 FPI — Forge Package Index

FPI is the planned official package registry for FORGE.

It aims to provide a central location for discovering and distributing community packages.

## 🗺️ Development Roadmap

- [x] Core interpreter
- [x] Variables and data types
- [x] Functions
- [x] Conditional statements
- [x] Loops
- [x] Arithmetic and comparisons
- [x] Logical operators
- [x] Initial FPM release
- [ ] Import system
- [ ] Standard library
- [ ] Expanded package management
- [ ] FPI registry
- [ ] FORGE 1.0.0

## 📊 Current Status

**Version:** 0.8.0  
**Release stage:** Development  
**Source extension:** `.forge`  
**Package manager:** FPM  
**Package registry:** FPI (planned)

FORGE is actively evolving toward its first stable release.

## 🔗 Official Links

- **Website:** https://forge.2bd.net
- **Downloads:** https://forge.2bd.net/download
- **Documentation:** https://forge.2bd.net/docs
- **Packages:** https://forge.2bd.net/packages

---

<p align="center">

**⚒️ FORGE**

*Forge your ideas into reality.*

</p>
