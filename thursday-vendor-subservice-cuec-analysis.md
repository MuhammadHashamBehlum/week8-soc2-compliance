# Vendor & Sub-Service Organization Management in SOC 2

---

**Prepared By:** Mohammad Hesham Wazir  
**University:** Rochester Institute of Technology (RIT) Dubai  
**Program:** Bachelor of Science in Cybersecurity  
**Internship:** Sohail Smart Solutions Summer Training Program 2026  

## Submission Date: 7 August 2026

---

# Vendor & Sub-Service Organization Management in SOC 2

## Introduction

SOC 2 compliance does not only focus on the security controls implemented by an organization itself. It also requires organizations to understand and manage the risks introduced by third-party vendors and sub-service organizations that support business operations. Modern SaaS companies rely on external providers for cloud hosting, payment processing, email services, and security monitoring. Since these vendors have access to systems or sensitive customer information, their security practices directly affect the organization's ability to maintain SOC 2 compliance.

For this assessment, I continued using the same SaaS client from the previous SOC 2 assignments. The organization has already completed its SOC 2 scope, readiness assessment, and evidence planning. This report identifies the sub-service organizations involved, determines whether the carve-out or inclusive method should be used, defines the Complementary User Entity Controls (CUECs), and explains how each vendor's SOC 2 report should be reviewed as part of the vendor risk management process.

---

# 1. Sub-Service Organization Analysis

| Sub-Service Organization | Service Provided | SOC 2 Method | Justification |
|--------------------------|-----------------|--------------|---------------|
| Amazon Web Services (AWS) | Cloud infrastructure, storage, networking, virtual servers, and backups | **Carve-Out** | AWS manages its own infrastructure and security controls. The SaaS company manages applications and configurations, making the carve-out method the most appropriate. |
| Stripe | Online payment processing | **Carve-Out** | Stripe operates its own secure payment platform and provides independent SOC 2 reports. The organization relies on those audited controls instead of including them in its own audit. |
| SendGrid | Email delivery and customer notifications | **Carve-Out** | SendGrid independently manages email services and infrastructure. The organization verifies its compliance by reviewing its SOC 2 report. |
| Managed Security Service Provider (MSSP) | Security monitoring, alert management, and incident response support | **Inclusive** | The MSSP directly supports important security operations. Including these controls in the SOC 2 scope provides stronger assurance over security monitoring activities. |

---

# 2. Carve-Out vs. Inclusive Method

SOC 2 allows organizations to choose between two approaches when relying on sub-service organizations.

The **carve-out method** excludes the vendor's internal controls from the organization's own SOC 2 examination. Instead, the organization reviews the vendor's SOC 2 report to verify that appropriate controls are operating effectively. This approach is commonly used for large providers such as AWS, Stripe, and SendGrid because they already maintain independent SOC 2 certifications.

The **inclusive method** includes the sub-service organization's controls within the organization's own SOC 2 audit. This approach is more suitable when the vendor performs operational activities that directly affect the effectiveness of security controls. In this scenario, the Managed Security Service Provider is included because it participates in continuous monitoring and incident response, making it an important part of the overall security program.

Using both methods allows the organization to balance audit efficiency while maintaining strong oversight of third-party services.

---

# 3. Complementary User Entity Controls (CUECs)

SOC 2 reports often describe **Complementary User Entity Controls (CUECs)**. These are controls that the vendor expects the customer organization to perform in order for the vendor's controls to remain effective.

### CUEC 1: Identity and Access Management

The organization must enforce multi-factor authentication (MFA), apply the principle of least privilege, review user permissions regularly, and immediately disable accounts that are no longer required. Although AWS secures the cloud infrastructure, user account management remains the organization's responsibility.

### CUEC 2: Secure Configuration Management

The organization is responsible for securely configuring cloud resources, databases, encryption settings, firewalls, logging, and backup policies. Cloud providers deliver secure infrastructure, but customers are responsible for protecting their own environments through proper configuration.

### CUEC 3: Vendor Monitoring and Annual Review

Management must regularly monitor vendor performance, maintain security agreements, review updated SOC 2 reports, and reassess vendor risk annually or whenever significant service changes occur. Continuous oversight ensures that third-party risks remain acceptable throughout the relationship.

---

# 4. Reviewing Vendor SOC 2 Reports

To verify that vendors continue to meet security requirements, the organization should follow a structured review process.

### Step 1: Obtain the Report

Request the vendor's latest SOC 2 Type II report through the vendor portal or after signing a Non-Disclosure Agreement (NDA).

### Step 2: Verify the Report Scope

Confirm that the report covers the required Trust Services Criteria, especially Security and Availability, and that the audit period overlaps with the organization's own SOC 2 audit period.

### Step 3: Review the Auditor's Opinion

Ensure the report contains an unqualified opinion and determine whether any significant findings or limitations are noted.

### Step 4: Review Control Exceptions

Carefully evaluate any control exceptions or observations to determine whether they introduce additional risks to the organization.

### Step 5: Review Complementary User Entity Controls

Verify that every CUEC listed within the vendor's SOC 2 report has been implemented by the organization and that supporting evidence exists.

### Step 6: Document the Review

Record the review date, auditor opinion, identified risks, residual risk, reviewer name, and next review date in the vendor risk register.

---

# 5. Connection to Previous Vendor Risk Management Work

This assignment builds directly on the vendor risk management activities completed earlier in the internship. During Week 5, vendors were identified, classified according to their risk level, and evaluated through security questionnaires and due diligence activities. SOC 2 expands that work by formally recognizing sub-service organizations within the audit scope and requiring documented evidence that their security controls are operating effectively.

Instead of relying only on questionnaires, organizations now review vendor SOC 2 reports, identify Complementary User Entity Controls, and continuously monitor vendor performance. This creates a stronger governance process and demonstrates that third-party risks are effectively managed throughout the compliance program.

---

# Conclusion

Managing vendors and sub-service organizations is one of the most important aspects of SOC 2 compliance because security responsibilities extend beyond the organization's own environment. For this SaaS client, AWS, Stripe, and SendGrid are best managed using the **carve-out method** because each maintains independently audited SOC 2 controls. The Managed Security Service Provider is better suited to the **inclusive method** because its activities directly support the organization's security operations.

By implementing strong Complementary User Entity Controls, reviewing vendor SOC 2 reports annually, and maintaining continuous vendor oversight, the organization strengthens its governance program, reduces third-party risk, and improves its readiness for a successful SOC 2 Type II audit.
