# 00 — Blueprint Terminology: Invariant Compositional Architecture

This document defines the minimal set of terms required to describe the Invariant Compositional Architecture (ICA). Every term maps to an axiom, derived law, or structural operation. No term is application-specific. No term requires knowledge of any implementation to understand.

Terms are defined in dependency order. Each term is defined using only terms that precede it or are defined alongside it. No circular definitions. No metaphor. No synonyms.

---

## Foundational Terms

### primitive

The smallest indivisible unit within the system. A primitive cannot be decomposed into smaller components within the architecture. It is defined only by its role class and function. It participates in composition but carries no meaning on its own.

### role class

A category that determines what a primitive can do within the system. Every primitive belongs to exactly one role class. Role classes are mutually exclusive and collectively exhaustive: every primitive in the system is assigned to one, and no primitive may be assigned to more than one.

There are exactly three role classes:

**substrate class** — primitives that define domains. A substrate primitive establishes the condition within which other operations occur. It does not move, act, or resolve.

**kinetic class** — primitives that define directed operations within domains. A kinetic primitive acts within or across the conditions established by substrate primitives. It does not define domains.

**operator class** — primitives that govern transitions between resolved and unresolved states. An operator primitive does not define a domain and does not act as a directed operation. It marks and resolves indeterminate positions within a structure.

### non-overlap

The constraint that role classes are absolutely separated. No primitive may perform the function of a role class other than its own. No role class may absorb the behavior of another. If non-overlap is violated, the system loses derivability and becomes interpretive.

Non-overlap is the structural keystone: it is the constraint that makes all other axioms enforceable.

---

## Function Terms

### function

The specific behavior assigned to a single primitive. Function describes what a primitive does, not what it means. Every primitive has exactly one function.

### invariant function

The constraint that a primitive's function does not change across any context in which it appears. A primitive behaves the same way regardless of where it occurs in a structure, at what scale it is realized, or which other primitives surround it.

---

## Composition Terms

### composition

The act of combining primitives to produce a structure. Composition is constrained by role classes and orientation: not all arrangements are valid. Composition is the sole generative mechanism. It does not import meaning from outside the system. It produces meaning by arranging primitives whose functions and role classes are fixed.

### structure

The result of composition. A structure is an arrangement of primitives that can be analyzed, compressed, or validated. A structure is not a primitive: it is what primitives produce when composed. Every structure is reducible to its component primitives through derivation.

### meaning

What a structure yields through its composition. Meaning is not assigned externally. It is not a property of any individual primitive. It is the output produced when primitives with invariant functions are arranged in a specific structure. If the structure changes, the meaning changes. If the structure is identical, the meaning is identical.

### derivation

The operation of reducing a structure back to its component primitives to verify that it was produced by valid composition. Derivation is the verificational counterpart of composition. Composition builds structure. Derivation confirms that a structure is legitimate. A structure that cannot be derived from primitives through valid composition is not a valid structure within the system.

---

## Directionality Terms

### orientation

The order in which primitives of different role classes are arranged within a composition. Because role classes are non-overlapping and function is invariant, the position of a primitive relative to primitives of other role classes carries structural information. Reversing the order produces a different structure with different meaning.

### binary directionality

The constraint that for any two-primitive composition involving different role classes, exactly two orientations are possible and no intermediate state exists. One orientation encodes the kinetic or operator primitive acting upon the substrate primitive. The reversed orientation encodes the substrate primitive expressing through the kinetic or operator primitive. These are structurally distinct and non-equivalent.

---

## Stability Terms

### attractor

The primitive within a stable structure that determines the identity of that structure. The attractor is determinable from structure alone, identifiable by its role class and position. It is what the structure resolves around.

### center

The positional role occupied by the attractor within a stable structure. The center is the point from which the structure is read and from which its identity is determined. In a stable structure, the center is always determinable from the arrangement of role classes.

### symmetric closure

The structural condition in which a composition reads identically from both directions around its center. A structure achieves symmetric closure when its directional tensions are resolved into balance. Symmetric closure is the formal mechanism by which a structure transitions from directional to stable.

### stability

The property of a structure that has achieved symmetric closure around a determinable attractor. A stable structure does not lean in either direction. It is a completed object rather than a transitional arrangement. Stability is not assigned. It is a structural condition that either holds or does not.

---

## Superposition Terms

### resolved state

The condition of a position within a structure where the primitive occupying that position is determined. A resolved position has a known primitive with a known role class and known function.

### unresolved state

The condition of a position within a structure where the primitive that should occupy that position is not yet determined. An unresolved position cannot be left implicit. It must be formally marked.

### superposition

The formal representation of an unresolved state. A position in superposition is occupied by an operator class primitive that marks the position as awaiting resolution. Superposition is not ambiguity. It is a specific, explicit structural condition with defined behavior.

### collapse

The operation by which a position in superposition transitions to a resolved state. Collapse is determined only by the surrounding structure, not by external choice. The structure constrains which resolution is valid. Collapse is the mechanism that converts superposition into a specific resolved state.

---

## Compression Terms

### compression

The operation of reducing a structure toward its irreducible center by removing primitives in a specific order determined by their role class. Compression is not arbitrary simplification. It is role-ordered reduction.

### role-ordered reduction

The rule governing the sequence in which primitives are removed during compression. Kinetic class primitives are removed first because their function is most dependent on sequential arrangement. Substrate class primitives then collapse toward the attractor. Operator class primitives proliferate at positions where collapse to a single substrate class primitive is not possible. This order is determined by the properties of the role classes, not by implementation choice.

### irreducible center

The terminal condition of compression. The irreducible center is the structure that remains when role-ordered reduction can proceed no further. It contains the attractor and enough structural information to serve as the basis for reconstruction. It is the minimal form that preserves the identity of the original structure.

### reconstruction

The operation of expanding an irreducible center back toward a fuller articulation of the original structure. Reconstruction is possible because role-ordered reduction is deterministic: the rules that governed compression, applied in reverse, recover the structure. Reconstruction does not require external information beyond the irreducible center and the system's rules.

---

## Scale and Projection Terms

### scale realization

The property that an invariant function can manifest at different magnitudes, scopes, or contexts without the function itself changing. A primitive that operates at a small scale and the same primitive operating at a large scale are performing the same function. Scale realization is a direct consequence of invariant function.

### projection mode

The manner in which a structure is expressed or perceived. The same underlying structure can be projected in different modes without alteration to its composition or meaning. Projection mode determines the format of expression, not the content.

### sequential projection

A projection mode in which a structure is articulated through time-bound, ordered presentation. Primitives are encountered one after another. Meaning unfolds progressively. Directionality and orientation are experienced as a sequence.

### simultaneous projection

A projection mode in which a structure is presented from its center outward as a whole. Primitives are not encountered in sequence. Meaning is recognized rather than unfolded. The attractor is perceived first and the periphery is resolved from it.

---

## Term Inventory

27 terms. Organized below by architectural dependency.

**Grounding layer (Axiom 1):**
primitive, role class, substrate class, kinetic class, operator class, non-overlap

**Function layer (Axiom 2):**
function, invariant function

**Composition layer (Axiom 3):**
composition, structure, meaning, derivation

**Directionality layer (Law 1):**
orientation, binary directionality

**Stability layer (Laws 2–3):**
attractor, center, symmetric closure, stability

**Superposition layer (Law 4):**
resolved state, unresolved state, superposition, collapse

**Compression layer (Laws 5–6):**
compression, role-ordered reduction, irreducible center, reconstruction

**Projection layer (Law 7 + emergent):**
scale realization, projection mode, sequential projection, simultaneous projection