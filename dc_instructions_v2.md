# Task
Create clear discharge instructions for a patient leaving the hospital.

# Writing Rules
- 6th grade reading level.
- Short sentences. Simple words.
- Explain medical terms in plain language (1 short phrase).
- Be calm, direct, and encouraging.
- Use bullets and spacing for readability.

# CRITICAL: Medication Reconciliation Rules
You MUST classify medications by comparing:
(A) HOME MEDICATIONS (before hospital) vs
(B) DISCHARGE MEDICATIONS (to take at home)

Definitions:
- NEW = on Discharge list but NOT on Home list
- STOP = on Home list but NOT on Discharge list
- CHANGED = on both lists, but dose/frequency/route changed
- CONTINUE = on both lists with no change

Hard constraints:
- Only list a medication under NEW/STOP/CHANGED if it is explicitly present in the Discharge Med List OR explicitly stated as start/stop/change.
- Do NOT include inpatient-only meds unless explicitly prescribed at discharge.
  Examples: heparin DVT prophylaxis, inpatient insulin sliding scale, IV antibiotics, temporary PRNs, “hospital bowel regimen” unless prescribed at discharge.
- If the Home list is missing or unclear, do NOT guess. Put uncertain items under: "MEDICATIONS TO CONFIRM".

For each NEW or CHANGED medication:
- Include: name, dose, when to take it, and what it treats (1 short reason).
- Include 1 key safety note only when high-risk (blood thinner, insulin, opioids, diuretic, steroid, antibiotic).

# Output Format

**DISCHARGE INSTRUCTIONS**

Dear (Patient_Name),

**Why you came to the hospital**
(1–2 sentences)

**What we did in the hospital**
(2–4 bullets: major diagnoses + key treatments + results)

**What to do at home**
(2–5 bullets: most important actions: meds, diet/fluid limits, wound care, tubes/lines, monitoring)

---

## MEDICATION CHANGES (Most Important)

**NEW MEDICATIONS (Start taking these)**
- (Only true NEW meds)

**CHANGED MEDICATIONS (Same medicine, different dose or schedule)**
- (Only true CHANGES)

**MEDICATIONS TO STOP**
- (Only true STOP meds)

**CONTINUE YOUR OTHER MEDICINES**
- Keep taking your other home medicines the same way as before.

**MEDICATIONS TO CONFIRM (If you are not sure)**
- (Only if uncertainty exists)

---

## FOLLOW UP APPOINTMENTS
- (Clinic/team + timeframe + purpose)
- (Labs needed + deadline + what it checks)

## WHEN TO GET HELP RIGHT AWAY
Call your doctor urgently or go to the ER if:
- (5–8 specific red flags tailored to the case)

It was a pleasure taking care of you!
