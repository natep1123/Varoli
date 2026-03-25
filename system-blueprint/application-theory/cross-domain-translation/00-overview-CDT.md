# 00 — Overview: Cross-Domain Structural Translation

This document describes how the architecture defined in `../../01-system-blueprint.md` applies to the domain of cross-system structural translation: the problem of validating, mapping, and translating structures between independently constructed formal systems without losing derivable meaning.

This document does not describe a specific translation system. It describes the architectural properties that make structural translation possible, the theoretical model by which translation would operate, the constraints that apply, and the boundaries of what remains unproven.

For the formal architecture, see `../../01-system-blueprint.md`. For terminology, see `../../00-blueprint-terminology.md`. Nothing in this document extends or modifies the architecture.

---

## The Problem

Formal systems are constructed independently. Each defines its own primitives, its own composition rules, and its own structures. When two such systems need to interoperate, the problem is translation: how does a structure valid in one system become a structure valid in another while preserving what the original structure means?

Conventional approaches to this problem rely on one of three strategies:

**Shared intermediary.** Both systems translate through a common representation (a database schema, an interchange format, a shared API). This works when the intermediary is expressive enough to capture what both systems produce. It fails when the intermediary imposes its own structural assumptions, forcing both systems to conform to a representation that distorts their native structures.

**Pairwise mapping.** Direct translation rules are written between every pair of systems. This works for small numbers of systems. It scales poorly: n systems require n(n-1)/2 mapping sets, each of which must be maintained independently.

**Interpretive bridging.** A human or an AI examines structures from both systems and produces translations based on judgment. This works for informal systems. It fails for formal systems because the translation is not deterministic, not reversible, and not verifiable.

All three strategies share a deeper problem: none of them guarantees that the structural properties of the source are preserved in the target. A structure that is derivable, self-interpreting, and deterministically compressible in its source system may become none of those things after translation.

The question for this architecture is: what properties would a system need to guarantee that structural translation is deterministic, reversible, and verifiable?

---

## What the Architecture Provides

The architecture offers five properties directly relevant to cross-domain structural translation.

### 1. Derivation as Validation

Every valid structure in the architecture can be reduced to its component primitives through derivation (Axiom 3 + derivation). This means any structure presented for translation can be verified before translation begins. If a structure cannot be derived from its primitives, it is not valid and cannot be translated. Derivation provides the entry gate: only structurally verified forms enter the translation process.

This also provides the exit gate. After translation, the resulting structure in the target system can be derived to confirm it is valid in the target. Translation that produces non-derivable structures has failed, and the failure is detectable.

### 2. Compression as Canonical Form

Role-ordered compression (Law 5) reduces any valid structure toward its irreducible center: the minimal form that preserves the identity of the original. This provides a canonical representation — a single, deterministic reduced form for any given structure.

Canonical forms are critical for translation because they strip away articulation-specific detail and expose the structural core. Equivalence = same structural properties, not just same center. Translation can operate on irreducible centers rather than on fully articulated forms, reducing the complexity of the mapping problem.

### 3. Reconstruction as Reversibility

Reconstruction (Law 6) guarantees that a compressed structure can be expanded back toward its full articulation without external information. This means translation is reversible in principle: a structure translated from system A to system B can be translated back to system A and verified against the original through derivation.

Reversibility is the structural guarantee that translation is not lossy within the architecture's own domain. Whether reversibility holds across independently constructed systems is a separate question addressed in the constraints section below.

### 4. Self-Interpretation Through Composition

Axiom 3 guarantees that meaning is produced by composition and requires no external reference. A valid structure contains everything needed for its own interpretation. This means structures presented for translation are self-describing: the translation process does not need to consult an external dictionary, schema, or reference table to understand what the source structure means. The meaning is in the arrangement.

This property is what distinguishes structural translation from interpretive bridging. The translation process reads the structure, not a description of the structure.

### 5. Domain-Scoped Operation

The architecture requires that kinetic-class primitives operate within substrate-class domains (role class definitions, Axiom 1). No operation is valid without a domain in which it occurs. This is a structural constraint, not merely an observation: it means that every force in the system is scoped to a domain, and that scope is determinable from the structure itself.

For cross-domain translation, this property is essential. It means that when examining any structure, the translation process can identify which operations occur within which domains. The scope boundaries are structural, not interpretive. Two systems that both satisfy this constraint have compatible scoping models even if their specific domains and operations are entirely different.

---

## Theoretical Translation Model

Given the five properties above, structural translation between two systems built on this architecture would follow a four-step process. Each step is structural rather than interpretive.

**Step 1: Derivation.** The source structure is derived to confirm validity. If derivation fails, the structure is rejected before translation is attempted.

**Step 2: Compression.** The source structure is compressed through role-ordered reduction to its irreducible center. This produces the canonical form: the structural identity of the expression stripped of articulation-specific detail.

