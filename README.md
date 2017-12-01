# SSmimic

MIMIC Database:

1. Subsetting the MIMIC database:

Demographic Characteristics: 
- subject_id, hadm_id, icustay_id, age, gender, ethnicity, marital status, insurance status, admit year , 

Clinical Characteristics: 
- mean pain, median pain, max pain, icu_los, oasis, e_score, 

Medication Characteristics: 
- drug, drug_name_generic, formulary_drug_cd, form_unit_disp, route


To include: 
- All patients with self-reported pain scores

To Exclude: 
- All patients with ICD - 9 codes for Drug Dependence or Abuse [codes beginning with 304 or 305]
- All patients with Elixhauser scores > _____
- Years 2001 and 2012

2. Identifying Patients who received IV Opioids:

- Patients who received ____
- All patients who received IV medication 


3. Analysis:
- Ethnicity categorized as Black, White, Hispanic and Other 
- Marital Status categorized as ____
- Insurance Status categorized as ____
- Patients who received Opioids coded as 1, and who did not were coded as 0
- Years categorized as 2002 - 2005; 2006 - 2008; 2009 - 2011





