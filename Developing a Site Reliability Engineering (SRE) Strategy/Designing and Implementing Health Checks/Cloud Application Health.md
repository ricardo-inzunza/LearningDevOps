Types of monitoring
- Health Monitoring
- Availability Monitoring
- Performance Monitoring
- Security Monitoring
- SLA Monitoring
- Usage Monitoring

Different Inputs to monitoring
- Tracing
- Simulation
- Logging
- System Metrics
- Third-Party
- Health Checks

Application Health States
- Green
- Yellow
- Red

Health Check Elements
[[Health Check Endpoint]] The checks performed by your application through a health check endpoint
[[Result Interpreter]] The system calling and interpreting the health check response

[[Service Level Objectives]]
Overall System Availability
Operational Throughput
Operational Response Time

###### Types of Analysis
[[Hot Analysis]] Time critical analysis of current state and cause
[[Warm Analysis]] Analysis of data leading up to health event
[[Cold Analysis]] Analysis long term data to determine overall trends

[[Application Insights]] SDK's for .NET and .NET Core provides automatic tracking
Supports [[Dependency Tracking]] of the following dependencies
- HTTP/HTTPS
- [[WCF]] Windows Communication Foundation is a framework for building service-oriented applications
- SQL
- Azure Storage
- EventHub Client SDK
- ServiceBus Client SDK

[[Application Map]]

[[Recovery Time Objective (RTO)]]

##### Types of Application Recovery
Redeploy -Cheaper cost since you are not actively keeping an active environment
Warm Spare- Active/passive
Hot Spare- Active/Active

Health monitoring Approaches
[[Azure Monitor]]
[[System Center Operations Manager]]
System Center Operations Manager with Azure Monitor

### Health Checks
[[Azure Batch]]
[[Service Fabric]]
[[Function App Health Checks]]

#### Health Check for Containers
[[Azure container instances (ACI)]]
[[Web App for Containers]]
Health checks for containers are created as [[probes]] with a configurable check period

[[Azure Kubernetes Service (AKS)]] supports three types of [[probes]]
	- [[Liveness probe]]
	- [[readiness probe]]
	- [[Startup Probe]]

### Configuring [[probes]]

