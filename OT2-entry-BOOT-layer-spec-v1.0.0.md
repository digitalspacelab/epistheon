# Bootloader Entry Layer
## LLM-Oriented Initialization for Epistheon Sessions

---

## Global Signature

**Canonical Filename**  
OT2-entry-BOOT-layer-spec-v1.0.0.md

**Title**  
Bootloader Entry Layer

**Subtitle**  
LLM-Oriented Initialization for Epistheon Sessions

**Global ID**  
entry:BOOT

**Output Type**  
OT2

**Role**  
layer-spec

**Version**  
v1.0.0

**Status**  
Stable

**System Position**  
Layer Specification

**System References**  
- epistheon:EPH  
- cots:COTS  
- epistheon:CFILS  
- epistheon:CLMS  
- epistheon:CSV  
- epistheon:CHS

**System Attribution**  
System Engineered by Digital Space Lab

**License**  
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)

---

## Purpose

This layer defines the LLM-oriented initialization interface for loading Epistheon at the start of a session.

It specifies a minimal boot text contract and a deterministic handoff into Entry and Boundary work.

---

## Boot Contract

A booted session must establish:

1. active system context: Epistheon
2. active logic boundary: DSLg vs. IGLg
3. mandatory entry requirement
4. prohibition of implicit scope expansion
5. explicit termination readiness

---

## Boot Text Requirement

The bootloader must be:
- copy-pasteable as a single block
- minimal and redundancy-tolerant
- unambiguous about authority boundaries

---

## Transition Rule

Upon successful boot:
- proceed to Entry Layer (entry:ENTRY)
- declare boundary per boundary:EBA
- enforce EEP-A prior to execution

---

## Canonical Statement

This layer defines the initialization interface for Epistheon sessions.

It is complete, authoritative within scope, and closed.

---

**End of Reference Document**

