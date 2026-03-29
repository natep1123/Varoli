# 06 — Verb Layering

*Last Updated: March 27, 2026*

**Status:** Canonical unless broken
**Layer:** Ground 4 / Grammar-Architecture
**Authority:** Structural
**Scope:** Defines verb layering as a formal structural extension in Varoli, formalizes suffix qualification of kinetic force, and states open questions around admissibility, stacking depth, and morphemic licensing.

---

## 1. Purpose

This document defines verb layering as a named structural mechanism in Varoli.

Verb layering is the operation by which a consonant suffix qualifies the kinetic force of a primitive directional form without replacing the force, without changing the form's structural category, and without altering terminal behavior. It is a grammar-level extension under active test. It is not among the named structural patterns in core generation rules and is not yet formally licensed at that level. It is motivated by existing structural properties and is consistent with all tested cases.

Three consonant suffixes have been tested and are documented here. Two-deep stacking is also attested. The mechanism is strong enough to guide downstream work, but the full suffix inventory and formal morphemic licensing remain open.

Primitive-level implementation is handled in downstream canonical and grammar documents.

---

## 2. Why the Language Needs This Category Now

The primitive directional system establishes a set of bare kinetic forces. Each bare force carries a specific mode of operation. Without a mechanism for qualifying those forces, the language has no native way to express how the same mode of operation can be completed, sustained, opposed, or otherwise shaped without introducing a new primitive class or importing grammatical categories from other languages.

Verb layering provides that mechanism. It extends the existing kinetic system through qualification rather than through new primitives. This gives the language productive growth capacity within the existing architecture.

The mechanism also grounds what would otherwise be described using tense or aspect terms imported from natural language grammar. Temporal and aspectual readings arise from the invariant functions of the suffix consonants, not from imported categories. The note preserves that grounding throughout.

---

## 3. Strongest Current Definition

**Verb layering** is the operation by which one or more consonant suffixes follow a primitive directional form, each contributing its invariant kinetic function as a qualification of the preceding force.

The result is a compound force: the original kinetic mode, qualified by the suffix's invariant function. The base form determines the directional character of the force relative to domain. Each suffix qualifies what has already been established by everything to its left.

Layered verbs are not among the named structural patterns in core generation rules. The mechanism is provisionally supported by testing and structural motivation. Formal licensing at the generation-rule level is a required next step, not yet taken.

---

## 4. Core Mechanism

### 4.1 Structure

**Single-suffix layering:** `CV + C` (e.g., `vek`) or `VC + C` (untested; see Section 10)

**Multi-suffix layering:** `CV + C + C` (e.g., `vekp`; tested at two-deep only)

### 4.2 How the mechanism works

Each consonant has an invariant function. Function does not change with position. A consonant appearing after a primitive directional form therefore contributes its invariant function to the composition.

The suffix consonant does not occupy a vowel position and does not define a new substrate domain. The best current structural reading is that the suffix qualifies the preceding kinetic force rather than establishing an independent force-domain relationship. This reading is consistent with all tested cases.

The positive mechanism by which a bare consonant following a CV form qualifies rather than independently acts has not been formally derived. The qualification reading is the least assumption-laden interpretation available given the architecture. It is not yet a closed derivation.

### 4.3 Order significance

Suffix order is provisionally meaningful. Each suffix qualifies the result of everything to its left.

`vekp`: the force `ve` is first qualified by `k` (completion), producing `vek`; `vek` is then qualified by `p` (ongoing pressure), producing individuation-completed-under-pressure. The completed form, held under weight.

`vepk`: the force `ve` is first qualified by `p` (ongoing pressure), producing `vep`; `vep` is then qualified by `k` (completion), producing individuation-under-pressure-completed. The pressurized form, brought to threshold.

These are structurally distinct readings under the qualification interpretation. Order significance is strongly suggested by the architecture: arrangement carries structural meaning, and each suffix qualifies a distinct input depending on its position. Reversed suffix pairs have not yet been independently contrast-tested in context. This should be treated as a near-term test priority.

---

## 5. Relation to Qualification

Suffix layering is an instance of suffix qualification as defined in `02-g4-qualification.md`.

The definition of qualification applies directly: one primitive contributes its invariant function as a specification of another primitive's structural role, without replacing the qualified element, without merging class identities, and without altering the qualified element's own invariant function.

In verb layering:

- the qualifier is a consonant suffix
- the qualified element is the preceding kinetic force
- the qualifier adds resolution: the original mode of operation is narrowed by the suffix's kinetic function
- the qualified force retains its identity: `ve` in `vek` is still individuation-originating-from-self
- the result is richer than either alone: individuation-with-completion is not the same as individuation, but it is not a new independent force either

