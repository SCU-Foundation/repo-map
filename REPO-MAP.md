# REPO‑MAP
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

Each repository is listed with its **current, correct status**.  
All required files now **EXIST**.

---

# 2.1 Architecture Repository

```
ARCHITECTURE/
│
├── README.md                         [EXISTS]
├── CHANGELOG.md                      [EXISTS]
├── LICENSE                           [EXISTS]
├── STATUS.md                         [EXISTS]
├── VERSION                           [EXISTS]
├── CODE_OF_CONDUCT.md                [EXISTS]
├── CONTRIBUTING.md                   [EXISTS]
├── GOVERNANCE.md                     [EXISTS]
└── STRUCTURE.md                      [EXISTS]

access-layer/                         [EXISTS]
domain-separation/                    [EXISTS]
lattice-language/                     [EXISTS]
lcsl/                                 [EXISTS]
lpl/                                  [EXISTS]
perceptual-safety/                    [EXISTS]
trust-stack/                          [EXISTS]
```

---

# 2.2 Governance Repository

```
GOVERNANCE/
│
├── README.md                         [EXISTS]
├── CHANGELOG.md                      [EXISTS]
├── LICENSE                           [EXISTS]
├── STATUS.md                         [EXISTS]
├── VERSION                           [EXISTS]
├── CODE_OF_CONDUCT.md                [EXISTS]
├── CONTRIBUTING.md                   [EXISTS]
├── GOVERNANCE.md                     [EXISTS]
└── STRUCTURE.md                      [EXISTS]

global-rules/
│   ├── AO-vE1.1.md                   [EXISTS]
│   ├── CCRM-vE1.1.md                 [EXISTS]
│   ├── CDI-vE1.1.md                  [EXISTS]
│   ├── CDR-vE1.1.md                  [EXISTS]
│   ├── EAM-vE1.1.md                  [EXISTS]
│   ├── GIC-vE1.1.md                  [EXISTS]
│   ├── GR-vE1.1.md                   [EXISTS]
│   ├── NTS-vE1.1.md                  [EXISTS]
│   ├── SC-vE1.1.md                   [EXISTS]
│   ├── SSO-vE1.1.md                  [EXISTS]
│   ├── USC-vE1.1.md                  [EXISTS]
│   └── VR-vE1.1.md                   [EXISTS]
```

---

# 2.3 Legal Repository

```
LEGAL/
│
├── README.md                         [EXISTS]
├── CHANGELOG.md                      [EXISTS]
├── LICENSE                           [EXISTS]
├── STATUS.md                         [EXISTS]
├── VERSION                           [EXISTS]
├── CODE_OF_CONDUCT.md                [EXISTS]
├── CONTRIBUTING.md                   [EXISTS]
├── GOVERNANCE.md                     [EXISTS]
└── STRUCTURE.md                      [EXISTS]

attribution.md                        [EXISTS]
licensing.md                          [EXISTS]
privacy-policy.md                     [EXISTS]
safety-disclosure.md                  [EXISTS]
security-disclosure.md                [EXISTS]
terms-of-use.md                       [EXISTS]
```

---

# 2.4 Standards Repository

```
STANDARDS/
│
├── README.md                         [EXISTS]
├── CODE_OF_CONDUCT.md                [EXISTS]
├── CONTRIBUTING.md                   [EXISTS]
├── GOVERNANCE.md                     [EXISTS]
├── STRUCTURE.md                      [EXISTS]
├── CHANGELOG.md                      [EXISTS]
├── LICENSE                           [EXISTS]
├── STATUS.md                         [EXISTS]
└── VERSION                           [EXISTS]

lp/                                   [EXISTS]
lw/                                   [EXISTS]
lm/                                   [EXISTS]
lit/                                  [EXISTS]
lcsl/                                 [EXISTS]
ts/                                   [EXISTS]
registry/                             [EXISTS]
```

---

# 2.5 Specifications Repository

```
SPECIFICATIONS/
│
├── README.md                         [EXISTS]
├── CHANGELOG.md                      [EXISTS]
├── LICENSE                           [EXISTS]
├── STATUS.md                         [EXISTS]
├── VERSION                           [EXISTS]
├── CODE_OF_CONDUCT.md                [EXISTS]
├── CONTRIBUTING.md                   [EXISTS]
├── GOVERNANCE.md                     [EXISTS]
└── STRUCTURE.md                      [EXISTS]

lp/                                   [EXISTS]
lw/                                   [EXISTS]
lm/                                   [EXISTS]
lit/                                  [EXISTS]
lcsl/                                 [EXISTS]
ts/                                   [EXISTS]
```

---

# 2.6 Repo‑Map Repository (This Repo)

```
REPO-MAP/
│
├── README.md                         [EXISTS]
├── CHANGELOG.md                      [EXISTS]
├── LICENSE                           [EXISTS]
├── STATUS.md                         [EXISTS]
├── VERSION                           [EXISTS]
├── CODE_OF_CONDUCT.md                [EXISTS]
├── CONTRIBUTING.md                   [EXISTS]
├── GOVERNANCE.md                     [EXISTS]
├── STRUCTURE.md                      [EXISTS]
└── REPO-MAP.md                       [EXISTS]
```

---

# 3. Canonical File‑Reference Format

All admin files MUST use:

```
REPO: <Repository Name> — <repo‑relative path>
```

Examples:

```
REPO: Governance — /global-rules/GIC-vE1.1.md
REPO: Standards — /lp/LP-v1.0.md
REPO: Specifications — /lw/LW-Spec-v1.0.md
REPO: Legal — /privacy-policy.md
```

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

# REPO‑MAP vE1.1 — COMPLETE
