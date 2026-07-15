# 🐍 Vebora GNU/Linux | Viper Package Manager

---

## 🛠 Project Overview
**vpm** is the custom-built, source-first package manager for **🐍 Vebora GNU/Linux**. Unlike conventional binary-based package managers, vpm is designed to automate the LFS (Linux From Scratch) build process, ensuring every binary is compiled with hardened flags, stripped of bloat, and optimized for security.

## 🚀 Key Features
* **Source-First Compilation:** Compiles packages from source with security-hardened flags.
* **Dependency Resolution:** A custom resolver engine built to handle complex LFS dependency trees.
* **Modular Service Management:** Seamless integration with `dinit` for minimalist init management.
* **Anti-Forensic Ready:** Designed to support memory-only execution and zero-logging protocols.

## 🏗 Roadmap
- [ ] **Phase 1:** Core structure & CLI architecture (In Progress)
- [ ] **Phase 2:** Dependency resolver engine
- [ ] **Phase 3:** Build automation (Source to Binary)
- [ ] **Phase 4:** LFS toolchain integration

## 📂 Architecture
Rose consists of four primary modules:
1. `resolver`: Manages dependency trees and conflicts.
2. `builder`: Wraps build processes and enforces hardening flags.
3. `db`: Tracks installed packages and state.
4. `cli`: Terminal interface for user interaction.

## 📦 Usage (Coming Soon)
```bash
sudo rose install <package-name>
sudo rose update
