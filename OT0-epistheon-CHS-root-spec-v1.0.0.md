# Epistheon
## Canonical Header Specifications (CHS)

---

## Global Signature

**Canonical Filename**  
OT0-epistheon-CHS-root-spec-v1.0.0.md

**Title**  
Epistheon

**Subtitle**  
Canonical Header Specifications (CHS)

**Global ID**  
epistheon:CHS

**Output Type**  
OT0

**Role**  
root-spec

**Version**  
v1.0.0

**Status**  
Canonical · Binding · Closed

**System Position**  
Epistemic Operating System — Header Authority Specification

**System References**  
- epistheon:EPH  
- epistheon:CFILS  
- epistheon:CLMS  
- epistheon:CSV  
- cots:COTS

**System Attribution**  
System Engineered by Digital Space Lab

**License**  
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)

---

## Purpose

This document defines the **canonical header formats** for all publication and artifact types within the Epistheon system.

Its purpose is to ensure:
- structural uniformity
- unambiguous authority signaling
- machine-readable metadata
- separation of system attribution and personal authorship

No artifact may deviate from its prescribed header format.

---

## Core Principle

**Header structure encodes epistemic authority.**

Header variation is permitted only where explicitly defined by output type.

---

## I. Header Classes

Headers are specified per **Output Type (OT)**.

The following header classes are defined:

- H0 — Foundational / Root Specification (OT0)
- H1 — Reference Architecture (OT1)
- H2 — Layer / Model Specification (OT2)
- H3 — Protocol Specification (OT3)
- H4 — Executable Illustration (OT4)
- H5 — Exploratory / Derivative Text (OT5)

Header classes are closed.

---

## II. H0 — Foundational / Root Specification Header

Applicable to: **OT0**

```text
Title
<document title>

Subtitle
<document subtitle>

Canonical Filename
<CFILS-conform filename>

Global ID
<namespace>:<module-id>

Output Type
OT0

Role
root-spec

Version
vX.Y.Z

Status
Canonical · Binding · Closed

System Position
<CSV-conform system position>

System References
- <namespace>:<module-id>

System Attribution
System Engineered by Digital Space Lab

License
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)
```

---

## III. H1 — Reference Architecture Header

Applicable to: **OT1**

```text
Title
<document title>

Subtitle
<document subtitle>

Canonical Filename
<CFILS-conform filename>

Global ID
<namespace>:<module-id>

Output Type
OT1

Role
ref-arch

Version
vX.Y.Z

Status
Canonical | Stable | Deprecated

System Position
Reference Architecture Specification

System References
- <namespace>:<module-id>

System Attribution
System Engineered by Digital Space Lab

License
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)
```

---

## IV. H2 — Layer / Model Specification Header

Applicable to: **OT2**

```text
Title
<document title>

Canonical Filename
<CFILS-conform filename>

Global ID
<namespace>:<module-id>

Output Type
OT2

Role
layer-spec

Version
vX.Y.Z

Status
Stable | Draft | Deprecated

System Position
Layer Specification

System References
- <namespace>:<module-id>

System Attribution
System Engineered by Digital Space Lab

License
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)
```

---

## V. H3 — Protocol Specification Header

Applicable to: **OT3**

```text
Title
<protocol name>

Canonical Filename
<CFILS-conform filename>

Global ID
<namespace>:<module-id>

Output Type
OT3

Role
protocol

Version
vX.Y.Z

Status
Stable | Draft | Deprecated

System Position
Protocol Specification

System References
- <namespace>:<module-id>

System Attribution
System Engineered by Digital Space Lab

License
Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)
```

---

## VI. H4 — Executable Illustration Header

Applicable to: **OT4**

```text
Title
<illustration title>

Output Type
OT4

Role
illustration

Version
vX.Y.Z

Status
Experimental

Logic Mode
IGLg
```

No system attribution or license declaration is required.

---

## VII. H5 — Exploratory / Derivative Header

Applicable to: **OT5**

```text
Title
<text title>

Output Type
OT5

Role
derivative

Status
Draft | Experimental
```

No system attribution, versioning, or license declaration is required.

---

## VIII. Invariant Rules

1. Headers must appear at the top of the document.
2. No additional fields may be inserted.
3. Field order is fixed per header class.
4. Personal author attribution is prohibited in OT0–OT3.
5. Header omission invalidates canonical status.

---

## Canonical Statement

This document defines the exclusive and binding header specifications for all Epistheon publication formats.

It is complete, authoritative, and closed.

---

**End of Reference Document**

