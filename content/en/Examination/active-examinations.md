---
title: "Active Examinations"
linkTitle: "Active Examinations"
weight: 1
description: >
  Learn how to manage patient examination form as a doctor
---

# MedAX – Capturing Vital Signs (User Guide)

## 1. Purpose  
The purpose of this document is to explain the steps for accurately and completely recording patient vital signs during visits in MedAX.  

## 2. Definition  
Vital signs are key indicators of a patient’s basic health status. The parameters recorded in MedAX are:  
- **T:** Temperature (°C)  
- **P:** Pulse (/min)  
- **SBP:** Systolic Blood Pressure (mmHg)  
- **DBP:** Diastolic Blood Pressure (mmHg)  
- **Wt(kg):** Weight (kg)  
- **Ht(cm):** Height (cm)  
- **BMI:** Body Mass Index (can be calculated automatically or manually)  
- **RR:** Respiratory Rate (/min)  
- **SpO₂:** Oxygen Saturation (%)  

## 3. Access Path  
1. Go to **Front Office > Visit List**.  
2. Select the patient visit you want to add vital signs to.  
3. Click the **Add Vital** button in the top menu.  

## 4. Data Entry  
In the **Add vital** panel (opens on the right side of the screen), enter the patient’s measurements:  
- Enter values with the correct units (e.g., °C, mmHg, %).  
- Missing or incorrect entries may affect the accuracy of the patient record.  
- After entering all required values, click **OK** to save.  

## 5. Recording and Review  
- The entered vital signs are linked to the patient’s visit.  
- You can view all past vital records from the **Vital History** menu.  

## 6. Example Scenario  
1. Patient: *Adam Smith*  
2. Visit: `000000048` (Outpatient – General Practice)  
3. Measured vital values:  
   - T: 37.2  
   - P: 84  
   - SBP: 120  
   - DBP: 78  
   - Wt: 72  
   - Ht: 175  
   - BMI: 23.5  
   - RR: 18  
   - SpO₂: 98  
4. Once saved, the vitals are available in the vital history.  

## 7. Tips  
- If the system calculates BMI automatically, only weight and height need to be entered.  
- For emergency visits, **RR and SpO₂** should always be recorded.  
- Vital information cannot be edited after saving — only new entries can be added (depending on organizational policy).

---

# MedAX – Issuing Sick Notes (Medical Report)

## 1. Purpose  
This document describes the steps to generate and issue a Sick Note (Medical Report) for patients in MedAX.  

## 2. Definition  
A **Sick Note (Medical Report)** is an official document provided by a physician to confirm a patient’s illness and recommend rest or exemption from work/school for a specific period.  

## 3. Access Path  
1. Go to **Front Office > Visit List**.  
2. Select the patient visit for which a sick note is required.  
3. Open the visit details and choose **Medical Report > Sick Note**.  

## 4. Data Entry  
When creating a Sick Note, fill in the following information:  
- **Patient Name** (auto-filled from visit record)  
- **Date of Visit** (auto-filled)  
- **Diagnosis / Reason for Sick Note**  
- **Start Date** of rest period  
- **End Date** of rest period  
- **Physician Name** (auto-filled)  
- **Additional Notes** (optional, e.g., “Fit to resume work on …”)  

After entering the required information, click **Generate Report**.  

## 5. Output  
- The system generates a formal Sick Note in PDF or printable format.  
- The document includes patient and physician details, rest period, and diagnosis.  
- The Sick Note is linked to the patient’s medical record for future reference.  

## 6. Example Scenario  
1. Patient: *Nina Frenz*  
2. Visit: `000000049` (Outpatient – General Practice)  
3. Reason: Influenza  
4. Sick Note: 3 days (16/07/2025 – 18/07/2025)  
5. Physician: *Dr. Steve Karagedik*  
6. Output: Printable Sick Note PDF stored in patient’s record.  

## 7. Tips  
- Ensure the **rest period** is compliant with organizational or legal policies.  
- For long-term absence, an extended medical certificate may be required.  
- Once issued, Sick Notes cannot be modified — if correction is needed, a new note must be generated.  
