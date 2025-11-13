# WEKAOU Specification

> **📐 The Canonical Standard for Cognitive Governance Systems**

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Version](https://img.shields.io/badge/version-2.5.0--draft-orange.svg)](./VERSION)
[![Status](https://img.shields.io/badge/status-DRAFT-yellow.svg)](./STATUS.md)

The WEKAOU® standard defines an open, interoperable specification for **Cognitive Governance Systems** - frameworks that enable organizations to manage knowledge, decisions, and evolution through explicit, traceable, and composable structures.

---

## 🎯 What is WEKAOU?

WEKAOU provides:

1. **SPOC-M**: A knowledge representation format (Subject-Predicate-Object-Context-Mechanism)
2. **CRL**: Cognitive Representation Language for expressing governance logic
3. **K-Cycle**: A formal process model for organizational cognition
4. **OOS**: 12-dimensional ontological validation system
5. **Meta-Architecture**: Tiered specification structure (Core → Stable → Experimental)

**Use Cases**:
- Enterprise knowledge management
- Regulatory compliance tracking
- Organizational decision auditability
- AI governance frameworks
- Academic knowledge graphs

---

## 📚 Specification Structure

```
specification/
├── README.md                    # This file
├── LICENSE                      # CC BY-SA 4.0
├── VERSION                      # Current version (semver)
├── STATUS.md                    # Specification maturity status
│
├── /meta-2.5-core/             # Immutable Core (v2.5)
│   ├── 00_ontology/
│   │   ├── README.md
│   │   ├── spoc-m_schema.json   # 211-field SPOC-M definition
│   │   └── primitives.md        # Core ontological primitives
│   │
│   ├── 01_language/
│   │   ├── README.md
│   │   ├── crl_grammar.ebnf     # CRL formal grammar
│   │   └── crl_semantics.md     # Language semantics
│   │
│   └── 02_process/
│       ├── README.md
│       ├── k-cycle_spec.md      # K-Cycle formal definition
│       └── oos_validation.md    # OOS 12D validation rules
│
├── /meta-2-applied/            # Applied Specifications
│   ├── /tier-1-core/           # Stable, immutable
│   │   ├── patterns/           # Design patterns (VQF, MST, etc.)
│   │   └── domain-profiles/    # Certified domain extensions
│   │
│   ├── /tier-2-stable/         # Mature, consensus-governed
│   │   └── frameworks/         # Implementation frameworks
│   │
│   └── /tier-3-experimental/   # Sandbox for innovation
│       └── simulators/         # Experimental tools
│
└── /archives/                  # Historical versions
    ├── v2.0/
    ├── v2.1/
    └── ...
```

---

## 🚀 Quick Start

### For Implementers

1. **Read the Core**: Start with [meta-2.5-core/](./meta-2.5-core/README.md)
2. **Understand SPOC-M**: [00_ontology/spoc-m_schema.json](./meta-2.5-core/00_ontology/spoc-m_schema.json)
3. **Review K-Cycle**: [02_process/k-cycle_spec.md](./meta-2.5-core/02_process/k-cycle_spec.md)
4. **Check Compliance**: Use [wekaou-compliance-suite](https://github.com/zaste/wekaou-compliance-suite)

### For Contributors

**⚠️ CRITICAL**: You cannot submit PRs directly to this repository.

All specification changes MUST go through the **RFC process**:
1. Open a proposal in [wekaou-rfc](https://github.com/zaste/wekaou-rfc)
2. Use the SCP (Standard Change Proposal) template
3. Community discussion (minimum 14 days)
4. TSC vote
5. Only after approval can changes be merged here

See [CONTRIBUTING.md](https://github.com/zaste/wekaou-.github/blob/main/CONTRIBUTING.md) for details.

---

## 📖 Key Concepts

### SPOC-M (Subject-Predicate-Object-Context-Mechanism)

The fundamental unit of knowledge representation in WEKAOU:

```json
{
  \"subject\": \"AgencyX\",
  \"predicate\": \"requires\",
  \"object\": \"ComplianceFramework\",
  \"context\": {
    \"domain\": \"regulatory\",
    \"timestamp\": \"2025-01-15T10:00:00Z\",
    \"jurisdiction\": \"EU\"
  },
  \"mechanism\": \"K-Cycle.Audit\"
}
```

SPOC-M has 211 fields across 7 major categories. See [schema documentation](./meta-2.5-core/00_ontology/README.md).

### K-Cycle (Knowledge Cycle)

The operational model for organizational cognition with 6 phases:

1. **Perception** (P): Detect perturbations
2. **Audit** (A): Validate against ontology
3. **Orchestration** (O): Decide on responses
4. **Execution** (E): Implement changes
5. **Reconciliation** (R): Update state
6. **Reflection** (R): Learn and adapt

Two modes: **Audit** (reactive) and **Orchestration** (proactive).

### OOS (Ontological Operating System)

12-dimensional validation ensuring semantic coherence:

- **Identity**: Entity uniqueness
- **Localization**: Spatial/temporal placement
- **Relation**: Connection validity
- **Composition**: Part-whole integrity
- **Causation**: Cause-effect chains
- **Modality**: Possibility/necessity
- **Attribution**: Property assignment
- **Quantification**: Numerical constraints
- **Temporality**: Time-based evolution
- **Normativity**: Rule compliance
- **Intentionality**: Goal alignment
- **Emergence**: Higher-order properties

---

## 🔖 Versioning

WEKAOU follows **semantic versioning** (MAJOR.MINOR.PATCH):

- **MAJOR**: Breaking changes (v1 → v2)
- **MINOR**: New features, backward-compatible (v2.5 → v2.6)
- **PATCH**: Bug fixes, clarifications (v2.5.0 → v2.5.1)

**Current Version**: `2.5.0-draft` (pre-release, not production-ready)

**Stability Tiers**:
- **Core (META-2.5)**: Requires MAJOR version change
- **Tier 1**: Requires MINOR version change
- **Tier 2**: PATCH changes allowed
- **Tier 3**: No version constraints

See [VERSION](./VERSION) for current status.

---

## 📋 Specification Status

| Component | Status | Coverage | Notes |
|-----------|--------|----------|-------|
| SPOC-M Schema | DRAFT | 80% | 211 fields defined, validation pending |
| CRL Grammar | DRAFT | 60% | Core syntax complete, semantics partial |
| K-Cycle | DRAFT | 90% | Formal model complete, examples needed |
| OOS Validation | DRAFT | 70% | 12 dimensions defined, tooling in progress |
| Domain Profiles | PROPOSED | 10% | Healthcare, Finance, Software in RFC |

**Overall Status**: **DRAFT** (Pre-1.0)

See [STATUS.md](./STATUS.md) for detailed roadmap.

---

## 🛡️ Intellectual Property

### License

This specification is licensed under **[CC BY-SA 4.0](./LICENSE)** (Creative Commons Attribution-ShareAlike 4.0 International).

**You are free to**:
- Use commercially
- Adapt and extend
- Create implementations

**You must**:
- Attribute the WEKAOU standard
- Share derivative specifications under the same license
- Indicate if changes were made

### Trademark

\"WEKAOU®\" is a registered trademark of the Alliance for Coherent AI (ACA).

- ✅ **Allowed**: \"WEKAOU-compatible\" for conformant implementations
- ❌ **Not Allowed**: \"WEKAOU-certified\" without formal certification

See [Compliance Suite](https://github.com/zaste/wekaou-compliance-suite) for certification process.

---

## 🔗 Related Repositories

| Repository | Purpose |
|------------|---------|
| [wekaou-rfc](https://github.com/zaste/wekaou-rfc) | Proposal and governance process |
| [wekaou-governance](https://github.com/zaste/wekaou-governance) | ACA charter, TSC mandate, statutes |
| [wekaou-compliance-suite](https://github.com/zaste/wekaou-compliance-suite) | Validation tools and test cases |
| [wekaou-kos-community-edition](https://github.com/zaste/wekaou-kos-community-edition) | Reference implementation (educational) |
| [wekaou-community](https://github.com/zaste/wekaou-community) | Discussions and Q&A |
| [wekaou-awesome-wekaou](https://github.com/zaste/wekaou-awesome-wekaou) | Curated resources |

---

## 💬 Questions & Support

- **Understanding the Spec**: Read [meta-2.5-core/README.md](./meta-2.5-core/README.md)
- **Implementation Help**: [wekaou-community discussions](https://github.com/zaste/wekaou-community)
- **Report Issues**: [wekaou-rfc](https://github.com/zaste/wekaou-rfc) (not here!)
- **Propose Changes**: RFC process via [wekaou-rfc](https://github.com/zaste/wekaou-rfc)

---

## 🏛️ Governance

This specification is stewarded by the **Technical Steering Committee (TSC)** of the Alliance for Coherent AI (ACA).

- **TSC Mandate**: [wekaou-governance/tsc/mandate.md](https://github.com/zaste/wekaou-governance/blob/main/tsc/mandate.md)
- **Charter**: [wekaou-governance/CHARTER.md](https://github.com/zaste/wekaou-governance/blob/main/CHARTER.md)
- **RFC Process**: [wekaou-rfc/README.md](https://github.com/zaste/wekaou-rfc/blob/main/README.md)

All decisions are transparent, documented, and community-driven.

---

<div align=\"center\">

**The Standard for Cognitive Governance.**

[Read the Spec](./meta-2.5-core/README.md) • [Join Community](https://github.com/zaste/wekaou-community) • [Propose Changes](https://github.com/zaste/wekaou-rfc)

</div>
