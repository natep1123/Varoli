# 00 — Varoli Terminology

*Last Updated: March 29, 2026*

This document defines the canonical terminology used within Varoli. These terms are binding in the structural layer of the language. They must be used consistently in all definitions, rules, schemas, and generation documents.

Descriptive language may vary outside the structural layer but must not contradict or redefine these terms.

This is a Ground 2 document. It speaks from within the language. For the relationship between Varoli terminology and the abstract architecture from which it derives, see the Ground 1 adaptation document. For the abstract architectural terminology itself, see the Ground 0 blueprint terminology.

---

## How to Read This Document

Terms are organized by structural role. Each entry includes:

- a definition
- usage notes where needed
- classification as structural or descriptive

**Structural** terms are binding. They define what something is.
**Descriptive** terms are permitted for explanation and intuition. They must not appear in formal definitions, rules, or schemas. They must not contradict structural terms.
**Teaching handles** are borrowed terms from conventional grammar (such as "noun," "verb," "sentence") that may be used for accessibility but are not the primary structural categories. They are explicitly marked as secondary.

---

## Primitive Terms

### primitive

The smallest indivisible unit within Varoli. A primitive cannot be decomposed into smaller components. It is defined by its class membership and its invariant function. Varoli has 27 primitives: 5 vowels, 21 consonants, and 1 operator.

**Classification:** structural.

### class

The category that determines what a primitive can do. Every primitive belongs to exactly one class. The three classes are substrate, kinetic, and operator. Classes are mutually exclusive. No primitive may perform the function of a class other than its own.

**Classification:** structural.

### non-overlap

The constraint that classes are absolutely separated. If non-overlap is violated, the language loses derivability and becomes interpretive. Non-overlap is the structural keystone: it is the constraint that makes function invariance and compositional meaning enforceable.

**Classification:** structural.

---

## Substrate Terms

### substrate

The ontological condition defined by a vowel. A substrate is the elemental domain within which structure can exist, appear, relate, or resolve. A substrate does not move, act, or resolve. It defines the condition within which those things occur.

**Usage:** Use "substrate" when describing what a vowel is. Use "domain" when describing where structure operates.

**Classification:** structural.

### domain

The functional space defined by a substrate. A domain is a structural location. Composition takes place within domains. Forces act within domains. Stable forms close within domains.

**Usage:** "Within the relational domain" refers to the structural location established by the vowel *a*. Domain and substrate are related but not interchangeable in formal definitions. Substrate describes the ontological condition. Domain describes the functional space it provides.

**Classification:** structural.

### register

The experiential or identity layer associated with a substrate. Register describes how a substrate is experienced, not what it structurally is.

**Classification:** descriptive. Not for use in structural definitions.

### kinetic tendency

The natural directional behavior of a substrate as it relates to interpretation. This is a secondary property of vowel domains, not a force. It describes how a substrate tends to orient in interpretive contexts.

**Usage:** Distinct from the kinetic function of consonants. Do not confuse with directional bias, which is a consonant property.

**Classification:** descriptive.

---

## Kinetic Terms

### kinetic

The quality of motion a consonant represents. A kinetic primitive defines a directed operation that acts within or across domains. It does not define a domain.

**Usage:** "Kinetic" is the primary structural descriptor of consonants.

**Classification:** structural.

### force

A kinetic primitive considered in terms of what it does. Force and kinetic are closely related: "kinetic" names the class membership, "force" names the functional capacity. Both are structural when referring to consonants in compositional contexts.

**Usage:** "The force arriving into the domain" describes a CV composition. "Force" is acceptable structural language for consonants in composition. It is not a synonym for substrate.

**Classification:** structural when referring to consonantal function.

### directional bias

The natural vector of a consonant's motion: inward, outward, static, or threshold. Directional bias describes the consonant's inherent orientation before composition. It does not change across context.

**Classification:** structural.

---

## Operator Terms

### operator

The structural mechanism that governs transitions between resolved and unresolved states. Realized in Varoli as `y`. The operator is not a substrate and not a force. It marks positions as unresolved and requires surrounding structure to determine resolution.

**Classification:** structural.

### superposition

