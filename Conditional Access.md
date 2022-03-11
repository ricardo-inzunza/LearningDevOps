Part of [[Azure Active Directory (AAD)]]

As part of a conditional access policy you might require security group membership, a location or network identity, a specific operating system, a managed device or other criteria.

Conditional access focused on [[authorization]] but can force strong authentication i.e require [[Multi-factor Authentication (MFA)]]

a P1 feature with P2 required for user risk integration

When the conditions are met the controls specified, are enforced.

Attributes such as location,device health, which application is being accessed, user risk and more can be used as part of policies.

These apply for all types of identity which means consider this for service principals
if you require MFA with a phone, a service principal will not be able to complete this request and WILL FAIL




