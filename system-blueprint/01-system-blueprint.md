# 01 — System Blueprint

## Architecture Specification

This document defines the complete architecture as a formal system. It contains three axioms, seven derived laws, and three emergent behaviors. Everything in this document is expressed using only the terminology defined in `00-blueprint-terminology.md`. No application-specific language is used. No implementation details are included.

This is a pre-implementation architecture. It defines the structural laws that any valid implementation must satisfy. It does not prescribe what the primitives are, how many exist, or what domains they describe. Those decisions belong to the implementation layer.

---

## Part I: Axioms

Axioms are irreducible. They cannot be derived from each other or from any other principle within the system. They must be assumed. If any axiom is removed, the architecture ceases to function.

All three axioms are independent. No two of them entail the third. Each one constrains a different aspect of the system: Axiom 1 constrains identity, Axiom 2 constrains behavior, Axiom 3 constrains semantics.

---

### Axiom 1: Non-Overlapping Typed Primitives

Every primitive belongs to exactly one role class. The three role classes are substrate class, kinetic class, and operator class. No primitive may perform the function of a role class other than its own. No role class may absorb the behavior of another.

Non-overlap is absolute. It is not a design preference. It is the condition that makes the other two axioms enforceable. Without non-overlap, invariant function cannot be verified because role boundaries do not exist. Without non-overlap, composition loses structural information because components become interchangeable across categories.

Non-overlap is the structural keystone of the architecture.

#### What this axiom prohibits:

- A substrate class primitive acting as a directed operation
- A kinetic class primitive defining a domain
- An operator class primitive carrying substrate or kinetic function
- Any primitive belonging to more than one role class
- Any role class absorbing the behavior of another

#### What this axiom guarantees:

- Every primitive has a determinable role
- Role boundaries are enforceable
- Composition carries structural information through the arrangement of distinct types

---

### Axiom 2: Invariant Function

Each primitive has exactly one function. That function does not change across any context in which the primitive appears. It does not change with position, scale, surrounding primitives, or the structure it participates in.

Invariant function is the constraint that makes composition deterministic. If function could shift, the same structure would yield different meanings depending on when or where it was encountered. Derivation would become unreliable because the components being verified would not be stable.

#### What this axiom prohibits:

- A primitive changing its function based on position within a structure
- A primitive changing its function based on which other primitives surround it
- A primitive changing its function based on scale realization
- Any context-dependent redefinition of what a primitive does

#### What this axiom guarantees:

- Every primitive behaves identically in every valid structure
- Composition produces predictable results
- Derivation can reliably verify structure by checking component functions
- Compression preserves function because function does not change under reduction

---

### Axiom 3: Composition as Sole Source of Meaning

Meaning arises only from composition. No primitive carries meaning in isolation. Meaning is the output produced when primitives with invariant functions are arranged in a specific structure. There is no interpretive layer outside composition. Meaning cannot be assigned externally, overridden by convention, or imported from outside the system.

This axiom is both generative and prohibitive. It establishes that composition produces meaning. It also forbids any other mechanism from producing or altering meaning.

#### What this axiom prohibits:

- External assignment of meaning to a structure
- Dictionary-based override of compositional meaning
- Meaning attributed to a primitive independent of its structural context
- Any source of meaning other than the arrangement of typed, function-invariant primitives

#### What this axiom guarantees:

- Identical structures yield identical meanings
- Different structures yield different meanings
- Meaning is fully determined by composition and derivable from it
- The system is self-interpreting: no external reference is required to read a valid structure

---

### Axiom Independence

The three axioms are co-equal and independent:

**Remove Axiom 1:** Role classes blur. Primitives become interchangeable across categories. Composition loses structural information. The system becomes ambiguous and non-derivable. Fatal.

**Remove Axiom 2:** Functions drift across context. The same structure yields different meanings at different times. Derivation becomes unreliable. Compression loses determinism. The system becomes context-dependent. Fatal.

**Remove Axiom 3:** Meaning can be assigned externally. Composition still produces structure but the structure's meaning is arbitrary. The architecture remains formally valid but semantically detached. The system becomes an encoding with no interpretive guarantee. Fatal.

All three must be present. Axiom 1 is the structural keystone because its violation causes the fastest total collapse: it destroys the enforcement mechanism for the other two axioms simultaneously.

---

## Part II: Derived Laws

Derived laws follow mechanically from the axioms. They are not additional assumptions. They are entailed consequences. Each law's derivation is stated explicitly.

---

### Law 1: Binary Directionality

For any composition of primitives from different role classes, exactly two orientations are possible and no intermediate state exists. Reversing the orientation produces a different structure with different meaning.

**Derives from:** Axiom 1 (non-overlap) + Axiom 3 (composition as sole source of meaning).

