# 01 — Varoli G3 Primitive Schemas

*Last Updated: March 28, 2026*

**Status:** Working reference  
**Layer:** Ground 3 / Primitive-Building-Blocks  
**Authority:** Schema reference  
**Scope:** Preserves the formal entry schemas used for substrate, operator, and kinetic primitives in compact reusable form.

---

## 1. Purpose

This file preserves the raw entry schemas for the primitive inventory.

Its purpose is to:
- keep the formal definition templates visible
- standardize how primitive entries are written
- support future normalization of the build-layer reference
- avoid duplicating the full schema block in every primitive class file

The compact class files in this folder may use shortened entries for readability.
Those shortened entries should still remain consistent with the schemas defined here.

---

## 2. Vowel schema

Use this schema when writing or expanding substrate entries.

### 2.1 Template structure

**[Vowel] — [Element Name]**

**Class:**  
Always `substrate`.

**Function (Invariant):**  
The ontological domain or condition this vowel defines. Fixed and non-overlapping.

**Articulation (Physical Basis):**  
The acoustic and articulatory quality that grounds the vowel’s structural identity.

**Kinetic Tendency:**  
The natural directional tendency associated with interpretation. Descriptive only. Not a kinetic function.

**Register (Experiential Layer):**  
The awareness, identity, or experiential layer commonly associated with the substrate. Descriptive only.

**Scale Realization:**  
How the same invariant substrate appears across different scales:
- internal / external
- temporal
- dimensional

**Exclusion:**  
What the vowel is not. Used to preserve non-overlap between substrates.

**Poetic Field (Mnemonic):**  
A concise mnemonic or embodied sense of the substrate. Subordinate to structural definition.

**Notes (Optional):**  
Pronoun assignments, stable worlds, special constraints, or important distinctions.

---

## 3. Operator schema

Use this schema when writing or expanding operator entries.

### 3.1 Template structure

**[Operator] — [Operator Name]**

**Class:**  
Always `operator`.

**Function (Invariant):**  
The structural operation the operator performs. Fixed and non-overlapping.

**Positional Behavior:**  
How the operator behaves in different positions:
- vowel position
- consonant position
- stable center
- terminal position

**Scope of Action:**  
What structural span the operator governs.

**Poetic Field (Mnemonic):**  
A concise mnemonic or embodied sense of the operator. Subordinate to structural definition.

**Exclusion:**  
What the operator is not. Must explicitly exclude substrate and kinetic identity.

**Operational Role (Contextual):**  
How the operator typically behaves in Varoli and, where relevant, in Yemu.

**Notes (Optional):**  
Structural cautions, special uses, center behavior, compression behavior, or known limits.

---

## 4. Consonant schema

Use this schema when writing or expanding kinetic entries.

### 4.1 Template structure

**[Consonant] — [Force Name]**

**Class:**  
Always `kinetic`.

**Function (Invariant):**  
The quality of motion this consonant defines. Fixed and non-overlapping.

**Quality of Motion:**  
A concise description of what the force does.

**Directional Bias:**  
Its natural vector or structural direction:
- inward
- outward
- bidirectional
- threshold
- static
- permeating
- etc.

**Articulation (Physical Basis):**  
The physical production of the sound that grounds its kinetic identity.

**Poetic Field (Mnemonic):**  
A concise mnemonic or embodied sense of the force. Subordinate to structural definition.

**Elemental Affinity (Attractor Set Only):**  
The substrate this kinetic makes real as an attractor. Only present for attractor consonants.

**Operational Role (Contextual):**  
How the consonant behaves in primitive generation and related contexts.

**Notes (Optional):**  
Pair relations, distinctions from nearby forces, suffix relevance, or other important constraints.

---

## 5. Compact-reference rule

The class files in this folder may use a shortened build-layer format for scanability.

A compact entry may reduce to:
- class
- invariant function
- short description
- key exclusions or contrasts
- brief structural notes

This is acceptable as long as the entry remains consistent with the full schema defined here.

---

## 6. Use rule

When expanding a primitive entry into a fuller reference form:
1. start from the relevant schema in this file
2. preserve invariant function
3. preserve class identity
4. do not add interpretive language that overrides structural definition
5. keep exclusions precise enough to protect non-overlap

---

## 7. Bottom line

This file preserves the formal templates.

The class files preserve the compact usable reference.

Both should remain aligned.