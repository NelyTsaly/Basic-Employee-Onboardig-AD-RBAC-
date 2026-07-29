# Basic Employee Onboarding (AD)(RBAC)
## Problem Statement
*This project demonstrates the design and deployment of a structured Identity and Access Management (IAM) onboarding pipeline within Active Directory Domain Services (AD DS). The goal was to replace ad-hoc user provisioning with a standardized Role-Based Access Control (RBAC) framework to enforce the principle of least privilege and satisfy strict healthcare compliance standards. Northstar Medical Group, a rapidly growing healthcare provider, historically outsourced its identity lifecycle operations to a third-party Managed Service Provider (MSP). As organizational complexity increased, severe identity governance gaps emerged: Absence of RBAC Policies: Permissions were assigned on an ad-hoc basis without standard operational procedures. HIPAA & Compliance Risks: Loose access controls created unauthorized access risks to sensitive Protected Health Information (PHI). Lack of Auditability: The organization lacked clean audit trails to track privilege escalation, user access history, or account modifications. Privilege Creep: Accumulation of excessive permissions over time left orphaned privileges across various departments. 
## Solution Overview
*To resolve these identity lifecycle issues, I designed and deployed a centralized onboarding pipeline in a controlled lab environment: RBAC Access Matrix: Established a structured matrix mapping organizational job roles directly to Active Directory Security Groups and resource permissions. Role-Based Provisioning: Standardized user account creation to ensure users receive access strictly required for their job function. 
Incident Simulation & Remediation: Simulated a real-world helpdesk ticketing scenario where a user received misprovisioned access permissions, demonstrating the identification, auditing, and remediation process. 
## Video Walkthrough
https://www.loom.com/share/2cbdf62759e74c43ac0764253eb5cb53 
## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub
## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging
## Key Accomplishments
* Built and configured the NMG.com domain from scratch in an isolated lab environment. 
*Implemented a least-privilege RBAC architecture to satisfy compliance requirements. 
*Successfully investigated and resolved helpdesk ticket NMG-0047 involving account misprovisioning. 
*Fully documented the deployment end-to-end to serve as an enterprise documentation template. 
