# Shakespeare in 2026 Slang

## Project status

This directory is the working GitHub home for the Shakespeare-to-2026-slang translation corpus and the Romeo Protocol used to construct, annotate, test, and evaluate the adaptations.

**Repository status:** working corpus / staged publication structure  
**Current protocol status:** Romeo Protocol v2.0 is a draft candidate under cumulative development; Revision D is the latest draft produced as of 2026-08-31.  
**License status:** unresolved for the original adaptations, annotations, protocol text, and editorial apparatus. No license is asserted here beyond the repository's existing license until the project owner explicitly determines applicability and licensing strategy.

## Editorial objective

The project reconstructs Shakespeare's dramatic, rhetorical, emotional, figurative, prosodic, and character-specific functions inside a defensible contemporary linguistic system. 2026 slang is treated as a semantic register and one editorial instrument rather than as decoration or a mandatory density target.

The project retains Shakespearean dramatic sequence and recognizable rhetorical architecture while testing contemporary vocabulary against meter, performance, character voice, ambiguity, power relationships, dramatic irony, tonal gravity, metaphor continuity, pragmatic alignment, and universality.

## Current corpus

The working corpus currently includes adaptations from:

- *Romeo and Juliet* — Act II, Scene II
- *A Midsummer Night's Dream* — Act I, Scenes I-II
- *Othello* — Act III, Scene III selected jealousy / "green-eyed monster" passage
- *King Lear* — Act III, Scene II storm scene
- *The Tempest* — Act III, Scene II

The project has also developed a cumulative Romeo Protocol, external Gemini methodological reviews, DRASP stress tests, lexical ledgers, annotation systems, and protocol-evolution materials.

## Proposed repository structure

```text
shakespeare-2026-slang/
├── README.md
├── protocols/
│   ├── README.md
│   ├── romeo-protocol-v2.0/
│   │   ├── revision-d/
│   │   └── prior-revisions/
│   └── external-reviews/
├── works/
│   ├── README.md
│   ├── romeo-and-juliet/
│   ├── midsummer-nights-dream/
│   ├── othello/
│   ├── king-lear/
│   └── the-tempest/
├── corpus/
│   ├── lexical-ledgers/
│   └── cross-work-analysis/
├── methodology/
│   ├── drasp-tests/
│   ├── prosody/
│   └── timeline/
└── publication/
    ├── provenance/
    └── release-notes/
```

Git does not store empty folders, so directories will appear as their first files are committed.

## Version-preservation rule

Successor protocol and adaptation versions are cumulative by default. Earlier versions are preserved as historical artifacts. No prior version should be silently overwritten, condensed, or deleted when a successor is created.

## Publication workflow

1. Stage changes on a dedicated branch.
2. Preserve original generated artifacts and revision provenance.
3. Add Markdown-readable versions for GitHub browsing where possible.
4. Retain DOCX/TXT source artifacts when they are part of the canonical project record.
5. Run protocol and corpus quality checks before promoting a draft to canonical status.
6. Merge to `main` only after explicit project-owner review/authorization.

## Current staging branch

`shakespeare-2026-slang-setup`

This branch is being used to organize the project before any changes are merged into the published GitHub Pages branch.