Suffix order significance follows directly from the qualification architecture: each suffix operates on the already-qualified result of everything to its left. The input to each successive qualifier is the compound result of prior qualification. This is not a separate claim about verb layering specifically. It is a consequence of how qualification composes.

The suffix does not predicate. It does not modify in the English grammatical sense. It does not introduce a new force-domain relationship. It qualifies an existing kinetic force by contributing its own invariant kinetic function to the specification of that force.

---

## 6. Relation to Terminal Behavior

Force qualification through suffix layering has not changed terminal behavior in any tested case. This is an observational result, not a derived rule.

A layered verb projects the same way a bare verb does. The suffix qualifies the force without providing a stable domain to absorb it. In the current architecture, a layered verb terminates in its final suffix consonant, which is a bare kinetic. All tested bare kinetic terminals have projected.

Consequence: a resolution unit ending in a layered verb is a projecting unit. It emits its compound force beyond its boundary. Terminal behavior is not determined by whether the force is qualified. It is determined by the structural character of the terminal element. A bare kinetic terminal projects regardless of what precedes it.

Whether this observational result follows necessarily from the architecture or holds only in currently tested cases is a remaining open question. No structural argument has been derived that makes it impossible for a suffix to change terminal behavior. The result is strong but not yet formally closed.

---

## 7. Relation to Chaining

### 7.1 Projection

A layered verb projects compound force. In all tested cases, the compound force is not decomposed during projection. No current rule strips suffix qualifications at a unit boundary. No mechanism separates the base form from its suffixes during transit. The architecture provisionally preserves compound forces during projection because function is invariant and no decomposition rule exists. This is currently an absence-of-decomposition result, not a fully derived positive rule of compound-force preservation.

### 7.2 Deep reception

The compound force provisionally resolves within a receiving stable domain through the containment relation (defined in `01-g4-containment.md`): kinetic force within substrate domain. The containment relation does not distinguish simple from compound forces in its current formulation. It operates on role class, not on internal force composition.

This is provisionally supported at the same level as deep reception generally. Cross-boundary verification remains weaker than within-form confirmation. Whether compound forces behave identically to simple forces under cross-boundary containment is assumed by the current architecture but not independently verified.

### 7.3 Inter-force readability

When a compound (qualified) force and a bare force both resolve within a shared stable domain, the qualification asymmetry between them is readable. One force is qualified; the other is bare. This produces a distinguishable pair even when both forces share the same orientation. Whether qualification asymmetry constitutes a governance mechanism beyond readability is an open question addressed in `05-g4-resolution-unit-chaining.md` Section 6.3.

---

## 8. What Verb Layering Explains Already

### 8.1 Attested suffix functions

Three consonant suffixes have been tested. Each is documented with its invariant function and its effect as a qualifier.

**`-k` (completion)**

Invariant function: forceful crossing, threshold rupture, completion through impact.

As qualifier: marks the force as having crossed its threshold. The mode of operation described by the base form is completed or realized through rupture. The force arrives at the other side of its own motion.

Attested: `vek` (individuation-with-completion). The compound force projects in `e vek` and provisionally resolves within `aVa` in both tested complex-composition patterns (see `05-g4-resolution-unit-chaining.md` Section 9.2). Qualification survives projection in all tested cases.

**`-p` (ongoing pressure)**

Invariant function: inward compressive force, weight without release, sustained density.

As qualifier: marks the force as under ongoing pressure. The mode of operation is compressed, sustained, held without release. The force continues under its own weight.

Attested: `vep` (individuation-under-pressure). The self that individuates while held under compression.

**`-d` (force opposition)**

Invariant function: opposing contact force, meeting an incoming force and holding ground rather than yielding.

As qualifier: marks the force as carrying internal opposition. The mode of operation proceeds but carries its own counter-force. The force acts against itself while still acting. This is negation-adjacent: the force is not negated, but it is internally opposed.

Attested: `ved` (individuation-with-resistance). The self that individuates against opposition.

### 8.2 Two-deep stacking

`vekp` (individuation-completed-under-pressure) is the strongest attested multi-suffix form. Two-deep stacking composes without producing contradictions or unclassifiable terminal states. The mechanism extends naturally from single-suffix layering under the qualification architecture.

### 8.3 Negation-adjacent result

`-d` provides a route toward negation-adjacent expression through force opposition. A separate route exists through operator-mediated suspension (terminal `y`). The strongest current negation-adjacent result combines both: a force qualified by opposition, whose resolution with a subsequent domain is suspended by the operator. Both mechanisms are available. Whether they are collectively sufficient for all negation needs is an open question addressed in Section 10.

### 8.4 Route toward temporal and aspectual expression

