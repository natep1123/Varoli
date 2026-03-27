# 07 — Verb Layering

**Status:** Provisional grammar formalization. This document captures the tested and provisionally supported mechanics of consonant-suffix verb layering. It does not generalize beyond attested cases. Weaker elements and open questions are explicitly marked.

---

## 1. Purpose

This document documents the current state of verb layering: the provisional mechanism by which consonant suffixes qualify the kinetic force of a primitive verb without changing its structural category or terminal behavior.

The core generation rules (`../core/06-generation-rules.md`) currently name CV, VC, and palindromic forms as valid structural patterns. Layered verbs (CV+C, CV+CC) are not among these named patterns. Verb layering is therefore a grammar-level extension under test, not a settled consequence of locked core rules. It is motivated by existing structural properties - consonant invariant function, the containment relationship, and directionality encoding - but its formal licensing depends on either expanding the core generation rules or establishing grammar-level composition rules that govern how named patterns extend. Neither step has been taken. This document treats the mechanism as provisionally supported by testing and structural motivation, pending that formal step.

No new primitives or operators are introduced.

For the primitive verb system, see `01-primitive-verbs.md` and `02-primitive-verbs-extended.md`. For the chaining architecture, see `06-resolution-unit-chaining-and-complex-sentences.md`. For the invariant function of each consonant, see `../core/05-phonemic-schemas.md`.

---

## 2. The Layering Mechanism

A layered verb is a primitive verb (CV or VC) followed by one or more consonant suffixes. The suffix consonant's invariant function qualifies the verb's kinetic force. The result is a compound force: the original verb's motion, qualified by the suffix's motion.

The base verb determines the directional kinetic form of the force relative to domain. The suffix determines how that force is qualified - whether it is completed, pressurized, opposed, or otherwise shaped by the suffix consonant's invariant function.

### Structure

**Single-suffix layering:**

CV + C (e.g., `vek`) or VC + C (e.g., `avk` - untested, see Section 8)

**Multi-suffix layering:**

CV + C + C (e.g., `vekp`) - tested at two-deep only

### Structural motivation

The current best structural reading of how the mechanism works:

1. Each consonant has an invariant function (from `../core/05-phonemic-schemas.md`).
2. Consonant function does not change with position (Axiom 2: function is invariant).
3. A consonant appearing after a CV verb therefore contributes its invariant function to the form.
4. The suffix consonant does not occupy a vowel position and therefore does not define a new domain.
5. The best current reading is that the suffix qualifies the preceding kinetic force rather than establishing an independent force-domain relationship. This reading is consistent with the tested cases but is not a fully resolved derivation. The positive mechanism by which a bare consonant following a CV verb qualifies rather than independently acts has not been formally derived. It is the least assumption-laden reading available.

The suffix is not treated as a separate verb. The compound `vek` is read as the force `ve` (self-originating projection into individuation) qualified by `k` (forceful crossing, completion, threshold), producing individuation-with-completion. This reading is consistent across all tested cases but depends on the qualification interpretation described in point 5 above.

---

## 3. Attested Suffixes

Three consonant suffixes have been tested. Each is documented below with its invariant function, its effect as a suffix, and the forms in which it has been attested.

### -k (Hard Threshold / Completion)

**Invariant function:** Forceful crossing force. The quality of motion that ruptures or severs a boundary through impact.

**As suffix:** Marks the verb's force as having crossed its threshold. The mode of existence or interaction described by the verb is completed, realized, or arrived at through rupture.

**Attested forms:**
- `vek` - individuation-with-completion. Self-originating projection into individuation, qualified by threshold crossing. The self that has become.
- `vek` in complex sentence: `e vek` | `a va aVa` (Pattern 1), `e vek` | `a av aVa` (Pattern 2). In both patterns, the compound force projects across the unit boundary and resolves within the receiving domain through deep reception. The qualification survives projection.

**Provisional temporal/aspectual reading:** Completed action. The threshold has been crossed. This is a structurally grounded analogue to past completion, derived from `k`'s invariant function rather than imported as a tense category.

### -p (Compression / Ongoing Pressure)

**Invariant function:** Inward compressive force. The quality of motion that presses toward a center, adding weight or density without releasing.

**As suffix:** Marks the verb's force as under ongoing pressure. The mode of existence or interaction described by the verb is compressed, sustained under weight, held without release.

**Attested forms:**
- `vep` - individuation-under-pressure. Self-originating projection into individuation, qualified by compression. The self held under weight.

**Provisional temporal/aspectual reading:** Ongoing or sustained action. The pressure continues. This is a structurally grounded analogue to progressive or durative aspect, derived from `p`'s invariant function.

### -d (Resistance / Force Opposition)

**Invariant function:** Opposing contact force. The quality of motion that meets an incoming force and holds its ground rather than yielding.

**As suffix:** Marks the verb's force as carrying internal opposition. The mode of existence or interaction described by the verb is resisted from within. The force proceeds but carries its own counter-force.

