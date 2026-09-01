# Binary Artifact Manifest

This manifest distinguishes **binary artifacts already committed to GitHub** from **binary artifacts verified in the project workspace but not yet committed through the connector**. SHA-256 values identify the exact project files and permit later upload verification.

## Work artifacts

| Artifact | Bytes | SHA-256 | Staging status |
| --- | ---: | --- | --- |
| `Shakespeare_2026_Slang_Annotated_Romeo_and_Juliet_II_ii.docx` | 50,903 | `7e912b8c0acef1ad41b9c3fd40c51f7d7c398fc8ac0008bd7b739653a284918a` | **Committed** under `works/romeo-and-juliet/act-02-scene-02/` and preserved at repository root. |
| `Midsummer_2026_Slang_Translation_Project_Complete_Dossier_v1.0.docx` | 80,147 | `bd5335394082e7e28b0c03e78efee82d44189312d9ac8b043f7b2a78f84d0a1e` | Workspace-verified; readable TXT dossier committed in multipart archive; binary pending connector-level binary commit. |
| `Othello_2026_Slang_Act_III_Scene_III_Green_Eyed_Monster_Working_Edition_v1.0.docx` | 49,990 | `3902ece3f882a24a4541b91bbefa553c664a29981022706829905dcdf4453fae` | Workspace-verified; full TXT committed; binary pending. |
| `King_Lear_2026_Slang_Act_III_Scene_II_Storm_Scene_Working_Edition_v1.0.docx` | 55,220 | `f8fbf29f07022a1f3c598ee8ba0a2d09a1153abaa8d7293a4d014bd7dd78b375` | Workspace-verified; full TXT committed; binary pending. |
| `The_Tempest_2026_Slang_Act_III_Scene_II_Working_Edition_v1.0.docx` | 54,615 | `f55b30cf51dd43c29d8a9eee7fb4f724217fc5502674ec1a457c7c3e5af35939` | Workspace-verified; full TXT committed; binary pending. |

## Protocol artifacts

| Artifact | Bytes | SHA-256 | Staging status |
| --- | ---: | --- | --- |
| `Romeo_Protocol_Improvement_Analysis_Verbatim_2026-08-31.docx` | 46,247 | `54463dc51a73b017ddbdff399ebb3b82ea76da140b38c9cd11de6810349a6c47` | Workspace-verified; textual analysis preserved in protocol archive; DOCX pending. |
| `Romeo_Protocol_v2.0_Nuance_Fidelity_Extension_DRAFT.docx` | 47,870 | `78249b88590ed3aa27582c78eb3ad5bf8fc0bca09056c552285ec224dfc56c2c` | Workspace-verified; initial-draft readable archive committed; DOCX pending. |
| `Romeo_Protocol_v2.0_Nuance_Fidelity_Extension_Revised_Draft_Gemini_Informed.docx` | 55,335 | `66086068066afd2e270d2c5040f06b6bb7a2cdd3c386668ad10f9d8fadcc80a8` | Workspace-verified; Revision B readable archive committed; DOCX pending. |
| `Romeo_Protocol_v2.0_Nuance_Fidelity_Extension_Revision_C_DRASP_Integrated.docx` | 63,374 | `32f143da27ecd1e4d736c117973f159bc3904b70125cd4d2438340a340542950` | Workspace-verified; Revision C readable archive committed; DOCX pending. |
| `Romeo_Protocol_v2.0_Nuance_Fidelity_Extension_Revision_D_Prose_Pragmatics_Integrated.docx` | 71,412 | `bc2a8364d93b309a842f5b536a3716634774107f7e79b01f1298e590c4d01091` | Workspace-verified; Revision D readable archive committed; DOCX pending. |

## Timeline graphic

| Artifact | Bytes | SHA-256 | Staging status |
| --- | ---: | --- | --- |
| `evolution_of_the_romeo_protocol_roadmap.png` | 2,491,425 | `0ee35a4733b89370465ed91e53ae45391fba26174e18441bc15f9f6546897627` | Workspace-verified; GitHub-readable timeline page committed; binary PNG pending. |

## Interpretation

A `pending` binary status does **not** mean the work is absent from the repository. Its readable textual content, version metadata, and provenance are already staged. It means the exact DOCX/PNG package has not yet been added as a binary Git object through the current connector workflow.

Before final public release, pending binary rows should either be committed and verified against the SHA-256 value above or explicitly excluded from the release with that decision documented.
