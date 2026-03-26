# 06 — Resolution-Unit Chaining and Complex Sentences

**Status:** Provisional grammar formalization. This document captures the current working architecture for larger-meaning composition in Varoli. It is derived from iterative structural testing against the existing primitive system. It is not canon closure. Weaker elements are explicitly marked with their current support levels. For the archive of how this was reached, visit the ../../appendix/notes folder

---

## 1. Purpose

This document formalizes how resolution units — the native compositional units of expression in Varoli — chain into larger structures that carry composite meaning. It defines terminal behavior, cross-unit interaction, inter-force governance, and the first supported complex-sentence patterns.

The architecture described here does not import conjunction, subordination, or clause logic from other languages. All mechanisms are derived from existing structural properties: palindromic closure, binary directionality, the containment relationship, and the operator's superposition-collapse function. No new primitives or mechanics are introduced.

For the primitive verb system, see `01-primitive-verbs.md` and `02-primitive-verbs-extended.md`. For primitive nouns, see `05-primitive-nouns.md`. For subject markers and primitive sentences, see `03-subject-markers.md` and `04-primitive-sentences.md`.

---

## 2. The Resolution Unit

The resolution unit is the basic compositional unit of larger meaning in Varoli. It is a structurally bounded composition of primitives whose terminal element determines whether the unit resolves locally, projects force beyond its boundary, or suspends in superposition.

The smallest validated resolution unit is the primitive sentence: `V + CV + VCV` — a perspective marker, a directional verb, and a stable palindromic noun. This pattern is documented in `04-primitive-sentences.md`.

Resolution units are not sentences in the conventional sense. They are structural units defined by their terminal behavior. A resolution unit may be a complete expression (if it closes) or a partial expression that requires connection to a subsequent unit (if it projects or suspends). The language does not have sentences with beginnings, middles, and ends. It has points of resolution that either complete locally or carry structural content forward.

---

## 3. Terminal Behavior

The terminal element of a resolution unit determines the unit's state. Three states are currently identified.

### Close

The terminal element is a stable centered form (VCV palindrome). The palindromic noun absorbs the preceding verb's directional force through the containment relationship (kinetic within substrate). The unit resolves locally. No force is projected beyond the unit boundary.

Strongly supported in all single-verb cases tested. Multi-verb unit closure (whether a single palindromic noun can close a unit containing more than one verb) remains untested.

### Project

The terminal element is a directional form (CV or VC verb) or a bare kinetic consonant (a verb suffix). The unit emits directed force beyond its boundary. No stable domain exists within the unit to absorb the force. The unit is structurally open.

Strongly supported across all cases tested. No directional terminal tested resolves internally. Domain consistency between subject marker and verb does not substitute for stable terminal closure. Operator verbs (y-set) are no exception.

Verb layering does not change terminal behavior. A layered verb (CV+C) projects the same way a bare verb (CV) does. In the tested cases, the suffix qualifies the force without changing the unit's structural state.

### Suspend

The terminal element is the operator (y). The unit is held in superposition at its terminal. The operator marks the position as unresolved. The unit neither closes nor projects.

Strongly supported across all cases tested. Terminal operator consistently suspends. Preceding directional force provides partial constraint but not full collapse. Preceding closed structures do not extend governance into post-terminal operator positions.

---

## 4. Cross-Unit Interaction Model

When a projecting unit is followed by another unit, the interaction is determined by what the projected force encounters. The provisional chaining architecture is best modeled as two governed interactions and one default state.

### Resolution (project into close)

Projected force from a projecting unit resolves in the first stable domain (palindromic noun) it reaches in a subsequent closing unit. The governing mechanism is the containment relationship: kinetic force operates within substrate domain.

The strongest current deep-reception hypothesis is that projected force is not received by the framing element (subject marker) and instead reaches the first structurally compatible stable domain. Whether the subject marker is transparent to incoming force, blocks it, or can simultaneously frame and receive is undeterminable from current testing. Deep reception bypasses this ambiguity by identifying the noun as the structurally compatible receiver.

