# FINAL RELEASE AUDIT — Elewana Group Emergency Procedure Protocol

**Audit date:** 28 August 2026  
**Release basis:** Controlled close-down audit following the final V9 workbook corrections  
**Repository:** `trainingelewana/Elewana-Emergency-Handbook`  
**Repository branch:** `main`  
**Repository commit audited:** `aa8197b7c255f5364b52f0b09fa5064ee011d481`

## 1. Release status

**DOCUMENT ALIGNMENT STATUS: GREEN — CLOSED FOR CONTROLLED RELEASE**

The Emergency Handbook workbook, Onsite Emergency Response Binder, live `index.html`, Forms & Templates Pack, and linked operational forms are substantively aligned in Incident Command structure, activation, command authority, responder responsibilities, escalation, emergency communications, scenario procedures, radio codes, country contact-card structure, and supporting forms.

No material contradiction was identified that requires another operational redevelopment cycle.

A separate specialist verification action remains open for defined clinical and medevac-provider content. This is a governance/sign-off action and is not a cross-document alignment defect.

## 2. Controlled sources audited

| Controlled source | Release state |
|---|---|
| `Emergency Handbook Final PreSignoff V9 - FINAL RELEASE.docx` | **CLOSED** |
| `Elewana_Onsite_Emergency_Response_Binder_REBUILT.pdf` | **CLOSED** |
| `index.html` | **CLOSED** |
| `elewana-forms-pack.html` | **CLOSED** |
| `forms/*.pdf` operational forms library | **CLOSED for document/form alignment** |
| `FINAL_RELEASE_AUDIT.md` | **Updated by this close-down pass** |

## 3. Closed items

| Item | Status | Close-down finding |
|---|---|---|
| Standard Incident Command structure | **CLOSED** | IC, OC, LC, EC, Medic, Fire Marshal and Responders are consistently defined across the operational sources. |
| Country Shutdown special ICS allocation | **CLOSED** | OC = Maintenance Manager, LC = Executive Chef, EC = Front Office Manager; same special allocation is used in the workbook, binder, live HTML and A26 checklist. |
| Fire vs Firearm radio-code duplication | **CLOSED** | Fire = **Code Red**; Firearm / Weapon Attack = **Code Security**. |
| Firearm / Weapon Attack drill frequency | **CLOSED** | Standardised to at least twice per year, including tabletop and practical components. |
| Bomb-threat fixed 50 m stand-off | **CLOSED** | No fixed distance is treated as universally safe; Police/Bomb Disposal determine stand-off based on the suspected device and site conditions. |
| Bomb-threat communications restriction | **CLOSED** | Radio/mobile/Wi-Fi transmissions are prevented in the immediate vicinity of the suspicious item and a safe communications point is established outside the isolated area. |
| A4-TZ / A4-KE Priority Contact Card split | **CLOSED** | Tanzania and Kenya contact cards remain separate and correctly linked. |
| Raw emergency-contact placeholders | **CLOSED as a document-control issue** | Unconfirmed local contacts use controlled fallback wording and national emergency numbers rather than unfinished placeholders or fabricated numbers. |
| A46 Food & Water-borne Illness Outbreak | **CLOSED** | A46 is integrated in the workbook/forms architecture, live index, Forms Pack and operational PDF forms. |
| Editable forms / linked forms integrity | **CLOSED** | Current repository QA records all operational form links resolving, white printable editable backgrounds, and fill/save/reopen persistence testing of editable AcroForms. |
| Death / CPR fixed-time wording | **CLOSED** | No inappropriate fixed 20-minute rule remains; authorised/qualified pronouncement requirements are retained. |
| Drowning terminology | **CLOSED** | Deprecated terminology has been removed from the controlled digital sources. |
| Crisis communications governance | **CLOSED** | Media/public communication remains under authorised spokesperson control; next-of-kin/family/DMC/embassy/insurer communication follows the defined Head Office coordination process. |
| V9 obsolete Section 5.1.2 cross-reference text | **CLOSED** | Two residual `Section 5.1.2.` hyperlink prefixes were removed from the final workbook. The correct references now point to Section 5.1 and A4-TZ / A4-KE. |
| Onsite Emergency Response Binder rebuild | **CLOSED** | Rebuilt binder was included in this close-down audit and is aligned with the current operational source set. |
| GitHub upload / live repository state | **CLOSED** | Current live repository state audited at commit `aa8197b7c255f5364b52f0b09fa5064ee011d481`. |

