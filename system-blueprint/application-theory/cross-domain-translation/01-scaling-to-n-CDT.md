# 01 — Scaling to N: Cross-Domain Structural Translation

This document applies the foundational universality test defined in `../../03-scaling-to-n.md` to the domain of cross-system structural translation. It asks whether the Invariant Compositional Architecture's (ICA's) translation capabilities remain sufficient as the number of independently constructed formal systems increases, and whether the structural guarantees that support translation between two systems hold across an arbitrarily growing network of systems.

This document does not test the architecture's generative capabilities. Those are tested in the domain-specific scaling documents. This document tests the architecture's interoperability capabilities: whether structures from increasing numbers of independent systems can be compared, mapped, and translated through shared architectural properties alone.

For the formal Invariant Compositional Architecture, see `../../01-system-blueprint.md`. For the general universality test, see `../../03-scaling-to-n.md`. For the cross-domain translation application properties, see `./00-overview-CDT.md`. This document introduces no new mechanics or terminology.

---

## What N Means in the Translation Domain

In the general test, N is the number of independently formalized domains. In the translation domain, N is the number of independently constructed systems between which structural translation is expected to operate.

N=1 is a single system. No translation is possible or necessary.

N=2 is two systems. Translation is pairwise. One mapping set is required. The structural properties of both systems can be directly compared. This is the minimum threshold for testing translation.

N=3 introduces triangulation. Structural correspondences visible between systems A and B, and between A and C, may predict correspondences between B and C before they are directly observed. The architecture's properties begin to function as a shared reference frame rather than a pairwise bridge.

At higher N, translation becomes a network problem. The number of pairwise mappings grows as N(N-1)/2, but if the architecture provides a shared structural layer, the mapping complexity need not grow pairwise. Each system maps to the architectural properties once, and translation between any two systems operates through that shared layer.

The test is therefore: as N increases, does the architectural layer remain sufficient as the shared reference frame for translation, or does it degrade, producing false equivalences, losing distinctions, or requiring supplementary conventions?

---

## What the Architecture Must Preserve Across Translation Pairs

### Derivation as Entry and Exit Gate

Every structure entering the translation process must be derivable in its source system. Every structure produced by the translation process must be derivable in its target system. At N=2, this is a single validation at each end. At higher N, derivation must remain tractable across systems with increasingly different primitive inventories and composition rules.

The test: does derivation remain a reliable gate as the structural distance between source and target systems increases? Can a structure from a system with five substrates and twenty kinetic forces be validated against a system with twelve substrates and eight kinetic forces without the derivation process becoming ambiguous or underdetermined?

### Compression as Canonical Intermediary

Translation operates on irreducible centers rather than fully articulated structures. At N=2, two compression algorithms (one per system) must both produce well-defined canonical forms. At higher N, every system in the network must produce irreducible centers that are comparable at the architectural level.

The test: do irreducible centers from structurally different systems remain comparable? As N increases, does the architectural level of comparison (role class arrangement, orientation relationships, closure conditions) provide enough resolution to distinguish structures that are genuinely different, or does increasing system diversity cause architecturally distinct structures to appear equivalent at the compressed level?

### Reconstruction as Fidelity Guarantee

After mapping, the translated structure must reconstruct in the target system without external information. At N=2, reconstruction draws on one target system's rules. At higher N, the same mapped structural description must be reconstructable in any target system that shares the relevant architectural properties.

The test: does reconstruction remain deterministic as target systems become more diverse? Can a single architectural-level structural description reconstruct correctly in systems with very different primitive inventories, or does the description become underdetermined when the target system offers multiple structurally valid reconstructions?

### Self-Interpretation Across System Boundaries

Within one system, structures are self-interpreting (Axiom 3). Across system boundaries, self-interpretation depends on the receiving system sharing the same architectural properties. At N=2, this is a bilateral condition. At higher N, every system in the network must share the same architectural properties for the self-interpretation guarantee to hold.

The test: is the architecture's property set sufficient to guarantee self-interpretation across all system boundaries, or do some system pairs require additional shared conventions beyond the architectural properties?

### Domain-Scoped Operation in Translation Context

Every system in the network must maintain domain-scoped operation: kinetic forces act within substrate domains, and that scoping is determinable from structure alone. Translation must preserve this scoping relationship. A structure whose operations are domain-scoped in the source must remain domain-scoped in the target.

