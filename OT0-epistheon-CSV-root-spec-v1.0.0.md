# Epistheon
## Canonical System Vocabulary (CSV)

---

## Global Signature

**Canonical Filename**  
OT0-epistheon-CSV-root-spec-v1.0.0.md

**Title**  
Epistheon

**Subtitle**  
Canonical System Vocabulary (CSV)

**Global ID**  
epistheon:CSV

**Output Type**  
OT0

**Role**  
root-spec

**Version**  
v1.0.0

**Status**  
Canonical · Binding · Closed

**System Position**  
Epistemic Operating System — Vocabulary Authority Specification

**System References**  
- epistheon:EPH  
- epistheon:CFILS  
- epistheon:CLMS  
- cots:COTS

**Author**  
Harald Meier

**Contact**  
harald@digitalspacelab.com

**License**  
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)

---

## Purpose

This document defines the **exclusive, binding vocabulary** permitted within the Epistheon system.

Its purpose is to prevent semantic drift, synonym inflation, and authority ambiguity by fixing a closed set of canonical tokens.

This document does not explain concepts. It defines **allowed words and their formal roles**.

---

## Scope

The Canonical System Vocabulary applies to all artifacts across all output types and logic modes.

No term outside this vocabulary may be used in authoritative contexts.

---

## Core Principle

**One token — one function.**  
**No synonyms. No substitutions. No metaphors.**

---

## I. Vocabulary Classes

All canonical tokens belong to exactly one vocabulary class:

1. Namespace Tokens (NS)
2. Role Tokens (ROLE)
3. Status Tokens (STATUS)
4. System Position Tokens (SP)
5. Authority Tokens (AUTH)
6. Logic Mode Tokens (LM)

Vocabulary classes are closed.

---

## II. Namespace Tokens (NS)

Permitted namespace tokens:

- `epistheon`
- `cots`
- `boundary`
- `mea`
- `entry`
- `eel`

Rules:
- lowercase
- kebab-case
- no semantic overloading

---

## III. Role Tokens (ROLE)

Permitted role tokens:

- `root-spec`
- `ref-arch`
- `layer-spec`
- `protocol`
- `bootloader`
- `illustration`
- `derivative`

Rules:
- roles define formal function only
- roles carry no descriptive semantics

---

## IV. Status Tokens (STATUS)

Permitted status tokens:

- `Canonical`
- `Stable`
- `Draft`
- `Deprecated`
- `Experimental`

Rules:
- exactly one status per artifact
- status does not affect output type

---

## V. System Position Tokens (SP)

Permitted system position tokens:

- `Epistemic Root Specification`
- `Epistemic Operating System Infrastructure Specification`
- `Vocabulary Authority Specification`
- `Logic Mode Boundary Specification`
- `Reference Architecture Specification`
- `Layer Specification`
- `Protocol Specification`
- `Executable Illustration`
- `Derivative Text`

Rules:
- system position declares scope, not authority
- wording is fixed and non-variable

---

## VI. Authority Tokens (AUTH)

Permitted authority tokens:

- `invariant`
- `binding`
- `non-binding`
- `local`
- `none`

Rules:
- authority tokens may not be inferred
- authority must be explicitly declared

---

## VII. Logic Mode Tokens (LM)

Permitted logic mode tokens:

- `DSLg` — Deterministic System Logic
- `IGLg` — Interpretive Guidance Logic

Rules:
- every artifact operates primarily in exactly one logic mode
- logic mode does not override output type

---

## VIII. Prohibited Practices

The following are explicitly prohibited:

- synonym substitution for canonical tokens
- metaphorical use of authority tokens
- redefining tokens outside this document
- introducing hybrid or compound tokens

---

## IX. Extension Rule

Any extension of the canonical vocabulary requires:

- a new version of this document
- explicit change of MAJOR or MINOR version
- full backward compatibility analysis

---

## Canonical Statement

This document defines the exclusive and binding vocabulary of the Epistheon system.

It is complete, authoritative, and closed.

---

**End of Reference Document**

