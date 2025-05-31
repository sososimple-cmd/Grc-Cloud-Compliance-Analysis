# 🌩️ Cloud Compliance Gap Analysis: AWS + NIST CSF 
_By Sophia Mitchell_

---

## 📌 Overview

This project simulates a real-world **Cloud Compliance Gap Analysis** using **AWS** as the cloud platform and the **NIST Cybersecurity Framework (CSF)** as the guiding standard.

The goal: Identify common compliance gaps and propose actionable remediation in an AWS environment—focusing on **IAM**, **logging**, and **data classification**.

---

## 🎯 Objective

✅ Assess a cloud environment’s compliance posture 
✅ Map AWS security controls to NIST CSF 
✅ Identify and document compliance gaps 
✅ Recommend technical and policy-based remediation 
✅ Present findings in business-friendly formats 

---

## 🛠️ Tools & Frameworks Used

- 🟦 **AWS (Mock Setup)** 
- 🔐 **NIST CSF Framework** 
- 📊 Excel for Gap Analysis 
- 📄 Word & PDF for Policies and Memos 
- 🖼️ Custom Graphics and Diagrams 

---

## 📂 Folder Structure

| Folder | Description |
|--------|-------------|
| `Gap-Analysis/` | Excel spreadsheet with mapped NIST controls, gaps, and remediation |
| `Business-Summary/` | Executive memo summarizing findings and recommendations |
| `Policies/` | Draft policy on AWS data classification and governance |
| `Executive-Summary/` | 1-page remediation slide deck for leadership |
| `Screenshots/` | Mock AWS console screenshot (IAM, logging, S3) |
| `Visuals/` | Medium blog header image and social banner |

---

## 📄 Key Files

📘 [Cloud_Compliance_Gap_Analysis.xlsx](./Gap-Analysis/Cloud_Compliance_Gap_Analysis.xlsx) 
📄 [AWS_Cloud_Compliance_Memo.pdf](./Business-Summary/AWS_Cloud_Compliance_Memo.pdf) 
🛡️ [Cloud_Data_Classification_Policy.docx](./Policies/Cloud_Data_Classification_Policy.docx) 
🖥️ [Compliance_Remediation_Slide.pdf](./Executive-Summary/Compliance_Remediation_Slide.pdf) 
📸 [Mock_AWS_Environment_Overview.png](./Screenshots/Mock_AWS_Environment_Overview.png)

---

## 🔍 Summary of Gaps

| Control Area | Gap | Risk | NIST Ref | Fix |
|--------------|-----|------|----------|-----|
| IAM | MFA not enforced | High | PR.AC-7 | Enable MFA for all users |
| Logging | No centralized CloudTrail logging | High | DE.CM-1 | Activate logging + alerts |
| S3 | No classification or tagging | Medium | ID.GV-3 | Create classification policy |

---

## 💡 Insights

> “MFA isn’t optional—compliance depends on it.” 
> This project taught me how **small oversights create massive risk** and how to connect technical issues with business impact.

---

## 📖 Related Blog Post

📚 [Read the full Medium article here](https://medium.com/@sophiamitchell/cloud-compliance-gap-analysis-nist-csf-aws)

---
