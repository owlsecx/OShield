# 🦉 OShield

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OShield** — UEBA login behavior anomaly engine using KDE statistical baselines

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OShield is a user-and-entity behaviour analytics (UEBA) engine that detects anomalous login activity from authentication data. It combines kernel-density estimation with temporal, geographic, velocity and device signals, applying decay weighting so recent behaviour counts more. It is built for authorized security analysis on Debian Linux and produces risk-scored findings from your login history.

---

## ✨ Features


- Login-behaviour anomaly scoring via kernel density estimation (KDE)
- Temporal, geographic, velocity and device-fingerprint signals combined into one risk model
- Time-decay weighting so recent events carry more influence than stale history
- Reads login/auth event data and surfaces unusual sessions for review
- Offline, read-only analysis intended for authorized security work only
- Built-in --self-test mode plus --version/--help entry points

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OShield
./OShield --self-test
./OShield --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
