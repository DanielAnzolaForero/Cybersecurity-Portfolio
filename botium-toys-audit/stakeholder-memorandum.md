# Internal IT Audit Findings and Recommendations

**TO:** IT Manager, Stakeholders  
**FROM:** Daniel Alejandro Anzola Forero  
**DATE:** 22/11/2025  
**SUBJECT:** Internal IT Audit Findings and Recommendations

---

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary, and recommendations.

## Scope

The audit focused on assessing the entirety of the Botium Toys cybersecurity program, covering all IT-managed assets, internal processes, and procedures. It evaluated the current user permissions and implemented controls across key systems, including accounting, endpoint detection, firewalls, Intrusion Detection Systems (IDS), and SIEM tools. The assessment included a review of hardware, system access, and the alignment of current protocols with necessary compliance requirements. Furthermore, the audit accounted for both on-premises equipment and remote workstation access to ensure a comprehensive security posture evaluation.

## Goals

The primary goal of this audit is to align Botium Toys' business practices with the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF). Key objectives include fortifying system controls and strictly implementing the concept of **least privilege** regarding user credential management. The audit also aims to establish clear policies and procedures, including incident response playbooks, to ensure the organization meets compliance requirements (such as PCI DSS and GDPR). Ultimately, the findings will be used to improve the overall security posture and justify the hiring of additional cybersecurity personnel.

## Critical Findings (Must be addressed immediately)

Based on the control assessment and compliance checklist, the following areas represent high risks and require immediate action:

- **Compliance Violations (PCI DSS & GDPR):** Current lack of encryption and weak access controls places the company in violation of PCI DSS (handling credit card information) and GDPR (handling EU customer data). This exposes the company to potential fines and legal repercussions.

- **Access Control & Least Privilege:** The principle of **Least Privilege** and **Separation of Duties** are not currently implemented. Users possess excessive permissions, increasing the risk of insider threats and unauthorized access to critical data.

- **Disaster Recovery & Backups:** There are no active Disaster Recovery Plans or consistent backup procedures in place. This poses a severe threat to business continuity in the event of a ransomware attack or system failure.

- **Threat Detection:** The organization lacks an active Intrusion Detection System (IDS) and comprehensive antivirus software implementation, leaving the network vulnerable to unmonitored attacks.

## Findings (Should be addressed, but no immediate need)

These controls are important for a mature security posture but are prioritized lower than the critical findings above:

- **Physical Security:** Controls such as time-controlled safes, adequate lighting, and alarm system signage are currently missing. While they should be implemented to deter physical theft, they are less critical than immediate digital vulnerabilities.

- **Password Management System:** Implementing a centralized password management system would improve security hygiene and reduce administrative overhead, but immediate focus should first be on establishing the password policies themselves.

- **Legacy System Monitoring:** Procedures for manually monitoring legacy systems need to be established, but this can occur after critical automated defenses are online.

## Summary / Recommendations

Botium Toys must prioritize the immediate implementation of administrative and technical controls aligned with the NIST CSF to mitigate high-risk vulnerabilities. It is imperative to enforce the **principle of least privilege**, implement robust **encryption**, and establish **disaster recovery plans** to ensure business continuity and compliance with **PCI DSS** and **GDPR**. Once these critical digital assets are secured, the organization should focus on enhancing physical security measures and refining password management workflows. To successfully implement and maintain these controls specifically the IDS and SIEM monitoring it is strongly recommended that the company proceed with hiring a dedicated cybersecurity analyst.
