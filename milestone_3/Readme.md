# Milestone 3 — Automated Clinical Note Generation
Milestone 3 focuses on automating clinical documentation by generating structured, human-readable medical notes from patient data. Using structured EHR records, this milestone demonstrates how manual clinical documentation can be reduced through programmatic note generation.
The generated notes simulate real-world EHR documentation and prepare the system for future automation such as ICD coding, billing, and clinical reporting.

---

## Objectives

- Automate clinical note generation from structured patient data  
- Convert tabular EHR data into readable medical documentation  
- Store individual patient notes in a traceable format  
- Demonstrate scalable documentation workflows using Python  

---

## Input Dataset

### `structured_data.csv`

Located inside the `Notebook` folder, this file contains structured patient information such as:

- Patient ID  
- Patient Name  
- Age  
- Gender  
- Symptoms  
- Diagnosis  

This dataset serves as the primary input for generating clinical notes.

---

## Workflow Description

### Step 1: Load Structured Data
The `structured_data.csv` file is loaded into a Pandas DataFrame to enable structured processing of patient records.

---

### Step 2: Clinical Note Generation Logic
A template-based approach is used to generate consistent and clinically meaningful notes.  
Each note includes:

- Patient demographics  
- Presenting symptoms  
- Clinical assessment  
- Follow-up recommendation  

---

### Step 3: Automated Note Generation
For each patient record:
- Relevant fields are extracted  
- A structured clinical note is generated  
- The note is saved as an individual text file  

---

### Step 4: Result Storage
Each generated note is stored in the `Results` folder as a `.txt` file.  

---

## Output Description

### Generated Clinical Notes

Each text file in the `Results` folder represents an automatically generated clinical note for a single patient.

These notes are:
- Readable and structured  
- Suitable for EHR upload  
- Easy to review and audit  
- Ready for future ICD and billing integration  

---

## Clinical & System Impact

This milestone demonstrates how automated documentation can:

- Reduce clinician documentation workload  
- Improve consistency across patient records  
- Enable scalable EHR documentation workflows  
- Support downstream analytics and automation  

---

## Milestone 3 Summary

- Structured patient data processed successfully  
- Automated clinical notes generated  
- Outputs stored in a clean, organized format  
- Workflow aligned with real-world EHR documentation  
- Foundation prepared for ICD automation and intelligent reporting  

---

## Future Scope

- ICD-10 code integration within generated notes  
- Use of Generative AI (Azure OpenAI) for richer narratives  
- Conversion of notes to JSON or FHIR formats  
- Integration with hospital EHR systems  



