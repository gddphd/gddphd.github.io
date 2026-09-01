# Staging Status

**Branch:** `shakespeare-2026-slang-setup`  
**Target branch intentionally unchanged:** `main`  
**Project state:** populated working corpus / pre-merge review

## Staged and browsable

- Project home and navigation.
- Work indexes for *Romeo and Juliet*, *A Midsummer Night's Dream*, *Othello*, *King Lear*, and *The Tempest*.
- Full GitHub-readable adaptation text for the current corpus.
- Preserved Midsummer drafting/revision layers within the complete dossier archive.
- Originating Romeo DOCX copied into the structured work directory while the historical root copy remains intact.
- Romeo Protocol v2.0 development note, initial draft, Revision B, Revision C, and Revision D preserved as separate revision artifacts.
- Exact multipart reconstruction metadata for the protocol revision archives.
- Corpus checkpoint and counting controls.
- Gemini / DRASP review register and attribution.
- Methodology and protocol-development timeline page.
- Provenance record, AI assistance disclosure, and changelog.
- Binary artifact manifest with file sizes and SHA-256 verification targets.

## Binary packages still pending direct Git-object archival

The readable project content and exact binary identities are staged, but the current connector workflow has not yet committed these local binary packages directly into GitHub:

- Midsummer DOCX
- Othello DOCX
- King Lear DOCX
- The Tempest DOCX
- Romeo Protocol development/revision DOCX files
- Gemini review PDFs
- protocol timeline PNG

Their exact names, sizes, and checksums are recorded in `BINARY_ARTIFACT_MANIFEST.md` and related per-work/protocol binary records. They must not be represented as already committed until their repository bytes are verified.

## Protocol integrity

Revision C was re-audited during staging. Multipart sections that had been split at incorrect cumulative boundaries were repaired. The current six-part archive reconstructs the 55,406-byte Revision C Markdown source when concatenated in numeric order, with reconstruction SHA-256:

`919e061ccc8ddc73518feaa77e0f6b3fd47b156f2ebd64dfaf011a88d7a3308b`

Revision D's eight-part archive is likewise normalized for exact concatenation to the 73,803-byte source, SHA-256:

`a1971691cc6899c578e97baefb65d60710b4c1b7791c0395b974e39c99ffd1e4`

## Adoption / merge controls

- Revision D remains a **draft candidate**, not the formally adopted Romeo Protocol.
- Historical v1.0 work artifacts have not been silently retro-audited or overwritten.
- No merge into `main` has been performed.
- A later merge or public release should follow explicit project-owner review and authorization.
