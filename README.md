# Miasm Wheels (Linux & Windows x86_64)

Automated GitHub Actions builder for [Miasm](https://github.com/cea-sec/miasm) binary wheels on **Linux x86_64** (`manylinux`) and **Windows 11 / x86_64** (`win_amd64`), packaged together with required dependency wheels (`future`, `pyparsing`).

## Prebuilt Packages

### Linux x86_64
- **miasm**: Compiled binary wheels for CPython `3.10`, `3.11`, `3.12`, `3.13` (manylinux2014 / glibc >= 2.17).
- [Linux Releases](../../releases/tag/v0.1.5-linux-x86_64)

### Windows 11 / x86_64 (win_amd64)
- **miasm**: Compiled binary wheels for CPython `3.10`, `3.11`, `3.12`, `3.13`, `3.14` (Windows AMD64).
- [Windows Releases](../../releases/tag/v0.1.5-windows-amd64)

### Dependencies
- **future**: Universal wheel (`future-1.0.0-py3-none-any.whl`).
- **pyparsing**: Universal wheel (`pyparsing-3.3.2-py3-none-any.whl`).

## Quick Install (Windows)

```powershell
pip install future pyparsing==3.3.2
pip install <path_to_miasm_wheel>.whl
```
