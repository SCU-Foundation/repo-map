REPO‑MAP.md v1.2 — SCU Ecosystem Repository Architecture (Canonical Final State)
Version: v1.2
Status: Final
Steward: SCU Foundation
Purpose: Define the complete, authoritative repository structure for the SCU ecosystem.
Scope: Governance, Legal, Standards, Specifications, Architecture, Kernel, Publications, Websites.
# SCU Ecosystem — Canonical Repository Map
Version: v1.2  
Status: Final  
Steward: SCU Foundation

This document defines the complete, authoritative repository architecture for the SCU ecosystem.  
It is the single source of truth for all institutional, standards, architecture, specification, kernel, and publication repositories.

---

# 1. Institutional Layer

## 1.1 `governance`
**Purpose:** Governance canonicals, institutional rules, global charters.

### Root
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  
- architecture-model.md  
- change-management-charter.md  
- conceptual-frame.md  
- global-body-summary.md  
- governance-charter.md  
- institutional-structure.md  
- proposal-lifecycle.md  
- public-sector-alignment.md  
- safety-governance.md  
- standards-registry.md  
- transparency-charter.md  
- versioning-governance.md  

### /global-rules/
- AO-vE1.0.md  
- CCRM-vE1.0  
- CDI-vE1.0.md  
- CMC-vE1.0.md  
- EAM-vE1.0.md  
- GIC-vE1.0.md  
- GR-vE1.0.md  
- NTS-vE1.0.md  
- README.md  
- SC-vE1.0.md  
- SSO-vE1.0.md  
- USC-vE1.0.md  
- VR-vE1.0.md  

---

## 1.2 `legal`
**Purpose:** Legal surfaces, compliance, licensing, safety disclosures.

### Root
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  
- attribution.md  
- licensing.md  
- privacy-policy.md  
- safety-disclosure.md  
- security-disclosure.md  
- terms-of-use.md  
- compliance-overview.md (to be created)

---

# 2. Standards Layer

## 2.1 `standards`
**Purpose:** Normative standards (v1.0).

### Root
- CODE_OF_CONDUCT.md  
- CONTRIBUTING.md  
- GOVERNANCE.md  
- README.md  
- STRUCTURE.md  

### /lcsl/
- LCSL-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lit/
- LIT-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lm/
- LM-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lp/
- LP-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lw/
- LW-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /ts/
- TS-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /registry/ (to be created)
- registry.md  
- registry.json  
- metadata.json  
- checksums.txt  

---

# 3. Specifications Layer

## 3.1 `specifications`
**Purpose:** Technical specifications for all standards.

### Root
- README.md  

### /lcsl/
- LCSL-Spec-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lit/
- LIT-Spec-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lm/
- LM-Spec-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lp/
- LP-Spec-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /lw/
- LW-Spec-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /ts/
- TS-Spec-v1.0.md  
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

---

# 4. Architecture Layer

## 4.1 `architecture`
**Purpose:** Conceptual, explanatory, non‑normative architecture.  
**Includes full file lists for all domains.**

### Root
- README.md  

---

### /lcsl/
- lcsl.md  
- certification-model.md  
- safety-constraints.md  
- attestation-requirements.md  
- device-certification.md  
- runtime-certification.md  
- extension-certification.md  
- version-floors.md  
- update-sequencing.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

### /access-layer/
- access-layer.md  
- agents.md  
- attestation-flow.md  
- capability-surfaces.md  
- devices.md  
- extensions.md  
- runtime-environment.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

### /domain-separation/
- domain-separation.md  
- dse.md  
- dtk.md  
- ste.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

### /lattice-language/
- lattice-language.md  
- meta-semantic-layer.md  
- semanitc-extensions.md  
- semantic-web.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

### /lpl/
- attestation-integration.md  
- event-types.md  
- ledger-structure.md  
- lpl.md  
- privacy-and-boundaries.md  
- provenance-model.md  
- reversibility.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

### /perceptual-safety/
- dem.md  
- perceptual-safety.md  
- rwil.md  
- rwim.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

### /trust-stack/
- attestation.md  
- extension-negotiation.md  
- extensions.md  
- gatekeeper.md  
- keymaster.md  
- lcsl.md  
- lit.md  
- lpl.md  
- memory-integrity.md  
- non-user-privacy.md  
- trust-stack.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

# 5. Kernel Layer

## 5.1 `kernel`
(To be created — no current repo)

**Purpose:** Behavioural, systemic, and substrate‑level invariants.

### Proposed structure:
- behavioural-kernel.md  
- systemic-integration-kernel.md  
- trust-stack-kernel-interface.md  
- invariants.md  
- README.md  
- STATUS.md  
- CHANGELOG.md  
- VERSION  
- LICENSE  

---

# 6. Publications Layer

## 6.1 `whitepaper`
**Purpose:** SCU Whitepaper editions and publication surfaces.

### Root
- CHANGELOG.md  
- LICENSE  
- README.md  
- STATUS.md  
- VERSION  

### /v1.7/
- README.md  
- metadata.json  
- release-notes.md  
- SCU-Whitepaper-v1.7.pdf  

### /v1.8/
- README.md  
- metadata.json  
- release-notes.md  
- SCU-Whitepaper-v1.8.pdf  
- /html/
  - index.html  
  - css/  
  - images/  
  - front-matter/  
  - chapters/  
  - appendices/  
  - supplementary/  

---

# 7. Websites Layer

## 7.1 `scu.foundation`
- README.md  

## 7.2 `latticeprotocol.org`
(To be populated)

## 7.3 `lattice.institute`
(To be populated)

## 7.4 `p-sc.cc`
(To be populated)

---

# END OF DOCUMENT
