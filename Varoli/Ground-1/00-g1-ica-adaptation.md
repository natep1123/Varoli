# Varoli Ground 1 — ICA Adaptation Layer

*Last Updated: March 27, 2026*

**Status:** Bridge document. This document defines how Varoli instantiates the Invariant Compositional Architecture (ICA) at the language level. It is not the abstract blueprint itself, and it is not the full language canon. It sits between them.

**Layer Position:**
- **Ground 0:** ICA abstract architecture (`../../Ground-0/`)
- **Ground 1:** Varoli adaptation of ICA (this document)
- **Ground 2:** Varoli-native orientation (`../Ground-2/`) — terminology and conceptual overview
- **Ground 3:** Generative foundation (`../Ground-3/`) — primitive building blocks, primitive directional forms and primitive stable worlds
- **Ground 4:** Higher-order structural development (`../Ground-4/`) — e.g. `Grammar-Architecture/`, `Exploring/` for Ground-4 frontier work, and room for further subfolders (Yemu, proof-object work) as that layer grows

**Canon-alignment note:** This document reflects the current project-level understanding of how ICA becomes Varoli. In some areas, this understanding is more precise than older Varoli formulations developed before the current layered repository structure. Where this occurs, the document states the current direction explicitly so that later downstream canonical and grammar documents can be aligned to it.

---

## 1. Purpose

This document exists to make one relationship explicit:

**Varoli is an implementation of the ICA, but it is not reducible to the ICA.**

The ICA defines the abstract structural architecture. Varoli instantiates that architecture as a language with its own primitive inventory, native terminology, generation logic, interpretive rules, and expressive consequences.

This document therefore serves four functions:

1. to identify which parts of Varoli are direct instantiations of ICA axioms, laws, and emergent behaviors
2. to identify which parts of Varoli are language-specific realizations that extend beyond the blueprint
3. to preserve the hierarchy between blueprint and language canon
4. to prevent drift in both directions:
   - reducing Varoli into blueprint abstraction
   - treating blueprint structure as optional or merely metaphorical

---

## 2. Layer Relationship

### 2.1 Ground 0: ICA

The ICA is the abstract architectural layer. It defines a closed inventory of structural commitments:

**Three axioms:**
- Axiom 1: Non-overlapping typed primitives
- Axiom 2: Invariant function
- Axiom 3: Composition as sole source of meaning

**Seven derived laws:**
- Law 1: Binary directionality (from A1 + A3)
- Law 2: Stability through symmetric closure (from A3 + L1)
- Law 3: Center-governed interpretation (from L2)
- Law 4: Explicit superposition with context-driven collapse (from A1 + A2 + A3)
- Law 5: Role-ordered compression (from A1 + A2 + L2)
- Law 6: Reconstruction from irreducible center (from L5 + L3)
- Law 7: Scale realization without function mutation (from A2)

**Three emergent behaviors:**
- EB1: Dual projection modes (sequential and simultaneous)
- EB2: Structural distinction between transitional and stable forms
- EB3: Recursive stability (stable structures nesting within stable structures)

At this level, no language-specific primitive inventory is assumed. No implementation details are included. For the full specification, see `../../Ground-0/01-g0-ica-blueprint.md`. For terminology, see `../../Ground-0/00-g0-ica-terminology.md`.

### 2.2 Ground 1: Varoli adaptation

Varoli Ground 1 answers the question:

**How does ICA become this language?**

This requires a mapping from every abstract architectural commitment to a language-specific structure, and an accounting of where the language extends beyond the blueprint through lawful elaboration.

### 2.3 Ground 2: Varoli-native canon

Ground 2 contains the language in its own terms:
- Varoli terminology (`../Ground-2/00-g2-varoli-terminology.md`)
- primitive inventories and schemas
- generation and interpretation rules
- conceptual overview
- grammar documents
- application and expression layers

Ground 2 must remain written primarily in language-native terminology, not blueprint terminology.

---

## 3. Foundational Adaptation Principle

Varoli instantiates ICA by assigning language-specific primitive classes to the blueprint role classes while preserving non-overlap, invariant function, derivability, and structural readability.

