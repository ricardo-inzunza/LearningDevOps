Log aggregation is important because the native logging for each application can be different and difficult to work with. Aggregation of logs will keep logs in one place, one format, for a defined amount of time (retention).

You can control permissions for one location.

Integration with Analysis and alerting

Logs we care about should be in a common store

# Azure Diagnostic Targets
[[Azure Storage]]
[[Event Hub]]
[[Log Analytics]]

[[Azure Storage]]
You can send logs to Azure blob storage
Logs and Metrics can be configured through Diagnostic Settings
There are different access tiers for logging in Azure storage

Hot
Cool
Archive

[[Event Hub]]
Good to send to external solutions like
Splunk

[[Log Analytics]]
Good for storage and analytical analysis

You can combine with query languages and Machine learning

Diagnostic Settings -> Add Diagnostic Settings

Most resources have a common diagnostic setting option
Can be configured through Azure policy
There are built in Policy definitions for things like monitoring and can be found by going to Home -> Policy
You can filter the categories to be by monitoring
Will always have the same three destinations to send any type of log
- Send to Log Analytics Workspace
- Archive to a storage account
- Stream to an Event hub

[[Log Analytics Workspace]]
A subscription can have multiple log analytics workspaces
They exist in specific regions
Have different pricing tiers (Pay as you go)
Pay based on ingestion, retention, and actions performed
Data is stored as tables based on the incoming data
KQL used to query and then visualize

 manage access control to logs (workspace-centric/resource-centric)
Companies may opt for centralized or decentralized log strategy
Two permissions required to send to a workspace instance from resource

Workspace/read
workspace/sharedkeys/action

Two access modes for Log Analytics workspace
Workspace-context and resource context

Access Control Mode
Toggled through Workspace -> Properties
**Requre workspace permissions**
- no granular RBAC
- must be granted permissions to workspace or tables

**Use resource or workspace permissions**
- Granular RBAC
- Default



