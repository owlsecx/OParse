# 🦉 OParse

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OParse** — Owl Data Formatter & Parser ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OParse is a data formatter and parser for converting and querying structured data (JSON, XML, YAML, TOML, CSV) with flatten, NDJSON, and keypath helpers on the CLI. Core features use the standard library; optional packages enable YAML/TOML/JMESPath. Batch transform, schema validation, and config persistence are available in the broader interactive workflow.

---

## ✨ Features

- Flatten JSON files to dotted keys (`--flatten`)
- Parse NDJSON into a JSON array (`--ndjson`)
- Extract a keypath from a JSON file (`--keypath FILE PATH`)
- Configurable output directory via `--output` / `-o`
- Broader workflow: JSON ↔ XML ↔ YAML ↔ TOML ↔ CSV convert, validate, diff, and hash
- Optional JMESPath query and JSON Schema validation when extra packages are installed

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OParse --flatten data.json
./OParse --ndjson events.ndjson -o oparse_results
./OParse --keypath data.json user.email
./OParse --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
