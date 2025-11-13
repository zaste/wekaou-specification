# CRL: Coherent Representation Language

> **The formal grammar for expressing WEKAOU knowledge**

---

## Overview

CRL is a domain-specific language for:
- Expressing SPOC-M instances in human-readable form
- Querying knowledge bases
- Defining transformation rules

---

## Current Status

**Version**: 2.5 (DRAFT)  
**Grammar**: EBNF formal definition in progress  
**Parser**: Reference implementation pending  

---

## Example Syntax

```crl
// Basic triple
[Project:WEKAOU] has_status [Status:DRAFT]

// With context
[Project:WEKAOU] has_status [Status:DRAFT]
  @context {
    temporal: 2024-11-13,
    source: "governance-repo"
  }

// With mechanism
[User:Antonio] created [Project:WEKAOU]
  @mechanism {
    derivation: "git-commit-analysis",
    confidence: 0.95
  }
```

---

## Grammar Files

- `crl_grammar.ebnf`: Formal EBNF specification
- `crl_examples.md`: Comprehensive examples
- `crl_semantics.md`: Formal semantics (pending)

---

## Integration

CRL compiles to SPOC-M JSON for storage and processing.