The strongest current hypothesis is that the containment relationship can govern reception regardless of compositional origin, with cross-boundary verification still weaker than within-form verification. Within-form precedent supports multi-force containment: `arOva` contains two kinetic forces within one substrate domain, and the soul crucible contains multiple forces within nested domains. The architecture defines containment by role class and function without a provenance condition. No primitive, rule, or role class encodes origin-sensitivity.

The verification gap: within-form multi-force containment is confirmable through palindromic closure. Cross-boundary multi-force containment is not confirmable through the same mechanism. The architecture currently favors the relationship by definition while leaving its cross-boundary confirmation weaker than the within-form case.

### Suspension (project into suspend)

Projected force from a projecting unit encounters a subsequent unit whose terminal is operator-marked. The subsequent unit contains no stable domain. The projected force has no reception target under the deep reception rule.

The current architecture leans toward extended suspension: the terminal operator encompasses both the unit's own unresolved force and the incoming projected force, producing a composite suspended state. This lean is based on the architecture's provenance-blindness and the operator's canonical description ("acts on relationships between primitives" without restriction to compositionally native primitives).

This is provisionally supportable, with the same operator-scope caveat: operator scope in cross-boundary contexts has not been formally derived or independently verified. Extended suspension is the weakest supported interaction in the chaining architecture.

### Continuation (project into project)

Projected force from a projecting unit encounters a subsequent unit that also projects. The subsequent unit contains no stable domain and no operator. The projected force has neither a reception target nor a suspending mechanism.

Continuation is currently the least assumption-laden default state when no receiver or suspender is encountered. The projected force persists. It is not resolved. It is not suspended. It continues forward, seeking a stable domain or operator in whatever follows.

Both the incoming projected force and the subsequent unit's own projected force continue forward together. Their coexistence is not prohibited by any current rule. Their inter-relationship is not specified by any current mechanism.

Continuation is not a governed interaction in the same sense as resolution and suspension. It is the structural state of unreceived projection persisting. The chain remains open until a stable domain closes it or an operator suspends it.

The current model suggests iterative continuation in principle, though practical containment limits remain untested. Three-unit chains (project, continue, resolve) have been tested and behave consistently with the two-unit model.

---

## 5. Deep Reception

Deep reception is the provisional mechanism by which projected force crosses a unit boundary and resolves within a subsequent unit's stable domain.

The rule: projected force resolves in the first stable domain (palindromic noun) it reaches in a subsequent unit. The containment relationship (kinetic within substrate) governs reception. The force and the domain relate through role class, not through compositional history.

Deep reception applies to both simple and qualified (layered) forces. In the tested cases, suffix qualifications survive projection at the same provisional support level as deep reception generally. No mechanism strips qualifications during cross-boundary transit. The architecture preserves compound forces during projection because no rule decomposes them and function is invariant.

The current architecture provisionally supports multiple projected forces being received in a later stable domain, though the specific three-force load on a simple VCV stable form remains less directly validated than the two-force case.

---

## 6. Inter-Force Governance

When two or more directional forces resolve within the same stable domain, their relationship is provisionally differentiated by orientation.

### Opposite-orientation forces (CV meeting VC)

The current architecture supports deriving a more determinate relation from the CV/VC distinction alone. One force arrives in the domain (CV, inward-facing). The other departs from the domain (VC, outward-facing). The directional asymmetry produces a structurally readable relationship: arrival meeting departure. The domain is the site of a crossing.

This is the first strongly plausible native multi-unit distinction derived from existing directional architecture. It is not an imported grammatical category. It arises from binary directionality applied to two forces within a shared space.

### Same-orientation forces (CV meeting CV, or VC meeting VC)

Same-orientation chains are currently the best candidate for relational openness within the tested chaining architecture. The forces are identifiable by their different invariant functions and different perspectives, but the inter-force relationship is not specified by orientation. The forces are co-present and co-directional within the shared domain. The chain specifies down to the domain layer and leaves the relational layer open.