This means:

- blueprint structure remains the abstract architectural source
- Varoli defines the specific language primitives that realize that structure
- language-specific development may enrich the implementation, but may not violate the blueprint laws from which it derives
- blueprint terminology and language terminology are mappable, but not interchangeable

---

## 4. Complete Mapping from ICA to Varoli

### 4.1 Core mapping table

The table below maps every ICA structural commitment to its Varoli realization. Items marked with a section reference are elaborated later in this document.

**Axioms:**

| ICA Commitment | Varoli Realization | Section |
|---|---|---|
| Axiom 1: Non-overlapping typed primitives | Vowels (substrate), consonants (kinetic), `y` (operator). Three classes, absolutely separated. | 5, 6 |
| Axiom 2: Invariant function | Each of Varoli's 27 primitives has one function that does not change across context. | 6 |
| Axiom 3: Composition as sole source of meaning | Meaning is derived from structure. No external assignment, convention, or interpretation overrides composition. | 6 |

**Derived Laws:**

| ICA Commitment | Varoli Realization | Section |
|---|---|---|
| Law 1: Binary directionality | CV / VC ordering. Two orientations, structurally distinct, non-reversible. | 7 |
| Law 2: Stability through symmetric closure | Attractor-centered stable forms. Strict phonemic palindrome (VCV and larger) was the first mapped manifestation. The current canon-level direction recognizes attractor-centered structural balance as the deeper invariant. | 8 |
| Law 3: Center-governed interpretation | Attractor-first reading. Interpretation begins from the attractor and moves outward. | 8 |
| Law 4: Explicit superposition | `y` marks unresolved positions. Collapse is governed by surrounding structure. Primitive-level adaptation is clean; extended compositional scope remains a Ground 2 development area. | 10 |
| Law 5: Role-ordered compression | Varoli-to-Yemu compression follows role-ordered reduction. Kinetics strip first. | 12 |
| Law 6: Reconstruction from irreducible center | Yemu forms can be expanded back toward full Varoli articulation. | 12 |
| Law 7: Scale realization | Each primitive's invariant function manifests across internal, external, temporal, and dimensional scales without changing. | 5 |

**Emergent Behaviors:**

| ICA Commitment | Varoli Realization | Section |
|---|---|---|
| EB1: Dual projection modes | Varoli (sequential, spoken) and Yemu (simultaneous, center-outward, non-spoken). Same primitive architecture, different projection mode. | 12, 13 |
| EB2: Transitional vs stable distinction | CV/VC forms are transitional (directional, leaning). Attractor-centered stable forms are stable (closed, centered). | 7, 8 |
| EB3: Recursive stability | Larger stable forms nest stable structures within stable structures. The self-crucible is the canonical proof object: a nested structure containing all five elemental attractor pairs in symmetric closure around the operator. | 8 |

### 4.2 Why this mapping matters

This mapping shows that Varoli is not a loose interpretation of ICA. It is a disciplined language-level realization covering every axiom, every derived law, and every emergent behavior.

The ICA says that a valid system must distinguish domain, operation, and structural unresolvedness. Varoli realizes those as vowels, consonants, and `y`. The ICA says that orientation is semantic, closure produces stability, and compression is role-ordered. Varoli realizes those as CV/VC directionality, attractor-centered stable forms, and Varoli-to-Yemu compression. Every structural commitment in the blueprint has a language-level instantiation.

---

## 5. Primitive Instantiation in Varoli

### 5.1 Vowels as substrate realization

In Varoli, vowels instantiate substrate class.

A vowel is not a quality of motion and not an operator. It defines an ontological condition or elemental substrate within which structure may exist, operate, or resolve.

Varoli extends the substrate class into a language-specific schema by giving each vowel:
- invariant function
- articulatory grounding
- descriptive kinetic tendency
- experiential register
- scale realization (Law 7: the same function manifests at internal, external, temporal, and dimensional scales)
- exclusion boundaries
- optional poetic field

These additions do not alter the blueprint role class. They specify how substrate class becomes a language primitive system.

### 5.2 Consonants as kinetic realization

In Varoli, consonants instantiate kinetic class.

