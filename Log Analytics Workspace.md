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