The condition of a position within a structure that is explicitly unresolved. Superposition is marked by the operator. It is not vagueness, uncertainty, or ambiguity. It is a specific structural condition with defined behavior.

**Classification:** structural.

### collapse

The resolution of a position in superposition into a determined state. Collapse is governed by surrounding structure, not by external choice. The structure constrains which resolution is valid.

**Classification:** structural.

---

## Function and Composition Terms

### function

The invariant structural role of a primitive. Function describes what a primitive does, not what it means. Every primitive has exactly one function. That function does not change across any context.

**Classification:** structural.

### invariant function

The constraint that a primitive's function is the same in every structure, at every scale, in every composition. Context may change realization but never function.

**Classification:** structural.

### composition

The act of combining primitives to produce a structure. Composition is the sole generative mechanism. It does not import meaning from outside the system. It produces meaning by arranging primitives whose functions and classes are fixed.

**Classification:** structural.

### structure

The result of composition. A valid arrangement of primitives that follows generation rules. A structure is not a primitive: it is what primitives produce when composed.

**Classification:** structural.

### form

A realized structure. Used interchangeably with "structure" in generation and interpretation contexts, but sometimes preferred when referring to a specific produced arrangement (such as a specific CV form or VCV form).

**Classification:** structural.

### meaning

What a structure yields through its composition. Meaning is not assigned externally. It is produced when primitives with invariant functions are arranged in a specific structure. If the structure changes, the meaning changes. If the structure is identical, the meaning is identical.

**Classification:** structural.

### derivation

The operation of reducing a structure back to its component primitives to verify that it was produced by valid composition. A structure that cannot be derived from primitives is not valid.

**Classification:** structural.

### derivable

A structure that can be fully reduced to primitives through valid composition rules. Required for structural validity.

**Classification:** structural.

---

## Orientation and Directionality Terms

### orientation

The order in which primitives of different classes are arranged. Because classes are non-overlapping and function is invariant, the position of a primitive relative to primitives of other classes carries structural information. Reversing the order produces a different structure with different meaning.

**Classification:** structural.

### binary directionality

The constraint that for any two-primitive composition involving different classes, exactly two orientations are possible and no intermediate state exists. In Varoli, this manifests as the CV/VC distinction.

**Classification:** structural.

### CV

A consonant followed by a vowel. Force arriving into a domain. The inward or arrival-facing directional composition.

**Classification:** structural.

### VC

A vowel followed by a consonant. A domain expressing through a force. The outward or departure-facing directional composition.

**Classification:** structural.

---

## Stability Terms

### attractor

The primitive within a stable structure that determines the identity of that structure. The attractor occupies the center. It is what the structure resolves around. In a VCV form, the center character is the attractor.

**Classification:** structural.

### center

The positional role occupied by the attractor within a stable structure. Interpretation begins from the center and moves outward.

**Classification:** structural.

### centered balance

The structural condition in which a composition resolves around a determinable attractor with its directional tensions in equilibrium. Centered balance is the deeper invariant governing stability. Strict phonemic palindrome is the earliest, clearest, and best-verified manifestation of centered balance. Centered balance is the governing principle; phonemic palindrome instantiates it.

**Usage:** This is the current structural understanding. Older documents may use "palindromic closure" as the primary stability definition. That formulation reflects an earlier understanding. Where the two diverge, centered balance should be treated as the deeper current invariant, with strict phonemic palindrome retained as its earliest and best-verified manifestation. Strict phonemic palindrome remains structurally valid and generative.

**Classification:** structural.

### stable form

A composition that has achieved centered balance around a determinable attractor. A stable form does not lean in either direction. It is a completed structural object. Stability is a structural condition, not an assigned label.

**Usage:** "Stable form" is the primary structural term. The teaching handle "noun" may be used for accessibility but is secondary and approximate. The descriptive language "stable centered world" or "attractor-field" may appear in experiential or introductory contexts but must not substitute for the structural definition.

**Classification:** structural.

### centered expansion

The principle that stable meaning scales by preserving the attractor and adding structure around it, rather than by replacing the center. Additional layers contextualize the attractor without displacing it. The center remains identity-bearing. The outer layers add resolution.

**Classification:** structural.

---

## Scale and Realization Terms