**Attested forms:**
- `ved` - individuation-with-resistance. Self-originating projection into individuation, qualified by opposition. The self that individuates against opposition.

**Negation-adjacent contact point:** The `-d` suffix does not negate the verb. It produces a force that carries internal opposition. The force still resolves if it reaches a stable domain. The result is negation-adjacent but not negation. For the relationship between `-d`, operator-mediated suspension, and the open question of full negation, see Section 7.

---

## 4. Multi-Suffix Stacking

Two-deep suffix stacking has been tested. The attested form is `vekp`: individuation-with-completion-under-pressure.

### Order significance

Suffix order is provisionally meaningful. Each suffix qualifies the result of everything to its left:

- `vekp`: the force `ve` is first qualified by `k` (completion), and the result `vek` is then qualified by `p` (ongoing pressure). Individuation that has completed, now held under pressure. The completed self, compressed.
- `vepk`: the force `ve` is first qualified by `p` (ongoing pressure), and the result `vep` is then qualified by `k` (completion). Individuation under pressure that has crossed its threshold. The pressurized self, completed.

These are structurally distinct readings under the qualification interpretation. The distinction is consistent with the principle that arrangement carries meaning (Generation Rule 3, directionality is structural). Position within the suffix chain determines the scope of each qualification.

**Support level:** Suffix order significance is strongly suggested by the architecture but has not been independently contrast-tested with reversed suffix pairs producing demonstrably different readings in context.

### Depth limit

Stacking beyond two-deep has not been tested. The architecture does not prohibit it. Whether deeper stacking remains interpretable is an open empirical question, not a structural constraint.

---

## 5. Interaction with Terminal Behavior

Verb layering has not changed terminal behavior in any tested case. This is an observational result across all forms tested, not a derived rule.

A layered verb (CV+C or CV+CC) has projected the same way a bare verb (CV) does in every case tested. The suffix qualifies the force but does not provide a stable domain to absorb it. In the current architecture, a layered verb terminates in its final suffix consonant, which is a bare kinetic. In all tested cases, such terminals project.

Consequence for resolution units: a resolution unit ending in a layered verb is a projecting unit. It emits its compound force beyond its boundary. The chaining architecture governs what happens next (resolution, suspension, or continuation) exactly as it does for bare verbs.

**Tested cases:**
- `e vek` projects. Terminal is `-k`, a bare kinetic. The unit is structurally open.
- `e vek` | `a va aVa` - the projected compound force `vek` provisionally resolves within `aVa` through deep reception. Qualification provisionally survives projection and reception.

---

## 6. Interaction with the Chaining Architecture

In the tested cases, verb layering composes with the resolution-unit chaining architecture without producing contradictions or unclassifiable terminal states. Force qualification and compositional trajectory provisionally operate as distinct interacting axes. Whether this holds across all untested combinations remains open.

### Projection

A layered verb projects compound force. In the tested cases, the compound is not decomposed during projection. No current rule strips suffix qualifications. No current mechanism separates the base verb from its suffixes at the unit boundary. The architecture provisionally preserves compound forces during projection because function is invariant and no rule targets compound structure. This is a negative claim: no decomposition rule exists. It is not a positive rule guaranteeing compound preservation.

### Deep reception

The compound force provisionally resolves within a receiving domain's stable palindromic noun through the containment relationship (kinetic within substrate). The containment relationship does not distinguish simple from compound forces in its current formulation. It operates on role class: kinetic force within substrate domain, regardless of the force's internal composition.

This is provisionally supported at the same level as deep reception generally. Cross-boundary verification remains weaker than within-form verification. Whether compound forces behave identically to simple forces under cross-boundary containment is assumed by the current architecture but not independently verified.

### Inter-force governance

When a compound (layered) force and a bare force both resolve within a shared domain, the qualification asymmetry between them is readable. One force is qualified; the other is bare. This produces a distinguishable pair even when both forces share the same orientation.

Whether qualification asymmetry constitutes a governance mechanism beyond readability is an open question.

---

## 7. Negation-Adjacent Contact Point

The `-d` suffix intersects with the broader question of negation in Varoli. This section documents the contact point without resolving the negation question.

### Suffix path: force opposition

`ved` (individuation-with-resistance) produces a verb whose force carries internal opposition. The force is not negated. It is opposed from within. If the force reaches a stable domain, it resolves - but the resolution carries the quality of opposition. The result is negation-adjacent: a force that acts against itself while still acting.

### Operator path: resolution suspension

`e ve y` produces a resolution unit where the verb's force is suspended at the terminal by the operator. The force and the operator are both present, but the resolution relationship between verb and any subsequent domain is held in superposition. This is documented in `06-resolution-unit-chaining-and-complex-sentences.md`, Section 3 (Suspend).

The operator path depends on operator scope, which is not settled in cross-boundary contexts. This path is provisionally supported but structurally weaker than the suffix path.

### Combined: strongest negation-adjacent result