The test: as systems become more diverse, does the domain-scoping relationship translate cleanly? If the source system has five substrate domains and the target has twelve, does the scoping relationship map at the architectural level (operations are scoped to domains) even when the specific domains are incommensurable?

---

## The Translation-Specific Scaling Sequence

### Stage 1: No Translation (N=1)

A single system. Translation is not applicable. The architecture's generative and compression capabilities are tested but not its interoperability.

### Stage 2: Pairwise Translation (N=2)

Two independently constructed systems. Translation operates through the four-step process: derive, compress, map, reconstruct. This stage tests:

Whether irreducible centers from both systems are comparable at the architectural level. Whether structural correspondences can be identified without reference to specific primitives. Whether gaps between the two systems are identifiable and annotatable. Whether round-trip translation (A→B→A) recovers the original structure or produces detectable degradation.

This stage has not been demonstrated. It is the immediate next test for the translation domain.

### Stage 3: Triangulation (N=3)

Three systems. Translation is no longer purely pairwise. Structural correspondences discovered between A-B and A-C can predict correspondences between B-C. This stage tests:

Whether the architectural layer functions as a genuine shared reference frame rather than a pairwise bridge. Whether predicted correspondences between B-C (inferred from A-B and A-C mappings) match actual correspondences when B-C translation is performed directly. Whether triangulation reduces the total mapping effort compared to exhaustive pairwise mapping.

Triangulation is the first test of whether the architecture enables structural inference rather than just structural translation.

### Stage 4: Network Effects (N=5 to N=20)

Multiple systems forming a translation network. Each new system maps to the architectural properties once, though the complexity of that mapping may increase as the system's structural distance from previously mapped systems grows. Translation between any two systems operates through the shared layer. This stage tests:

Whether the shared architectural layer scales sublinearly. At N=20, exhaustive pairwise mapping requires 190 mapping sets. If the architecture provides a sufficient shared layer, each system requires one mapping to the architecture, and translation operates through the shared layer. Whether the quality of translation degrades as the network grows — whether structures passing through the shared layer lose resolution with each additional system in the network. Whether structural clustering emerges: groups of systems that translate with high fidelity within the cluster and lower fidelity between clusters. Clustering would reveal which architectural properties are broadly shared and which are domain-specific.

### Stage 5: Saturation (N approaching asymptote)

At very high N, the question becomes whether the architectural layer continues to provide a meaningful shared reference frame, or whether the diversity of systems causes the shared layer to become so abstract that it loses discriminating power.

The risk at this stage is that the architectural properties — role class arrangement, orientation, closure, superposition — become insufficient to distinguish structures that are genuinely different across highly diverse systems. If two very different source structures produce the same architectural-level description, the shared layer has lost resolution.

The asymptote for the translation domain may be the set of all system pairs whose structural overlap is sufficient for meaningful mapping through architectural properties alone. System pairs with minimal structural overlap may require additional conventions or may simply fall below a useful fidelity threshold. Identifying this threshold is a key open question.

---

## Translation-Specific Pressure Points

### Gap Accumulation

At N=2, gaps between two systems are finite and manageable. At higher N, the total number of gaps across all system pairs grows rapidly. The question is whether gaps remain informative (precise maps of structural differences) or become overwhelming (so numerous that they obscure the correspondences).

The architecture treats gaps as first-class information. The test is whether this treatment scales: can a translation network with hundreds of annotated gaps per system pair remain usable, or does gap management become a bottleneck?

### False Equivalence Under Compression

Two structures from different systems may compress to irreducible centers that appear equivalent at the architectural level but differ in ways that only their respective full articulations reveal. At N=2, this risk is contained because the two systems can be studied in detail. At higher N, false equivalences may propagate: a structure in system A is mapped to a structure in system B through a false architectural equivalence, and that structure in B is then mapped to a structure in system C, compounding the error.

The test is whether the architecture's canonical forms are fine-grained enough to prevent false equivalence chains, or whether additional verification mechanisms are needed at each translation step.

### Fidelity Variance Across the Network

Translation fidelity is a property of each system pair. At higher N, the network will contain pairs with high fidelity and pairs with low fidelity. The question is whether fidelity can be predicted from architectural properties alone (before translation is attempted), or whether fidelity can only be determined empirically (after translation is tested).

If fidelity is predictable from architecture, the network can be planned rationally. If fidelity is only empirical, scaling requires exhaustive testing of every pair.

### Reconstruction Ambiguity in Rich Target Systems

