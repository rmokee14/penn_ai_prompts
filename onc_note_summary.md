I will paste a long outpatient oncology note that contains noise, duplications, improper tenses, and irrelevant details.

GOAL
Create a clean, hospitalist-ready summary that is HIGH-YIELD for inpatient care.

RULES
- Use ONLY information present in the pasted note. Do not guess.
- If missing, write “Not stated.” If not relevant, do not include in the output.
- Output in markdown. Use bold headings and concise bullets.
- Keep dates whenever available (MM/YYYY or exact).
- Remove fluff (ROS templates, billing text, repeated history, long prose).
- When listing meds, include the generic name, dose, route, and frequency (acyclovir 500mg PO BID)
- If you see conflicting data, show both briefly and label as “Conflict”.

OUTPUT (use this exact structure)

**ONC NOTE SUMMARY**

**1) Cancer Snapshot**
- **Primary tumor:** 
- **Histology/subtype:** 
- **Stage at diagnosis:** 
- **Biomarkers/molecular:** 
- **Metastatic sites (current):** 
- **Key disease complications:** (e.g., malignant obstruction, brain mets, spinal cord risk, effusions, ascites)
- **Disease status:** (responding/stable/progressing; cite imaging date if present)


**2) Current Anticancer Therapy and Disease Status**
- **Regimen:** 
- **Intent:** (curative/adjuvant/palliative/maintenance/clinical trial)  
- **Cycle/Day:** 
- **Last received (date):** 
- **Next planned dose (date):** 
- **Expected high-risk toxicities / what to watch in hospital:** (1–5 bullets)
- **Onc plan:** (next steps)

**3) Cancer-Related Meds**
- **Steroids:** (drug, dose, taper plan)
- **Infectious prophylaxis:** (PJP/HSV/VZV/antifungal; indicate indication if stated)
- **Anticoagulation/antiplatelet:** (drug, dose, indication)
- **Pain regimen:** (baseline + breakthrough; include methadone if present)
- **Antiemetics/appetite/neuropathic agents:** 
- **Bone mets meds:** (zoledronic acid/denosumab; last dose if present)
- **Other critical meds:** (e.g., seizure meds, pressors not applicable, etc.)

**4) Treatment Timeline (broad strokes only)**
- **Dx:** 
- **Surgeries/procedures:** (date + what)
- **Radiation:** (date range + general location)
- **Systemic therapy lines:**  
  - Line 1: (date range, regimen, outcome)  
  - Line 2: …  
  - Current line: …

**5) Devices / Access / Anatomy Changes**
- **Vascular access:** (port/PICC; laterality; issues)
- **Drains/stents/tubes/ostomy:** (type + indication)
- **Anatomic considerations:** (e.g., biliary stent, nephrostomy, prior gastrectomy)

**6) Performance Status / Goals of Care**
- **Goals of care / prognosis statements:** 
- **Code status / hospice / palliative involvement:** 
