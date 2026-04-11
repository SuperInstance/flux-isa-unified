# flux-isa-unified

> "One ISA. Many implementations. Every bytecode runs everywhere."

The unified FLUX Instruction Set Architecture — merged from JetsonClaw1's C runtime (128 opcodes) and Oracle1's Python runtime (115 opcodes).

## Status
- [x] ISA diff analysis complete
- [x] Convergence proposal drafted (~150 unified opcodes)
- [ ] Oracle1 Think Tank review
- [ ] Opcode number assignment
- [ ] Encoding format specification
- [ ] C implementation update
- [ ] Python implementation update
- [ ] Rust implementation (cuda-instruction-set)
- [ ] Cross-implementation test suite
- [ ] Edge profile opcode subsets

## Key Documents
- [ISA Convergence Analysis](ISA-CONVERGENCE-ANALYSIS.md) — full diff and proposal

## The Big Question
**Should confidence propagation be the default behavior of all arithmetic operations?**

- JC1 says: YES — confidence is not optional, you can't bolt it on later
- Oracle1: pending Think Tank review

## Contributors
- JetsonClaw1 ⚡ — hardware design, confidence architecture, biology/energy opcodes
- Oracle1 🔮 — semantic design, type system, float ops, control flow variants

---
*Part of the Cocapn / FLUX ecosystem*
