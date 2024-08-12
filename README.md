<h1>Secure Cloud Migration and Compliance for SWBTL LLC</h1>

<h2>Description</h2>
This project showcases the cloud security solutions i designed and implemented for SWBTL LLC, a nationwide document and delivery service provider. The project highlights the challenges faced during the company's migration to Microsoft Azure and the strategic solutions applied to enhance the security posture while ensuring regulatory compliance.


# Summary
SWBTL LLC faced significant challenges due to its reliance on rented data centers, including limited control over physical infrastructure, potential vulnerabilities, and difficulties in meeting regulatory compliance. To address these issues, the company decided to migrate to the Microsoft Azure cloud environment, leveraging its advanced security capabilities.

- Security Posture Improvement: Implemented robust access controls, data encryption, and continuous monitoring to protect sensitive data.
- Regulatory Compliance: Ensured adherence to industry standards such as FISMA and PCI DSS to prevent financial penalties and reputational loss.
- Azure Migration: Focused on migrating critical departments (marketing, accounting, and IT) to Azure for enhanced security and scalability.
- Role-Based Access Control: Configured Azure Active Directory groups and enforced the principle of least privilege to control access and reduce risks.


# Proposed Secure Azure Cloud Solution

  - Service Model,
    
    - The IaaS model within Microsoft Azure was selected to meet both security and compliance requirements. This model allows SWBTL LLC to manage the provisioning and management of virtual servers, tailoring the infrastructure to specific business needs.

- Security Benefits,
  
    - Advanced Access Control: Implemented encryption, network security, and centralized management to align with security requirements.
    - Scalability: Azure's scalability allows SWBTL LLC to dynamically adjust resources based on demand, ensuring optimal performance and cost efficiency.
    - Compliance: Adhered to PCI DSS and FISMA guidelines, ensuring data protection and meeting regulatory requirements.


# Role-Based Access Control (RBAC) Configuration
   
- Azure Active Directory Groups: Created separate groups for marketing, accounting, and IT departments to maintain the principle of least privilege. ![image](https://github.com/user-attachments/assets/795aeda0-a69e-4d12-bcb6-182820ea3cb6) ![image](https://github.com/user-attachments/assets/77c4434c-1868-44e7-a636-f48945e837b2)
![image](https://github.com/user-attachments/assets/6e0080a0-ef81-44d3-b9aa-08a95399a344)


- Multi-Factor Authentication (MFA): Required a second form of authentication to enhance security and reduce the risk of unauthorized access.

# Azure Key Vault Implementation

- Centralized Key Management: Managed cryptographic keys and secrets securely using Azure Key Vault.
- Encryption: Protected data-in-transit and data-at-rest with encryption strategies tailored to the needs of each department.
- Access Policies: Implemented strict access policies in Azure Key Vault to ensure sensitive information is compartmentalized and protected.

# Backup Strategy

- Backup Policy: Established a "SWBTL Backup Policy" to govern backup procedures and ensure data protection. ![image](https://github.com/user-attachments/assets/ffcc2930-9ace-4f5d-bdcf-3fa1ee314bdb)
- Scheduled Backups: Configured daily backups to minimize disruptions and ensure business continuity. ![image](https://github.com/user-attachments/assets/0aa9db1a-aab7-4b80-a909-f654d6c18939)



# Division of Security Responsibilities

- SWBTL LLC's Responsibilities:

 - Configuration and Security: Managed virtual machines, applied security patches, and configured firewall rules within Azure.
 - Data Protection: Ensured encryption, access control, and compliance with data privacy regulations.


- Azure's Responsibilities:
 - Physical Security: Managed the security of data centers, network security, and host infrastructure.

# Compliance and Security Recommendations

- Regular Security Assessments: Conducted frequent security assessments and audits to maintain a resilient security posture.
- Continuous Monitoring: Implemented continuous monitoring and a well-defined incident response plan to address potential security risks.

# Conclusion
This project highlights the strategic approach I led at SWBTL LLC to successfully migrate their operations to a secure and compliant cloud environment using Microsoft Azure. Through the implementation of advanced security measures, I enhanced the protection of sensitive data, ensured compliance with industry regulations, and provided a scalable solution that supports the company’s growing business needs.


