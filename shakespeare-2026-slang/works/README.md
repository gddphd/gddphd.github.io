# Shakespeare Adaptation Corpus Index

This directory organizes the individual Shakespeare-to-2026-slang adaptations governed by the Romeo Protocol.

## Current canonical / working adaptation set

| Work | Passage | Current artifact status | Notes |
| --- | --- | --- | --- |
| *Romeo and Juliet* | Act II, Scene II | Existing DOCX already present in repository root; canonical reference artifact | Originating adaptation and protocol floor. |
| *A Midsummer Night's Dream* | Act I, Scenes I-II | Working dossier exists outside this branch and is ready to be organized here | Important comedy/prose and character-density test case. |
| *Othello* | Act III, Scene III selected passage | GitHub-ready DOCX/TXT working edition exists | Evidence/verification lexical system; dramatic-irony and manipulation test case. |
| *King Lear* | Act III, Scene II | GitHub-ready DOCX/TXT working edition exists | Tragic-gravity, prosodic-friction, rhyme, and retro-audit test case. |
| *The Tempest* | Act III, Scene II | GitHub-ready DOCX/TXT working edition exists | Comic/prose versus lyrical-register test case. |

## Planned per-work structure

Each work should ultimately use a structure similar to:

```text
works/<work-name>/
├── README.md
├── adaptations/
│   ├── <canonical-or-working-edition>.md
│   ├── <canonical-or-working-edition>.txt
│   └── <canonical-or-working-edition>.docx
├── annotations/
├── lexical-ledger/
├── source-register/
└── revisions/
```

## Required metadata for each adaptation

Each work-level README should identify:

- play, act, scene, and passage scope;
- protocol version used;
- canonical / draft / superseded status;
- Shakespeare baseline source;
- slang lexicon / supplemental source policy;
- lexical occurrence and distinct-term counts;
- major recurring lexical systems;
- prosodic and performance notes;
- known nuance losses or unresolved questions;
- revision history;
- links to downloadable DOCX/TXT artifacts;
- links to GitHub-readable Markdown when available.

## Version preservation

A later edition does not erase an earlier one. Historical versions remain available under `revisions/` or another clearly identified provenance location.

## Corpus-wide checkpoint

The latest working checkpoint before organization into this repository is 292 canonical slang/slang-derived occurrences and 156 normalized distinct expressions across the completed adaptation set. Future retro-audits and revisions may alter canonical counts; any changes must be documented rather than silently substituted.