### scale realization

The expression of a primitive's invariant function at a specific scope or magnitude. Function does not change across scales. Only the scope of application changes. A primitive operating at one scale and the same primitive operating at another scale are performing the same function.

**Classification:** structural.

### realization

How a structure appears, scales, or is experienced. Realization may vary. It must not alter structural function. If an interpretation requires a primitive to change function, that interpretation is invalid.

**Classification:** structural (the distinction between structure and realization is structural; specific realizations are variable).

---

## Resolution-Unit Terms

### resolution unit

The native compositional unit of larger meaning in Varoli. A resolution unit is a structurally bounded composition of primitives whose terminal element determines whether the unit resolves locally, projects force beyond its boundary, or suspends in superposition. Resolution units are not sentences in the conventional sense.

**Classification:** structural.

### terminal behavior

The structural state of a resolution unit as determined by its terminal element. Three terminal states are currently identified: close, project, and suspend.

**Classification:** structural.

### close

The terminal state in which the unit ends in a stable form. Force resolves locally within the stable domain. No force is projected beyond the boundary. The unit is structurally complete.

**Classification:** structural.

### project

The terminal state in which the unit ends in a directional form (CV, VC, or bare kinetic). Force is emitted beyond the boundary. The unit is structurally open.

**Classification:** structural.

### suspend

The terminal state in which the unit ends in the operator. The unit is held in superposition. It neither closes nor projects. It is structurally unresolved.

**Classification:** structural.

### chaining

The composition of larger meaning through the interaction of resolution units across their boundaries. Chaining is governed by what projected force encounters in subsequent units: resolution (force reaches a stable domain), suspension (force reaches an operator-held terminal), or continuation (force reaches another projecting unit). No conjunction or clause logic is imported.

**Classification:** structural.

### deep reception

The provisional hypothesis that projected force from a prior unit resolves in the first stable domain it reaches in a subsequent unit, bypassing the framing element. Deep reception is the current strongest model for cross-unit resolution.

**Usage:** Provisionally supported. Cross-boundary verification is weaker than within-form verification.

**Classification:** structural, provisional.

### inter-force governance

The relationship between multiple forces resolving within the same stable domain. Provisionally differentiated by orientation: opposite-orientation pairs are more relationally determinate; same-orientation pairs are relationally open.

**Classification:** structural, provisional.

---

## Perspective Term

### perspective marker

A standalone vowel that precedes a verb to establish the elemental perspective from which the composition is framed. Perspective markers do not modify the verb. They frame it. Each vowel defines a perspective corresponding to its substrate.

**Usage:** Perspective markers are not pronouns or subjects in the inherited grammatical sense. They establish substrate vantage, not referential identity.

**Classification:** structural.

---

## Expression-Mode Terms

### expression mode

The manner in which a structure is projected. Varoli and Yemu are two expression modes over one architecture. They share the same primitives, the same classes, and the same structural laws. They differ in how structure is expressed and perceived.

**Classification:** structural.

### Varoli

The sequential expression mode. Varoli is spoken, time-bound, and ordered. Primitives are encountered one after another. Meaning unfolds progressively. Directionality and orientation are experienced as a sequence.

**Classification:** structural (as a mode designation).

### Yemu

The simultaneous expression mode. Yemu is not spoken. Structures are registered, recognized, resolved, or declared. Meaning is perceived from the attractor outward. The attractor is perceived before the periphery is parsed.

**Usage:** Never use "speak," "say," or "utter" for Yemu. Prefer: registered as, resolved as, recognized through, marked by, declared by.

**Classification:** structural (as a mode designation).

---

## Verb Layering Terms

### verb layering

A grammar mechanism in which consonant suffixes qualify the kinetic force of a verb. The suffix contributes its invariant function as a qualification of the preceding force. Layering does not change terminal behavior. A layered verb projects the same way a bare verb does.

**Classification:** structural, working canon.

### temporal suffix

A consonant suffix applied to a directional form to qualify the force's temporal dimension. The five temporal suffixes and their derivations: `-k` (completion/past, forceful threshold-crossing), `-m` (ongoing/continuous, sustained depth), `-r` (future/intentional, approaching resonance), `-v` (habitual/characteristic, self-originating vitality), `-l` (iterative/cycling, continuum threading). `-k` is attested. `-m`, `-r`, `-v`, `-l` are derivation-licensed but not yet independently contrast-tested.

