# FINAL_RELEASE_AUDIT.md — Elewana Group Emergency Procedure Protocol

**Purpose:** a short, current-state summary of release status. For full history and rationale, see `CHANGE_LOG_AND_AUDIT.md` (lettered sections A–FF). This file reflects the state as of Section FF and should be updated (not archived) as future controlled passes close items.

## Closed items (verified this pass, Section FF)

| Item | Status | Where verified |
|---|---|---|
| Fire vs Firearm radio-code duplication | **CLOSED** — Fire = "Code Red", Firearm/Weapon Attack = "Code Security", no overlap | `index.html` scenario wording, `elewana-forms-pack.html` A34 radio code table |
| A4-TZ / A4-KE contact card split | **CLOSED** — separately linked everywhere, correctly labelled | Every `contact-card.pdf` / `contact-card-ke.pdf` link in `index.html` |
| Bomb-threat fixed 50 m stand-off | **CLOSED** — no fixed distance; Police/Bomb Disposal set stand-off | `index.html`, `elewana-forms-pack.html`, `forms/ckl-bomb.pdf` |
| Death/CPR fixed 20-minute rule | **CLOSED** — no fixed time limit; authorised/qualified pronouncement only | `index.html`, `elewana-forms-pack.html`, `forms/ckl-death.pdf` |
| Kenya emergency numbers vs Tanzania 114 | **CLOSED** — Kenya 999/112/911, Tanzania 114, no cross-contamination | `index.html`, `forms/contact-card-ke.pdf` |
| Drowning terminology ("secondary"/"delayed"/"dry"/"near-drowning") | **CLOSED** — retired repo-wide | `index.html`, `elewana-forms-pack.html`, `forms/ckl-aquatic.pdf` |
| Crisis-comms governance (media vs next-of-kin) | **CLOSED** — spokesperson for media/public only; HO-coordinated next-of-kin/family/DMC/embassy/insurer | `index.html`, `elewana-forms-pack.html` |
| Raw `[to confirm]` / placeholder contact text | **CLOSED** — replaced with controlled fallback messages or "Role holder pending confirmation"; no numbers fabricated | `index.html` (P1 list, Police — Tanzania table, Police — Kenya table) |
| Editable PDF form backgrounds | **CLOSED** — all 47 editable forms converted cream → white for print; 7 static role cards intentionally left cream (out of scope, no fillable fields) | All `forms/*.pdf` except `role-card-*.pdf` |
| A46 (Food & Water-borne Illness Outbreak) fillable form | **CLOSED** — already a genuine AcroForm, correct field-naming convention, correct title | `forms/ckl-foodborne.pdf` |
| Internal navigation / broken links | **CLOSED** — all 21 scenario nav targets resolve; no PDF download button points to `href="#"` | Automated check + Playwright smoke test |

## Open / pending items

| Item | Status | Notes |
|---|---|---|
| Clinical and medevac content (A42, tourniquet/IV-IO/BP, AMREF coverage, mobilisation cut-offs, night-airstrip instructions) | **PENDING VERIFICATION** | Not rewritten by Claude on any pass. Requires sign-off from a medical adviser / WFA provider / medevac provider before any wording change. Record verifier name, date, and scope here once obtained. |
| Onsite Emergency Response Binder rebuild | **PENDING** | Not present in the current sandbox session; binder-specific corrections from the Final Safety Alignment brief (front-matter note, page renumbering, binder-only process-flow relabels) have not been applied. Apply on next binder rebuild from the corrected HTML sources. |
| Roxanne Cragg personnel discrepancy | **DEFERRED** | Present in Word source, absent from live dashboard. Flagged for human decision; not actioned. |
| "SafariCo" branding on Word SOP document | **DEFERRED** | Confirmed intentional in an earlier session; no action needed unless Winnie says otherwise. |
| GitHub push / commit | **NOT DONE** | Sandbox has no push credentials. All changes delivered as a changed-files-only zip for manual upload. Commit SHA to be recorded here once Winnie completes the upload. |

## Verification method notes

- Text-content checks (placeholder strings, radio codes, banned phrases) were done via direct string search across `index.html`, `elewana-forms-pack.html`, and the text layer of every `forms/*.pdf`, not by sampling.
- PDF field-count and fill/save/reopen persistence were tested programmatically (PyMuPDF) on every directly-edited PDF.
- Internal link integrity and a basic regression check (page navigation, console errors, mobile viewport overflow) were run with Playwright/Chromium against the local file, not a live deployed URL — Winnie should spot-check the live GitHub Pages site after upload, particularly the PDF download buttons, which cannot be exercised from a local file with certainty that server paths match.

**Last updated:** this pass (Section FF). Update this file, not a duplicate, on the next controlled pass.
