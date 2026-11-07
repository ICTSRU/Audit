# Changelog

## v1.4 — 2026-11-07
- New button "تصدير الردود إلى Excel": downloads an .xlsx with three columns (السؤال | الإجابة | اسم المرفق), RTL, answered rows shaded light green. Reads the latest data from the Sheet at export time. Uses ExcelJS 4.4.0 from cdnjs.
- Apps Script backend unchanged (no redeploy needed).

## v1.3 — 2026-11-07
- Answered questions are shaded light green; the shading and the "answered" tag update live while typing, uploading or deleting.
- Apps Script backend unchanged (no redeploy needed).

## v1.2 — 2026-11-05
- Web App URL set in index.html (WEB_APP_URL). Version bump only; Code.gs unchanged functionally.

## v1.1 — 2026-11-05
- Backend linked to the existing Google Sheet "ICTD Audit Responses" (SHEET_ID) instead of creating a new one.
- Questions now read from tab `Responses`; `evidence_links` column auto-filled with Drive links.

## v1.0 — 2026-11-05
- First release: 32 audit questions, answers to Google Sheet, evidence upload (Word/Excel/PDF/images) to Drive, @sr.edu.sa-only sign-in with ITOC gate screen, sign-in log.
