# SOC 2 Framework Foundations — The Trust Services Criteria in Practice

**Prepared By:** Mohammad Hesham Wazir Ali Behlum

**University:** Rochester Institute of Technology (RIT) Dubai

**Program:** Bachelor of Science in Cybersecurity

**Internship:** Sohail Smart Solutions Summer Training Program 2026

**Submission Date:** 27 July 2026

---

## Introduction

Throughout the previous weeks of this internship, I worked with ISO/IEC 27001 by performing gap assessments, developing security policies, preparing audit evidence, and assessing cloud security. This assignment builds on that experience by introducing the **SOC 2 framework**, which is widely used by Software-as-a-Service (SaaS) companies to demonstrate that they protect customer information through effective security controls.

Unlike ISO/IEC 27001, which focuses on establishing and maintaining an Information Security Management System (ISMS), SOC 2 evaluates whether security controls are operating effectively based on the **Trust Services Criteria (TSC)**.

For the EduTrack Learning Solutions SaaS environment used throughout this internship, SOC 2 is an appropriate framework because the organization stores customer information, delivers cloud-based services, and must provide assurance that its systems are secure, reliable, and properly managed.

---

## SOC 2 Scoping for EduTrack Learning Solutions

For the EduTrack Learning Solutions SaaS platform, all five Trust Services Criteria should be included within the SOC 2 assessment scope.

| Trust Services Criteria | Applicable | Justification |
|---|:---:|---|
| **Security** | ✅ | Protects systems through access control, Multi-Factor Authentication (MFA), monitoring, and incident response. |
| **Availability** | ✅ | Ensures the learning platform remains accessible through backups, disaster recovery, and monitoring. |
| **Processing Integrity** | ✅ | Ensures student records and learning data are processed accurately and completely. |
| **Confidentiality** | ✅ | Protects sensitive business and customer information using encryption and access controls. |
| **Privacy** | ✅ | Protects personal information belonging to students and staff according to privacy requirements. |

---

## SOC 2 Type I vs. Type II

### SOC 2 Type I

A **SOC 2 Type I** report evaluates whether controls are properly designed and implemented at a specific point in time.

### SOC 2 Type II

A **SOC 2 Type II** report evaluates whether those controls continue operating effectively over a period of time. This provides stronger assurance because the auditor evaluates ongoing compliance rather than a single point-in-time review.

Auditors typically examine security policies, access reviews, incident response records, monitoring logs, change management, audit evidence, and control testing.

---

## ISO/IEC 27001 to SOC 2 Crosswalk

| Existing ISO/IEC 27001 Control | SOC 2 Trust Services Criteria | Purpose |
|---|---|---|
| Multi-Factor Authentication (MFA) | Security | Prevents unauthorized access. |
| Role-Based Access Control (RBAC) | Security, Confidentiality | Limits permissions according to job roles. |
| Information Security Policy | Security | Establishes governance and security expectations. |
| Access Control Policy | Security, Confidentiality | Defines authentication and authorization requirements. |
| Incident Response Plan | Security, Availability | Supports detection, containment, recovery, and lessons learned. |
| Security Awareness Training | Security | Reduces human error and phishing risk. |
| Cloud Security Posture Management (CSPM) | Security, Availability | Identifies cloud misconfigurations and compliance issues. |
| Audit Evidence Register | Security | Demonstrates that controls operate effectively. |

---

## Additional Controls Emphasized by SOC 2

### Continuous Control Monitoring

SOC 2 emphasizes continuous monitoring and ongoing evidence collection to demonstrate that controls remain effective throughout the audit period.

### Service Availability

Organizations should continuously monitor uptime, backups, disaster recovery readiness, and system reliability to meet customer expectations.

### Vendor and Sub-Service Organization Management

SOC 2 requires stronger oversight of cloud providers and third-party vendors to ensure outsourced services continue meeting security requirements.

---

## Conclusion

Implementing SOC 2 for EduTrack Learning Solutions builds naturally on the ISO/IEC 27001 work completed throughout this internship. Existing governance documents, access controls, audit evidence, cloud security controls, and incident response procedures can all be mapped directly to the SOC 2 Trust Services Criteria.

Learning both ISO/IEC 27001 and SOC 2 strengthens framework crosswalk skills and prepares GRC professionals to support organizations that must comply with multiple industry standards while maintaining a secure and reliable cloud environment.
