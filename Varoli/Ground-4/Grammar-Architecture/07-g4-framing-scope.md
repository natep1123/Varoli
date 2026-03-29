# 07 — Framing Scope

*Last Updated: March 27, 2026*

**Status:** Provisional Structural
**Layer:** Ground 4 / Grammar-Architecture
**Authority:** Structural
**Scope:** Investigates whether scope in Varoli is a consequence of resolution behavior rather than an imported syntactic mechanism, and tests whether three currently separate open problems share a common structural basis.

---

## 1. Purpose

This document develops and formalizes the resolution-governed scope hypothesis for Varoli.

Three currently separate open problems in the chaining architecture can all be read as scope questions: perspective marker scope, operator scope across unit boundaries, and deep reception targeting. This document asks whether they share a common structural basis. If they do, a single principle would advance all three simultaneously without introducing new primitives or importing syntactic mechanisms.

The document is explicitly a hypothesis under test. The perspective-marker case is the strongest and best-tested instance. The deep-reception case is strong and promising. The operator cross-boundary case is the weakest and remains the most provisional. These confidence levels are maintained throughout and are not flattened.

---

## 2. Why the Language Needs This Category Now

Three open problems in the current architecture each involve scope and are currently treated as independent:

**Perspective marker scope.** A substrate primitive in unit-initial framing position frames the entire resolution unit. This scope behavior is observed across all tested cases but is not derived from a named structural rule. What determines how far the marker's framing extends and what terminates it is not yet formally stated.

**Operator scope across boundaries.** When a unit ends in the operator, does the operator's suspension encompass only the unit's own force or does it also encompass incoming projected force from a prior unit? This is the acknowledged weakest link in the chaining architecture. It is a scope question: how far does the operator's governance extend beyond the unit that contains it?

**Deep reception targeting.** Projected force resolves in the first stable domain it reaches in a subsequent unit. What determines "first"? Does the perspective marker of the receiving unit interact with incoming force, or is it transparent to it? This is a scope question about what an arriving force can reach and what, if anything, stands between the force and its resolution target.

These three problems are currently handled locally in the chaining document. If they share a common structural basis, that basis should be named and developed rather than left implicit across three separate treatments.

---

## 3. Strongest Current Hypothesis

**Scope in Varoli is resolution-governed.** A structural element's influence extends until something resolves it.

More precisely: a structural element that is not itself resolved -- not contained, not closed, not collapsed -- extends its governance forward through the composition until a resolution event terminates or absorbs it. The boundary of scope is not determined by syntactic position or by an imported scope rule. It is determined by the presence or absence of a resolution event.

This hypothesis does not introduce a new mechanism. It is a claim about what the existing structural properties already produce. Resolution events are already defined: containment closes forces within stable domains, centered closure terminates units, and superposition marks positions as unresolved. The hypothesis says that elements which have not yet encountered a resolution event continue to extend until they do.

---

## 4. The Three Cases

### 4.1 Perspective marker scope

**Confidence: strongest current case.**

A substrate primitive in unit-initial framing position has no local force relationship and no closure. Nothing in the unit-initial position contains a bare substrate in framing position. The marker is not a stable form and does not close. Under resolution-governed scope, the marker's framing therefore extends until the unit resolves. The unit boundary -- the point of closure, projection, or suspension -- is the natural terminus of its scope.

This is not a special rule introduced for perspective markers. It is the consequence of having no resolution event that would terminate the marker's framing before the unit boundary. The perspective-marker case is the strongest current instance of resolution-governed scope because it is the most directly testable: the marker's framing consistently extends to the unit boundary in all tested cases, and no tested case has produced a resolution event that terminates the marker's scope earlier.

This formulation is already locked in `03-g4-perspective-markers.md` as the substrate-in-framing-position formulation. The resolution-governed scope hypothesis provides the deeper architectural basis for why that formulation holds. The two documents are consistent and mutually reinforcing: the perspective-marker document locks the formulation; this document develops the principle that explains it.

### 4.2 Projected force and deep reception targeting

**Confidence: strong and promising, more inferential than the perspective-marker case.**

