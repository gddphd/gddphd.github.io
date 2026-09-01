# Shakespeare in 2026 Slang

## Project status

This directory is the working GitHub home for the Shakespeare-to-2026-slang translation corpus and the Romeo Protocol used to construct, annotate, test, and evaluate the adaptations.

**Repository status:** populated working corpus on staging branch  
**Staging branch:** `shakespeare-2026-slang-setup`  
**Current protocol status:** Romeo Protocol v2.0 Revision D is the latest **draft candidate** as of 2026-08-31; it has not been declared adopted.  
**License status:** unresolved for the original adaptations, annotations, protocol text, and editorial apparatus. No project-specific license is asserted here until the project owner explicitly determines applicability and licensing strategy.

## Editorial objective

The project reconstructs Shakespeare's dramatic, rhetorical, emotional, figurative, prosodic, and character-specific functions inside a defensible contemporary linguistic system. 2026 slang is treated as a semantic register and one editorial instrument rather than as decoration or a mandatory density target.

The project retains Shakespearean dramatic sequence and recognizable rhetorical architecture while testing contemporary vocabulary against meter, performance, character voice, ambiguity, power relationships, dramatic irony, tonal gravity, metaphor continuity, pragmatic alignment, temporal localization, and universality.

## Repository navigation

- [Works and adaptations](works/)
- [Romeo Protocol and revision history](protocols/)
- [Corpus counts and lexical-analysis layer](corpus/)
- [Methodology, DRASP testing, and protocol timeline](methodology/)
- [Project changelog](publication/CHANGELOG.md)
- [AI assistance disclosure](publication/AI_DISCLOSURE.md)
- [Provenance record](publication/provenance/PROVENANCE.md)

## Current corpus

The working corpus includes:

- *Romeo and Juliet* — Act II, Scene II
- *A Midsummer Night's Dream* — Act I, Scenes I-II
- *Othello* — Act III, Scene III selected jealousy / "green-eyed monster" passage
- *King Lear* — Act III, Scene II storm scene
- *The Tempest* — Act III, Scene II

The historical working checkpoint before future v2.0 retro-audits is **292 canonical slang/slang-derived occurrences and 156 normalized project-wide distinct expressions**. Scene-level distinct counts are preserved separately and are not simply summed.

## Current repository structure

```text
shakespeare-2026-slang/
├── README.md
├── protocols/
│   ├── README.md
│   └── romeo-protocol-v2.0/
│       ├── initial-draft/
│       ├── revision-b/
│       ├── revision-c/
│       └── revision-d/
├── works/
│   ├── README.md
│   ├── romeo-and-juliet/
│   ├── midsummer-nights-dream/
│   ├── othello/
│   ├── king-lear/
│   └── the-tempest/
├── corpus/
│   └── README.md
├── methodology/
│   ├── README.md
│   ├── drasp-tests/
│   └── timeline/
└── publication/
    ├── CHANGELOG.md
    ├── AI_DISCLOSURE.md
    └── provenance/
```

Git does not store empty folders, so additional subdirectories will appear when their first files are committed.

## Version-preservation rule

Successor protocol and adaptation versions are cumulative by default. Earlier versions are preserved as historical artifacts. No prior version should be silently overwritten, condensed, or deleted when a successor is created.

The *Midsummer* dossier preserves its superseded drafting layers. The Romeo Protocol directories preserve the v2.0 initial draft and Revisions B-D separately. Later retro-audits of *Othello*, *King Lear*, or other works must create new artifacts rather than rewriting the historical v1.0 files.

## Publication workflow

1. Stage changes on a dedicated branch.
2. Preserve original generated artifacts and revision provenance.
3. Add Markdown/TXT-readable versions for GitHub browsing.
4. Retain DOCX or other binary source artifacts when they form part of the canonical project record.
5. Run protocol and corpus quality checks before promoting a draft to canonical status.
6. Merge to `main` only after explicit project-owner review/authorization.

## Binary-artifact note

The originating Romeo DOCX has been copied into the structured work directory. Other DOCX/PDF/image artifacts are being tracked separately from the readable archive; their binary archival status should be checked before final public release.

## Main-branch safety

No project-organization change on this staging branch should be treated as permission to modify or merge into the GitHub Pages `main` branch.
