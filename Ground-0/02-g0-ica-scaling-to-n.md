# 02 — Scaling to N: Invariant Compositional Architecture

*Last Updated: March 26, 2026*

## The Foundational Universality Test

This document defines the threshold test that determines whether the Invariant Compositional Architecture (ICA) described in `./01-g0-ica-blueprint.md` is a valid formal system for one domain, a reusable formal system for several domains, or a genuinely general structural substrate for all domains that can be formally specified.

This is not an application document. It is a test specification. It defines what the architecture must preserve under increasing domain diversity, what would constitute success, what would constitute failure, and what remains unknown.

For the formal Invariant Compositional Architecture, see `./01-g0-ica-blueprint.md`. For terminology, see `./00-g0-ica-terminology.md`. This document uses only the terms defined in those sources.

---

## What Scaling to N Means

N is the number of independently formalized domains the architecture is expected to support. A domain is any formally specified system that satisfies the architectural constraints.

Scaling to N is not a question of volume. It is not "can the system handle more structures within one domain." It is a question of dimensional breadth:

Can the same axioms, laws, and structural operations remain sufficient as the number of formally distinct domains increases without bound?

At N=1, the architecture needs only to work within a single domain. Internal coherence is sufficient.

At N=2, the architecture must support two structurally different domains without modification. This is the first real pressure point.

At large N, the architecture must remain coherent across domains that share no primitives, no subject matter, and no surface resemblance. Only architectural properties are shared.

The test is therefore:

Given the architecture's axioms, laws, and operations, does the system remain sufficient to generate, validate, compress, reconstruct, and compare valid structures across an arbitrarily increasing number of formally distinct domains without introducing new axioms, violating existing constraints, or collapsing into interpretation?

---

## Why This Is the Foundational Test

The architecture makes strong claims. It guarantees derivability, determinism, compositional meaning, canonical reduction, lossless reconstruction, and self-interpretation. At N=1, these are local guarantees. They describe the behavior of one system.

Scaling to N tests whether these guarantees are local truths or general truths.

If the architecture fails at higher N, then applications to human language and cross-domain translation are bounded applications of a powerful but limited system. The guarantees hold within a narrow scope and do not extend beyond it.

If the architecture passes at higher N, then human language and cross-domain translation are not exceptional use cases. They are ordinary consequences of a general architecture. Every future application document in this folder depends on this test.

Internal coherence has already been demonstrated. One full implementation exists with hundreds of derived forms, stable derivation, grammar, and compression behavior. That proves local validity. It does not prove universality. This document defines what universality requires.

---

## What the Architecture Must Preserve at Scale

Scaling to N tests every layer of the architecture. Each layer faces specific pressure.

### Axiom Layer

All three axioms must remain intact across all candidate domains.

Axiom 1 (non-overlap): Role classes must remain absolutely separated. No domain may force a primitive to serve multiple role classes. No domain may blur the boundary between substrate, kinetic, and operator.

Axiom 2 (invariant function): Primitives must retain fixed function across all contexts within their domain. No domain may require context-dependent function to achieve its expressive goals.

Axiom 3 (composition as sole source of meaning): Meaning must remain fully determined by structure. No domain may require external assignment, interpretive convention, or lookup tables to determine what a valid structure means.

This is the strictest layer. If the axioms fail for any valid formal domain, the architecture is not universal.

### Law Layer

All seven derived laws must remain sufficient to describe the structural behavior of every candidate domain. The specific pressure points are:

Law 1 (binary directionality): Does every domain produce exactly two orientations for any two-primitive composition, or do some domains require intermediate or multi-directional states?

Law 2 (stability through symmetric closure): Does symmetric closure produce stability in every domain, or do some domains define stability through different mechanisms?

Law 4 (explicit superposition): Does every domain that contains unresolved states represent them through an operator-class mechanism, or do some domains handle unresolved states implicitly?

Law 5 (role-ordered compression): Does the compression sequence (kinetic strips first, substrate collapses toward attractor, operator proliferates at unresolvable positions) hold for every domain, or do some domains require a different reduction order?

If any law proves insufficient for a valid formal domain, the architecture must either derive an additional law from the existing axioms or accept that the domain is outside scope.

