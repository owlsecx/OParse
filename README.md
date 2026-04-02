# 📝 OFrm

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OUtility%20%2F%20Data%20Engineering-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v2.0-cyan?style=flat-square"/>
</p>

> **OFrm** is a powerful data formatter and converter. It supports formatting, validation, and conversion between **JSON**, **XML**, and **YAML**, plus minify, diff, batch processing, and customizable output.

---

## 📌 Overview

OFrm makes working with structured data simple and fast. Whether you need to pretty-print, validate, convert formats, minify, or compare JSON objects — OFrm handles it all in a clean terminal interface with colored output and automatic file saving.

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Format / Validate**       | Pretty-print and validate JSON, XML, or YAML |
| **[2]** | **JSON → XML**              | Convert JSON to well-formatted XML |
| **[3]** | **XML → JSON**              | Convert XML to JSON |
| **[4]** | **JSON → YAML**             | Convert JSON to YAML (requires pyyaml) |
| **[5]** | **YAML → JSON**             | Convert YAML to JSON (requires pyyaml) |
| **[6]** | **Minify**                  | Compress JSON or XML (remove whitespace) |
| **[7]** | **Diff**                    | Compare two JSON objects and show differences |
| **[8]** | **Batch Convert**           | Process all matching files in a folder |
| **[9]** | **Settings**                | Configure indent, output directory, XML tags, preview lines |

---

## 📊 Key Features

- **Multi-Format Support**: JSON, XML, YAML (with optional pyyaml)
- **Smart Format Detection**: Automatically detects input format
- **Pretty Printing**: Clean, readable output with configurable indent
- **Validation**: Detailed error messages for malformed data
- **JSON Diff**: Clear ADD/DEL/CHNG comparison between two objects
- **Batch Processing**: Convert entire folders with summary CSV report
- **Custom XML Tags**: Define root and item tags for JSON → XML conversion
- **Automatic Saving**: All results saved to `ofrm_results/` with timestamp

---

## ⚙️ Requirements

- **Linux or Windows**
- **No Python installation needed** — runs as a standalone executable
- **Optional**: `pyyaml` for YAML support (`pip install pyyaml`)

---

## 🚀 Usage

```bash
./OFrm


📁 Output
All results are saved to the ofrm_results/ directory:

ofrm_YYYYMMDD_HHMMSS.json
ofrm_YYYYMMDD_HHMMSS.xml
ofrm_YYYYMMDD_HHMMSS.yaml
ofrm_batch_YYYYMMDD_HHMMSS.csv (batch summary)


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
