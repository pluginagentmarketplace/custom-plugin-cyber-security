---
# ═══════════════════════════════════════════════════════════════════════════════
# COMMAND: EXPLORE CYBER SECURITY
# Version: 2.0.0 | Production-Grade
# ═══════════════════════════════════════════════════════════════════════════════

name: explore-cyber-security
description: Explore Cyber Security learning paths, resources, and skill assessments
allowed-tools: Read, Glob, Grep
version: "2.0.0"
last_updated: "2025-01-01"

# ─────────────────────────────────────────────────────────────────────────────
# COMMAND CONFIGURATION
# ─────────────────────────────────────────────────────────────────────────────
usage:
  syntax: "/explore-cyber-security [domain] [--option]"
  examples:
    - "/explore-cyber-security"
    - "/explore-cyber-security offensive"
    - "/explore-cyber-security defensive --roadmap"
    - "/explore-cyber-security compliance --assessment"

# ─────────────────────────────────────────────────────────────────────────────
# INPUT VALIDATION
# ─────────────────────────────────────────────────────────────────────────────
input:
  parameters:
    domain:
      type: "enum"
      values: ["offensive", "defensive", "forensics", "compliance", "cryptography", "all"]
      default: "all"
      required: false
    options:
      --roadmap: "Display learning roadmap"
      --assessment: "Run skill assessment"
      --resources: "List learning resources"
      --projects: "Show hands-on projects"
      --help: "Display command help"

  validation:
    - check: "domain in valid_domains"
      error: "E_INVALID_DOMAIN"
    - check: "option in valid_options"
      error: "E_INVALID_OPTION"

# ─────────────────────────────────────────────────────────────────────────────
# EXIT CODES
# ─────────────────────────────────────────────────────────────────────────────
exit_codes:
  0: "Success"
  1: "Invalid domain specified"
  2: "Invalid option"
  3: "Resource not found"
  4: "Internal error"

---

# /explore-cyber-security

> Explore Cyber Security learning paths, roadmaps, and resources.

## Usage

```bash
/explore-cyber-security [domain] [options]
```

## Parameters

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| domain | enum | all | Security domain to explore |
| --roadmap | flag | - | Display learning roadmap |
| --assessment | flag | - | Run skill assessment |
| --resources | flag | - | List learning resources |
| --projects | flag | - | Show hands-on projects |

## Available Domains

| Domain | Agent | Description |
|--------|-------|-------------|
| offensive | offensive-security-expert | Penetration testing, red team |
| defensive | defensive-security-expert | SOC, incident response |
| forensics | forensics-analyst | Digital forensics, malware analysis |
| compliance | compliance-specialist | GRC, frameworks |
| cryptography | cryptography-expert | Encryption, PKI |

## Examples

```bash
# Explore all domains
/explore-cyber-security

# View offensive security roadmap
/explore-cyber-security offensive --roadmap

# Run compliance skill assessment
/explore-cyber-security compliance --assessment

# List cryptography learning resources
/explore-cyber-security cryptography --resources

# View defensive security projects
/explore-cyber-security defensive --projects
```

## Learning Paths

### Beginner → Expert Progression

```
LEVEL 1: FOUNDATIONS
├── Security Fundamentals
├── Networking Basics
├── Linux/Windows Administration
└── Programming Basics

LEVEL 2: CORE SKILLS
├── Offensive: OWASP, Basic Pentesting
├── Defensive: SIEM, Log Analysis
├── Forensics: Evidence Handling
├── Compliance: ISO 27001 Basics
└── Crypto: Symmetric/Asymmetric

LEVEL 3: ADVANCED
├── Offensive: Exploit Dev, Red Team
├── Defensive: Threat Hunting, IR
├── Forensics: Memory/Malware Analysis
├── Compliance: Multi-Framework
└── Crypto: PKI, Protocol Analysis

LEVEL 4: EXPERT
├── Research & Development
├── Architecture & Strategy
├── Leadership & Mentoring
└── Industry Contribution
```

## Certifications by Domain

| Domain | Entry | Intermediate | Advanced |
|--------|-------|--------------|----------|
| Offensive | CEH, PenTest+ | OSCP | OSCE, OSEE |
| Defensive | Security+ | CySA+, GCIH | GCIA, GCFA |
| Forensics | CHFI | GCFE | GCFA, GNFA |
| Compliance | CISA | CISM | CISSP |
| Crypto | - | CCSP | Specialized |

## Troubleshooting

```
Command Error
    │
    ├─► E_INVALID_DOMAIN (exit: 1)
    │   └── Use: offensive, defensive, forensics, compliance, cryptography, all
    │
    ├─► E_INVALID_OPTION (exit: 2)
    │   └── Use: --roadmap, --assessment, --resources, --projects
    │
    └─► E_RESOURCE_NOT_FOUND (exit: 3)
        └── Check domain availability and file paths
```

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 2.0.0 | 2025-01-01 | Production-grade with validation |
| 1.0.0 | 2024-12-29 | Initial release |
