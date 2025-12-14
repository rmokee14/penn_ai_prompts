## Task
Your goal is to organize the information provided by medical condition, listing the key information a physician would need to know when admitting this patient to the hospital. 
The information you list should represent information that a physician would search for in the EHR to ensure they have a complete understanding of the patient's medical history, and to help them best take care of the patient.

## Instructions

- The diseases should be ordered in terms of relevance to the patient's presentation, as well as the seriousness of the condition. They should NOT be numbered. Diseases should be listed in proximity to each other or grouped if they are closely related (i.e are also a disease of the heart, lungs, etc.) or share many of the same medications and relevant data.
- The bullets for each disease should include the following IF there is relevant information provide in the input: 
  - **Medications**: this section should list off all medications that are presumed to be prescribed for the disease process. They should NOT include medications that were prescribed during the current encounter in the emergency setting, but rather those the patient is prescribed in the outpatient setting. The format should be the following: medication name, dose, route, frequency. Please refer to the provided examples for formatting.
  - **Relevant Data**: this section should list off all relevant data (vtials, labs, imaging, other testing, etc.) related to the specific disease process. Data generated during the current clinical encounter should NOT be included.
  - **Complications**: this section should list off any prior exacerbations or complications associated with the disease. This can be a list of the items in the problem list related to the disease instead of its own standalone disease process.
- All relevant information for each of the above bullets should be listed on one line.
- In the case where there is not relevant information provided for each bullet point, that bullet point should be skipped. In certain circumstances where a piece of data would be incredibly important to best understand the dsease or clinical scenario but is NOT provided, note that such information is absent.
- Diseases that are not relevant to the clinical presentation, do not impact inpatient management of the patient, or do not have significant information about them provided in the input should be listed all on one line at the end of the output. Every problem or disease in the patient's provided past medical history should be included at some point in the output, even if only listed at the end.
- Utilize common medical abbreviations to save room

## Example

**Sickle Cell Disease (HbSS)**
- **Medications**: Hydroxyurea 1500 mg PO daily, Folic Acid 1 mg PO daily, Ferrous Sulfate 325 mg PO three times daily (for iron overload)
- **Relevant Data**: [9/27/2024] Hgb 8.4
- **Complications**: Recurrent vaso-occlusive crises, acute chest syndrome (multiple episodes), chronic anemia, iron overload (transfusion history), splenectomy (history).

**Chronic Pain (related to Sickle Cell & other causes)**
- **Medications**: Hydrocodone/Acetaminophen 5/325 mg: 1-2 tablets PO every 4 hours as needed, Gabapentin 300 mg PO three times daily
  
**Pulmonary Hypertension**
- **Medications**: None listed.
- **Relevant Data**: [4/26/2023] Echocardiogram with PASP 45.

**Asthma**
- **Medications**: Albuterol Inhaler 90 mcg: 2 puffs every 4 hours as needed, Fluticasone/Salmeterol Inhaler 250/50 mcg: 1 puff twice daily
- **Relevant Data**: [2/12/2022] Pulmonary Function Tests (PFTs) with FEV1/FVC ratio of 0.60

**Hypertension**
- **Medications**: Lisinopril 40 mg PO daily
- **Relevant Data**: [8/08/2024] Blood Pressure 167/96 during hematology visit

**Type 2 Diabetes Mellitus**
- **Medications**: Metformin 1000 mg PO twice daily
- **Relevant Data**: 9/27/2024 HgbA1c 8.7%

**Anxiety**
-  **Medications**: Sertraline 50 mg PO daily

**Gastroesophageal Reflux Disease (GERD)**
- **Medications**: omeprazole 20 mg PO daily

**Vitamin D Deficiency**
-  **Medications**: Vitamin D 50,000 IU PO once weekly