A projected force has no local resolution target within its originating unit -- that is the definition of projection. Under resolution-governed scope, the force therefore extends forward until it encounters a stable domain that can contain it (resolution), an operator that holds it in superposition (suspension), or neither (continuation).

This provides a unified account of deep reception targeting without requiring a separate targeting mechanism. The force does not "target" a stable domain. It extends until a stable domain resolves it. The first stable domain it reaches is the first structure capable of containing it, and containment is what terminates its forward extension.

This also accounts for the perspective marker's transparency to incoming force without requiring a separate transparency rule. The perspective marker of a receiving unit is a bare substrate in framing position. It is not a stable form and cannot contain a kinetic force. The arriving force passes through to the first structure that can resolve it because the marker is not a resolution event for kinetic force. This is a consequence of the hypothesis, not an additional stipulation.

The inferential element: within-unit behavior is directly testable through composition. Cross-boundary extension of force is less directly verifiable. The hypothesis predicts clean behavior, and the tested complex-composition patterns in `05-g4-resolution-unit-chaining.md` are consistent with it, but cross-boundary resolution-governed scope is not verified by a mechanism equivalent to palindromic closure confirming within-unit containment.

### 4.3 Operator scope across unit boundaries

**Confidence: weakest case. Explicitly provisional.**

When a unit ends in the operator, the operator marks a position as unresolved. Nothing within the unit resolves it. Under resolution-governed scope, the operator's superposition therefore extends forward. The question is whether incoming projected force from a prior unit falls within that scope.

The resolution-governed hypothesis predicts that the operator's scope extends until collapse occurs. Whether the arrival of projected force constitutes a structural event that triggers collapse -- or whether the operator encompasses the arriving force into its superposition -- is the question the hypothesis does not yet answer. Both outcomes are consistent with resolution-governed scope. The hypothesis narrows the question but does not resolve it.

This is the weakest case for three reasons. First, operator scope in cross-boundary contexts has not been formally derived from existing architecture. Second, the question of what constitutes collapse in a cross-boundary context is not settled. Third, the two possible outcomes (force arrival triggers collapse; operator encompasses arriving force) have not been tested against a distinguishing case. The current lean toward extended suspension in `05-g4-resolution-unit-chaining.md` is consistent with the hypothesis but remains a lean, not a result.

---

## 5. What Framing Scope Explains Already

### 5.1 Why perspective markers frame whole units rather than adjacent elements only

Under resolution-governed scope, the marker extends because nothing resolves it locally before the unit boundary. If a mechanism existed that resolved the marker's framing after only the adjacent directional force, the scope would terminate there. No such mechanism exists in the current architecture. The marker's framing therefore extends to the unit boundary. This follows from the hypothesis without a separate scope rule for perspective markers.

### 5.2 Why deep reception bypasses the perspective marker of the receiving unit

The perspective marker of the receiving unit is a substrate primitive in framing position. It is not a stable form. A stable form is what closes a kinetic force through containment. The arriving force extends until it reaches a structure that can resolve it. The marker is not that structure. The force therefore continues to the first stable domain. This is a consequence of resolution-governed scope plus the definition of containment, not a separate transparency property.

### 5.3 Why continuation is a default state rather than a governed interaction

Under resolution-governed scope, projected force that encounters another projecting unit has met nothing that resolves it. The second unit's perspective marker cannot contain it. The second unit's directional force does not resolve it. Both forces therefore persist forward. Continuation requires no dedicated mechanism. It is the structural state that obtains when resolution-governed extension meets no resolution event.

### 5.4 A testable prediction

If perspective marker framing scope terminates at the unit boundary while kinetic force projects beyond it, the two elements follow different scope paths because they belong to different role classes. A substrate marker in framing position does not project force. Its framing is unit-internal. A kinetic force without a resolution target does project. The receiving unit's perspective marker therefore provides a fresh frame for the resolved force rather than the originating unit's marker governing the force at its destination.

This predicts: a force that originates in a unit framed by perspective `e` and resolves within a unit framed by perspective `a` is read through the receiving unit's frame, not the originating unit's. Constructing and verifying this case is the most direct available test of the hypothesis.

---

