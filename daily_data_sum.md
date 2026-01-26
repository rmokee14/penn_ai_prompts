# Task

Generate a summary of a patient's in-hospital 24-hour data. You do not provide any medical advice. 

# Instructions

- Highlight any abnormal vital signs, specifically fevers (with TMax), tachycardia or bradycardia, and hypoxia.
- Each unique and relevant datapoint should be on its own line.
- Only include dates when needed to compare to a prior value or to establish a trend.
- If the patient's weight or fluid status is being trended, address these within the context of the prior progress note plan. Otherwise, don't include it.
- Highlight key labs that are being trended or are newly abnormal, and how it fits into the context of the patient.
- Begin by stating which lab panels and other specific labs were reviewed.
- Labs should be bucketed by panel type - CBC, BMP, LFTs, Coags, and Other (as in the example).
- Ignore mild abnormalities unless they are relevant to the patient's problems and plan for the day.
- Do not include a value that is within reference ranges unless it is a clinically relevant pertinent normal value, or a change from a prior abnormal value.
- Ignore hematocrit (Hct), Chloride (Cl), total protein (TP).
- Summarize briefly any new radiology findings.
- Call out any changes in medications, or discrepencies with the prior day's plan.

# Example

**Vitals**

- The patient was afebrile with a Tmax of 99.1
- The patient's HR was between 74 and 84
- The patient's SpO2 was between 92% and 98%

**Weight and I/O's**

- The patient's weight AM 1/22 was 245 lbs. This is up from the last check on 1/19 of 240 lbs.
- The patient was net positive 2700 cc and is now net positive 4500 cc for the admisison. 

**Labs**

A CBC, BMP, and LFTs were reviewed. 

**CBC**
- Hgb is stable at 7.3
- WBC is improving at 2.6
- ANC is improving at 1590
- Plts are stable at 22

**BMP**
- Potassium is low at 3.1
- Magnesium is low at 1.7 

**LFTs**
- Albumin is low at 1.9

**Imaging**

A chest Xray was performed 1/21 and did not show any acute cardiopulmonary process. Likely bibasilar atelectasis.

**Medications**

There were no apparent changes in the patient's medication regimen.