The invariant functions of the three attested suffixes produce readings that are structurally analogous to completion (`-k`), ongoing or durative aspect (`-p`), and adversative or resistant aspect (`-d`). These readings arise from the suffix consonants' own invariant functions, not from imported tense or aspect categories. The note preserves that grounding. Temporal and aspectual expression in Varoli is a downstream grammatical application of the layering mechanism, not a primary structural category.

---

## 9. What Verb Layering Is Not

**Not a new primitive class.** Suffix consonants are kinetic class primitives with invariant functions. No new role class is introduced. The layered form is a composition of existing primitives, not a new type of element.

**Not independent new verbs.** The suffix does not establish its own force-domain relationship. `vek` is not two verbs. It is one compound force: individuation qualified by completion. The suffix qualifies the existing force rather than acting independently alongside it.

**Not modification in the English grammatical sense.** English adverbs or verb modifiers are defined by syntactic position and dependency rules. Suffix qualification in Varoli is class-based and compositional: the suffix contributes its invariant kinetic function to the specification of the preceding force, governed by the qualification architecture.

**Not predication.** The suffix does not assign a property to the force. It qualifies the force by contributing its own kinetic function to the specification of the force's mode of operation.

**Not a full tense system.** Temporal and aspectual readings arise from the suffix functions as a downstream grammatical consequence. Verb layering is not the import of a tense system. It is a structural qualification mechanism whose outputs can be applied toward temporal and aspectual expression.

**Not formally licensed at the generation-rule level.** Layered forms are not among the named structural patterns in core generation rules. The mechanism is structurally supported by testing and current architecture. Formal morphemic licensing at the generation-rule level remains a required next step.

---

## 10. Open Questions

### 10.1 Suffix admissibility

Three general consonant suffixes have been tested. Whether all consonants can function as suffixes by the same mechanism is not established. No prohibition against additional consonant suffixes has been derived. No positive admission rule has been derived either. Expansion by individual testing is the recommended approach.

Attractor consonants (`v`, `l`, `r`, `m`) carry elemental affinity in addition to invariant kinetic function. Whether elemental affinity produces qualitatively different suffix behavior from general consonant suffixes is untested and must not be assumed.

### 10.2 Operator as suffix

Whether `y` can function as a suffix is structurally ambiguous. The operator is not a consonant. Its positional behavior differs from consonants. A terminal `y` on a verb may be indistinguishable from a terminal operator producing suspension. This question intersects with the open operator-scope question and is not resolved here.

### 10.3 VC-base layering

All attested layered forms use a CV base. Whether VC verbs accept suffixes by the same mechanism is untested. Whether reversed directionality produces a different compositional relationship is an open structural question.

### 10.4 Suffix order contrast testing

Suffix order significance is strongly suggested by the qualification architecture and by the invariant-function constraint, but reversed suffix pairs have not been independently contrast-tested. This is the highest-priority near-term test for the layering mechanism.

### 10.5 Stacking depth

No structural constraint on stacking depth has been derived. No stacking beyond two-deep has been tested. Whether deeper stacking remains interpretable or produces diminishing structural returns is an open empirical question.

### 10.6 Formal morphemic licensing

Layered forms are not among the named structural patterns in core generation rules. Whether verb layering is formally licensed by expanding those rules or by establishing grammar-level composition rules that govern how named patterns extend is not yet resolved. This is the most significant structural gap in the current formalization.

### 10.7 Full negation

Whether the negation-adjacent mechanisms documented in Section 8.3 are collectively sufficient for all negation needs, or whether a dedicated negation mechanism is required, remains open. Resolution depends on operator scope (unsettled) and on the range of negation-like constructions the language will need to support.

---

## 11. Propagation Targets

**Immediate:**
- Add verb layering and suffix qualification to `../../Ground-2/00-g2-varoli-terminology.md` with the definition from Section 3 and the three attested suffix functions.
- Update `../../Ground-2/01-g2-varoli-conceptual-overview.md` to reflect current status.

**Short-term:**
- Revise any downstream document describing suffix behavior in local informal language; replace with explicit reference to suffix qualification as defined in `02-g4-qualification.md` and this document.
- Propagate the qualification-survives-projection result into any downstream grammar or chaining documents that address compound force behavior at unit boundaries.

**Test:**
- Construct reversed suffix pairs and contrast-test whether order produces distinct readings in context. This is the highest-priority open test (Section 10.4).
- Test VC-base layering to determine whether the mechanism holds under reversed directionality (Section 10.3).
- Test individual untested consonants as suffixes and verify whether the qualification reading holds (Section 10.1).

**Investigate:**
- Formal morphemic licensing at the generation-rule level (Section 10.6).
- Whether operator qualification is structurally possible and what it would produce (Section 10.2).
- Whether attractor consonants in suffix position behave differently from general consonant suffixes (Section 10.1).