### Both types are meaningful

Neither is currently shown invalid within the tested chaining architecture. The distinction is in determinacy of the inter-force layer, not presence or absence of meaning. Opposite-orientation chains tell the reader what direction each force faces relative to the domain. Same-orientation chains tell the reader both forces are present without specifying their directional relationship to each other.

### Qualification asymmetry

When one force carries a suffix qualification and another does not, the reader can distinguish the forces by their qualification as well as by their invariant function and perspective. One force may be completed while the other is bare. One may carry opposition while the other does not. This produces a readable asymmetry within shared domains. Whether qualification asymmetry constitutes a governance mechanism beyond readability is an open question.

---

## 7. Closure Plus Closure

Two independently closed resolution units placed in sequence yield juxtaposition rather than structural chaining in the tested architecture.

Each closed unit resolves locally. No force is emitted beyond its boundary. No structural content crosses into the adjacent unit. The chaining architecture's interaction mechanisms are all initiated by projection. Without projection, no cross-unit interaction occurs.

Two closed units in sequence are two independent expressions that happen to occur in order. A reader may infer a relationship between them, but that inference is interpretive, not structural. The architecture does not produce it.

This confirms that the tested architecture strongly supports the constraint that complex sentence formation requires at least one projecting unit. Two resolved statements placed side by side do not automatically form a complex sentence. To compose them into a single complex expression, at least one unit must be structurally open (projecting) so that its force connects to the other unit through the chaining architecture.

---

## 8. First Supported Complex-Sentence Patterns

### Pattern 1: Same-orientation complex sentence

`e vek` | `a va aVa`

Unit 1 projects: self individuates-with-completion (CV, qualified, inward). Unit 2 closes: the collective flows as relation within the ocean (CV, bare, inward).

The projected compound force `vek` resolves within `aVa` through deep reception. The ocean holds both individuation-completed (from Unit 1) and relational flow (from Unit 2). Two perspectives, two forces (one qualified, one bare), one shared resolution domain.

The two forces are same-orientation (both CV, inward). Their inter-force relationship is co-present but relationally open. The qualification asymmetry (one completed, one bare) is readable but does not fully govern the inter-force relationship.

This is the strongest current candidate for the first directly supported complex-sentence pattern in Varoli's native chaining architecture.

### Pattern 2: Opposite-orientation complex sentence

`e vek` | `a av aVa`

Unit 1 projects: self individuates-with-completion (CV, qualified, inward). Unit 2 closes: the collective's relation expresses outward through vitality within the ocean (VC, bare, outward).

The projected compound force `vek` resolves within `aVa` through deep reception. The ocean holds both individuation-completed (arriving) and relational expression (departing). Two perspectives, two forces differentiated by both qualification and orientation, one shared resolution domain.

The two forces are opposite-orientation (CV meeting VC). The directional asymmetry produces a more determinate inter-force reading: arrival meeting departure within the ocean. The domain is the site of a crossing.

This pattern is more relationally determinate than Pattern 1. The reader can derive not only that both forces are present but also their directional relationship within the shared domain.

### What both patterns share

Both require at least one projecting unit. Both use deep reception. Both produce composite meaning that neither unit alone can express. Both are derivable from primitives without external interpretation. Both preserve invariant function, non-overlapping role classes, and compositional meaning throughout.

---

## 9. Verb Layering in Complex Sentences

Verb layering (consonant suffixes qualifying verb force) composes with the chaining architecture without interference. The current tests support treating force qualification and compositional trajectory as distinct interacting axes.

Suffix consonants modify the verb's kinetic force by adding the suffix's invariant function as a qualification. In the tested cases, suffixes qualify force while preserving both terminal behavior and containment type. A layered verb projects the same way a bare verb does. A layered verb resolves within a stable domain through the same containment relationship as a bare verb.

The current architecture provisionally supports the suffix qualification surviving projection at the same support level as deep reception generally. The compound force arrives at the receiving domain intact. No mechanism strips it. No rule decomposes it.

