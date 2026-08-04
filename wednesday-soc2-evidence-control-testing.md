# Wednesday — Evidence & Control Testing: Building the SOC 2 Audit Evidence Package

**Prepared By:** Mohammad Hesham Wazir Ali Behlum

**University:** Rochester Institute of Technology (RIT) Dubai

**Program:** Bachelor of Science in Cybersecurity

**Training:** Sohail Smart Solutions Summer Training Program 2026

**Date:** 29 July 2026

---

## Introduction

A SOC 2 Type II audit does more than verify that security controls exist. It also confirms that those controls operated effectively over a period of time. This is one of the biggest differences between a SOC 2 Type I report and a SOC 2 Type II report. While Type I focuses on whether controls are designed properly at a specific point in time, Type II evaluates whether those controls consistently worked throughout the audit period.

Auditors evaluate two important concepts during testing: **design effectiveness** and **operating effectiveness**. Design effectiveness determines whether a control is capable of reducing a specific risk. Operating effectiveness confirms that the control was actually performed according to the organization's documented procedures over several months.

Another key concept is **population and sample testing**. The population represents every activity related to a control during the audit period, such as all user access reviews or all production changes. Rather than reviewing every record, auditors select a representative sample and inspect the supporting evidence. If the sampled evidence demonstrates that the control operated correctly and consistently, the control is considered effective.

The following evidence matrix outlines six important SOC 2 controls, their operating frequency, the evidence required for a three-month audit period, the sample an auditor would normally select, and the criteria used to determine whether each control passes testing.

---

## SOC 2 Evidence Matrix

| Control | Operating Frequency | Evidence Required (3-Month Period) | Auditor Sample | Passing Criteria |
|----------|---------------------|------------------------------------|----------------|------------------|
| Multi-Factor Authentication (MFA) | Continuous (every login) | MFA configuration exports, authentication logs, user enrollment reports, exception records | Sample 25 active user accounts | MFA is enabled for every sampled account and no unauthorized exceptions exist. |
| User Access Reviews | Quarterly | Access review reports, manager approvals, user access lists, remediation records | Sample 20 user accounts from the quarterly review | Reviews are completed on time, approvals are documented, and unnecessary access has been removed. |
| Security Monitoring and Log Reviews | Daily | SIEM alerts, investigation tickets, analyst notes, escalation records | Sample 30 security alerts from the audit period | Every alert was investigated, documented, and resolved according to the incident response process. |
| Backup and Recovery Verification | Daily backups, monthly recovery testing | Backup logs, recovery test reports, failed backup tickets, restoration results | Review three monthly recovery tests and selected daily backup logs | Backups completed successfully and recovery tests met the required recovery objectives. |
| Change Management | Per production change | Change requests, approval records, testing results, deployment logs, rollback plans | Sample 20 production changes | Every sampled change was approved, tested, documented, and successfully implemented. |
| Security Awareness Training | New hire and quarterly | Training completion reports, attendance records, phishing simulation results, LMS reports | Sample 20 employees | All sampled employees completed the required security awareness training within the required timeframe. |

---

## Control Testing Narrative

### 1. Multi-Factor Authentication (MFA)

Multi-factor authentication helps protect user accounts by requiring an additional verification factor besides a password. Since users authenticate every time they sign in, this control operates continuously. During a SOC 2 Type II audit, the auditor would review the complete population of active user accounts and select a sample of 25 accounts. The evidence should include MFA configuration exports, authentication logs, and enrollment records. The control passes when every sampled account has MFA enabled and there are no unauthorized exceptions.

### 2. User Access Reviews

User access reviews verify that employees only have the permissions required for their current job responsibilities. This control is normally performed every quarter. Auditors review access review reports, manager approvals, permission lists, and records showing that unnecessary access was removed. A sample of 20 user accounts is compared with the completed access review. The control passes if reviews were completed on schedule, approvals were documented, and inappropriate access was removed promptly.

### 3. Security Monitoring and Log Reviews

Security monitoring provides continuous visibility into suspicious activities and potential security incidents. This control operates every day through SIEM monitoring and analyst investigations. Auditors select a sample of security alerts from the three-month audit period and verify that each alert was investigated, documented, and resolved according to the incident response process. The control passes when all sampled alerts include complete investigation records and appropriate response actions.

### 4. Backup and Recovery Verification

Daily backups protect critical business information, while regular recovery testing proves that data can be restored successfully. Evidence includes backup logs, restoration reports, recovery test results, and support tickets for failed backups. Auditors review several backup jobs together with monthly recovery tests. The control passes when backups complete successfully, failures are resolved, and recovery testing confirms that business recovery objectives were achieved.

### 5. Change Management

Change management ensures that production changes are properly reviewed before implementation. Evidence includes approved change requests, testing documentation, deployment records, and rollback plans. Auditors select a sample of production changes completed during the audit period and verify that every change followed the organization's documented approval process. The control passes when all sampled changes were approved, tested, documented, and implemented successfully.

### 6. Security Awareness Training

Security awareness training helps employees recognize cyber threats and follow company security policies. Evidence includes learning management system reports, attendance records, training certificates, and phishing simulation results. Auditors sample employee records to verify that training was completed within the required timeframe. The control passes when every sampled employee completed the required training and the organization maintained accurate training records.

---

## Conclusion

A successful SOC 2 Type II audit depends on more than having written policies and documented controls. Organizations must also prove that those controls operated consistently throughout the audit period by providing reliable evidence. This evidence includes system logs, approval records, configuration exports, change tickets, backup reports, access reviews, and training records.

Using a population-and-sample approach allows auditors to evaluate operating effectiveness without reviewing every record. If the selected samples consistently demonstrate that controls were performed according to policy, the control is considered effective.

Maintaining an organized evidence repository throughout the year makes the audit process more efficient, reduces preparation time, and improves confidence in the organization's security and compliance program. A strong evidence management process also supports continuous compliance by ensuring that controls are monitored, documented, and reviewed on a regular basis rather than only before an audit.
