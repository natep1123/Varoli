# 05 — Resolution-Unit Chaining

*Last Updated: March 29, 2026*

**Status:** Working Canon
**Layer:** Ground 4 / Grammar-Architecture
**Authority:** Structural
**Scope:** Defines the resolution unit as the native larger-meaning compositional unit in Varoli, formalizes terminal behavior and cross-unit interaction, and establishes the first supported complex-composition patterns.

---

## 1. Purpose

This document formalizes the resolution-unit chaining architecture as the native mechanism for larger-meaning composition in Varoli.

The resolution unit is real architecture. Terminal behavior, cross-unit interaction, and inter-force governance are established well enough to guide downstream work. Support levels across these areas are uneven and are marked honestly throughout.

The architecture described here does not import conjunction, subordination, or clause logic from other languages. All mechanisms derive from existing structural properties: centered stable form closure, binary directionality, containment, and the operator's superposition function. No new primitives or role classes are introduced.

Primitive-level implementation is handled in downstream canonical and grammar documents.

---

## 2. Why the Language Needs This Category Now

Varoli's primitive architecture establishes how individual forces, domains, and stable forms are composed. It does not by itself explain how those units combine into structures that carry composite meaning.

Without a formalized chaining architecture, every multi-unit construction is either described locally each time or left without structural explanation. The language cannot develop temporal expression, multi-perspective composition, negation-adjacent structures, or discourse-level organization without a native account of how resolution units interact across boundaries.

The chaining architecture is the required foundation. It provides the structural basis for all larger-meaning composition without importing grammatical categories from other languages.

---

## 3. Strongest Current Definition

A **resolution unit** is a structurally bounded composition of primitives whose terminal element determines whether the unit resolves locally, projects force beyond its boundary, or suspends in superposition.

Resolution units are not sentences in the conventional sense. They are structural units defined by their terminal behavior. A resolution unit may be a complete expression or a partial expression that requires connection to a subsequent unit. The language does not have sentences with fixed beginnings, middles, and ends. It has points of resolution that either complete locally or carry structural content forward.

The smallest validated resolution unit is the primitive sentence: a perspective marker, a directional force, and a stable centered form. Primitive sentence structure is handled in downstream implementation documents.

---

## 4. Terminal Behavior

The terminal element of a resolution unit determines the unit's structural state. Three states are established.

### 4.1 Close

The terminal element is a stable centered form. The stable form's substrate domain absorbs the preceding kinetic force through the containment relation (defined in `01-g4-containment.md`): kinetic within substrate. The unit resolves locally. No force is projected beyond the unit boundary.

The stable centered form governing closure is understood through the centered-balance framing established in `04-g4-stable-form-expansion.md`. Strict phonemic palindrome is the earliest and best-verified manifestation of this closure. Centered balance is the deeper invariant. Where this document refers to a stable form as a closure target, that framing applies.

Strongly supported in all single-force cases tested. Whether a single stable centered form can close a unit containing more than one internally generated force is untested and remains open.

### 4.2 Project

The terminal element is a directional form or a bare kinetic consonant. The unit emits directed force beyond its boundary. No stable domain exists within the unit to absorb the force. The unit is structurally open.

Strongly supported across all cases tested. No directional terminal tested resolves internally. Operator verbs are no exception. Force qualification through suffix layering does not change terminal behavior: a qualified force projects the same way a bare force does. The suffix qualifies the force without changing the unit's structural state.

### 4.3 Suspend

The terminal element is the operator (`y`). The unit is held in superposition at its terminal position. The operator marks the position as unresolved. The unit neither closes nor projects.

Strongly supported across all cases tested. Terminal operator consistently suspends. Preceding directional force provides partial constraint on the suspended position but does not produce full collapse. Preceding closed structures do not extend governance into post-terminal operator positions.

---

## 5. Cross-Unit Interaction

When a projecting unit is followed by another unit, the interaction is determined by what the projected force encounters. The chaining architecture currently identifies two governed interactions and one default structural state.

### 5.1 Resolution

Projected force from a projecting unit resolves within the first stable domain it reaches in a subsequent closing unit. The governing mechanism is containment: kinetic force operates within substrate domain, governed by role class rather than compositional origin.

The strongest current formulation is that projected force is not received by the framing element (perspective marker) and instead reaches the first structurally compatible stable domain. Whether the perspective marker is transparent to incoming force, blocks it, or can simultaneously frame and receive is not determinable from current testing. Deep reception bypasses this ambiguity by identifying the stable centered form as the structurally compatible receiver.

