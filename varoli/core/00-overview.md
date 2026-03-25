# 00 — Overview

This folder contains the formal specification of Varoli. Everything here is locked: defined, validated, and stable under expansion. Nothing in this folder is exploratory or provisional.

If you are new to Varoli, begin with `varoli/introduction.md` before reading anything here. The introduction is the experiential entry point. This folder is the formal system that underlies it.

---

## What This Folder Contains

The core specification is organized in dependency order. Each file builds on what precedes it.

`01-primitives.md` defines the three categories of character: vowels, consonants, and operator. It states the hard rules that govern the entire system. Read this first.

`02-vowels.md` is a compressed reference for the five elemental vowels. For full definitions see `05-phonemic-schemas.md`.

`03-consonants.md` is a compressed reference for the twenty-one consonants. For full definitions see `05-phonemic-schemas.md`.

`04-operator-y.md` is a compressed reference for the operator. For full definition see `05-phonemic-schemas.md`.

`05-phonemic-schemas.md` is the canonical source of truth for every character in the language. Full definitions for every character, including function, structure, and descriptive fields (register, poetic field, scale realization). All other files derive from this one.

`06-generation-rules.md` defines how valid forms are constructed. These rules govern structure.

`07-interpretation-rules.md` defines how valid forms are interpreted. These rules govern meaning.

---

## How to Read This Folder

The files in `02`, `03`, and `04` are quick reference views extracted from `05`. They exist for fast lookup during active use. When you need the full definition of a character, go to `05`. When you need to check a function quickly while building a word, use `02`, `03`, or `04`.

The rules in `06` and `07` are not guidelines. They do not have exceptions. If a form violates a generation rule it is invalid. If an interpretation violates an interpretation rule it is invalid.

The grammar files in `varoli/grammar/` depend on this folder. The lexicon files in `varoli/lexicon/` depend on both.

---

## The Core Principle

Every file in this folder follows one rule above all others:

**Function is invariant. Interpretation is subordinate to function. Structure determines meaning. A form may be realized at different scales without changing its function.**

If anything you read here appears to contradict that principle, the contradiction is an error to be corrected, not a feature to be preserved.