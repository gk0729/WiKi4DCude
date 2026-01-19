# WiKi4DCube — Chinese Semantic WhiteBox Coordinate System (Spec v0.1)

WiKi4DCube is a **white-box semantic coordinate system** for Chinese words and concepts.

This repository is the **canonical specification** (Spec) for the WiKi4DCube coordinate space.
It defines a 241-dimensional semantic basis:

- **NSM64+1 semantic primes layer**: 65 dims (foundation semantics)
- **Chinese concept-attribute layer**: 48 dims (fine-grained semantics)
- **Core anchor-word relation layer**: 128 dims (contextual positioning)

> This repo publishes the **dimension definitions (the “exam questions”)**, not the full coordinate values (the “answer key”).
> The refined coordinate datasets, model weights, and large-scale scoring logs can be released separately.

## Status

- Spec version: **v0.1**
- Scope: **241-dim definitions only**
- Data: **not included** (users must compute/derive coordinates)

## Why this exists

Modern embeddings are powerful but often black-box and hard to audit.
WiKi4DCube aims to make semantic representation:

- **Auditable** (explicit dimensions, transparent definitions)
- **Composable** (dimensions can be weighted / combined / versioned)
- **Queryable** (filtering, analogy, retrieval, relation graphs)
- **Updatable** (daily close / versioned coordinate releases)

## Dimension space (v0.1)

The canonical dimension definition file is:

- `spec/dimensions.toon`

Total dimensions: **241 = 65 + 48 + 128**

### Layer A — NSM64+1 (65 dims)

Natural Semantic Metalanguage semantic primes as a universal semantic baseline.
Each dim is a semantic prime with a stable ID.

### Layer B — Chinese Concept Attributes (48 dims)

A curated set of Chinese linguistic/conceptual attributes for fine-grained semantics.

### Layer C — Anchor-word Relations (128 dims)

A fixed anchor vocabulary for contextual positioning and relation strength.

## Coordinate representation (recommended)

A WiKi4DCube coordinate for a word is conceptually:

- `nsm_vector[65]` in range `[0,1]`
- `attr_vector[48]` in range `[0,1]`
- `anchor_vector[128]` in range `[0,1]`

Exact scoring rules and aggregation pipelines are **implementation-dependent** and can be standardized in later specs.

## Versioning policy

WiKi4DCube specs are versioned as `vMAJOR.MINOR`:

- **MAJOR**: breaking changes (dimension ID changes, removals, semantic meaning changes)
- **MINOR**: backward-compatible additions (new notes, examples, clarifications)

See: `spec/versions.md` (optional).

## License

Code and spec text in this repository are released under the **MIT License** (see `LICENSE`).

## Name / Brand Policy (IMPORTANT)

Even though the content is MIT-licensed, the **project name “WiKi4DCube” is controlled**.
See `NAME-POLICY.md`.

Forks and derived works are welcome, but must not present themselves as the official WiKi4DCube release unless explicitly authorized.

## Contact / Maintainer

- Maintainer: **gk0729**
- Repo: This repository is the canonical WiKi4DCube spec maintained by gk0729.
