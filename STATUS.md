# WEKAOU Specification Status

> **Current state and roadmap**

---

## Current Version

**Version**: 2.5.0-draft  
**Status**: DRAFT  
**Release Date**: [PENDING - Awaiting inaugural TSC approval]  
**Last Updated**: 2024-11-13  

---

## Status Definitions

### DRAFT
The specification is under active development. Content may change
significantly based on community feedback.

**Stability**: Low  
**Implementation**: Experimental only  
**RFC Process**: Informal (pre-governance structure)  

### CANDIDATE
The specification is feature-complete and stable. Only editorial
changes and critical fixes are accepted.

**Stability**: Medium  
**Implementation**: Early adopters encouraged  
**RFC Process**: Full RFC process in effect  

### STABLE
The specification is ratified and production-ready. Changes require
formal RFC approval and version bump.

**Stability**: High  
**Implementation**: Production use supported  
**RFC Process**: Mandatory for all changes  

### DEPRECATED
The specification version is being phased out. Migration path to
newer version is documented.

**Stability**: Frozen  
**Implementation**: Maintenance mode only  
**Support**: Until next MAJOR version + 2 years  

---

## Roadmap

### Phase 1: Foundation (Current)
**Target**: Q1 2025  
**Status**: DRAFT  

- [ ] Complete META-2.5 Core primitives
- [ ] Document SPOC-M schema (211 fields)
- [ ] Define CRL grammar formally
- [ ] Specify K-Cycle state machine
- [ ] Establish OOS validation framework

### Phase 2: Applied Layer
**Target**: Q2 2025  
**Status**: Not started  

- [ ] Tier-1 Core patterns (immutable)
- [ ] Tier-2 Stable frameworks (consensus-driven)
- [ ] Tier-3 Experimental sandbox
- [ ] Domain-specific profiles (via WG-Domains)

### Phase 3: Ecosystem
**Target**: Q3 2025  
**Status**: Not started  

- [ ] Compliance suite v1.0
- [ ] Reference implementation (K-OS CE)
- [ ] Certification program
- [ ] First conformant implementations

### Phase 4: Governance
**Target**: Q4 2025  
**Status**: Not started  

- [ ] Inaugural ACA assembly
- [ ] First TSC election
- [ ] Transition to STABLE status
- [ ] Formal RFC process activated

---

## Versioning Policy

WEKAOU follows semantic versioning: `MAJOR.MINOR.PATCH`

- **MAJOR**: Breaking changes (e.g., 2.x → 3.0)
- **MINOR**: New features, backward-compatible (e.g., 2.5 → 2.6)
- **PATCH**: Bug fixes, clarifications (e.g., 2.5.0 → 2.5.1)

See [CHARTER.md](https://github.com/zaste/wekaou-governance/blob/main/CHARTER.md#article-v-specification-versioning) for full policy.

---

## Change Log

### 2.5.0-draft (Current)
**Date**: 2024-11-13  
**Changes**:
- Initial specification structure
- Core primitives defined (SPOC-M, CRL, K-Cycle, OOS)
- Three-tier architecture established
- Governance framework linked

### Previous Versions
_No prior versions - inaugural specification._

---

## Stability Guarantees

### META-2.5 Core
**Stability**: IMMUTABLE (once STABLE)  
Changes require MAJOR version bump and extensive migration period.

### Tier-1 Core
**Stability**: HIGH  
Changes require RFC + TSC supermajority (2/3)

### Tier-2 Stable
**Stability**: MEDIUM  
Changes require RFC + TSC simple majority

### Tier-3 Experimental
**Stability**: LOW  
Rapid iteration, no backward compatibility guarantees

---

## Known Issues

### Critical
_None at this time_

### Major
1. SPOC-M schema incomplete (currently 150/211 fields documented)
2. CRL grammar lacks formal semantics
3. OOS validation rules need specification

### Minor
1. Missing examples for most patterns
2. Domain profiles not yet started
3. Compliance test cases undefined

---

## Contributing

While in DRAFT status, contributions are welcome via:

1. **Issues**: Report errors, ambiguities, missing content
2. **Discussions**: Ask questions, propose improvements
3. **Pull Requests**: For editorial fixes only (content changes require RFC)

Once governance is established, all changes must go through the
[RFC process](https://github.com/zaste/wekaou-rfc).

---

## Questions?

- **Technical**: [wekaou-community discussions](https://github.com/zaste/wekaou-community)
- **Governance**: [wekaou-governance](https://github.com/zaste/wekaou-governance)
- **RFCs**: [wekaou-rfc](https://github.com/zaste/wekaou-rfc)

---

**Last Status Update**: 2024-11-13  
**Next Review**: Upon first TSC meeting  