`e ved y oRo` (attested in development testing) combines both mechanisms. The verb carries internal opposition (`-d`) and its resolution with the noun is suspended by the operator (`y`). The force opposes itself and its relationship to the receiving domain is unresolved. This produces the strongest negation-adjacent result currently available in the architecture.

Whether this combined form, the suffix path alone, the operator path alone, or some other mechanism is sufficient for all negation needs remains an open question. This document does not resolve it. The negation question depends on operator scope (unsettled) and on whether the architecture requires a dedicated negation mechanism or can derive negation from existing primitives.

---

## 8. Open Questions

### Suffix admission

Which consonants may serve as suffixes? The three attested suffixes (`-k`, `-p`, `-d`) are all general consonants. Whether all 17 general consonants can function as suffixes is not tested. Whether the 4 attractor consonants can function as suffixes is a separate open question and has not been structurally derived here. Whether the operator can function as a suffix is a structurally distinct question (see below) - the operator is not a consonant and must be considered separately.

A general suffix-admission rule (e.g., "any consonant may suffix any verb") is not formalized here. No prohibition against additional consonant suffixes has been derived, but no positive admission rule has been derived either. Every consonant has an invariant function, and that function would qualify the preceding verb by the same mechanism under the current structural reading. Whether this generalization holds must be verified by testing individual cases and confirming that the mechanism produces interpretable, non-contradictory results.

**Status:** Open. No admission rule formalized. Expansion by individual testing recommended.

### VC-base layering

All attested layered forms use a CV base verb. Whether VC verbs accept suffixes by the same mechanism (`avc`, `avk`, etc.) is untested. The structural question is whether a suffix consonant following a VC form qualifies the verb's force in the same way it qualifies a CV form's force, or whether the reversed directionality of VC produces a different compositional relationship.

**Status:** Open. Not tested.

### Suffix order contrast-testing

The claim that suffix order is meaningful is strongly suggested by the architecture but not yet independently verified through contrast-tested pairs producing demonstrably different contextual readings.

**Status:** Open. Strongly suggested, not contrast-tested.

### Stacking depth limit

No structural constraint on stacking depth has been derived. No stacking beyond two-deep has been tested. Whether deeper stacking remains interpretable or produces diminishing structural returns is unknown.

**Status:** Open. Empirical question.

### Attractor consonants as suffixes

The four attractor consonants (`v`, `l`, `r`, `m`) carry elemental affinity in addition to their invariant kinetic function. Whether elemental affinity produces a qualitatively different suffix behavior is untested. The structural question is whether an attractor consonant in suffix position contributes only its kinetic function (as general consonants appear to) or whether its elemental affinity also participates in the qualification. This question cannot be resolved without testing specific attractor-suffix forms and examining whether the result differs structurally from general-consonant suffixes.

**Status:** Open. Theoretically distinct from general consonant suffixes but not tested.

### Operator as suffix

Whether `y` can function as a suffix (producing forms like `vey`) is structurally ambiguous. The operator is not a consonant. Its positional behavior is defined differently from consonants (see `../core/05-phonemic-schemas.md`). A terminal `-y` on a verb may be indistinguishable from a terminal operator producing suspension. This question intersects with operator scope and is not resolved here.

**Status:** Open. Intersects with operator scope.

### Morphemic boundary

How verb layering relates to the broader morphemic composition system (how forms grow beyond CV/VC and VCV) is not addressed here. Verb layering is a specific instance of consonant composition within verbs. The general rules for consonant clustering, morphemic boundaries, and form growth are a separate open grammar question.

**Status:** Deferred to morphemic composition rules.

### Full negation

Whether the negation-adjacent mechanisms documented in Section 7 are collectively sufficient for all negation needs, or whether a dedicated negation mechanism is required, remains open. Resolution depends on operator scope (unsettled) and on the range of negation-like constructions the language will need to support.

**Status:** Open. Not resolved in this document.

---

## Summary

**Attested results.** Three consonant suffixes have been tested as verb qualifiers: `-k` (completion), `-p` (ongoing pressure), `-d` (force opposition). Two-deep suffix stacking has been tested (`vekp`). In all tested cases, layered verbs have projected the same way bare verbs do - terminal behavior has not changed under layering. The `-d` suffix produces a negation-adjacent contact point (force opposition, not full negation).

**Provisional claims.** Verb layering is a grammar-level extension under test; layered forms (CV+C, CV+CC) are not among the named patterns in the core generation rules and are not yet formally licensed. The current best structural reading is that the suffix qualifies the preceding force rather than acting independently; this reading is consistent with all tested cases but is not a fully resolved derivation. Suffix order is provisionally meaningful but not contrast-tested. In the tested cases, layered verbs compose with the chaining architecture without producing contradictions: they have projected, they have provisionally resolved through deep reception, and their qualifications have provisionally survived cross-boundary transit at the same support level as deep reception generally. The combined negation-adjacent form (`e ved y oRo`) depends on operator scope, which is unsettled.