## 4. Final V9 workbook correction completed

Two obsolete hyperlink prefixes reading `Section 5.1.2.` remained in the V9 Word source even though the sentence wording had already been corrected.

They were removed without altering the surrounding operational content.

Final wording now reads:

1. **Use the emergency priority numbers in Section 5.1 and the A4-TZ / A4-KE Priority Contact Cards to alert external responders.**
2. **All camps must keep emergency contact numbers posted near radios and phones (see Section 5.1 and the A4-TZ / A4-KE Priority Contact Cards).**

The final workbook was rendered after the correction. Page count remained **124 pages**. A page-by-page render comparison against the audited V9 source showed visual changes only on pages **25** and **35**, corresponding exactly to the two controlled corrections.

## 5. Forms and digital-source close-down

The live repository contains the operational scenario checklists, contact cards, medical forms, radio-code reference, incident forms, logs and supporting tools required by the controlled forms architecture.

Key high-risk checks closed during the final audit include:

- A24 Bomb Threat — no fixed stand-off distance; communications restriction aligned.
- A26 Country Shutdown / Movement Restriction — special ICS role allocation aligned.
- A34 Radio Codes — Fire and Firearm codes clearly separated.
- A46 Food & Water-borne Illness Outbreak — correctly integrated.
- A4-TZ and A4-KE — separately maintained and linked.
- Operational PDF links — repository QA records no missing linked form targets.

## 6. Open specialist verification action

### Clinical and medevac-provider content — PENDING SPECIALIST SIGN-OFF

The following content is intentionally **not rewritten by the document audit** and should be verified by an appropriately qualified medical adviser / wilderness first-aid provider and the relevant medevac/aviation provider:

- A42 trauma and vitals clinical content.
- Tourniquet, IV/IO and blood-pressure target wording.
- AMREF / Flying Doctors / Arusha Medivac coverage statements.
- Mobilisation cut-offs, including the stated 16:00 same-day air mobilisation wording.
- Night-airstrip operating instructions and provider-specific limitations.

**Audit position:** no cross-source contradiction requiring document redevelopment was identified. The outstanding action is evidence of specialist verification: verifier name, organisation/qualification, date, scope reviewed, and any approved amendments.

## 7. Release decision

**FINAL PANEL POSITION: APPROVED FOR CONTROLLED RELEASE, WITH SPECIALIST CLINICAL/MEDEVAC VERIFICATION RECORDED AS AN OPEN GOVERNANCE ACTION UNTIL SIGNED OFF.**

The document-control and cross-source close-down is complete.

No additional broad rewrite of the Emergency Handbook, Binder, HTML handbook, Forms Pack or operational forms is recommended.

## 8. Release-control actions

Before organisational issue, the document owner should:

- retain the final V9 workbook as the controlled master;
- retain the rebuilt binder as the controlled onsite source;
- retain the audited GitHub commit/reference as the digital release baseline;
- record the final medical and medevac verifier details when received;
- update emergency contact details as local confirmed numbers become available without removing the national fallback;
- manage all future changes through formal revision control so the workbook, binder, HTML and forms remain synchronised.

---

**Close-down audit result:** **GREEN — DOCUMENT ALIGNMENT CLOSED**  
**Outstanding controlled action:** **Clinical / medevac specialist verification only**  
**Audited repository baseline:** `aa8197b7c255f5364b52f0b09fa5064ee011d481`
