# REPO‑MAP‑vE1.1  
Version: vE1.1  
Status: Active Canonical Document  
Maintained by: SCU Foundation  
Document Class: Repository Index (Group B)

This document defines the complete repository structure of the SCU ecosystem.  
It is the authoritative source of truth for:

- repository layout  
- required admin files  
- canonical folder structure  
- cross‑repo alignment  
- ecosystem‑wide file‑reference rules  
- global refactor operations  

This document is paired with the machine‑readable Global Reference Map:

- REPO: Repo‑Map — /GRM-vE1.1.json

All repositories MUST conform to this structure.

---

# 0. Repository List (Ecosystem Era vE1.x)

The SCU ecosystem contains the following repositories:

- **Architecture**  
- **Governance**  
- **Legal**  
- **Standards**  
- **Specifications**  
- **Repo‑Map** (this repository)

Future repositories (e.g., websites, whitepaper) are excluded from this map.

---

# 1. Required Root‑Level Admin Files (All Admin‑Grade Repos)

Every admin‑grade repository MUST contain the following files at root:

```
README.md
CHANGELOG.md
LICENSE
STATUS.md
VERSION
CODE_OF_CONDUCT.md
CONTRIBUTING.md
GOVERNANCE.md
STRUCTURE.md
```

These files define:

- governance  
- contribution rules  
- repository structure  
- licensing  
- versioning  
- behavioural expectations  

All admin‑grade repositories now contain the full required set.

---

# 2. Repository Maps  
(Each repository is listed with its current, correct status. All required files now **EXIST**.)

---

# 2.1 Architecture Repository

```
ARCHITECTURE/
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── STATUS.md
├── VERSION
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
└── STRUCTURE.md

access-layer/
domain-separation/
lattice-language/
lcsl/
lpl/
perceptual-safety/
trust-stack/
```

---

# 2.2 Governance Repository

```
GOVERNANCE/
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── STATUS.md
├── VERSION
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
└── STRUCTURE.md

global-rules/
│   ├── AO-vE1.1.md
│   ├── CCRM-vE1.1.md
│   ├── CDI-vE1.1.md
│   ├── CDR-vE1.1.md
│   ├── EAM-vE1.1.md
│   ├── GIC-vE1.1.md
│   ├── GR-vE1.1.md
│   ├── NTS-vE1.1.md
│   ├── SC-vE1.1.md
│   ├── SSO-vE1.1.md
│   ├── USC-vE1.1.md
│   └── VR-vE1.1.md
```

---

# 2.3 Legal Repository

```
LEGAL/
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── STATUS.md
├── VERSION
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
└── STRUCTURE.md

attribution.md
licensing.md
privacy-policy.md
safety-disclosure.md
security-disclosure.md
terms-of-use.md
```

---

# 2.4 Standards Repository

```
STANDARDS/
│
├── README.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── STRUCTURE.md
├── CHANGELOG.md
├── LICENSE
├── STATUS.md
└── VERSION

lp/
lw/
lm/
lit/
lcsl/
ts/
registry/
```

---

# 2.5 Specifications Repository

```
SPECIFICATIONS/
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── STATUS.md
├── VERSION
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
└── STRUCTURE.md

lp/
lw/
lm/
lit/
lcsl/
ts/
```

---

# 2.6 Repo‑Map Repository (This Repo)

```
REPO-MAP/
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── STATUS.md
├── VERSION
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── STRUCTURE.md
├── REPO-MAP-vE1.1.md
└── GRM-vE1.1.json
```

---

# 3. Canonical File‑Reference Format

All admin files MUST use:

```
REPO: <Repository Name> — <repo-relative path>
```

Examples:

- REPO: Governance — /global-rules/GIC-vE1.1.md  
- REPO: Standards — /lp/LP-v1.0.md  
- REPO: Specifications — /lw/LW-Spec-v1.0.md  
- REPO: Legal — /privacy-policy.md  
- REPO: Architecture — /lpl/lpl.md  
- REPO: Repo‑Map — /GRM-vE1.1.json  

This rule is mandatory across:

- admin files  
- canonical documents  
- architecture families  
- kernel layers  
- PSCS  
- routing trees  
- READMEs  
- governance files  

Normative standards/specs **do not** use repo‑scoped references.

---

# REPO‑MAP‑vE1.1 — COMPLETE