**Step 3: Structural Mapping.** The irreducible center is examined for its structural properties: which role classes are present, what orientation relationships hold, whether symmetric closure exists, whether superposition positions are present. These properties are compared against the target system's structural capabilities. Where both systems share a structural property, a correspondence is established. Where one system has a property the other lacks, a gap is identified.

**Step 4: Reconstruction.** The mapped structural properties are reconstructed in the target system using the target's own primitives and composition rules. The result is a valid structure in the target system that preserves the structural properties shared between the two systems. Gaps are explicitly noted rather than silently dropped.

This model does not require the two systems to share primitives. It requires them to share structural properties — the properties guaranteed by the architecture. The primitives are domain-specific. The structural properties are architectural.

---

## What This Enables

If both the source and target systems are built on this architecture, the following capabilities become available:

**Structural equivalence detection.** Two structures from different systems can be compared at the level of their irreducible centers. If the centers share the same structural properties (same role class arrangements, same orientation relationships, same closure conditions), they are structurally equivalent even though their primitives are different.

**Deterministic transformation within shared structure.** For any structural property shared between two systems, the transformation from source to target is deterministic: the same source property always maps to the same target property. This is guaranteed by invariant function (Axiom 2) and compositional meaning (Axiom 3).

**Verifiable translation.** Every step in the translation process is verifiable. Derivation confirms source validity. Compression is deterministic. Mapping is explicit about correspondences and gaps. Reconstruction produces a derivable target structure. If any step fails, the failure is detectable and locatable.

**Elimination of interpretive ambiguity.** Because both systems prohibit external meaning assignment (Axiom 3) and require non-overlapping types (Axiom 1), the translation process never needs to guess what a structure means. The meaning is in the composition. The translation preserves composition. The meaning is preserved.

---

## Constraints

Structural translation under this architecture is subject to hard constraints. These are not limitations to be overcome. They are boundary conditions that define where the architecture applies.

**Both systems must be derivable.** Translation requires derivation at both ends: verifying the source and verifying the target. A system whose structures cannot be reduced to primitives through a finite derivation process cannot participate in structural translation under this architecture. Systems with ambiguous structures, non-invariant primitives, or externally assigned meaning are outside scope.

**Both systems must have invariant primitives.** If the primitives of either system change function across context, the translation mapping becomes unreliable. Invariant function (Axiom 2) is a prerequisite for deterministic mapping, not just a desirable property.

**Primitive sets need not be shared but must be structurally mappable.** The two systems do not need to share primitives. They need to share structural properties at the architectural level: typed role classes, compositional meaning, binary directionality, and the other derived laws. If both systems satisfy the architecture, their structural properties are compatible even if their primitive inventories are entirely different. If one system satisfies the architecture and the other does not, structural translation is not possible.

**Gaps are inevitable and must be tracked.** No two independently constructed systems will have perfectly overlapping structural capabilities. Some structures in the source will use properties that the target cannot express. These gaps are not errors. They are information about the structural differences between the two domains. The translation process must identify gaps explicitly and annotate them rather than forcing false correspondences.

**Translation fidelity is a property of the system pair, not of the architecture.** Two closely related systems will have high translation fidelity (most structural properties map). Two distant systems will have lower fidelity. The architecture guarantees that whatever does map is mapped correctly. It does not guarantee that everything maps.

---

## What Remains Unproven

**Canonical form sufficiency.** The irreducible center preserves the identity of a structure within its own system. Whether it preserves enough structural information to serve as the basis for cross-system mapping has not been tested. It is possible that two structurally different source expressions compress to irreducible centers that appear equivalent at the architectural level but differ in ways that only the source system's full articulation reveals.

**Fidelity measurement.** The architecture does not currently define a metric for translation fidelity. A quantitative measure of how much structural content is preserved versus lost in translation would be necessary for any practical implementation. This metric must be defined and validated.

**Cross-domain scaling.** The theoretical model has been tested within one domain (human language, with hundreds of derived forms). Whether it scales to systems with fundamentally different primitive inventories, different numbers of role classes, or different composition constraints is unknown.

**Independent primitive mapping.** The hardest open question: whether two independently defined primitive systems can be structurally mapped without any shared foundational alignment beyond the architectural laws themselves. The architecture guarantees that both systems satisfy the same structural properties. Whether those guarantees are sufficient to produce meaningful mappings in practice, or whether additional shared conventions are needed, has not been demonstrated.

---

## Status

The architecture provides the structural properties that cross-domain translation requires: derivation, canonical compression, deterministic reconstruction, self-interpretation, and domain-scoped operation. The theoretical model is consistent with the architecture and introduces no new mechanics.

No translation system has been implemented. No cross-domain mapping has been tested. The claims in this document are theoretical consequences of the architecture, not demonstrated capabilities.

The architecture is compatible with this domain. Implementation and empirical validation are required.