Cross-boundary containment is provisionally supported by architectural definition and within-form precedent. `arOva` confirms multi-force containment within a single stable form. The architecture defines containment by role class and function without a provenance condition, which grounds the deep reception mechanism. Cross-boundary verification remains weaker than within-form confirmation: centered closure, with strict phonemic palindrome as its clearest current manifestation, confirms within-form containment directly; no equivalent mechanism currently confirms cross-boundary containment. This is the known verification gap.

### 5.2 Suspension

Projected force from a projecting unit encounters a subsequent unit whose terminal is operator-marked. The subsequent unit contains no stable domain. The projected force has no reception target under the deep reception rule.

The current architecture leans toward extended suspension: the terminal operator encompasses both the unit's own unresolved force and the incoming projected force, producing a composite suspended state. This lean is grounded in the architecture's provenance-blindness and the operator's function of acting on structural relations without restriction to compositionally native elements.

Extended suspension is the weakest supported interaction in the chaining architecture. Operator scope in cross-boundary contexts has not been formally derived or independently verified. The lean is stated honestly as provisional.

### 5.3 Continuation

When a projecting unit is followed by another projecting unit, the projected force encounters no stable domain and no operator. The force persists. It is not resolved. It is not suspended. It continues forward.

Continuation is not a governed interaction in the same sense as resolution and suspension. It is the structural state of unreceived projection persisting until a stable domain closes it or an operator suspends it. Both the incoming projected force and the subsequent unit's own projected force continue forward together. Their coexistence is not prohibited by any current rule.

Three-unit chains (project, continue, resolve) have been tested and behave consistently with the two-unit model. Whether continuation accumulates without structural limit or whether some constraint bounds the number of coexisting projected forces is untested.

---

## 6. Inter-Force Governance

When two or more directional forces resolve within the same stable domain, their relationship is provisionally differentiated by orientation.

### 6.1 Opposite-orientation forces

When one force arrives inward-facing (CV) and another departs outward-facing (VC), their directional asymmetry produces a structurally readable relationship: arrival meeting departure. The domain is the site of a crossing. This is the most determinate inter-force reading currently derivable from the existing directional architecture. It arises from binary directionality applied to two forces within a shared domain, not from an imported grammatical category.

### 6.2 Same-orientation forces

When both forces share orientation (both CV or both VC), the inter-force relationship is not specified by directional asymmetry. The forces are identifiable by their different invariant functions and different perspectives, but the relational layer between them is structurally open. Same-orientation chains specify the composition down to the domain layer and leave the inter-force relational layer undetermined.

Neither type is structurally invalid. The distinction is in determinacy of the inter-force layer, not in the presence or absence of meaning. Whether additional structural mechanisms can resolve the inter-force relationship in same-orientation pairs is untested.

### 6.3 Qualification asymmetry

When one force carries suffix qualification and another does not, the reader can distinguish the forces by their qualification as well as by their invariant function and perspective. This produces a readable asymmetry within shared domains. Whether qualification asymmetry constitutes a governance mechanism beyond readability is an open question.

---

## 7. Relation to Stable Forms

Stable centered forms are the resolution targets of the chaining architecture. Every closure and every deep reception event depends on the containment capacity of a stable domain.

The chaining architecture inherits the current stable-form law: strict phonemic palindrome is the earliest and best-verified manifestation of stability, and centered balance is the deeper governing invariant. This matters for chaining in two ways.

First, the validity of closure and deep reception is not indexed to palindromic form specifically but to stable centered form as governed by centered balance. If a larger centered form satisfies the stability law through centered balance without strict phonemic mirror identity, it is in principle a valid closure target. Whether any such forms exist and are verified is an open question addressed in `04-g4-stable-form-expansion.md`.

Second, the containment capacity of simple stable forms is an open question that directly affects chaining. If a simple VCV stable form has a containment limit, then chains that project more force than the limit can hold may require larger stable forms as closure targets. The interaction between expansion and chaining capacity is not yet formally resolved.

---

## 8. Relation to Containment and Perspective Markers

### 8.1 Containment

The containment relation (defined in `01-g4-containment.md`) is the mechanism underlying both closure and deep reception. Terminal closure is containment completing locally. Deep reception is containment operating across a unit boundary, governed by the same class-based relation without provenance condition.

Provenance-blindness is what makes deep reception structurally continuous with local containment rather than a separate mechanism. The verification gap noted in Section 5.1 is a gap in confirmation, not in the architectural definition.

### 8.2 Perspective markers

The perspective marker that opens a resolution unit is a substrate primitive in a framing position whose scope extends over the unit (defined in `03-g4-perspective-markers.md`). In the chaining architecture, the perspective marker frames unit entry. It does not appear to receive incoming projected force. Whether it is transparent to cross-boundary projection, blocks it, or can simultaneously frame and receive remains undetermined. The deep reception rule identifies the stable centered form as the reception target, which is consistent with the framing function of the perspective marker but does not formally resolve its behavior at the boundary.

