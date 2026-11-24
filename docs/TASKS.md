# Daftar pekerjaan — story.invitationku

Planning Gate APPROVED. Design, Architecture and Release Gates PENDING. Owner assigns tasks; use handoff/TASK-LOCK.md when coordinating multiple agents.

| ID | Task | Dependency | Status |
|---|---|---|---|
| P-001 | Wawancara awal dan draf rencana produk | none | DONE |
| P-002 | Tinjauan dan persetujuan rencana oleh pemilik | P-001 | DONE |
| D-001 | UX, design system, prototype | P-002 | IN PROGRESS |
| D-002 | Owner Design Gate | D-001 | TODO |
| A-001 | Architecture, data, API, security | D-002 | TODO |
| A-002 | Owner Architecture Gate | A-001 | TODO |
| I-001 | Implement approved feature specs | A-002 | TODO |
| Q-001 | QA and independent review | I-001 | TODO |
| R-001 | Owner Release Gate | Q-001 | TODO |

Add real feature tasks, acceptance criteria, owners, branches and evidence when planning. Never mark DONE without evidence.


P-001 dikerjakan oleh AI pendamping bersama pemilik proyek di `main`. Bukti P-001: [ringkasan proyek](PROJECT_INTAKE.md) dan [draf PRD v0.2](PRD.md) siap ditinjau. Bukti P-002: persetujuan pemilik tercatat sebagai D-020 di [DECISIONS.md](DECISIONS.md). D-001 berjalan. Sketsa awal landing page desktop dan ponsel tersedia di [Sketsa-Landing-Page-v0.1.pdf](../design/Sketsa-Landing-Page-v0.1.pdf). Pemilik menyetujui penempatan tombol dan contoh template pada sketsa. Arah visual, layar lain, dan prototipe masih dikerjakan pada tahap desain.
