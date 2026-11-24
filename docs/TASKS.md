# Daftar pekerjaan — story.invitationku

All project gates PENDING. Owner assigns tasks; use handoff/TASK-LOCK.md when coordinating multiple agents.

| ID | Task | Dependency | Status |
|---|---|---|---|
| P-001 | Wawancara awal dan draf rencana produk | none | DONE |
| P-002 | Tinjauan dan persetujuan rencana oleh pemilik | P-001 | IN PROGRESS |
| D-001 | UX, design system, prototype | P-002 | TODO |
| D-002 | Owner Design Gate | D-001 | TODO |
| A-001 | Architecture, data, API, security | D-002 | TODO |
| A-002 | Owner Architecture Gate | A-001 | TODO |
| I-001 | Implement approved feature specs | A-002 | TODO |
| Q-001 | QA and independent review | I-001 | TODO |
| R-001 | Owner Release Gate | Q-001 | TODO |

Add real feature tasks, acceptance criteria, owners, branches and evidence when planning. Never mark DONE without evidence.


P-001 dikerjakan oleh AI pendamping bersama pemilik proyek di `main`. Bukti P-001: [ringkasan proyek](PROJECT_INTAKE.md) dan [draf PRD v0.2](PRD.md) siap ditinjau. P-002 menunggu persetujuan eksplisit pemilik atas revisi yang ditinjau.