## 6. What Framing Scope Is Not

**Not syntactic scope.** Syntactic scope in conventional linguistics is tree-based: an element's scope is determined by its position in a hierarchical phrase structure. Varoli does not have phrase structure trees. If resolution-governed scope holds, scope in Varoli is determined by the presence or absence of resolution events, not by hierarchical dominance.

**Not a new primitive mechanism.** The hypothesis makes no claim that requires a new role class, a new primitive, or a new structural rule. It claims that scope is a consequence of existing structural conditions: resolution behavior, containment, closure, and superposition. The hypothesis is that these existing conditions already produce scope behavior, and that naming the principle makes the behavior derivable rather than observed case by case.

**Not unlimited by default.** Resolution-governed scope does not mean structural elements extend indefinitely. It means they extend until resolved. Resolution events are real structural boundaries. The hypothesis predicts bounded scope whose boundaries are determined by resolution rather than by imported syntactic rules.

**Not yet proven for the operator case.** The perspective-marker and deep-reception cases are strong enough to guide downstream work. The operator cross-boundary case is not. The hypothesis is applied with different confidence levels across the three cases. The operator case should not be treated as resolved on the basis of this document.

---

## 7. Open Questions

### 7.1 Does the hypothesis formally resolve operator scope?

The hardest case. For the perspective marker and for projected force, the hypothesis produces clean predictions consistent with observed behavior. For the terminal operator, the prediction is that its superposition extends until collapse occurs. What constitutes collapse in a cross-boundary context is not answered by the hypothesis alone. Two outcomes remain possible: the arriving force triggers collapse, or the operator encompasses the arriving force. The hypothesis is consistent with both. A distinguishing test case is required.

### 7.2 Is resolution-governed scope derivable or must it be stated as a rule?

The hypothesis claims scope is a consequence of existing structural properties, not a new mechanism. But consequences sometimes require explicit statement to function as derivable rules. Whether resolution-governed scope can remain implicit or must be stated as a formal principle in the blueprint is a Ground 0 question flagged here and not resolved here.

### 7.3 Does framing scope compose cleanly in multi-unit chains?

In a multi-unit chain, if Unit 1 projects and Unit 2 has its own perspective marker, the framing scope of the marker and the kinetic scope of the projected force overlap in the interaction zone. The hypothesis treats them as structurally distinct because they belong to different role classes: substrate framing and kinetic projection are not the same kind of extension. Whether they compose cleanly across all untested multi-unit cases has not been verified.

### 7.4 Does a projecting unit's perspective marker scope terminate at the unit boundary?

Under the hypothesis, a substrate marker in framing position does not project and does not cross the unit boundary with the kinetic force. The marker's framing is unit-internal. This is a specific prediction that distinguishes substrate-class framing scope from kinetic-class projection scope. It has not been independently tested and should be treated as a prediction pending verification.

---

## 8. Propagation Targets

**Conditional on further testing:**
If the perspective-marker case and its core framing prediction in Section 5.4 continue to hold under targeted testing, add resolution-governed scope to `../../Ground-2/00-g2-varoli-terminology.md` as a provisional structural principle.
- Revise the discussion of perspective marker scope, operator scope, and deep reception targeting in `05-g4-resolution-unit-chaining.md` to reference the common principle rather than treating each as an independent problem.
- Update `../../Ground-2/01-g2-varoli-conceptual-overview.md` if status strengthens.

**Immediate:**
- Use this document as the reference for the broader framing-scope hypothesis when other Ground 3 documents need to address scope questions. Do not restate the hypothesis locally in each document.
- Keep the operator cross-boundary scope question explicitly open in `05-g4-resolution-unit-chaining.md` until Section 7.1 of this document is resolved by testing.

**Test priorities:**
- Construct a case where the projecting unit uses perspective `e` and the receiving unit uses perspective `a`, and verify that the force resolves within the receiving unit's frame. This is the most direct test of the hypothesis (Section 5.4).
- Construct a minimal case where projected force encounters a terminal operator in a subsequent unit and determine whether force arrival triggers collapse or the operator encompasses the force. This is the most important test for advancing the weakest case (Section 7.1).