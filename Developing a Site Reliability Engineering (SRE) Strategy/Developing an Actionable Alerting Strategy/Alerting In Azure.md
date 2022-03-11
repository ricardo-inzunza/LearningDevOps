# Alerting in Azure

Alerting is important because we want to be notified of critical failures as well as prevent this in the future.
We want to avoid excessive noise

Sources of signals for alerting

Types of [[Signals]]
Microsoft Azure Active Directory (Audit sign in)
Subscription (activity log)
Resources (Metric Logs)

[[Azure Service Health]] notifies you about Azure service incidents and planned maintenance so you can take action to mitigate downtime. Configure customizable cloud alerts and use your personalized dashboard to analyze health issues, monitor the impact to your cloud resources, get guidance and support, and share details and updates.

In order to configure alerts you might need to configure other things first. For example Azure Active directory, if you would like to Alert for Audits/Sign-ins you would need to go to "Diagnostic Settings" and send those Logs to a [[Log Analytics Workspace]]. Then you would be able to set up alerts.

If you are using [[Azure Kubernetes Service (AKS)]] you can use [[Recommended Alerts]] which is a preview feature that you can use to easily toggle on alerts that Azure thinks is important.

[[## Alerting with [[Azure Monitor]]
[[Alert rules]]
	- Conditions to alert with optional action group
[[Action Groups ]]
	- Actions to perform
[[Action Rules]]
	- Alert conditions to trigger or suppress action group

[[ITSM]] IT Service Management, ticketing system like JIRA