A consonant is not a substrate and not an operator. It defines a quality of motion or force that acts within or across domains.

Varoli extends the kinetic class into a language-specific schema by giving each consonant:
- invariant function
- quality of motion
- directional bias
- articulatory grounding
- optional poetic field
- operational role
- attractor-set distinction where relevant (four attractor consonants carry elemental affinity; seventeen general consonants do not)

These do not change the blueprint role class. They specify its language-level implementation.

### 5.3 `y` as operator realization

In Varoli, `y` instantiates operator class.

`y` is not an element and not a force. It does not contribute substrate identity or kinetic identity. It operates on relationships between primitives by introducing explicit superposition and governed collapse.

Varoli extends the operator class into a language-specific schema by giving `y`:
- invariant function
- positional behavior (distinct behavior in vowel position, consonant position, and palindrome center)
- scope of action
- explicit exclusion from substrate and kinetic classes

This is the cleanest one-to-one adaptation in the system. One ICA role class, one Varoli primitive.

---

## 6. Non-Overlap and Invariant Function

The ICA requires non-overlapping classes (Axiom 1) and invariant function (Axiom 2). Varoli implements both directly.

### 6.1 Non-overlap

Varoli preserves the absolute distinctness of:
- vowels as substrate
- consonants as kinetic
- `y` as operator

No class may substitute for another without structural corruption. This is not a design preference. It is the condition that makes derivation and composition reliable.

### 6.2 Invariant function

Each of Varoli's 27 primitives has one invariant function. Context may change realization, scale, or experiential reading, but it may not change primitive function.

This is a direct adaptation of Axiom 2.

### 6.3 Composition as sole source of meaning

Varoli meaning is derived from structure. No external assignment, convention, or interpretive layer overrides compositional meaning. If an interpretation cannot be reduced to the structure and its primitives, it is invalid.

This is a direct adaptation of Axiom 3.

### 6.4 Exclusion as implementation guardrail

Varoli makes non-overlap operational by explicitly writing exclusions into primitive schemas. Each vowel schema states what that vowel is not. Each consonant schema states its non-overlap with other consonants and with substrates.

This is a language-specific strengthening of the blueprint principle. It is not extra theory. It is a practical implementation safeguard.

---

## 7. Orientation in Varoli

The ICA defines binary directionality as structurally meaningful (Law 1). Varoli instantiates this through CV and VC ordering.

### 7.1 CV: force arriving into substrate

In Varoli, CV realizes kinetic class primitive followed by substrate class primitive.

Structurally, this is force arriving into a domain. The inward or arrival-facing directional realization.

### 7.2 VC: substrate expressing through force

In Varoli, VC realizes substrate class primitive followed by kinetic class primitive.

Structurally, this is a domain expressing through a force. The outward or expressive directional realization.

### 7.3 Why this is a Ground 1 issue

At Ground 0, binary directionality is abstract: for any two-primitive composition involving different role classes, exactly two orientations exist.

At Ground 1, Varoli specifies how this appears in the language:
- through the ordering of consonant and vowel characters
- through distinct directional readings (arrival vs departure, inward vs outward)
- through the structural non-reversibility of order

### 7.4 Transitional forms

CV and VC forms are the Varoli realization of what the blueprint describes as structures with binary directionality but no symmetric closure (Emergent Behavior 2). They are transitional: they lean in one direction and encode a relation between role classes. They do not close. They do not resolve around an attractor.

In Varoli grammar, these transitional forms are the primitive verbs.

---

## 8. Stability and Centered Closure in Varoli

The ICA defines stability through symmetric closure around a determinable attractor (Law 2), with center-governed interpretation (Law 3). This section documents how Varoli realizes these commitments, including the evolution in the language's own understanding of what centered closure requires.

### 8.1 The ICA commitment

Law 2 requires symmetric closure around a determinable attractor. The ICA does not specify what symmetric closure looks like in any particular implementation. It specifies the structural condition: resolved directional tensions, balanced around a center, readable from both directions.

### 8.2 Strict phonemic palindrome: the first mapped manifestation

