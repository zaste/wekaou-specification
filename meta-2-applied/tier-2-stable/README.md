# Tier 2: Stable Frameworks

> **Mature patterns under community governance**

---

## Status

**Current Count**: 0 frameworks  
**Status**: Awaiting first promotions from Tier 3  
**Requirements**: TSC approval (simple majority)  

---

## Inclusion Criteria

1. **Community Validation**
   - At least 2 independent implementations
   - Positive feedback from early adopters
   - Active usage/discussion in community

2. **Stability**
   - 6+ months in Tier 3 without breaking changes
   - No critical issues outstanding
   - Semantic versioning adopted

3. **Documentation**
   - Complete specification document
   - Usage examples and tutorials
   - Migration guide (if applicable)

4. **Governance**
   - RFC approved by TSC (simple majority)
   - Designated maintainer(s)
   - Clear contribution guidelines

---

## Change Process

All changes to Tier 2 content require:
1. RFC submission to wekaou-rfc
2. Community discussion (minimum 14 days)
3. TSC approval (simple majority)
4. Version bump (semantic versioning)

---

## Structure

### /frameworks/
End-to-end frameworks for specific use cases

Examples (hypothetical):
- `decision-support/` - Clinical decision support framework
- `audit-trail/` - Immutable audit logging
- `distributed-kg/` - Distributed knowledge graph

---

## Proposing a Framework

1. Develop and prove framework in Tier 3
2. Demonstrate stability (6+ months, 2+ implementations)
3. Submit RFC with:
   - Full specification
   - Implementation examples
   - Community feedback summary
4. TSC review and vote
5. Upon approval, framework moves to Tier 2

---

## Demotion to Tier 3

A framework may be demoted if:
- Critical security/correctness issues discovered
- No implementations remain active
- Community consensus for major redesign

---

**Next Review**: Upon first TSC formation
