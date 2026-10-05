# Cyber GRC Risk Assessment

## Project Overview

A practical Cyber GRC case study based on a fictional healthcare organization, **ABC Healthcare Pvt. Ltd.**

The project demonstrates a basic qualitative risk assessment process, from identifying assets, threats, and vulnerabilities to assessing likelihood and impact, selecting risk treatment, and recommending security controls.

## Organization

**ABC Healthcare Pvt. Ltd.** is a fictional healthcare organization that manages patient records, billing information, appointment data, and patient documents through internal applications, employee endpoints, email, and cloud storage.

## Objective

* Identify key information assets
* Identify relevant threats and vulnerabilities
* Assess risks based on likelihood and impact
* Determine appropriate risk treatment
* Recommend security controls
* Document the assessment in a structured risk register

## Scope

The assessment covers:

* Patient personal data
* Medical records
* Patient documents
* Cloud-stored information
* Billing and appointment data
* Employee access to systems
* Endpoint and backup security

## Risk Assessment Approach

The assessment follows a simple qualitative approach:

**Asset → Threat → Vulnerability → Likelihood → Impact → Risk Rating → Treatment → Controls**

Likelihood and impact were assessed as **Low, Medium, or High** based on the scenario context, exposure, existing controls, recent suspicious activity, and identified weaknesses.

No numerical risk scoring was used.

## Risks Identified

| Risk ID | Risk                                      | Rating | Treatment |
| ------- | ----------------------------------------- | ------ | --------- |
| R-01    | Malware affecting patient personal data   | High   | Mitigate  |
| R-02    | Excessive access to medical records       | High   | Mitigate  |
| R-03    | Phishing leading to patient data exposure | High   | Mitigate  |
| R-04    | Cloud storage misconfiguration            | High   | Mitigate  |
| R-05    | Ransomware affecting critical systems     | High   | Mitigate  |

## Key Controls Recommended

* Security Awareness Training
* Multi-Factor Authentication (MFA)
* Role-Based Access Control (RBAC)
* Principle of Least Privilege
* Periodic Access Reviews
* Endpoint Protection and EDR
* Email Security and Phishing Protection
* Public Access Restrictions
* Cloud Configuration Monitoring
* Patch Management
* Tested Backup and Restore Procedures
* Web Filtering

## CIA Impact

**Confidentiality:** Unauthorized access or exposure of patient and medical information.

**Integrity:** Unauthorized modification or deletion of critical information.

**Availability:** Disruption or loss of access to critical healthcare systems, particularly in a ransomware scenario.

## Deliverables

* `Risk_Register.xlsx`
  Structured risk register containing the identified risks, ratings, treatments, controls, owners, and status.

* `Risk_Assessment_Report.pdf`
  Detailed report explaining the assessment methodology, findings, risk scenarios, and overall observations.

## Skills and Concepts Demonstrated

* Cyber GRC
* Risk Assessment
* Risk Analysis
* Risk Treatment
* Risk Register
* Likelihood and Impact Assessment
* Security Controls
* CIA Triad
* Access Control
* MFA
* RBAC
* Least Privilege
* ISO 27001 Awareness
* NIST CSF and RMF Awareness

## Disclaimer

This is a fictional portfolio case study created for learning and demonstration of Cyber GRC risk assessment concepts. It is not an assessment of a real organization.