Varoli's earliest and most explicit realization of symmetric closure was strict phonemic palindrome: structures that read identically from both directions at the character level. VCV forms (a substrate, a kinetic or operator at center, the same substrate repeated) are the simplest case. Larger palindromes such as `arOva` extend this pattern.

This realization was powerful and generative. It produced the primitive noun system, the elemental palindromes, and the self-crucible. It remains structurally valid. Phonemic palindrome is a clear, verifiable, unambiguous instance of symmetric closure.

Older canon drafts (historically under informal paths such as `varoli/core/06-generation-rules.md`, Rule 4) used the formulation "palindromic closure defines stability." Current direction is reflected in `../Ground-2/01-g2-varoli-conceptual-overview.md` and formalized in `../Ground-3/`; those legacy files are not present in this repository.

### 8.3 The current canon-level direction: attractor-centered structural balance

The current project understanding recognizes that strict phonemic palindrome was the first explicit manifestation of a deeper invariant. The deeper invariant is attractor-centered structural balance: stability is achieved when a composition resolves around a determinable attractor in a way that preserves centered closure, whether or not the surface form is a strict character-level palindrome.

This is not a rejection of phonemic palindrome. It is a recognition that the governing principle operates at a level above strict phonemic mirroring. Phonemic palindrome satisfies the principle. It may not be the only way to satisfy it.

The distinction matters because the language needs to scale. If stability is defined exclusively as strict phonemic palindrome, then every stable form at every scale must achieve character-level mirroring. If stability is defined as attractor-centered structural balance, then larger and more complex forms can achieve stability through centered closure that preserves the attractor without requiring literal mirroring at every level.

**What this means for Ground 1:** The adaptation of Law 2 is stated as follows. The ICA requires symmetric closure around a determinable attractor. Varoli realizes this as attractor-centered structural balance. Strict phonemic palindrome is the earliest, most explicit, and best-verified manifestation of that law. It remains valid and generative. The current canon-level direction treats attractor-centered structural balance as the deeper invariant that phonemic palindrome instantiates.

### 8.4 Attractor as language-specific realization of irreducible center

The ICA speaks of the irreducible center: the terminal condition of compression that preserves the identity of the structure.

Varoli realizes this as the attractor: the identity-bearing center of a stable form. The attractor is not just a middle position. It is the primitive around which centered closure occurs, from which interpretation begins, and which determines what the form structurally is.

### 8.5 Stable forms as a structural category

Varoli stable forms are not equivalent to the inherited grammatical category "noun." They are a structurally distinct category native to the language: attractor-centered stable structures in which a kinetic force or operator event is held in centered closure within a substrate domain.

The structural definition: a stable form is a composition that has achieved centered closure (Law 2) around a determinable attractor (Law 3). It is a resolved structure, not a label.

The teaching handle "noun" has been historically useful for some Ground 2 documents. It should be understood as secondary and approximate. The primary structural category is the attractor-centered stable form.

The descriptive vocabulary used in some Ground 2 documents (terms like "stable centered world" or "attractor-field") is experiential and mnemonic. It is not structural terminology. The structural definition above is the authority. Descriptive language may aid intuition but must not override or substitute for the structural definition.

### 8.6 Centered expansion derives from the blueprint

The claim that stable meaning scales by centered expansion (preserving the attractor and adding structure around it, rather than abandoning the center) is not an independent language-level assertion. It derives from the interaction of three ICA commitments:

1. Law 2 (stability through symmetric closure): stability requires centered closure around a determinable attractor. If expansion broke centered closure or replaced the attractor, the result would not be stable.
2. Law 3 (center-governed interpretation): interpretation begins from the center. If expansion proceeded by displacing the center, the identity of the structure would change rather than being enriched.
3. Emergent Behavior 3 (recursive stability): stable structures can nest within stable structures, each level achieving closure around its own attractor. Expansion is therefore not linear extension but concentric nesting.

Varoli realizes this through larger stable forms (such as `arOva`) in which the attractor center is preserved and additional layers contextualize it. The center remains identity-bearing. The outer layers add structural resolution without replacing the attractor.