### Operation Layer

Derivation, compression, and reconstruction must remain functional at increasing scale and structural complexity.

Derivation must still reduce any valid structure to its component primitives in a finite number of steps, regardless of domain complexity.

Compression must still produce a unique irreducible center for any given structure, regardless of how many role classes or composition rules the domain employs.

Reconstruction must still expand an irreducible center back to its full articulation without external information, regardless of domain.

### Projection Layer

The same architecture must instantiate as multiple domain systems without modification to the architecture itself. Each domain defines its own primitives and composition rules, but those primitives and rules must satisfy all axioms and laws. If any domain requires the architecture to change in order to accommodate it, the architecture is not universal for that domain.

---

## Domain-Scoped Operation Under Scaling Pressure

The architecture requires that kinetic-class primitives operate within substrate-class domains. This relationship is encoded in the role class definitions: substrate establishes the condition within which operations occur, and kinetic acts within those conditions.

At low N, this constraint can remain implicit in the role definitions. At high N, it becomes one of the central properties under test. Domain diversity increases pressure on scoped operation:

Can all operations in every candidate domain be understood as occurring within a defined domain? Can those domains be clearly identified from structure alone? Can cross-domain structures preserve operation-within-domain rather than blurring into unscoped relation?

If the answer to any of these questions is no for a valid formal domain, the architecture faces a boundary condition. Scaling to N is the strongest reason to treat domain-scoped operation as an explicit structural constraint rather than an implicit consequence of role definitions. Making it explicit does not add a new mechanic. It names a mechanic already present and makes it auditable under universality pressure.

---

## Necessary Conditions for Passing

The architecture passes the scaling-to-N test only if all of the following hold.

**No new axioms are needed.** The existing three axioms remain sufficient. No new irreducible assumptions are required to absorb new domains. If a new axiom is required, the architecture is incomplete in its current form.

**No role class collapse occurs.** Substrate, kinetic, and operator remain non-overlapping and adequate. New domains do not force categories to blur or primitives to exchange function. If role classes begin to overlap under domain pressure, Axiom 1 is violated and the architecture fails.

**No external interpretive layer is introduced.** Meaning must remain derivable from structure alone. If the system begins relying on conventions, lookup tables, domain-specific interpretive patches, or implicit context to handle new domains, Axiom 3 is violated and the architecture fails.

**Compression remains identity-preserving.** Irreducible centers must continue to preserve the identity of full structures across increasingly different domains. If two structurally distinct forms collapse to the same irreducible center in a way that destroys important distinctions, compression has failed at scale.

**Reconstruction remains deterministic.** Reconstruction must not require hidden information, domain-specific guesswork, or interpretive supplementation. If multiple equally valid reconstructions become possible from the same compressed structure without structural means of resolution, the architecture has lost determinism at scale.

**Domain growth does not generate contradictions.** As N increases, structures from different domains must remain mutually intelligible at the architectural level without forcing the laws into contradiction. If accommodating one domain requires a law that contradicts a law required by another domain, the architecture cannot hold both.

---

## Failure Conditions

The architecture fails the scaling-to-N test if any of the following occur.

**Domain failure.** A valid formal domain cannot be represented without violating one or more axioms. The domain requires capabilities the architecture does not provide and cannot derive.

**Primitive overload.** A role class begins carrying multiple functions or standing in for missing mechanics. Substrate begins acting as kinetic, or operator begins carrying domain-specific meaning. The non-overlap boundary erodes.

**Hidden-law emergence.** A recurring structural necessity appears across multiple domains but cannot be derived from the existing axioms or laws. The architecture requires an additional law that is not entailed by its current foundation.

**Compression loss.** Two structurally distinct forms collapse to the same irreducible center in a way that destroys distinctions critical to one or both domains. Canonical form generation produces false equivalences.

**Reconstruction ambiguity.** Multiple equally valid reconstructions become possible from the same compressed structure. The architecture cannot determine which reconstruction is correct without external information.

**Mapping dependence on convention.** Cross-domain structural correspondence becomes dependent on human judgment, arbitrary alignment, or domain-specific convention rather than on architectural properties alone.