At least two-deep compositional layering is supported (two suffixes on one verb), with greater depth remaining an open structural possibility. The current architecture strongly suggests suffix order is meaningful (each suffix qualifies the result of everything to its left), though this has not yet been independently contrast-tested.

For the full verb layering derivation, see the development notes. Formal integration into the core verb documents is pending.

---

## 10. What Remains Provisional

**Deep reception.** Cross-boundary containment is provisionally supported by architectural definition and within-form precedent. It is not verified by a structural mechanism equivalent to palindromic closure operating across unit boundaries.

**Extended operator scope.** The weakest link. Whether the terminal operator's suspension encompasses incoming projected force depends on operator scope in cross-boundary contexts, which has not been formally derived.

**Subject marker behavior at boundaries.** Whether the opening subject marker of a receiving unit is transparent to projected force, blocks it, or can serve a dual role is undeterminable from current testing.

**Same-orientation governance.** Same-orientation force pairs within shared domains are relationally open. Whether additional structural mechanisms can resolve the inter-force relationship within same-orientation pairs is untested.

**Multi-verb unit closure.** Whether a single palindromic noun can close a unit containing more than one verb is untested.

**Containment capacity.** Whether a simple VCV palindrome can contain arbitrarily many forces is untested beyond the three-force case. Larger palindromic forms may be needed for higher force loads.

**Continuation accumulation limits.** Whether continuation accumulates without structural limit or whether some constraint bounds the number of coexisting projected forces is untested.

**Suffix order semantics.** The claim that suffix ordering carries meaning is strongly suggested by the architecture (Law 1: arrangement carries meaning) but not yet independently contrast-tested with reversed suffix pairs.

---

## 11. Implications for Further Grammar Development

The resolution-unit chaining architecture provides a native framework for larger-meaning composition. Several grammar domains are now reachable:

**Temporal and aspectual expression.** Verb layering through consonant suffixes produces force qualifications that may function as temporal and aspectual markers. Completion (`-k`), ongoing pressure (`-p`), and other consonant functions applied as suffixes provide structurally grounded alternatives to imported tense categories.

**Negation-adjacent expression.** Two mechanisms are currently available. Suffix-based force opposition (`-d`, resistance) produces a force that carries its own internal opposition. Operator-mediated resolution suspension (`y` between verb and noun) provisionally produces a form where the force and domain are both present but their resolution is held open. The two mechanisms can combine. Whether they are collectively sufficient for all negation needs, or whether a dedicated negation mechanism is required, remains an open question.

**Multi-perspective composition.** The chaining architecture naturally supports expressions involving multiple perspectives (subject markers from different elemental domains) contributing different forces to shared resolution domains. This is the basis of complex sentences in Varoli.

**Discourse structure.** Longer chains of projecting, continuing, suspending, and closing units can produce extended discourse. The interaction model (resolution, suspension, continuation) provides native structural articulation for how discourse units relate. Closure-after-closure produces juxtaposition. Projection-based chaining produces structural connection.

The chaining architecture will be pressure-tested naturally as these grammar domains develop. Every new grammatical mechanism will either compose cleanly with the chaining framework or reveal a limitation that requires revisiting. Results that force a return to chaining work include: a layered verb producing an unclassifiable terminal type, a construction requiring same-orientation governance to be determinate, negation requiring resolved operator scope, temporal realization contradicting the continuation default, or multi-noun constructions producing ambiguous force-target assignment.

---

## Summary

The resolution unit is the native compositional unit. Terminal behavior determines unit state (close, project, suspend). Cross-unit interaction operates through two governed types (resolution and suspension) and one default state (continuation). Inter-force governance within shared domains is provisionally differentiated by directional orientation. Verb layering composes orthogonally with chaining. The first complex-sentence patterns are provisionally supported as projecting layered units resolving within closing units through deep reception.

The architecture produces complex meaning from primitive structural properties without importing external grammar. It is provisional. It is testable. It is the beginning of Varoli's native larger-meaning system.