# Tier 3: Experimental Sandbox

> **Rapid iteration and innovation**

---

## Status

**Current Count**: 0 experiments  
**Status**: Open for contributions  
**Requirements**: Lightweight PR review (technical clarity only)  

---

## Purpose

Tier 3 is a low-barrier space for:
- Testing new ideas and patterns
- Prototyping domain-specific applications
- Exploring alternative approaches
- Learning and experimentation

---

## Stability Guarantee

**NONE**. Tier 3 content:
- May change or disappear at any time
- Has no backward compatibility requirements
- Is not suitable for production use
- May have incomplete documentation

---

## Contribution Process

### Simple PR Workflow

1. **Create** your pattern/simulator/tool
2. **Add README** with:
   - What problem it solves
   - Basic usage example
   - Your contact info (GitHub handle)
3. **Open PR** to this repository
4. **Lightweight review**: We check for:
   - Clear explanation of purpose
   - No malicious code
   - Basic technical soundness
5. **Merge** (typically within 1 week)

### No RFC Required

You do NOT need to go through the RFC process for Tier 3.
This is intentional - we want low friction for experimentation.

---

## Structure

### /simulators/
Tools for simulating WEKAOU systems

Examples (hypothetical):
- `k-cycle-sim/` - Visual K-Cycle simulator
- `conflict-generator/` - Generate test conflicts
- `spoc-m-playground/` - Interactive SPOC-M editor

### Other directories as needed

Feel free to propose new categories!

---

## Promotion Path

If your Tier 3 experiment gains traction:

1. **Stabilize** it (6+ months without breaking changes)
2. **Get adoption** (2+ independent implementations)
3. **Submit RFC** to promote to Tier 2
4. **TSC review** and vote

---

## Cleanup Policy

Experiments with no activity for 12+ months may be:
- Archived (moved to `/archived/`)
- Removed (if no adoption whatsoever)

Maintainers will be notified 30 days before cleanup.

---

## Examples to Inspire You

_Once the first experiments land, we'll showcase them here._

---

## Get Started!

1. Read [CONTRIBUTING.md](../../CONTRIBUTING.md)
2. Check existing experiments for inspiration
3. Build something cool
4. Open a PR
5. Iterate based on community feedback

---

**Questions?** Ask in [wekaou-community](https://github.com/zaste/wekaou-community/discussions).