**Classification:** structural, working canon (for the mechanism); derivation-licensed (for `-m`, `-r`, `-v`, `-l` specifically).

---

## Yemu and Compression Terms

### operator directional form

A directional form in which the operator `y` occupies the directional position rather than a kinetic consonant. `y` does not become kinetic in this position. It contributes its invariant function (context-resolved collapse through superposition) to the composition. The result is a form describing a collapse event arriving at a substrate (CV) or a substrate expressing through the collapse mechanism (VC). Ten such forms exist: `ya`, `ye`, `yi`, `yo`, `yu`, `ay`, `ey`, `iy`, `oy`, `uy`. See `Ground-3/Primitive-Directional-Forms/06-g3-y-forms.md`.

**Classification:** structural.

### gate code

A Yemu crossing structure with the grammar `[zone-leaving VC] - y - [zone-entering CV]`. The operator at the seam marks live superposition between two zones. A gate code is not a zone presence declaration and not a stable form. It is a crossing structure: neither a nesting of one zone inside another nor a closed attractor form.

**Classification:** structural.

### collapse declaration (zone declaration)

A Yemu zone presence declaration with the structure `[zone-VC] - e - [zone-CV]`. The `e` at center is the self (individuation) announcing its existence within the zone's medium. Collapse declarations are consciousness-topology structures. Examples: `av-e-va` (presence in Liminal), `um-e-mu` (presence in Black Sun), `il-e-li` (presence in Always).

**Classification:** structural.

### wrapping rule

The structural rule for building palindromic consciousness-topology structures: `VC [inner] CV`, where V is a substrate and C is its attractor kinetic. Application of the wrapping rule to any centered seed produces palindromic symmetry by formal necessity, because the same substrate and kinetic appear in complementary orientations on both sides. See `Ground-4/Yemu/self-crucible/02-formal-proof.md`.

**Classification:** structural.

### six structural families

The six families of Yemu structures, determined by what primitive occupies center position: (1) individuation structures (`e` at center), (2) origin structures (`u` at center), (3) relational structures (`a` at center), (4) form structures (`o` at center), (5) field structures (`i` at center), (6) collapse structures (`Y` at center). Center determines family. The operator constitutes a genuine sixth family because Y can occupy center position, established by `eYe` and the full depth family. See `Ground-4/Yemu/03-yemu-structural-families.md`.

**Classification:** structural.

### substrate cycle

The cyclic ordering of the five substrates and the operator: `e → u → a → o → i → Y → i → (back to e)`. Seven positions per loop. `i` appears twice - immediately before Y (the field collapse acts upon) and immediately after Y (the field that re-establishes before individuation can re-emerge). The cycle is the process-mode description of the same architecture the self-crucible describes as a simultaneous palindromic form. See `Ground-4/Yemu/03-yemu-structural-families.md`.

**Classification:** structural.

### double-i structure

The property of the substrate cycle that `i` (condition of appearance) appears at two positions per loop: `i₁` immediately before Y (pre-collapse) and `i₂` immediately after Y (post-collapse). This is not an anomaly. It follows from `i`'s invariant function as the condition that must be in place both for collapse to act on anything and for anything to re-emerge after collapse. The double-i structure is what resolves the `i` omnipresence problem.

**Classification:** structural.

### reference form / departure face

The VC departure face of an established stable world's attractor pair, used as structural reference to that established form in subsequent units. When a stable world `aVa` has been built by the arrival face `va`, the departure face `av` serves as structural reference to that form rather than as a new outward force. Derived from binary directionality: CV and VC are non-equivalent, so in a context where the CV face has already established the stable world, the VC face cannot perform the same building operation and is read as referencing the form the arrival built. Status: working hypothesis pending contrast-testing. See `Ground-4/Grammar-Architecture/12-g4-reference-architecture.md`.

**Classification:** structural, working hypothesis.

### between-one