---

## 9. What Chaining Explains Already

### 9.1 Why complex meaning requires projection

Two independently closed resolution units placed in sequence yield juxtaposition, not structural chaining. Each closed unit resolves locally. No force crosses the boundary. No structural content connects the units. A reader may infer a relationship between them, but that inference is not structurally produced.

Complex sentence formation requires at least one projecting unit. This follows directly from the chaining architecture: the interaction mechanisms are all initiated by projection. Without projection, no cross-unit interaction occurs.

### 9.2 The first supported complex-composition patterns

Two patterns are currently the strongest empirical precedents for the chaining architecture. Both are derived from primitive structural properties without external interpretation.

**Pattern 1: Same-orientation composition**

`e vek` | `a va aVa`

Unit 1 projects: self individuates-with-completion (CV qualified, inward-facing). Unit 2 closes: the collective flows relationally within the ocean (CV bare, inward-facing, closing on `aVa`).

The projected compound force `vek` resolves within `aVa` through deep reception. The stable domain holds both individuation-completed (from Unit 1) and relational flow (from Unit 2). Two perspectives, two forces (one qualified, one bare), one shared resolution domain.

The two forces are same-orientation (both CV, inward). Their inter-force relationship is co-present but relationally open. The qualification asymmetry (one completed, one bare) is readable but does not fully govern the inter-force relationship. This is the strongest current candidate for the first directly supported complex-composition pattern in the native chaining architecture.

**Pattern 2: Opposite-orientation composition**

`e vek` | `a av aVa`

Unit 1 projects: self individuates-with-completion (CV qualified, inward-facing). Unit 2 closes: the collective's relation expresses outward through vitality within the ocean (VC bare, outward-facing, closing on `aVa`).

The projected compound force `vek` resolves within `aVa` through deep reception. The stable domain holds both individuation-completed (arriving inward) and relational expression (departing outward). Two perspectives, two forces differentiated by both qualification and orientation, one shared resolution domain.

The two forces are opposite-orientation (CV meeting VC). The directional asymmetry produces a more determinate inter-force reading: arrival meeting departure within the ocean. The domain is the site of a crossing. This pattern is more relationally determinate than Pattern 1: the reader can derive not only that both forces are present but also their directional relationship within the shared domain.

**What both patterns establish**

Both require at least one projecting unit. Both use deep reception. Both produce composite meaning that neither unit alone can express. Both preserve invariant function, non-overlapping role classes, and compositional meaning throughout. Together they establish that same-orientation and opposite-orientation chains are both valid but structurally distinct in the determinacy of their inter-force layer.

### 9.3 Why suffix qualification survives projection

No mechanism strips suffix qualifications during cross-boundary transit. Function is invariant. The architecture preserves compound forces during projection because no rule decomposes them and the invariant function constraint holds across boundaries. A qualified force arrives at the receiving domain intact.

### 9.4 Why suffix order in projecting units remains meaningful

Each suffix qualifies the result of everything to its left. The compounding is internal to the force before projection occurs. The order of qualification is determined before the force crosses any boundary, and the receiving domain holds the compound force as a whole. This follows from qualification as a structural relation (defined in `02-g4-qualification.md`) and from the invariant-function constraint.

---

## 10. What Chaining Is Not

**Not clause-based grammar.** The chaining architecture does not import subject, object, or clause logic. Resolution units are not sentences with grammatical roles assigned to positions. They are structural units defined by terminal behavior. Force and domain relations are determined by role class and containment, not by syntactic position labels.

**Not sequential accumulation of independent units.** Closed units placed in sequence do not chain structurally. Chaining is not proximity. It is initiated by projection and governed by the interaction mechanisms defined in Section 5.

**Not a new primitive layer.** The chaining architecture introduces no new primitives and no new role classes. All mechanisms derive from existing structural properties: terminal behavior follows from role class and position, cross-unit interaction follows from containment and the operator function, inter-force governance follows from binary directionality.

**Not fully closed architecture.** Several chaining mechanisms are provisionally supported rather than formally verified. Deep reception is real but its cross-boundary verification is weaker than within-form confirmation. Operator scope across boundaries is the weakest link. The note does not pretend these gaps are closed.

---

## 11. Questions

A question is a resolution unit whose terminal state is suspend: the unit ends in the operator `y`. The unit holds its force-domain relation in superposition. The relation is present but unresolved. In a conversational context, a suspended unit presented to another speaker is a question: the speaker has built the structure and left it in superposition, making explicit that collapse is expected from outside.

