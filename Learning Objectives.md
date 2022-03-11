# **Develop an instrumentation strategy (5-10%)** 

## **Design and implement logging**
-  assess and configure a logging framework 
-  design a log aggregation and storage strategy (e.g., Azure storage) 
-  design a log aggregation and query strategy (e.g., Azure Monitor, Splunk, Exabeam, LogRhythm) 
-  interrogate Log Analytics logs using basic Kusto (KQL) queries 
- manage access control to logs (workspace-centric/resource-centric) 
-  integrate crash analytics (App Center Crashes, Crashlytics) 

## **Design and implement telemetry** 
- design and implement distributed tracing 
-  inspect application performance indicators 
- inspect infrastructure performance indicators 
-  define and measure key metrics (CPU, memory, disk, network)  implement alerts on key metrics (email, SMS, webhooks, Teams/Slack) 
-  integrate user analytics (e.g., Application Insights funnels, Visual Studio App Center, TestFlight, Google Analytics)

## **Integrate logging and monitoring solutions** 
-  configure and integrate container monitoring (Azure Monitor, [[Prometheus]], etc.) 
-  configure and integrate with monitoring tools (Azure Monitor Application Insights, Dynatrace, New Relic, Naggios, Zabbix) 
-  create feedback loop from platform monitoring tools (e.g., Azure Diagnostics extension, Log Analytics agent, Azure Platform Logs, Event Grid)  manage Access control to the monitoring platform