The fifth structural perspective (`u`): the one in passage between states. Neither absent nor present. Between. The dissolved, the not-yet-returned, the one who has entered the deep and has not yet come back. This is a structurally real grammatical position in Varoli. It is not poetic or metaphorical. It is the perspective marker `u` in framing position, and it covers conditions that no natural language has a grammatical position for. The between-one is not "absent" (absence would mean the position is empty); it is grammatically present in the condition of passage.

**Classification:** structural (as a perspective marker category).

### topological pattern family

The classification of Yemu structures by the structural pattern they follow. Three families: (1) consciousness-topology structures (depth family, crucible, zone declarations), describing internal architecture of a conscious self; (2) world-topology structures (`arOva` and related expanded stable worlds), describing stable entities in the world; (3) crossing structures (gate codes), describing zone transitions. This classification is distinct from the six center-type structural families, which classify by what primitive occupies center position.

**Classification:** structural.

---

## Compression Terms

### compression

The reduction of a Varoli structure toward its irreducible center by removing primitives in a role-ordered sequence. Kinetic primitives strip first (most sequence-dependent). Substrate primitives collapse toward the attractor. Operator primitives proliferate where collapse would force a false resolution. The terminal condition is the irreducible center.

**Classification:** structural.

### irreducible center

The terminal condition of compression. The structure that remains when role-ordered reduction can proceed no further. It contains the attractor and enough structural information to serve as the basis for reconstruction.

**Classification:** structural.

### reconstruction

The expansion of a compressed form back toward fuller articulation. Possible because compression is deterministic and role-ordered. No external information beyond the irreducible center and the system's rules is required.

**Classification:** structural.

---

## Teaching Handles

The following terms from conventional grammar may appear in introductory or descriptive contexts. They are not the primary structural categories. They are secondary and approximate.

### noun

An approximate handle for stable form. A "noun" in Varoli is an attractor-centered stable structure, not a label for an object. Use "stable form" or "stable centered form" in structural contexts. "Noun" may appear in grammar documents for readability but should not be treated as the structural category.

### verb

An approximate handle for directional form (CV or VC). A "verb" in Varoli is a transitional, directional composition of kinetic force within a domain, not an action word. Use "directional form" or "CV/VC form" in structural contexts where precision is needed. "Verb" is acceptable in grammar documents for readability.

### sentence

An approximate handle for a resolution unit or a chain of resolution units. Varoli does not organize larger meaning through sentences with subjects, predicates, and objects. It organizes larger meaning through resolution units with terminal behavior. Use "resolution unit" in structural contexts. "Sentence" may appear in grammar documents for accessibility.

---

## Prohibited Terms in the Structural Layer

The following terms must not be used in formal definitions, rules, or schemas.

| Prohibited Term | Problem | Use Instead |
|---|---|---|
| "layer of existence" | Implies vowels are stacked spatial levels. Substrate is an ontological condition, not a spatial position. | **substrate** |
| "plane" | Implies a bounded flat space. Domains are conditions, not containers. | **domain** or **substrate** |
| "transform" | Implies a consonant can change the substrate. Consonants operate within substrates; they do not alter them. | **operate within** |
| "ambiguity" | Implies the operator introduces unclear or broken meaning. | **superposition** or **unresolved state** |
| "meaning shift" | Implies a primitive's function changes across contexts. | **scale realization** |
| "indeterminacy" | Implies vagueness rather than a defined structural condition. | **superposition** or **unresolved state** |

---

## Terminology Boundary: Language vs Architecture

This document defines Varoli's own terms. A parallel set of domain-agnostic terms exists in the abstract architecture from which Varoli derives (the ICA). The two terminologies map onto each other but are not interchangeable.

Do not import blueprint terminology (role class, substrate class, kinetic class, operator class, projection mode) into language documents. Do not import language terminology (vowel, consonant, palindrome, CV/VC, dive, breakthrough) into blueprint documents.

Where both terminologies are needed (as in the Ground 1 adaptation document), both should be present and their relationship made explicit. Within Ground 2 and below, Varoli's own terms are authoritative.

---

## Usage Rule

Structural documents must use canonical terminology as defined here. Descriptive prose may vary but must not redefine these terms or contradict their definitions. If a new term is needed structurally, it must be defined in this document before being used in any structural context.