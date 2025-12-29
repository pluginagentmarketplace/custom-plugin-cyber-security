<div align="center">

<!-- Animated Typing Banner -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Cyber+Security+Assistant;5+Agents+%7C+5+Skills;Claude+Code+Plugin" alt="Cyber Security Assistant" />

<br/>

<!-- Badge Row 1: Status Badges -->
[![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)](https://github.com/pluginagentmarketplace/custom-plugin-cyber-security/releases)
[![License](https://img.shields.io/badge/License-Custom-yellow?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Production-brightgreen?style=for-the-badge)](#)
[![SASMP](https://img.shields.io/badge/SASMP-v1.3.0-blueviolet?style=for-the-badge)](#)

<!-- Badge Row 2: Content Badges -->
[![Agents](https://img.shields.io/badge/Agents-5-orange?style=flat-square&logo=robot)](#-agents)
[![Skills](https://img.shields.io/badge/Skills-5-purple?style=flat-square&logo=lightning)](#-skills)
[![Commands](https://img.shields.io/badge/Commands-0-green?style=flat-square&logo=terminal)](#-commands)

<br/>

<!-- Quick CTA Row -->
[📦 **Install Now**](#-quick-start) · [🤖 **Explore Agents**](#-agents) · [📖 **Documentation**](#-documentation) · [⭐ **Star this repo**](https://github.com/pluginagentmarketplace/custom-plugin-cyber-security)

---

### What is this?

> **Cyber Security Assistant** is a Claude Code plugin with **5 agents** and **5 skills** for cyber security development.

</div>

---

## 📑 Table of Contents

<details>
<summary>Click to expand</summary>

- [Quick Start](#-quick-start)
- [Features](#-features)
- [Agents](#-agents)
- [Skills](#-skills)
- [Commands](#-commands)
- [Documentation](#-documentation)
- [Contributing](#-contributing)
- [License](#-license)

</details>

---

## 🚀 Quick Start

### Prerequisites

- Claude Code CLI v2.0.27+
- Active Claude subscription

### Installation (Choose One)

<details open>
<summary><strong>Option 1: From Marketplace (Recommended)</strong></summary>

```bash
# Step 1️⃣ Add the marketplace
/plugin add marketplace pluginagentmarketplace/custom-plugin-cyber-security

# Step 2️⃣ Install the plugin
/plugin install cyber-security-assistant@pluginagentmarketplace-cyber-security

# Step 3️⃣ Restart Claude Code
# Close and reopen your terminal/IDE
```

</details>

<details>
<summary><strong>Option 2: Local Installation</strong></summary>

```bash
# Clone the repository
git clone https://github.com/pluginagentmarketplace/custom-plugin-cyber-security.git
cd custom-plugin-cyber-security

# Load locally
/plugin load .

# Restart Claude Code
```

</details>

### ✅ Verify Installation

After restart, you should see these agents:

```
cyber-security-assistant:05-cryptography-expert
cyber-security-assistant:03-forensics-analyst
cyber-security-assistant:02-defensive-security
cyber-security-assistant:04-compliance-specialist
cyber-security-assistant:01-offensive-security
```

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🤖 **5 Agents** | Specialized AI agents for cyber security tasks |
| 🛠️ **5 Skills** | Reusable capabilities with Golden Format |
| ⌨️ **0 Commands** | Quick slash commands |
| 🔄 **SASMP v1.3.0** | Full protocol compliance |

---

## 🤖 Agents

### 5 Specialized Agents

| # | Agent | Purpose |
|---|-------|---------|
| 1 | **05-cryptography-expert** | Expert in cryptographic algorithms, protocols, and implement |
| 2 | **03-forensics-analyst** | Expert in digital forensics, malware analysis, and evidence  |
| 3 | **02-defensive-security** | Expert in SOC operations, incident response, threat detectio |
| 4 | **04-compliance-specialist** | Expert in security compliance, governance, and regulatory fr |
| 5 | **01-offensive-security** | Expert in penetration testing, ethical hacking, vulnerabilit |

---

## 🛠️ Skills

### Available Skills

| Skill | Description | Invoke |
|-------|-------------|--------|
| `defensive` | SOC operations, incident response, and threat detection | `Skill("cyber-security-assistant:defensive")` |
| `cryptography` | Cryptographic algorithms, protocols, and implementations | `Skill("cyber-security-assistant:cryptography")` |
| `compliance` | Security compliance frameworks and governance | `Skill("cyber-security-assistant:compliance")` |
| `forensics` | Digital forensics and malware analysis | `Skill("cyber-security-assistant:forensics")` |
| `offensive` | Penetration testing, ethical hacking, and vulnerability asse | `Skill("cyber-security-assistant:offensive")` |

---

## ⌨️ Commands

| Command | Description |
|---------|-------------|

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [CHANGELOG.md](CHANGELOG.md) | Version history |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to contribute |
| [LICENSE](LICENSE) | License information |

---

## 📁 Project Structure

<details>
<summary>Click to expand</summary>

```
custom-plugin-cyber-security/
├── 📁 .claude-plugin/
│   ├── plugin.json
│   └── marketplace.json
├── 📁 agents/              # 5 agents
├── 📁 skills/              # 5 skills (Golden Format)
├── 📁 commands/            # 0 commands
├── 📁 hooks/
├── 📄 README.md
├── 📄 CHANGELOG.md
└── 📄 LICENSE
```

</details>

---

## 📅 Metadata

| Field | Value |
|-------|-------|
| **Version** | 1.0.0 |
| **Last Updated** | 2025-12-29 |
| **Status** | Production Ready |
| **SASMP** | v1.3.0 |
| **Agents** | 5 |
| **Skills** | 5 |
| **Commands** | 0 |

---

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md).

1. Fork the repository
2. Create your feature branch
3. Follow the Golden Format for new skills
4. Submit a pull request

---

## ⚠️ Security

> **Important:** This repository contains third-party code and dependencies.
>
> - ✅ Always review code before using in production
> - ✅ Check dependencies for known vulnerabilities
> - ✅ Follow security best practices
> - ✅ Report security issues privately via [Issues](../../issues)

---

## 📝 License

Copyright © 2025 **Dr. Umit Kacar** & **Muhsin Elcicek**

Custom License - See [LICENSE](LICENSE) for details.

---

## 👥 Contributors

<table>
<tr>
<td align="center">
<strong>Dr. Umit Kacar</strong><br/>
Senior AI Researcher & Engineer
</td>
<td align="center">
<strong>Muhsin Elcicek</strong><br/>
Senior Software Architect
</td>
</tr>
</table>

---

<div align="center">

**Made with ❤️ for the Claude Code Community**

[![GitHub](https://img.shields.io/badge/GitHub-pluginagentmarketplace-black?style=for-the-badge&logo=github)](https://github.com/pluginagentmarketplace)

</div>
