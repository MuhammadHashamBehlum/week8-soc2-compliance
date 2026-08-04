# Control Gap Analysis Against SOC 2 — Readiness Assessment

**Prepared By:** Mohammad Hesham Wazir  
**University:** Rochester Institute of Technology (RIT) Dubai  
**Program:** Bachelor of Science in Cybersecurity  
**Internship:** Sohail Smart Solutions Summer Training Program 2026  

---

# Introduction

A SOC 2 Readiness Assessment helps an organization determine whether its security controls are ready for a formal SOC 2 Type II audit. Before hiring an external auditor, organizations perform a readiness assessment to identify weaknesses, strengthen existing controls, and collect the evidence needed to demonstrate compliance.

For this assessment, the same SaaS organization from Monday's assignment was used. The assessment focuses on the four selected Trust Services Criteria (TSC):

- Security
- Availability
- Confidentiality
- Privacy

Each control was evaluated using four standard audit techniques:

- **Inquiry** – Interviewing employees responsible for the control.
- **Observation** – Watching the control being performed.
- **Inspection** – Reviewing policies, procedures, logs, reports, and supporting evidence.
- **Re-performance** – Independently verifying that the control works correctly.

Controls were rated as:

- Met
- Partially Met
- Not Met

---

# SOC 2 Readiness Control Assessment

| No. | Control | Trust Services Criteria | Status | Control Deficiency | Management Remediation Response |
|------|----------|-------------------------|---------|--------------------|--------------------------------|
| 1 | Information Security Policy | Security | **Met** | Security policies are documented, approved, and reviewed regularly. | Continue annual reviews and maintain version control. |
| 2 | Multi-Factor Authentication (MFA) | Security | **Met** | MFA is enabled for privileged accounts. | Continue monitoring privileged accounts and enforce MFA for all future administrator accounts. |
| 3 | User Access Reviews | Security | **Partially Met** | User access reviews are performed but documentation is inconsistent. | Implement quarterly documented access reviews with management approval. |
| 4 | Incident Response Plan Testing | Security | **Partially Met** | Incident response procedures exist, but annual testing has not been completed. | Conduct annual tabletop exercises and document corrective actions. |
| 5 | Security Monitoring and Log Management | Security | **Met** | Centralized logging is operating effectively. | Continue monitoring security events and verify log retention. |
| 6 | Backup and Disaster Recovery Testing | Availability | **Partially Met** | Backups are completed, but restoration testing has not been documented. | Perform restoration testing every six months and retain evidence. |
| 7 | Change Management | Processing Integrity | **Met** | Formal approval process exists before production changes. | Continue documenting approvals and testing results. |
| 8 | Encryption of Sensitive Data | Confidentiality | **Met** | Customer data is encrypted both in transit and at rest. | Continue reviewing encryption standards and certificate renewals. |
| 9 | Vendor Risk Management | Security | **Partially Met** | Vendors are assessed during onboarding but not consistently reassessed. | Schedule annual vendor risk reviews based on business criticality. |
| 10 | Privacy Management | Privacy | **Not Met** | Privacy documentation does not fully define data retention and customer rights. | Update privacy policies, define retention schedules, and document procedures for privacy requests. |

---

# Control Testing Methods

## Inquiry

Responsible employees, including IT administrators and compliance personnel, were interviewed to understand how security controls operate and who is responsible for maintaining them.

## Observation

Daily operational activities such as user access approvals, security monitoring, and backup procedures were observed to verify that documented processes are followed consistently.

## Inspection

Evidence including policies, audit logs, change requests, backup reports, access review records, and incident response documentation was reviewed to confirm that controls are properly documented.

## Re-performance

Selected activities, such as verifying user permissions and reviewing backup restoration procedures, were independently repeated to ensure the controls operate as intended.

---

# Readiness Assessment Summary

A total of **10 controls** were evaluated.

| Result | Number |
|---------|-------:|
| Met | 5 |
| Partially Met | 4 |
| Not Met | 1 |

## Overall Readiness Score

**70% Ready**

The organization has established a strong security foundation and already satisfies several important SOC 2 control requirements. Security governance, access management, encryption, centralized logging, and change management are operating effectively.

However, several operational improvements are still required before proceeding to a SOC 2 Type II audit. Most of the remaining gaps relate to documenting recurring control activities rather than implementing new technical controls. Areas that require improvement include backup restoration testing, quarterly access reviews, annual incident response exercises, vendor reassessments, and privacy documentation.

Addressing these findings will improve the organization's compliance maturity and significantly increase the likelihood of a successful SOC 2 audit.

---

# Final Recommendation

## Recommendation: **NO-GO for SOC 2 Type II Audit**

Based on this readiness assessment, I do not recommend proceeding with a SOC 2 Type II audit at this time.

While the organization has implemented many important security controls, several controls still require stronger documentation and more consistent operational evidence. Since a SOC 2 Type II audit evaluates how controls perform over time, these gaps should be addressed before engaging an external auditor.

The recommended next steps are:

- Formalize quarterly user access reviews.
- Conduct annual incident response exercises.
- Perform regular backup restoration testing.
- Complete annual vendor reassessments.
- Update privacy policies and document data retention procedures.

Once these improvements have been implemented and sufficient evidence has been collected over several months, the organization should complete another readiness assessment.

At that point, the organization is expected to achieve approximately **90–95% readiness**, making it well prepared for a successful SOC 2 Type II audit.
