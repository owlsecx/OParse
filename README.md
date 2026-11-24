# 🦉 OParse

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OParse** — Owl Data Formatter & Parser

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

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

---

## 🔍 Verification & Transparency

This tool is closed-source. These files let you see exactly what is inside it,
without the source:

- [`SBOM.cdx.json`](SBOM.cdx.json) — CycloneDX inventory: SHA-256 of this
  binary, bundled CPython version, and every bundled library with its exact
  version and license. Feed it to Grype, Trivy or Dependency-Track to audit
  our dependencies for CVEs yourself.
- [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) — the full license text
  of every third-party component, extracted from this binary.

**No telemetry, no analytics, no licence check-in.** This tool does not phone
home. Verify that claim yourself:

```bash
sudo strace -f -e trace=network ./OParse --help   # watch every network call
firejail --net=none ./OParse --help               # deny the network entirely
```

Release signing, GPL compliance and vulnerability reporting:
[**TRUST.md**](https://github.com/owlsecx/owl-os/blob/main/TRUST.md)
