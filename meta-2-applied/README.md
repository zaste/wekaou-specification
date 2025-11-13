# META-2 Applied

> **The Genome of Behaviors - Practical WEKAOU Applications**

---

## Overview

META-2 Applied contains domain-specific implementations, patterns,
and frameworks built on META-2.5 Core primitives.

**Three-Tier Architecture**:

### Tier 1: Core (Immutable)
Canonical patterns that have achieved consensus and are part of
the stable specification.

### Tier 2: Stable (Consensus-Driven)
Mature patterns undergoing community review. Changes require RFC.

### Tier 3: Experimental (Sandbox)
Rapid iteration space for new ideas. No stability guarantees.

---

## Structure

```
meta-2-applied/
├── tier-1-core/
│   ├── patterns/              # Canonical architectural patterns
│   └── domain-profiles/       # Mature domain-specific profiles
│
├── tier-2-stable/
│   └── frameworks/            # Community-validated frameworks
│
└── tier-3-experimental/
    └── simulators/            # Experimental tools and prototypes
```

---

## Tier Lifecycle

```
Experimental (T3)
    ↓ (Community validation + 6 months stability)
Stable (T2)
    ↓ (TSC approval + proven adoption)
Core (T1)
```

### Promotion Criteria

**T3 → T2**:
- At least 2 independent implementations
- 6 months without breaking changes
- Positive community feedback
- RFC approved by TSC (simple majority)

**T2 → T1**:
- Proven adoption in production
- At least 5 implementations
- 12 months stability
- RFC approved by TSC (supermajority 2/3)

### Demotion/Removal

**T2 → T3**: Significant issues discovered  
**T1 → Deprecated**: Only via MAJOR version change  
**T3 → Removed**: 12 months inactivity + no adoption  

---

## Contributing

### To Tier 3 (Experimental)
1. Open PR with your pattern/framework/simulator
2. Include README with motivation and examples
3. Lightweight review (technical clarity only)
4. Iterate rapidly based on usage

### To Tier 2/1
Must go through RFC process in [wekaou-rfc](https://github.com/zaste/wekaou-rfc).

---

## Current Contents

### Tier 1: Core
_Empty - pending inaugural TSC approval_

### Tier 2: Stable
_Empty - awaiting first promotions from T3_

### Tier 3: Experimental
_Empty - awaiting community contributions_

---

See individual tier directories for detailed guidelines.
