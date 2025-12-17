# Digital Forensics Investigation: Expert Witness Case Study

This repository contains a comprehensive digital forensic analysis conducted for a simulated legal case (**Paul Djanko v Stuart Tchaikovsky**). The project demonstrates the full lifecycle of a forensic investigation, from evidence recovery to expert witness reporting for the Crown Prosecution Service.

## ⚖️ Case Background
On March 22, 2023, a warrant was executed at the residence of Paul Djanko. A laptop and a damaged dashcam were recovered in connection with an assault on Stuart Tchaikovsky. The objective was to verify the suspect's location, identify connections between parties, and assess the truthfulness of the suspect's statements.

## 🛠️ Forensic Toolkit
- **Autopsy:** Used for disk image analysis, file recovery, and keyword searching.
- **FTK Imager:** Utilized for creating bit-stream forensic images and mounting drives.
- **ExifTool:** Used to extract and analyze metadata from media files.
- **GPXSee:** Employed to map and visualize GPS coordinates extracted from dashcam footage.
- **Registry Explorer:** Used to investigate system artifacts and user activity.

## 🔍 Key Findings & Evidence

### 1. Evidence Recovery (Autopsy)
- Recovered deleted communications (emails and payment records) that established a prior relationship between the suspect and the victim.
- Identified specific file pathways and timestamps that contradicted the suspect's initial interview statements.

### 2. Geolocation & Alibi Refutation
- **Device:** Damaged Dashcam.
- **Process:** Extracted hidden metadata from video files using `ExifTool`.
- **Result:** Successfully mapped the suspect's movements using `GPXSee`. The GPS data proved the suspect was at the scene of the assault, directly refuting his geographical alibi.



### 3. Media & Metadata Analysis
- Identified file tampering by analyzing "Date Modified" vs. "Date Created" metadata.
- Recovered image files that provided visual evidence of suspicious activity leading up to the incident.

## 📄 Deliverables
- **Expert Witness Report:** A 26-page professional report detailing the methodology, compliance with forensic standards, and objective findings.
- **Evidence Logs:** Documentation of hashes (MD5/SHA1) to ensure the integrity of the digital evidence.
- **Forensic Artifacts:** Visualizations of timelines and GPS mapping.

## 🛡️ Compliance & Standards
This investigation was conducted with strict adherence to:
- **Chain of Custody** protocols.
- **Expert Witness Duties:** Providing independent, objective, and unbiased opinion to the court.
- **Data Integrity:** Ensuring no data on the original media was modified during the analysis.

---
*Project completed by Mohammed Anwar Salman as part of a Digital Forensics specialization.*
