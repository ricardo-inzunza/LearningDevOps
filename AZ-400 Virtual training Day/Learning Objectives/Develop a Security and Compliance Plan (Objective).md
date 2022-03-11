# Objective Domain 5
[[## Develop a Security and Compliance Plan]]
[[Azure Active Directory (AAD)]] will be used as the main security mechanism for securing Azure DevOps.

Azure AD [[Privileged Identity Management (PIM)]] - Just-in-time, time-bound privileged access. Requires approval and justification, enforces MFA to activate any role
Azure AD [[Conditional Access]] - As part of a conditional access policy you might require security group membership, a location or network identity, a specific operating system, a managed device or other criteria.
[[Multi-factor Authentication (MFA)]] MFA increases security of your identity by limiting the impact of credential exposure.

Two different Azure AD Group types
[[Security group]] Used to manage member and computer access to shared resources for a group of users
[[Microsoft 365 Groups]] provides collaboration opportunities by giving members access to a shared mailbox, calendar, files, sharepoint site, and more.

Membership types
[[Assigned Membership]] lets you add specific users to be members of this group and to have unique permissions
[[Dynamic Membership]]- Lets you use dynamic membership rules to automatically add or remove users as part of the groups

[[Service Principals]] are used to authenticate systems. They are user accounts that are assigned to our applications.
[[Managed Identity]] we do not need to keep track of an ID for the application. We will ask Azure to assign an Identity to our application.
	[[System Assigned Identity]]
	[[User Assigned Identity]]


[[Azure Key Vault]] lets you provision, manage, and deploy certificates for use with Azure and your internal connected resources. Items you can have within an Azure Key vault include
[[Certificate Metadata]]
[[Key]]
[[Secret]]
www.azuredevopslabs.com is great for labs to implement keys and secrets

[[Secure DevOps Kit for Azure (AzSK)]] Assess and report risks
[[Azure Security Center]] Gives us a score and tells us how we can improve the security score of our resources
[[SonarQube]] is an open-source platform that inspects source code for quality
[[GitHub Security]] features like dependabot and vulnerability scanning

[[Azure policies]] and [[Blueprints]] can be used to enforce requirements on resource creation and management through policies


[[Azure Security Center]] can scan your [[Docker]] configuration, [[Azure Kubernetes Cluster(AKS)]], and [[Azure Container registry]] images for vulnerability.

A good incident response is supported by three pillars
Roster, Roles and Rotation

[[Rosters]]- Determine who responds to problems and how they will know when a response is required
[[Roles]]- Primary responder, secondary responder, Subject matter experts, scribe
[[Rotation]]- Divide up shifts in a way that works best for the individuals on your response team