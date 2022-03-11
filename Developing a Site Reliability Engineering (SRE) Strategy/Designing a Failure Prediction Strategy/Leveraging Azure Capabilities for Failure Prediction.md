# Learning Objectives
##### Analyze behavior of systems with regards to load and failure conditions
##### Calculate when a system will fail under various conditions
##### Measure baseline metrics for system
##### Recommend the appropriate tools for a failure prediction strategy
[[Failure Mode Analysis]]
[Failure mode analysis - Azure Architecture Center | Microsoft Docs](https://docs.microsoft.com/en-us/azure/architecture/resiliency/failure-mode-analysis)

A key to predicting failure is to understand normal conditions. [[Azure Monitor]] and [[Application Insights]] are key tools to capture baseline information

[[Microsoft App Center]] can be used to capture information about usage and crashed, great for client applications.
https://appcenter.ms
https://docs.microsoft.com/en-us/appcenter/diagnostics/
[[App Center Diagnostics]] is a cloud service that helps developers monitor the health of an application, delivering the data needed to understand what happens when an app fails during testing or in the wild.

[[Project Tardigrade]] focuses on improving the Azure platform resilience

[[in-place healing]] predicts hardware faults in advanced and can restore even the kernel in place without having to reboot


