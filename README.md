# Third-Party Risk Assessment (TPRA) – Rex Medical

## Project Overview

Rex Medical Pty Ltd is a healthcare organisation that relies on CloudHR Solutions, a third-party SaaS provider, to manage HR and payroll-related information. The platform stores sensitive employee data, including personal information, payroll records, employment contracts, and onboarding documents.

As part of Rex Medical’s supplier governance process, a Third-Party Risk Assessment was performed before contract renewal. I acted as a GRC/Security Analyst and assessed CloudHR Solutions using a structured Third-Party Risk Assessment (TPRA) questionnaire. The assessment reviewed the supplier's security posture, identified key risks, and provided recommendations to management.

---

# Supplier Profile

| Item | Details |
|------|---------|
| Supplier Name | CloudHR Solutions |
| Service Provided | Cloud-based Human Resources and Payroll SaaS Platform |
| Business Owner | Human Resources Manager |
| Supplier Contact | John Smith – Account Manager *(fictional)* |
| Contract Status | Annual Renewal Assessment |
| Data Processed | Employee PII, Payroll Information, Employment Contracts, Tax Information |
| Data Classification | Confidential |
| Hosting Model | Software as a Service (SaaS) |
| Internet Facing | Yes |
| Critical Business Function | Yes |
| Criticality Tier | Tier 1 (Critical Supplier) |

CloudHR Solutions has been classified as a Tier 1 supplier because it processes sensitive employee information and supports critical HR and payroll functions. Any compromise of the service could impact payroll operations, employee privacy, regulatory compliance, and business continuity. As a result, the supplier requires a comprehensive security assessment before contract renewal.

---

# Assessment Scope

The purpose of this assessment is to evaluate the security posture of CloudHR Solutions and determine whether the supplier provides an acceptable level of security to protect Rex Medical's sensitive employee information. The assessment focuses on key security domains that support governance, risk management, and regulatory compliance.

## Assessment Objectives

- Evaluate the supplier's overall cybersecurity maturity.
- Identify security weaknesses that may impact Rex Medical.
- Assess the effectiveness of security controls.
- Determine the overall level of third-party risk.
- Provide recommendations to reduce identified risks.

## Assessment Scope

The assessment covers the following security domains:

- Governance and Security Management
- Security Policies and Standards
- Asset Management
- Identity and Access Management (IAM)
- Vulnerability Management
- Security Monitoring and Logging
- Incident Response
- Data Protection and Encryption
- Backup and Disaster Recovery
- Security Awareness Training
- Business Continuity
- Regulatory Compliance

## Assessment Methodology

The assessment was performed using a structured Third-Party Risk Assessment (TPRA) questionnaire. Responses supplied by the vendor were reviewed and evaluated to determine the effectiveness of existing security controls. Risks were identified, assigned a severity rating, and documented with recommendations for remediation where appropriate.

---

# Assessment Outcome

| Item | Result |
|------|--------|
| Assessment Type | Third-Party Risk Assessment |
| Overall Vendor Rating | Medium Risk |
| Controls Reviewed | 97 |
| High Risk Findings | 2 |
| Medium Risk Findings | 14 |
| Low Risk Findings | 81 |
| Recommendation | Approved with Remediation |

**Screenshot 1 – Completed TPRA Questionnaire**

<img width="1448" height="727" alt="image" src="https://github.com/user-attachments/assets/b5782b20-efbb-485d-b80f-f995218a1f18" />

---

# Executive Summary

Rex Medical conducted a Third-Party Risk Assessment (TPRA) of CloudHR Solutions as part of its supplier governance and contract renewal process. The assessment evaluated the supplier's security controls across governance, information security, application security, identity and access management, physical security, incident management, and third-party oversight.

Overall, the supplier demonstrated a mature security posture with most controls operating effectively. However, several medium and high-risk findings were identified, including the absence of file integrity monitoring, incomplete server hardening across desktop systems, delayed vulnerability remediation, and gaps in backup protection. These findings should be addressed through a formal remediation plan to reduce risk before contract renewal.

## Overall Vendor Risk Rating: Medium

- There are numerous controls that are implemented and operating effectively.
- A small number of High-Risk findings were identified.
- There are several Medium Risk findings that require remediation.
- Overall vendor risk is considered acceptable, subject to remediation activities.

The following risk heat map provides a visual summary of the assessment results. The majority of controls were assessed as low risk, with a limited number of medium and high-risk findings requiring remediation before contract renewal.

**Screenshot 2 – Vendor Risk Heat Map**

<img width="2678" height="1695" alt="Picture1" src="https://github.com/user-attachments/assets/4ad469a8-5eb8-4379-a63c-a5ff03bdf8e3" />

---

# Risk Register

**Screenshot 3 – Risk Register**

<img width="1858" height="463" alt="image" src="https://github.com/user-attachments/assets/982e0a10-af29-43a7-9068-086ca534b7d7" />

---

# Recommendations

The following recommendations are prioritised according to the level of risk identified during the assessment.

## High Priority

- Implement File Integrity Monitoring (FIM) across all production servers.
- Obtain ISO 27001 certification or provide equivalent independent assurance.
- Extend server hardening standards to desktop systems.

## Medium Priority

- Complete and approve the Information Protection Policy.
- Conduct regular Incident Response testing.
- Improve patch management and vulnerability remediation timeframes.
- Apply production-equivalent security controls to test environments.
- Perform monthly privileged access reviews.
- Increase the frequency of web server log reviews.
- Encrypt backup media and perform quarterly backup integrity testing.

## Low Priority

- Continue maintaining existing security controls.
- Continue annual security awareness training.
- Review security controls annually as part of the supplier review process.

---

# Conclusion

The Third-Party Risk Assessment found that CloudHR Solutions has implemented the majority of expected security controls and demonstrates an overall mature security posture. However, several medium and high-risk findings require remediation to further reduce operational and cybersecurity risk. Based on the assessment, CloudHR Solutions is considered an acceptable supplier for Rex Medical, provided the identified remediation activities are completed and monitored through a formal risk treatment plan.


