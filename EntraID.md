# Identity Management in Azure (From AAD to Microsoft Entra ID)

# Introduction to Identity and Access Management (IAM)

> Identity and Access Management (IAM) is a comprehensive framework that ensures only authorized individuals can access specific resources within an organization. IAM covers user management, authentication, authorization, and compliance, establishing a secure foundation for business operations.

> IAM becomes especially crucial in cloud environments where resources are accessed remotely. In this context, Microsoft Entra, formerly known as Azure Active Directory (Azure AD), plays a key role. Entra is a comprehensive solution for IAM, emphasizing security and efficient identity governance.

> Azure AD, now part of Microsoft Entra ID, is a cloud-based IAM service. It enables organizations to grant employees access to various resources, both external (e.g., Microsoft 365, Azure portal) and internal (e.g., custom-developed cloud applications).

# Differences between Active Directory (AD), Azure AD, and Microsoft Entra
> AD is primarily on-premises and manages users within a corporate network.
> Azure AD is cloud-centric, supporting modern authentication protocols and integrating seamlessly with cloud services.
> Microsoft Entra, an evolved form of Azure AD, offers enhanced security features, workload identities, and identity governance.

# Azure AD integrates within the Microsoft ecosystem
> Microsoft 365 Integration: Every Microsoft 365 subscription is linked to an Azure AD tenant.
> Azure Portal Integration: Azure AD manages user identities, ensuring the right permissions for Azure resources.
> SaaS Applications Integration: Azure AD supports Single Sign-On (SSO) for various SaaS applications.

# Azure AD offers different licenses (Free, Premium P1, Premium P2) with varying features
> Free: Basic user and group management, on-premises directory synchronization, basic reports, self-service password change, and SSO
> Premium P1: Includes features like hybrid users access, dynamic groups, self-service group management, and Microsoft Identity Manager.
> Premium P2: Adds advanced features like Azure AD Identity Protection and Privileged Identity Management.

# Key Benefits of Azure AD:
> Access Control: Granular access control with features like Conditional Access.
> Multi-Factor Authentication (MFA): Enhances security with additional verification methods
> User Provisioning: Streamlines user identity management with automated provisioning.
> Powerful Security Tools: Features like Identity Protection detect suspicious activities.

# Core Features of Azure AD
> Application Management: Manages cloud and on-premises apps, SSO, and My Apps portal.
> Authentication: Self-service password reset, MFA, and banned password lists.
> B2B and B2C: Manages guest users, external collaborations, and customizable user experiences.
> Conditional Access: Policy-based secure access.
> Device Management: Defines trusted devices and integrates devices with Azure AD.
> Hybrid Identity: Integrates on-premises directories with Azure AD
> Identity Governance and Protection: Manages access controls, detects vulnerabilities, and offers PIM.

# IAM – Deep Dive into Key Features
> Active Directory & M365 Management: Unified identity, seamless integration, and enhanced security.
> Multi-Factor Authentication (MFA): Setup, configuration, and benefits of MFA.
> Single Sign-On (SSO): Configuring SSO and its benefits.
> Zero Trust Security Model: Principles and implementation with Azure AD
> Privileged Access Management (PAM): Setting up PAM and its benefits.

# Microsoft Entra ID Updates
> Unified Identity and Security Features: New features aligning with the Zero Trust model.
> Key Highlights: Updates to Azure AD, permissions management, workload identities, external ID, and B2B sign-in.
> Additional Features: Security baseline, user and group management, application and data access, hybrid identity, monitoring, and governance.

# Conclusion
> The shift from Azure AD to Microsoft Entra ID is a milestone in Azure's identity management. Microsoft Entra ID offers advanced features, redefining IAM in the cloud. Staying updated and leveraging Entra's potential ensures a secure, efficient, and productive environment in this new era.