If role classes are non-overlapping (Axiom 1), then the position of a primitive relative to primitives of other role classes carries structural information. If meaning comes only from composition (Axiom 3), then that positional information is semantic. Because the composition involves exactly two role-typed positions, and each position is occupied by a primitive of a fixed type, there are exactly two possible orderings. No gradient exists between them. Directionality is binary.

---

### Law 2: Stability Through Symmetric Closure

A structure achieves stability when it forms symmetric closure around an attractor. The attractor occupies the center and determines the identity of the structure. A structure with symmetric closure reads identically from both directions around its center.

**Derives from:** Axiom 3 (composition as sole source of meaning) + Law 1 (binary directionality).

If directionality is semantic (Law 1), then a structure that reads identically in both directions has resolved its directional tensions into balance. If meaning comes only from composition (Axiom 3), then this balanced condition is a structural property, not an assigned label. The structure either achieves symmetric closure or it does not. If it does, it is stable. If it does not, it retains directionality and is transitional. The attractor at center is determinable from structure alone (Axiom 1: role classes are identifiable) and governs the identity of the whole.

---

### Law 3: Center-Governed Interpretation

Meaning is read from the center outward. The attractor determines the identity of a stable structure before the periphery is parsed.

**Derives from:** Law 2 (stability through symmetric closure).

If a stable structure is defined by symmetric closure around a determinable attractor (Law 2), then the attractor is the most structurally significant element: it is the point around which closure occurs. Interpretation must therefore begin at the center, because the center determines what the structure is. The periphery specifies how the center is contextualized, not the reverse.

---

### Law 4: Explicit Superposition with Context-Driven Collapse

Unresolved states must be formally represented by an operator class primitive. A position in superposition must resolve into a resolved state through collapse determined only by surrounding structure.

**Derives from:** Axiom 1 (non-overlap) + Axiom 2 (invariant function) + Axiom 3 (composition as sole source of meaning).

If role classes are non-overlapping (Axiom 1) and function is invariant (Axiom 2), then an unresolved position cannot be represented by a substrate or kinetic primitive, because those primitives have fixed functions that would falsely resolve the position. The unresolved state must therefore be marked by the operator class, whose function is precisely to govern transitions between resolved and unresolved states. If meaning comes only from composition (Axiom 3), then the resolution of superposition cannot come from external choice. It must come from the surrounding structure. Collapse is structurally determined.

---

### Law 5: Role-Ordered Compression

Compression operates by removing primitives in a specific sequence determined by their role class. Kinetic class primitives are removed first. Substrate class primitives then collapse toward the attractor. Operator class primitives proliferate at positions where collapse to a single substrate class primitive is not possible. The terminal condition is the irreducible center.

**Derives from:** Axiom 1 (non-overlap) + Axiom 2 (invariant function) + Law 2 (stability through symmetric closure).

If role classes are non-overlapping (Axiom 1), then each class has distinct structural properties that determine its removability. Kinetic class primitives define operations within domains. Their function is most dependent on sequential arrangement: they encode directionality. When sequence is removed, they are the first class whose contribution cannot be preserved without position. Substrate class primitives define domains. Under compression, they collapse toward the attractor because the attractor is the structural anchor of the domain (Law 2). The operator proliferates where collapse would force a false resolution, because invariant function (Axiom 2) prohibits the operator from resolving into a substrate or kinetic primitive. The sequence is not arbitrary. It follows from the type definitions.

---

### Law 6: Reconstruction from Irreducible Center

A compressed structure can be expanded back toward its full articulation. Reconstruction is possible because role-ordered reduction is deterministic: the rules that governed compression, applied in reverse, recover the structure. Reconstruction does not require external information beyond the irreducible center and the system's laws.

**Derives from:** Law 5 (role-ordered compression) + Law 3 (center-governed interpretation).

If compression follows a deterministic, role-ordered sequence (Law 5), then the process is reversible in principle. If the center preserves the identity of the structure (Law 3), then the irreducible center plus the compression rules contain sufficient information to reconstruct. No external input is needed because the laws themselves encode the reconstruction path.

---

### Law 7: Scale Realization Without Function Mutation

An invariant function can manifest at different scales without the function itself changing. A primitive operating at one scale and the same primitive operating at a different scale are performing the same function. Scale realization does not introduce new functions, alter existing ones, or produce exceptions to invariant function.

**Derives from:** Axiom 2 (invariant function).

This law is a direct consequence. If function does not change across any context (Axiom 2), then it does not change across scale. Scale is a context. Therefore function is preserved across scale.

---

### Dependency Structure

