# Miasm Wheels (Linux x86_64)

Automated GitHub Actions builder for [Miasm](https://github.com/cea-sec/miasm) binary wheels on Linux x86_64 (`manylinux`), packaged together with required dependency wheels (`future`, `pyparsing`).

## Built Packages

- **miasm**: Compiled binary wheels for CPython `3.10`, `3.11`, `3.12`, `3.13` (manylinux x86_64).
- **future**: Universal wheel (`future-1.0.0-py3-none-any.whl`).
- **pyparsing**: Universal wheel (`pyparsing-3.3.2-py3-none-any.whl`).

## Quick Install

Download the wheels from the latest [GitHub Release](../../releases) and install offline:

```bash
pip install future-1.0.0-py3-none-any.whl pyparsing-3.3.2-py3-none-any.whl miasm-*.whl
```
