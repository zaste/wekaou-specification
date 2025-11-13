# Tier 1: Core Patterns

> **Canonical, immutable patterns with proven adoption**

---

## Status

**Current Count**: 0 patterns  
**Status**: Awaiting first promotions from Tier 2  
**Requirements**: TSC approval (2/3 supermajority)  

---

## Inclusion Criteria

1. **Proven Adoption**
   - At least 5 independent implementations
   - Production use in at least 3 organizations
   - Documented case studies

2. **Stability**
   - 12+ months in Tier 2 without breaking changes
   - No major issues reported
   - Clear deprecation path if needed

3. **Community Support**
   - RFC approved by TSC (2/3 supermajority)
   - Positive feedback from implementers
   - Active maintenance commitment

4. **Technical Quality**
   - Complete documentation
   - Comprehensive test suite
   - Reference implementation available

---

## Structure

### /patterns/
Architectural patterns (e.g., Event Sourcing for K-OS)

### /domain-profiles/
Domain-specific WEKAOU applications (e.g., Healthcare Profile)

---

## Immutability Guarantee

Once a pattern enters Tier 1:
- Breaking changes require MAJOR version bump
- Deprecation requires 2+ year migration period
- Removal only via community consensus + RFC

---

## Proposing a Pattern

1. Mature pattern in Tier 2 for 12+ months
2. Gather evidence of adoption (implementations, case studies)
3. Submit RFC to wekaou-rfc with:
   - Full specification
   - Adoption metrics
   - Migration plan (if applicable)
4. TSC review and vote (2/3 required)
5. Upon approval, pattern moves to Tier 1

---

**Next Review**: Upon first TSC formation