---

## The Scaling Sequence

The test can be evaluated through progressive stages.

### Stage 1: Intra-Domain Scaling (N=1)

Can the architecture scale within one domain? Can it generate, validate, compress, and reconstruct an increasing number of structures without degradation?

This stage has been demonstrated through one full implementation. Local validity is confirmed.

### Stage 2: Dual-Domain Scaling (N=2)

Can the architecture support two structurally different domains without modification? This is the first genuine universality test. Two independently constructed systems, both built on the architecture, must remain internally valid and architecturally comparable.

This stage has not been demonstrated. It is the immediate next test.

### Stage 3: Multi-Family Scaling (N=5 to N=10)

Can the architecture support multiple domains from different formal families? At this stage, surface resemblance between domains disappears entirely. Only architectural properties remain as common ground. If the architecture still holds, it is genuinely cross-domain rather than cross-dialect.

### Stage 4: Structural Clustering

At larger N, do domains begin to cluster by shared architectural patterns without forcing architecture changes? If yes, the architecture is discovering structural taxonomy rather than merely absorbing examples. Clustering would indicate that the architectural properties capture real invariants of formal structure, not artifacts of the first few domains tested.

### Stage 5: Universality Pressure (N approaching asymptote)

At very high N, do any new domains force new primitives, new axioms, or new laws? If no, universality is strongly supported. If yes, the current architecture is incomplete or bounded. The asymptote may not be infinite — it may be the set of all domains that are formally specifiable under the architecture's conditions. That is still a very large claim, but it is more precise and more defensible than unbounded universality.

---

## Open Questions

These are genuine unknowns that scaling to N must eventually resolve.

**Are three role classes enough?** Substrate, kinetic, and operator may be universally sufficient. They may also prove to be the minimal basis only for a subset of domains. If a valid formal domain requires a fourth role class that cannot be derived from the existing three, the architecture must be extended or the domain must be classified as outside scope.

**Is the irreducible center sufficient for cross-domain identity?** Compression preserves structural identity within one domain. Whether that identity remains meaningful and sufficient when compared across structurally different domains is untested.

**Can all valid formal systems be represented without role drift?** If some domains force substrate-like or kinetic-like behavior to blur, the non-overlap axiom comes under pressure. Whether such domains exist and whether they are formally specifiable under the architecture's conditions is unknown.

**Can structural mapping occur without extra conventions?** Cross-domain translation assumes that shared architectural properties provide sufficient common ground for mapping. Whether this is true in practice or whether additional shared conventions are needed has not been demonstrated.

**Is there an asymptote?** The architecture may not scale to literally every imaginable domain. It may scale to every domain that is formally specifiable under the blueprint's conditions. Identifying the boundary between domains that satisfy the conditions and domains that do not is itself a major open question.

---

## Relationship to Application Documents

This document precedes and conditions the application documents in this folder.

The Varoli adaptation (`../Varoli/Ground-1/00-g1-ica-adaptation.md`) instantiates the architecture as human language. The scaling-to-N test asks the more basic question: is language one local expression of a generally scalable architecture, or is language the natural limit of the architecture?

A cross-domain translation layer would assume that multiple systems can be related through shared architectural properties. The scaling-to-N test asks whether the architecture remains structurally sufficient as those systems proliferate. (No separate CDT overview document exists in this repository yet.)

If the architecture does not scale, language remains the primary validated domain and translation remains narrow. If the architecture does scale, both become ordinary consequences of a general substrate.

---

## Summary

Scaling to N is the foundational universality test of the Invariant Compositional Architecture. It determines whether the architecture's guarantees — derivability, determinism, compositional meaning, canonical compression, lossless reconstruction, self-interpretation — are local properties of one implementation or general properties of all formally specifiable domains.

The test is defined by necessary conditions for passing, explicit failure conditions, a progressive scaling sequence, and a set of open questions that must be resolved empirically. No claim of universality is made in advance of evidence. The architecture is currently validated at N=1. Each subsequent stage of scaling either confirms the architecture's generality or reveals its boundaries.

The honest position is this: the architecture is designed for universality but has not yet proven it. This document defines what proof would require.