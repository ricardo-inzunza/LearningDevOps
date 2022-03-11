[[Telemetry]]  is the automatic recording and transmission of data from remote or inaccessible sources to an IT system in a different location for monitoring and analysis.

Azure resource metrics are stored in the native metrics store for 90 days and can optionally be sent to a target

Azure resource logs MUST be sent to a target

[[Azure storage]] - Good for long term, cheap retention
[[Event Hub]] - Good to send to external solutions
[[Log Analytics]] - Good for storage and analytical analysis

[[Key performance Indicators (KPI)]]

[[Azure Monitor insights]] provides the best KPIs and many include customizable workbooks
Basically Insights shows you metrics that it thinks is the most important to monitor

[[Azure Monitor]] is the central hub, like the homepage for telemetry

[[Workbooks]] are customizable telemetry. You can hit Edit and it will give you the query in KQL, and you can customize it however you want.

## Alerting with Azure monitor
[[Alert Rules]]
Conditions to alert with optional action group

[[Action groups]]
Actions to perform i.e send an SMS text, output to Slack

[[Action Rules]]
Alert conditions to trigger or suppress action group

# Gather application Telemetry
[[Distributed Tracing]] - Provides a map of the connections an application has. For example an application that leverages microservices through API calls. Those microsoervices are dependencies and will be shown on the Distributed Tracing's map.

It can show you the metrics of the connections between the applications so you can troubleshoot

[[OpenCensus Python SDK]] This is the recommended library to integrate Python applications with Application Insights and to use distributed tracing

# Container Monitoring Tools
[[Prometheus]] 
[[Azure Monitor]]

# Monitoring Tools
[[Azure Monitor]]
[[Application Insights]]
[[Dynatrace]]
[[New Relic]]
[[Naggios]]
[[Zabbix]]