```
AXIOM 1: Non-overlapping typed primitives
AXIOM 2: Invariant function
AXIOM 3: Composition as sole source of meaning
  │
  ├── LAW 1: Binary directionality .............. (A1 + A3)
  │     └── LAW 2: Stability through closure .... (A3 + L1)
  │           ├── LAW 3: Center-governed ......... (L2)
  │           └── LAW 6: Reconstruction .......... (L5 + L3)
  │
  ├── LAW 4: Explicit superposition ............. (A1 + A2 + A3)
  │
  ├── LAW 5: Role-ordered compression ........... (A1 + A2 + L2)
  │
  └── LAW 7: Scale realization .................. (A2)
```

No circular dependencies. Every law traces to axioms or to laws that trace to axioms. The hierarchy is strictly stratified.

---

## Part III: Emergent Behaviors

Emergent behaviors are not additional rules. They are observable consequences that arise when the laws interact. They are not prescribed by the architecture. They appear within it.

---

### Emergent Behavior 1: Dual Projection Modes

The architecture supports two projection modes over one structure without alteration to the structure's composition or meaning.

**Sequential projection** articulates a structure through time-bound, ordered presentation. Primitives are encountered in sequence. Directionality and orientation are experienced as a progression. This mode arises naturally from Law 1 (binary directionality): if orientation is semantic and composition is ordered, then a structure can be expressed by presenting its components in sequence.

**Simultaneous projection** presents a structure from its center outward as a whole. The attractor is perceived first. The periphery is resolved from it. This mode arises naturally from Law 3 (center-governed interpretation) + Law 5 (role-ordered compression): if interpretation begins at the center and compression produces an irreducible center, then a compressed structure can be recognized as a whole rather than unfolded sequentially.

These two modes are not designed. They emerge from the interaction of directionality, center-governance, and compression. Any implementation of this architecture will naturally support both.

---

### Emergent Behavior 2: Structural Distinction Between Transitional and Stable Forms

Structures with binary directionality but no symmetric closure are transitional: they lean in one direction and encode a relation between role classes. Structures with symmetric closure around a determinable attractor are stable: they are completed objects with resolved directionality.

This distinction arises from Law 1 + Law 2 without requiring a separate classification system. The architecture does not assign the categories "transitional" and "stable." It produces them as structural conditions that either hold or do not.

---

### Emergent Behavior 3: Recursive Stability

Stable structures can themselves compose into larger structures. When a larger composition achieves symmetric closure around a determinable center, it becomes stable at a higher level. This process can recurse: stable structures nesting within stable structures, each level achieving closure around its own attractor.

The maximum stable object within any implementation is the structure that nests all possible stable forms into a single symmetric closure. This object is not prescribed by the architecture. It emerges from recursive application of Law 2.

---

## Part IV: Boundaries

This section defines what the architecture does not include. These boundaries are as important as the laws.

---

### What the architecture does not specify

**Primitive inventory.** The architecture requires typed, non-overlapping primitives with invariant function. It does not specify how many primitives exist, what their functions are, or what domains they describe. Those decisions belong to the implementation.

**Encoding format.** The architecture defines structural laws. It does not define bit-level representation, transmission format, or machine-readable encoding. Implementations may encode structures in any format that preserves the axioms and laws.

**Computational complexity.** The architecture does not specify the computational cost of composition, derivation, compression, or reconstruction. Implementations must determine their own performance characteristics.

**Error handling.** The architecture defines what valid structures are. It does not define what happens when invalid structures are encountered. Implementations must define their own error models.

**Application domain.** The architecture is domain-agnostic. It does not prescribe whether the implementation is a language, a protocol, a data format, a state machine, or any other system. Any domain that can instantiate typed, non-overlapping primitives with invariant function and follow the seven derived laws is a valid implementation.

---

### What the architecture does guarantee

**Derivability.** Every valid structure can be reduced to its component primitives through derivation.

**Deterministic composition.** Identical arrangements of identical primitives produce identical meanings.

**Deterministic compression.** Role-ordered reduction follows a fixed sequence and produces a unique irreducible center for any given structure.

**Reconstructibility.** A compressed structure can be expanded back toward its full articulation without external information.

**Self-interpretation.** No external reference, dictionary, or interpretive layer is required to read a valid structure. The structure interprets itself through its composition.

**Closure under operations.** Composition, compression, and reconstruction all produce valid structures. The system does not generate forms that violate its own laws through its own operations.

---

## Summary

Three axioms. Seven derived laws. Three emergent behaviors.

The axioms define what the system requires: typed primitives, invariant function, compositional meaning.

The laws define what follows: directionality, stability, superposition, compression, reconstruction, scale invariance.

The emergent behaviors define what appears: dual projection, transitional/stable distinction, recursive nesting.

The boundaries define what is excluded: implementation details, domain specifics, encoding formats, computational models.

Together these constitute a complete, minimal, self-consistent architecture for generating, stabilizing, compressing, and recovering structured meaning from typed primitive relations.