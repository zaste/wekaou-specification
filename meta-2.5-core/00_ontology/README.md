# SPOC-M: Subject-Predicate-Object-Context-Mechanism

> **The 211-field knowledge representation schema**

---

## Overview

SPOC-M is WEKAOU's core knowledge representation format. It extends
the classic RDF triple (Subject-Predicate-Object) with:

- **Context**: Where/when the knowledge applies
- **Mechanism**: How the knowledge was derived

---

## Current Status

**Version**: 2.5 (DRAFT)  
**Fields Documented**: 150/211  
**Schema File**: `spoc-m_schema.json` (coming soon)  

---

## Core Structure

```json
{
  "subject": {},
  "predicate": {},
  "object": {},
  "context": {},
  "mechanism": {}
}
```

See `spoc-m_schema.json` for complete 211-field specification.

---

## Evolution

- **v1.0**: Basic S-P-O (RDF-like)
- **v2.0**: Added Context (S-P-O-C)
- **v2.5**: Added Mechanism (SPOC-M) + expanded to 211 fields

---

## Examples

See `/examples/` directory for complete SPOC-M instances.