A question is not a separate grammatical category. It is a terminal state. The language already has it. This section names it.

The structural form of a question in Varoli is identical to any other suspended resolution unit. What makes it a question is not any additional marker but the context of address: a suspended unit directed at another perspective, whose perspective marker indicates the other, is a question. The speaker has emitted a force into a domain and left the resolution open. The other resolves it or receives the suspension.

This also means questions can be left unanswered structurally - the suspended unit continues projecting forward until something in the chain resolves it or until the chain ends in suspension. The unresolved question is not a broken expression. It is a structurally valid condition: the superposition holds, unresolved, across units.

---

## 12. Open Questions Named

### 12.1 Deep reception verification

Within-form multi-force containment is confirmable through centered-balance closure. Cross-boundary multi-force containment is not confirmable through the same mechanism. Whether a native verification mechanism exists for cross-boundary containment, or whether provenance-blindness functions as a sufficient architectural guarantee, is not yet determined.

### 12.2 Operator scope across boundaries

Whether the terminal operator's suspension encompasses incoming projected force depends on operator scope in cross-boundary contexts. This has not been formally derived. Extended suspension is the current lean, but it is the weakest supported interaction in the chaining architecture and must not be overstated.

### 12.3 Perspective marker behavior at boundaries

Whether the opening perspective marker of a receiving unit is transparent to projected force, blocks it, or can simultaneously frame and receive is not determinable from current testing. The deep reception rule is consistent with the framing function of the perspective marker, but does not formally resolve its boundary behavior.

### 12.4 Multi-force closure in a single unit

Whether a single stable centered form can close a unit containing more than one internal force (not counting cross-boundary reception) is untested. This is distinct from the deep reception question: it concerns the containment capacity of the terminal stable form with respect to forces generated within the same unit.

### 12.5 Same-orientation governance

Whether additional structural mechanisms can resolve the inter-force relationship within same-orientation force pairs is untested. The architecture currently leaves same-orientation pairs relationally open. If a mechanism can close them, it has not yet been identified.

### 12.6 Continuation accumulation

Whether continuation accumulates without structural limit or whether some constraint bounds the number of coexisting projected forces in an open chain is untested. The interaction between continuation accumulation and containment capacity is not yet formally addressed.

### 12.7 Suffix order contrast testing

Suffix order is strongly suggested to be meaningful by the qualification architecture and by the invariant-function constraint, but reversed suffix pairs have not yet been independently contrast-tested. This should be treated as a near-term test priority.

### 12.8 Reference within chains

The reference architecture (`12-g4-reference-architecture.md`) proposes the departure face (VC) as the mechanism for referencing an established stable form. Whether this mechanism operates identically within a chaining sequence as in a standalone context is not established. Specifically: does a stable form established in one unit maintain reference availability for departure faces in subsequent units? Does reference scope have a distance limit across unit boundaries? Does a perspective marker's framing affect which established forms are in reference scope?

### 12.9 Perspective marker change at unit boundaries

Whether the perspective marker can or must change at every unit boundary is not established. The self-crucible decompression chain changes perspective marker at every boundary: `e`, `u`, `a`, `o`. Whether this is a structural requirement of the decompression context, a general chaining principle, or an artifact of the crucible's specific containment order is not determined. Whether two consecutive units can share a perspective marker without this being structurally flat, or whether shared perspective markers mark a particular kind of chaining relation, is untested.

---

## 13. Propagation Targets

**Immediate:**
- Ensure chaining terminology is consistent with `../../Ground-2/00-g2-varoli-terminology.md`. Any downstream document using "sentence," "clause," "subject," or "object" as primary structural categories should be revised to use resolution-unit language.
- Update `../../Ground-2/01-g2-varoli-conceptual-overview.md` to reflect current status.

**Short-term:**
- Propagate the formal chaining architecture into downstream grammar documents, replacing locally described cross-unit behavior with references to this document.
- Integrate verb layering into the chaining note's worked examples as that document is formalized (see `06-g4-verb-layering.md`).
- Revisit the perspective marker boundary question as the perspective marker formulation is tested further (see `03-g4-perspective-markers.md`).

**Test:**
- Construct a multi-force single-unit closure case and verify whether one stable centered form can close a unit with more than one internally generated force (Section 12.4).
- Construct reversed suffix pairs and contrast-test whether order produces distinct readings (Section 12.7).
- Construct an explicit suspension-into-suspension chain to test extended operator scope directly (Section 12.2).

**Investigate:**
- Whether a native verification mechanism exists for cross-boundary containment (Section 12.1).
- Whether same-orientation force pairs can be governed more determinately by any current structural mechanism (Section 12.5).
- Whether continuation has a structural upper bound (Section 12.6).