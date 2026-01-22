# Epistheon OS
## Canonical File, Identity & Loading System (CFILS)

---

## Global Signature

**Canonical Filename**  
OT0-epistheon-CFILS-root-spec-v1.0.0.md


**Title**  
Epistheon OS

**Subtitle**  
Canonical File, Identity & Loading System (CFILS)

**Global ID**  
epistheon:CFILS

**Output Type**  
OT0

**Role**  
root-spec

**Version**  
v1.0.0

**Status**  
Canonical · Binding · Closed

**System Position**  
Epistemic Operating System Infrastructure Specification

**System References**  
- epistheon:EPH  
- cots:COTS

**Author**  
Harald Meier

**Contact**  
harald@digitalspacelab.com

**License**  
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)

---

## Purpose

This document defines the **canonical file system, identity scheme, loading mechanism, and governance rules** required to operate Epistheon as an epistemic operating system.

Its purpose is to ensure that all artifacts within the system are structurally addressable, machine-loadable, version-stable, authority-bounded, and resistant to semantic drift.

This specification does not define epistemic content. It defines how epistemic artifacts exist, relate, and load.

---

## Scope

This specification applies to all artifacts produced within the Epistheon system, including foundational specifications, reference architectures, layer specifications, protocols, executable illustrations, and derivative texts.

No artifact within the system is exempt.

---

## Core Principle

Structure precedes content.  
Identity precedes interpretation.  
Loading precedes execution.

No epistemic work is legitimate without a structurally valid artifact context.

---

## I. Canonical Output Types

The system adopts the Canonical Output Type System (COTS). Each artifact belongs to exactly one output type.

| Code | Output Type |
|---|---|
| OT0 | Foundational Specification |
| OT1 | Reference Architecture |
| OT2 | Layer / Model Specification |
| OT3 | Protocol Specification |
| OT4 | Executable Illustration |
| OT5 | Exploratory / Derivative Text |

The set of output types is closed.

---

## II. Canonical File Naming Scheme

All artifacts are named according to the following mandatory schema:

```
[OT]-[NS]-[MID]-[ROLE]-v[MAJOR].[MINOR].[PATCH].[EXT]
```

The filename carries formal information only. No stylistic, thematic, or promotional language is permitted.

---

## III. Namespaces (NS)

Namespaces define systemic domains.

Canonical namespace rules:
- lowercase
- kebab-case
- no synonyms
- no branding
- no metaphors

Initial canonical namespaces:
- epistheon
- cots
- boundary
- mea
- entry
- eel

---

## IV. Module ID (MID)

The Module ID defines the global, stable identity of an artifact.

Rules:
- uppercase
- 3–10 characters
- immutable across all versions
- independent of title or wording

The Module ID is the primary identity anchor of the artifact.

---

## V. Role Tokens (ROLE)

Roles define the formal function of an artifact.

Canonical role set:
- root-spec
- ref-arch
- layer-spec
- protocol
- bootloader
- illustration
- derivative

The role set is closed.

---

## VI. Versioning

Versioning follows semantic discipline:
- MAJOR: change of authority, scope, or meaning
- MINOR: structural or formal change
- PATCH: editorial change only

Version v1.0.0 denotes first canonical stabilization.

---

## VII. Global Artifact Signature

All artifacts of OT0–OT3 must include a global signature in the document header containing title, Global ID, output type, role, version, status, system position, references, author, contact, and license.

The Global ID (NS:MID) is invariant.

---

## VIII. Boot Mechanism

The system defines exactly one stable boot entry:

```
BOOTLOADER.txt
```

This file must never be renamed. It either contains the active bootloader text or points to a versioned bootloader artifact.

---

## IX. Manifest / Init System

System loading order is defined by a single canonical file:

```
MANIFEST.yaml
```

The manifest defines the boot target, kernel set, architecture, layer and protocol load order, and canonical release bundles. It is the single source of truth for system initialization.

---

## X. Repository Structure

```
/
├─ BOOTLOADER.txt
├─ MANIFEST.yaml
├─ core/
├─ layers/
├─ protocols/
├─ workbench/
└─ derivatives/
```

---

## XI. Release Bundles

Canonical releases consist of OT0–OT3 only. Each release is versioned, frozen, and reproducible. Exploratory and illustrative artifacts are excluded.

---

## XII. Governance Rules

1. Module IDs are immutable.  
2. Global IDs are immutable.  
3. Output Types 0 and 1 are finite.  
4. Lower output types may reference higher ones, never the reverse.  
5. MANIFEST.yaml defines canonical load order.  
6. BOOTLOADER.txt is the only stable entry point.  
7. Derived formats are never authoritative.

Violation of these rules invalidates system coherence.

---

## Canonical Statement

This specification defines the canonical file system, identity model, and loading discipline required to operate Epistheon as an epistemic operating system.

It is complete and closed.

---

**End of Reference Document**