Centered expansion is one of the most important language-level consequences of the blueprint. It governs how the lexicon can grow: by preserving the attractor, preserving centered balance, adding lawful surrounding structure, and increasing contextual resolution without replacing center identity.

### 8.7 Recursive stability and the self-crucible

Emergent Behavior 3 (recursive stability) is realized in Varoli through nested stable structures. A larger stable form may contain sub-structures that are themselves stable.

The self-crucible is the canonical proof object of recursive stability in the system. It is a nested structure in which all five elemental attractor pairs are held in centered closure around the operator at center. It is the first Yemu structure discovered, the proof object of the entire system, and the source from which the language names "Yemu" and "Varoli" were extracted. It is not merely an illustration or a poetic artifact. It is the canonical Yemu structure: the declaration of self inside breakthrough space, structurally complete and non-redundant.

---

## 9. From Primitive Composition to Larger Meaning

The ICA provides laws of compositional organization. Varoli extends those laws into a language-level larger-meaning architecture.

At Ground 1, the key point is this:

**Varoli does not stop at primitive instantiation. It also derives a native method for larger composition.**

That method is resolution-unit chaining, formalized in Ground 2 grammar documents. The following sections explain why this and other grammar-level developments are lawful language-specific outgrowths of the blueprint.

---

## 10. Superposition and Collapse in Varoli

The ICA defines explicit superposition and context-driven collapse (Law 4). Varoli realizes this through `y`.

### 10.1 Primitive-level adaptation

At the primitive level, the adaptation is clean:

- unresolvedness is structural, not accidental
- superposition is explicit, marked by `y`, not left implicit or vague
- collapse must be context-governed, determined by surrounding structure, not by external choice

This is one of the reasons Varoli cannot be reduced to a conventional grammatical system. It treats unresolvedness as a primitive structural possibility with its own class.

### 10.2 Extended compositional scope: a Ground 2 development area

The primitive-level mapping is settled. However, the compositional behavior of `y` in extended and cross-boundary contexts remains an active development area at Ground 2.

Specifically: operator scope (whether `y` governs only locally or can encompass force arriving from beyond the unit boundary) has not been formally derived. This is the acknowledged weakest link in the current grammar architecture. The blueprint requires that collapse be structurally determined (Law 4), but the blueprint does not specify how scope behaves at the larger-composition level. That is a question the language must resolve through its own development.

Ground 1 records that the primitive adaptation is complete while the compositional extension is in progress.

---

## 11. Resolution-Unit Chaining as Language Architecture

The ICA does not define "sentence" as a necessary universal category. Varoli correspondingly does not ground larger meaning in inherited clause logic.

Instead, Varoli derives the resolution unit as its native larger-meaning compositional unit. Resolution-unit chaining is now treated as real Varoli language architecture, not a tentative sketch. It is provisionally formalized in Ground 3 (`../Ground-4/Grammar-Architecture/05-g4-resolution-unit-chaining.md`), with unevenly supported edges explicitly marked there.

### 11.1 Derivation from ICA conditions

The resolution unit is defined by terminal behavior: close, project, or suspend. Each terminal state traces to ICA-derived structural conditions:

**Close** arises when a composition ends in a stable form. The stable form has achieved centered closure (Law 2). Force resolves locally through the containment relationship (kinetic within substrate, an application of Axiom 1: role classes interact but do not merge). No force is projected beyond the boundary. This is the language-level consequence of stability: a closed stable form absorbs and resolves directional force.

**Project** arises when a composition ends in a directional form (CV, VC, or bare kinetic). The form has binary directionality (Law 1) but no centered closure (it is transitional, per Emergent Behavior 2). Force cannot resolve locally because no stable domain is present to contain it. The force is therefore emitted beyond the unit boundary. This is the language-level consequence of directionality without closure.

**Suspend** arises when a composition ends in the operator. The operator marks the position as unresolved (Law 4: explicit superposition). The unit neither closes nor projects as directed force. It is held in a structurally defined unresolved state.

### 11.2 Cross-unit interaction

Cross-unit interaction follows from what a projected force encounters:

- **Resolution:** projected force reaches a later stable domain and resolves there through the containment relationship.
- **Suspension:** projected force reaches a later operator-held terminal and enters a composite unresolved state. (This depends on operator scope, which is not yet settled; see Section 10.2.)
- **Continuation:** projected force reaches another projecting form. Neither resolves nor suspends. Both forces persist. This is a default state requiring no positive mechanism.

These interactions are compositional consequences of the blueprint laws meeting language-level structure. They do not require imported conjunction, subordination, or clause logic.

### 11.3 Inter-force governance

When multiple forces resolve within the same stable domain, their relationship is provisionally differentiated by orientation:

- **Opposite-orientation** (CV meeting VC within a shared domain) is more relationally determinate. The directional asymmetry produces a structurally readable relationship: arrival meeting departure.
- **Same-orientation** (CV meeting CV, or VC meeting VC) is relationally open. The forces are co-present and co-directional. The chain specifies down to the domain layer and leaves the relational layer open.

This distinction is derived from binary directionality (Law 1) applied to multi-force compositions. It is not an imported grammatical category.

### 11.4 What makes this a lawful extension

Resolution-unit chaining is not a restatement of the blueprint. The blueprint does not define resolution units, terminal behavior, or cross-unit interaction. These are language-specific developments.

But they are lawful developments because every component traces to ICA commitments: binary directionality (Law 1), centered closure producing stability (Law 2), center-governed interpretation (Law 3), explicit superposition (Law 4), and the transitional/stable distinction (EB2). The language combined these structural conditions into a native compositional architecture. The result is a grammar that did not need to be imported because the blueprint's own structural conditions, once instantiated, produced the conditions from which it emerged.

### 11.5 What remains provisionally supported

Resolution-unit chaining is real architecture, but some edges have uneven support:

- **Deep reception** (projected force resolving in a subsequent unit's stable domain) is provisionally supported. Cross-boundary verification is weaker than within-form verification.
- **Extended operator scope** across boundaries is the weakest link in the chaining architecture. See Section 10.2.
- **Containment capacity** (whether a simple stable form can contain arbitrarily many forces) is untested beyond the three-force case.
- **Same-orientation governance** remains relationally open. Whether additional mechanisms can resolve the inter-force relationship in same-orientation pairs is untested.

Ground 2 documents mark these explicitly. Ground 1 records them so the bridge is honest about support levels.

---

## 12. Verb Layering as Provisional Grammar Mechanism

Verb layering is a working provisional grammar mechanism in which consonant suffixes qualify the kinetic force of a primitive verb.

Ground 1 includes it because it is now securely supported enough to work from, though it is not yet fully closed morphemic theory.

### 12.1 The mechanism

A consonant suffix following a CV verb contributes its invariant function as a qualification of the verb's force. The current best structural reading is that the suffix qualifies the preceding kinetic force rather than establishing an independent force-domain relationship.

Three suffixes have been tested: `-k` (completion/threshold), `-p` (ongoing pressure), `-d` (force opposition/resistance). Two-deep stacking has been tested. Suffix order is provisionally meaningful.

### 12.2 Interaction with chaining

In all tested cases, verb layering has not changed terminal behavior. A layered verb projects the same way a bare verb does. The compound force provisionally composes with the chaining architecture: it projects, it provisionally resolves through deep reception, and its qualifications provisionally survive cross-boundary transit.

### 12.3 Status

Verb layering is a grammar-level extension under test. Layered forms (CV+C, CV+CC) are not among the named patterns in the current locked core generation rules. The mechanism is motivated by existing structural properties but is not yet formally licensed through expanded generation rules or closed morphemic composition rules.

Ground 1 records it as a working provisional mechanism. Full formalization depends on morphemic composition rules, which are not yet closed.

---

## 13. Compression, Reconstruction, and Expression Modes

The ICA defines role-ordered compression (Law 5), reconstruction from the irreducible center (Law 6), and dual projection modes (EB1). Varoli realizes all three.

### 13.1 Compression

Varoli-to-Yemu compression follows role-ordered reduction. Kinetic class primitives (consonants) are the most sequence-dependent and compress first. Substrate class primitives (vowels) collapse toward the attractor. Operator class primitives (`y`) proliferate at positions where collapse to a single substrate would force a false resolution. The terminal condition is the irreducible center.

### 13.2 Reconstruction

Yemu forms can be expanded back toward full Varoli articulation because the compression is deterministic and role-ordered. The irreducible center plus the system's laws contain sufficient information for reconstruction. No external input is required (Law 6).

### 13.3 Varoli and Yemu as dual projection modes

Varoli and Yemu are the language-level realization of the two projection modes predicted by Emergent Behavior 1. This must be stated with maximum clarity:

**Varoli and Yemu share the same primitive architecture.** They do not differ in primitive inventory, role class definitions, or structural laws. They are not two languages with different classes. They are one architecture under two projection modes.

They differ in expression mode:
- **Varoli** is sequential, spoken, and time-bound. Primitives are encountered in order. Meaning unfolds progressively. This is sequential projection, arising from Law 1 (binary directionality).
- **Yemu** is simultaneous, center-outward, and non-spoken. The attractor is perceived first. The structure is registered, recognized, resolved, or declared, not spoken or read left-to-right. This is simultaneous projection, arising from Law 3 (center-governed interpretation) + Law 5 (role-ordered compression).

The two modes are not a design choice. They are an emergent consequence of the architecture. The language did not need to invent two expression modes. The blueprint produced the conditions from which both naturally arise.

---

## 14. What Varoli Adds Beyond the Blueprint

Ground 1 must distinguish inheritance from innovation. The blueprint gives the abstract architecture. Varoli adds:

### 14.1 A fully specified primitive inventory

Varoli does not merely posit role classes. It specifies 27 actual primitives: 5 vowel substrates, 21 consonantal kinetics (4 attractor + 17 general), and 1 operator.

### 14.2 Articulatory grounding

Varoli ties primitive classes to physical articulation. Each primitive has an articulatory basis that grounds its abstract function in a producible sound.

This is not required by the blueprint. It is a language-level implementation choice.

### 14.3 Scale realization and experiential register

Varoli allows the same invariant function to appear at different scales and in different experiential registers without changing the primitive function (Law 7 applied to the language domain).

This is a language-specific enrichment: the blueprint guarantees scale realization; Varoli specifies exactly how it manifests across internal, external, temporal, and dimensional axes.

### 14.4 Attractor-centered stable forms as a rich structural category

Varoli develops the blueprint's symmetric closure into a generative system of stable forms, with attractor marking, center-outward reading, and centered expansion. These forms carry structural identity, not merely formal balance. The evolution from strict phonemic palindrome toward attractor-centered structural balance is itself a discovery about what the ICA's stability law requires at the language level.

### 14.5 Resolution-unit chaining

Varoli derives a native larger-meaning architecture from the interaction of closure, projection, suspension, and reception. This is not blueprint vocabulary, but it is a lawful language-specific development from blueprint principles (see Section 11).

### 14.6 Verb layering as force qualification

Varoli develops consonant-suffix force qualification as a grammar-level mechanism for enriching verb meaning without changing terminal behavior. This is a provisional grammar innovation not anticipated by the blueprint (see Section 12).

### 14.7 Expression-mode divergence

Varoli and Yemu diverge in mode of expression while sharing the same primitive architecture. This divergence is not a departure from the blueprint. It is the language-level realization of Emergent Behavior 1 (see Section 13.3).

---

## 15. What Remains Explicitly Provisional

Ground 1 must be honest about what is not yet closed.

- **Morphemic composition rules:** How forms grow beyond CV/VC and VCV is not yet formally closed. This is the key upstream dependency for verb layering, expanded stable forms, and lexicon growth.
- **Full formal rule set for expanded stable forms:** The principle of centered expansion is established. The specific generation rules for all larger stable forms are not yet fully formalized.
- **Deep reception:** Cross-boundary containment is provisionally supported but not verified by a mechanism equivalent to palindromic closure operating across unit boundaries.
- **Operator scope across boundaries:** The weakest link in the grammar. Not formally derived.
- **Containment capacity:** Whether a simple stable form can contain arbitrarily many forces is untested beyond three.
- **Same-orientation inter-force governance:** Relationally open. Whether additional mechanisms exist is untested.
- **Negation-adjacent architecture:** Two mechanisms tested (suffix opposition, operator suspension). Whether they are collectively sufficient or whether a dedicated negation mechanism is needed remains open.
- **Suffix admission:** Which consonants may serve as verb suffixes is not closed beyond three tested cases.
- **Propagation of current canon-level direction into published canon:** Legacy generation-rule drafts (notably Rule 4 in older `06-generation-rules.md` paths) still carry older formulations where they exist outside this tree. Within this repository, align `../Ground-2/` and downstream `../Ground-3/` to attractor-centered structural balance as the deeper stability invariant.

---

## 16. What Ground 1 Must Not Do

A proper adaptation document must preserve boundaries.

### 16.1 It must not rewrite Varoli in blueprint terms alone

Blueprint terms are useful for mapping, but Varoli must remain expressible in its own native language terminology. If Ground 2 documents begin reading like blueprint restatements, something has gone wrong.

### 16.2 It must not treat the blueprint as a replacement for language canon

The blueprint is the abstract source. The language canon is the authoritative language-level realization. In any conflict, language canon takes precedence (per the authority hierarchy in the system instructions).

### 16.3 It must not flatten language-specific discoveries into abstract restatement

Developments like centered stable forms and resolution-unit chaining are not trivial restatements of the blueprint. They are real language-specific elaborations that required derivation and testing. Ground 1 should trace their derivation path, not reduce them to abstract labels.

### 16.4 It must not import categories from other ICA implementations

Each implementation must get its own Ground 1 adaptation layer. Terms and mechanisms from another domain may illuminate structure, but they may not overwrite Varoli's own realization.

---

## 17. What Ground 1 Is For

This document is useful because it makes four kinds of work easier:

1. **Documentation clarity.** It shows how Varoli grows out of ICA without collapsing into it.

2. **Drift prevention.** It prevents both blueprint erasure (treating the architecture as optional) and language erasure (treating the language as merely an illustration of the blueprint).

3. **Cross-domain comparison.** It allows future ICA implementations to be compared at the adaptation layer rather than by forced direct analogy between implementation-specific terms.

4. **Development sequencing.** It helps identify which later language developments are direct architectural inheritances, which are lawful language-specific elaborations, and which are still-open questions.

---

## 18. Summary

The ICA is Ground 0: abstract architecture. Three axioms, seven derived laws, three emergent behaviors.

Varoli Ground 1 is the adaptation layer in which ICA becomes a language. In this layer:

- substrate class becomes vowels (5 elemental substrates)
- kinetic class becomes consonants (21 kinetic forces)
- operator class becomes `y` (one operator)
- binary directionality becomes CV / VC ordering
- stability through symmetric closure becomes attractor-centered stable forms; strict phonemic palindrome is the first mapped manifestation, with the current canon-level direction recognizing attractor-centered structural balance as the deeper invariant
- center-governed interpretation becomes attractor-first reading
- explicit superposition becomes operator-governed unresolvedness, with extended compositional scope still in development
- role-ordered compression and reconstruction become the Varoli-to-Yemu compression path
- scale realization becomes the multi-scale primitive schemas
- dual projection modes become the Varoli/Yemu expression-mode distinction: same architecture, different projection mode
- transitional/stable distinction becomes the verb/stable-form structural difference
- recursive stability becomes nested stable forms, with the self-crucible as the canonical proof object

Varoli then extends this architecture through language-specific realization:
- articulatory grounding
- invariant primitive schemas with full definitional fields
- attractor-centered stable forms as a generative structural category, governed by centered expansion
- resolution-unit chaining as a native larger-meaning architecture with terminal behavior, cross-unit interaction, and inter-force governance
- verb layering as a provisional grammar mechanism for force qualification
- expression-mode divergence between Varoli and Yemu

Ground 1 does not replace either the blueprint or the language canon. It bridges them. Its task is to show how the architecture becomes this language while preserving the integrity of both, and to record where the language's current understanding has advanced beyond older formulations so that Ground 2 revisions can follow.