A target system with a large primitive inventory and flexible composition rules may admit multiple valid reconstructions from a single architectural-level structural description. At N=2, this ambiguity can be resolved by examining the target system in detail. At higher N, resolution becomes harder because the translation process must handle multiple target systems simultaneously.

The test is whether the architecture's structural descriptions are constraining enough to produce unique reconstructions in most target systems, or whether reconstruction ambiguity becomes the norm as target systems grow richer.

### Convention Pressure

As N increases, independent system designers may adopt implicit conventions that are not part of the architecture but that make their systems more compatible with the translation network. If these conventions become necessary for practical translation, the architecture's claim that shared architectural properties are sufficient for translation is weakened.

The test is whether translation remains convention-free at all values of N, or whether practical interoperability requires conventions beyond the architecture.

---

## Necessary Conditions for Passing (Translation Domain)

The architecture passes the translation-domain scaling test only if:

**The architectural layer scales sublinearly.** Adding a new system to the network does not require pairwise mapping against every existing system. One mapping to the architectural properties is sufficient for translation to any other system in the network.

**Irreducible centers remain discriminating at higher N.** Canonical forms from diverse systems remain distinguishable at the architectural level. The shared layer does not lose resolution as the number of systems increases.

**Round-trip translation remains verifiable.** A structure translated from system A to system B and back to system A can be verified against the original through derivation at every value of N.

**Gaps remain informative and manageable.** Gap annotation scales with the network without becoming a bottleneck or obscuring the correspondences it is meant to complement.

**No conventions beyond architectural properties are required.** Translation operates through shared structural properties alone at every value of N. If supplementary conventions become necessary, they must be identified explicitly as extensions beyond the architecture.

**Triangulation produces valid predictions.** Structural correspondences inferred from multi-system comparison match actual correspondences when verified directly. If inference fails systematically, the architectural layer does not support structural prediction.

---

## Failure Conditions (Translation Domain)

The architecture fails the translation-domain scaling test if:

**The shared layer loses discriminating power.** Irreducible centers from structurally different systems become architecturally indistinguishable at higher N. The canonical forms are too coarse to support meaningful translation.

**False equivalences propagate.** A false architectural correspondence between two systems cascades through the network, producing compounding errors in third-party translations.

**Reconstruction becomes systematically ambiguous.** Most target systems admit multiple valid reconstructions from a single architectural description, and the architecture provides no structural means of selecting among them.

**Gap volume overwhelms correspondence.** At higher N, the gaps between system pairs become so numerous that the correspondences they surround are no longer practically useful.

**Fidelity becomes unpredictable.** The architecture provides no basis for estimating translation fidelity between a given system pair before translation is attempted. Every pair must be tested exhaustively.

**Convention dependence emerges.** Practical translation requires shared conventions beyond the architectural properties. The architecture alone is insufficient for interoperability.

---

## Open Questions

**Does sublinear scaling actually hold?** The architecture theoretically provides a shared reference frame that each system maps to once. Whether this produces genuine sublinear scaling in practice, or whether the architectural mapping itself becomes increasingly complex at higher N, is untested.

**Is triangulation reliable?** Structural inference across three or more systems has not been tested. Whether predicted correspondences are accurate, approximately accurate, or unreliable is unknown.

**What is the fidelity floor?** For any given system pair, there is some minimum fidelity below which translation is not useful. Whether the architecture can predict or estimate this floor from structural properties alone is an open question.

**Can false equivalences be detected before they propagate?** If two structures from different systems produce the same architectural description but differ meaningfully, is there a structural test that catches this before the false equivalence enters the translation network?

**Does the architecture support incremental network growth?** Can a new system be added to an existing translation network without disrupting existing translations, or does each addition require revalidation of existing mappings?

**What is the asymptote?** The translation domain may have a natural limit: the set of system pairs whose structural overlap exceeds a minimum fidelity threshold. Identifying this limit, and whether it is a property of the architecture or a property of the system pair, is a major open question.

---

## Status

The architecture provides the structural properties that cross-domain translation requires: derivation, canonical compression, deterministic reconstruction, self-interpretation, and domain-scoped operation. The theoretical translation model is consistent with the architecture.

No translation between two independently constructed systems has been performed. No pairwise mapping has been tested. No triangulation has been attempted. The claims in this document are theoretical projections based on the architecture's properties, not demonstrated capabilities.

The architecture is designed to support cross-domain structural translation at arbitrary N. Whether it does so in practice is the test this document defines. The honest position is the same as the general scaling document: designed for universality, not yet proven.