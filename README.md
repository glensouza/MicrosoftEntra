# Microsoft Entra

![Microsoft Entra](./me.png)

Microsoft has announced that it will be renaming Azure Active Directory (Azure AD) to **Microsoft Entra ID** as part of its commitment to simplify secure access experiences for everyone.

The renaming will take effect on October 1, 2023, and all existing deployments, configurations, and integrations will continue to function as they do today without any action from users.

The new names of standalone offers will be **Microsoft Entra ID Free**, **Microsoft Entra ID P1**, and **Microsoft Entra ID P2**.

## Agenda

- [What is Microsoft Entra](#what-is-microsoft-entra)
- [Azure AD to Microsoft Entra ID](#azure-ad-to-microsoft-entra-id)
- [License renames](#license-renames)
- [Azure AD feature renames](#azure-ad-feature-renames)
- [What names aren't changing](#what-names-arent-changing)

## What is Microsoft Entra

Microsoft Entra is a cloud-based identity and access management service that helps employees sign in and access resources in:

- External resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications.
- Internal resources, such as apps on your corporate network and intranet, along with any cloud apps developed by your own organization.

Microsoft Entra provides a robust set of capabilities to empower enterprises with more demanding needs on identity and access management. It provides an advanced set of features that help empower organizations with more demanding identity and access management needs.

The expanded product family includes:

| Identity and access management | New identity categories | Network access |
| --- | --- | --- |
| Microsoft Entra ID (currently known as Azure AD) | Microsoft Entra Verified ID | Microsoft Entra Internet Access |
| Microsoft Entra ID Governance | Microsoft Entra Permissions Management | Microsoft Entra Private Access |
| Microsoft Entra External ID | Microsoft Entra Workload ID | |

Some features of Microsoft Entra ID (formally known as Azure AD) commonly used by developers and IT professionals include:

- **Single Sign-On (SSO)**: Azure AD enables users to access multiple applications using a single set of login credentials, streamlining the authentication process and improving productivity.
- **Multi-Factor Authentication (MFA)**: By requiring an additional authentication factor alongside traditional username and password credentials, MFA adds an extra layer of security to protect sensitive patient data from unauthorized access. Examples of how MFA can be used include:
  - requiring users to enter a one-time passcode sent to their mobile device
    - SMS text message
    - phone call
    - mobile app notification
  - use a biometric identifier such as a fingerprint or facial scan
- **Role-Based Access Control (RBAC)**: Administrators can define and enforce role-based access policies, ensuring that users have access only to the resources they need to perform their duties. For example, a nurse would have access to patient records but not financial data, whereas a billing specialist would have access to billing information but not medical records.
- **Conditional Access**: Microsoft Entra enables administrators to create policies that grant or block access based on various conditions, such as the user's location, device, or risk level. This can help prevent unauthorized access to sensitive information from untrusted devices or locations.
- **Identity Protection**: Azure AD continuously monitors user behavior and login patterns to detect suspicious activities, such as repeated failed login attempts or logins from unfamiliar locations, which may indicate a potential security threat. In such cases, Azure AD can automatically enforce additional security measures or alert the security team for further investigation.
- **Azure Privileged Identity Management (Azure PIM)**: a service that provides granular access control and management of privileged accounts in Microsoft Entra ID and other Azure services. It helps organizations reduce the risk of unauthorized access and security breaches by enforcing the principle of least privilege and implementing just-in-time (JIT) access for users with elevated permissions. Azure PIM can be employed to enhance security and maintain compliance by ensuring that privileged access is granted only when necessary and for a limited time.
  - **Just-In-Time Access**: Azure PIM enables organizations to grant temporary, time-limited access to privileged roles, such as administrators or data owners, when required. This reduces the risk of unauthorized access or misuse of sensitive data by limiting the exposure of privileged accounts.
  - **Role-Based Access Control (RBAC)**: Azure PIM allows organizations to define and enforce granular access controls based on users' roles and responsibilities. This ensures that users have access only to the resources they need to perform their duties, preventing unauthorized access to sensitive patient data and critical systems.
  - **Access Requests and Approvals**: Azure PIM provides a streamlined process for users to request privileged access, with customizable approval workflows that involve designated approvers, such as IT security staff or department heads. This helps organizations maintain oversight and control over who can access sensitive information and systems.
  - **Monitoring and Auditing**: Azure PIM offers comprehensive monitoring and reporting capabilities, enabling organizations to track privileged access requests, approvals, and actions of privileged users. This audit trail can help organizations detect and investigate suspicious activities, maintain compliance with regulations, and demonstrate accountability.
  - **Security Alerts and Notifications**: Azure PIM can generate security alerts and notifications based on pre-defined policies or unusual activities, such as multiple failed login attempts or privilege escalation. This helps organizations proactively identify and respond to potential security incidents.

## Azure AD to Microsoft Entra ID

Microsoft Entra is the new name for Azure Active Directory. The name change will be reflected across the service, including the Azure portal, PowerShell, CLI, and APIs.

Personally, I always thought the naming didn't reflect its purpose. Azure AD was not just an on-premise Active Directory version in the cloud. It's a cloud-based identity and access management service.

So now we can think of Microsoft Entra as that **entry** way into all of our services like single sign-on and other centralized security services.

### Why is the name being changed

As part of our ongoing commitment to simplify secure access experiences for everyone, the renaming of Azure AD to Microsoft Entra ID is designed to make it easier to use and navigate the unified and expanded Microsoft Entra product family.

The Microsoft Entra ID name more accurately represents the multicloud and multiplatform functionality of the product, alleviates confusion with the on-premises identity solution (Active Directory), and creates a path to deliver a simpler way to protect every identity and secure every access point as we expand the Microsoft Entra identity and network access portfolio.

### Logo/icon change

Azure AD product icons are replaced with the Microsoft Entra ID product icon.

| Azure AD product icons | Microsoft Entra ID product icon |
| --- | --- |
| ![Azure AD product icon Alternative](./azure-ad-icon-1.png) ![Azure AD product icon](./azure-ad-icon-2.png) | ![Microsoft Entra ID product icon](./microsoft-entra-id-icon.png) |

## License renames

The new names of standalone offers will be **Microsoft Entra ID Free**, **Microsoft Entra ID P1**, and **Microsoft Entra ID P2**.

![Azure AD license rename](./azure-ad-new-name.png)

## Azure AD feature renames

![Microsoft Entra Products](./me-products.drawio.png)

Licensing, pricing, and functionality aren't changing. Display names will be updated October 1, 2023. Here are some of the most popular Microsoft Entra naming changes, for full list please refer to [this](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/new-name#glossary-of-updated-terminology) list.

| Category | Old display name for service plan | New display name for service plan | Second use |
| --- | --- | --- | --- |
| Microsoft Entra product family | Microsoft Azure Active Directory, Azure Active Directory, Azure Active Directory (Azure AD), Azure AD, AAD | Microsoft Entra ID | Microsoft Entra ID is preferred, ID is acceptable in product/UI experiences, ME-ID if abbreviation is necessary |
| | Azure Active Directory External Identities, Azure AD External Identities | Microsoft Entra External ID | External ID |
| | Azure Active Directory Identity Governance, Azure AD Identity Governance, Microsoft Entra Identity Governance | Microsoft Entra ID Governance | ID Governance |
| | Azure Active Directory Identity Governance, Azure AD Identity Governance, Microsoft Entra Identity Governance | Microsoft Entra ID Governance | ID Governance |
| |Azure Active Directory Domain Services, Azure AD Domain Services | Microsoft Entra Domain Services | Domain Services |
| Features and functionality | Azure AD account, Azure Active Directory account | Microsoft Entra account - This terminology is only used with IT admins and developers | End users authenticate with a work or school account |
| | Azure AD activity logs | Microsoft Entra activity logs | |
| | Azure AD admin, Azure Active Directory admin |  Microsoft Entra admin | |
| | Azure AD admin center, Azure Active Directory admin center (_Deprecated_) | Replace with Microsoft Entra admin center and update link to entra.microsoft.com | |
| | Azure AD application proxy, Azure Active Directory application proxy | Microsoft Entra application proxy | |
| | Azure AD B2B, Azure Active Directory B2B | Microsoft Entra B2B | |
| | Azure AD built-in roles, Azure Active Directory built-in roles | Microsoft Entra built-in roles | |
| | Azure AD Conditional Access, Azure Active Directory Conditional Access | Microsoft Entra Conditional Access | Conditional Access |
| Acronym usage | AAD | ME-ID _Note:_ that this isn't an official abbreviation for the product but may be used in code or when absolute shortest form is required | |

## What names aren't changing

The following table lists terminology that is not impacted by the Azure AD rename. Names aren't changing for Active Directory, developer tools, Azure AD B2C, nor deprecated or retired functionality, features, or services.

### Active Directory

Windows Server Active Directory, commonly known as Active Directory, and related features and services associated with Active Directory aren't branded with Microsoft Entra.

- Windows Server Active Directory
- Active Directory Federation Services (AD FS)
- Active Directory Domain Services (AD DS)
- Active Directory
- Any Active Directory feature(s)

### Authentication library

- **Azure Active Directory Authentication Library (ADAL)** is deprecated. While existing apps that use ADAL continue to work, Microsoft will no longer release security fixes on ADAL. Migrate applications to the _Microsoft Authentication Library (MSAL)_ to avoid putting your app's security at risk.
- [**Microsoft Authentication Library (MSAL)**](https://learn.microsoft.com/en-us/azure/active-directory/develop/msal-overview) - Provides security tokens from the Microsoft identity platform to authenticate users and access secured web APIs to provide secure access to Microsoft Graph, other Microsoft APIs, third-party web APIs, or your own web API.

### Azure AD B2C

[Azure Active Directory B2C](https://learn.microsoft.com/en-us/azure/active-directory-b2c) isn't being renamed. We're continuing to invest in security, availability, and reliability in Azure AD B2C and our next-generation solution for external identities, [Microsoft Entra External ID](https://learn.microsoft.com/en-us/azure/active-directory/external-identities).

### Graph

- **Azure Active Directory (Azure AD) Graph** is deprecated. Going forward, further investment in Azure AD Graph won't be made, and Azure AD Graph APIs have no SLA or maintenance commitment beyond security-related fixes. Investments in new features and functionalities will only be made in _Microsoft Graph_.
- [Microsoft Graph](https://learn.microsoft.com/en-us/graph) - Grants programmatic access to organization, user, and application data stored in Microsoft Entra ID.

### PowerShell

- **Azure AD PowerShell** for Graph is planned for deprecation on March 30, 2024. For more info on the deprecation plans, see the deprecation update. We encourage you to migrate to _Microsoft Graph PowerShell_, which is the recommended module for interacting with Azure AD.
- [Microsoft Graph PowerShell](https://learn.microsoft.com/en-us/powershell/microsoftgraph/overview) - Acts as an API wrapper for the Microsoft Graph APIs and helps administer every Microsoft Entra ID feature that has an API in Microsoft Graph.

### Accounts

- Microsoft account
- Work or school account

For end user sign-ins and account experiences, follow guidance for work and school accounts in [Sign in with Microsoft branding guidelines](https://learn.microsoft.com/en-us/azure/active-directory/develop/howto-add-branding-in-apps).

### Microsoft identity platform

The Microsoft identity platform encompasses all our identity and access developer assets. It continues to provide the resources to help you build applications that your users and customers can sign in to using their Microsoft identities or social accounts.

### Sync

DirSync and Azure AD Sync aren't supported and no longer work. If you're still using DirSync or Azure AD Sync, you must upgrade to [Microsoft Entra Connect](https://learn.microsoft.com/en-us/azure/active-directory/hybrid/connect/how-to-dirsync-upgrade-get-started) to resume your sync process.

## Resources

### Learn more about Microsoft Entra

- [What is Azure Active Directory?](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/whatis)
- [Pricing and free trials](https://aka.ms/PricingEntra)
- [Microsoft Entra ID icon](https://learn.microsoft.com/en-us/azure/active-directory/architecture/architecture-icons)

### Azure AD renamed to Microsoft Entra

- [Official announcement blog](https://www.microsoft.com/en-us/security/blog/2023/07/11/microsoft-entra-expands-into-security-service-edge-and-azure-ad-becomes-microsoft-entra-id)
- [Azure AD is being renamed to Microsoft Entra ID](https://devblogs.microsoft.com/identity/aad-rebrand/)
- [New name for Azure Active Directory - Microsoft Entra](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/new-name)
- [Microsoft is Renaming Azure AD to Entra ID - Thurrott.com](https://www.thurrott.com/cloud/285529/microsoft-is-renaming-azure-ad-to-entra-id)
- [Microsoft whips up unrest after revealing Azure AD name change](https://www.theregister.com/2023/07/12/azure_ad_name_change)
