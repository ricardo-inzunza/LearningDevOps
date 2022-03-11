# Objective Domain 3
[[## Define and implement continuous integration]]

Testing Strategy Considerations
1) Test environment configuration
2) Process to be used
3) Define success and failure
4) Plan for performance measurement before and after release

Package Management Tools
- Azure Artifacts
- Github Packages
We can organize pieces of code by functionality for better control

[[Semantic Versioning]] example 1.2.3
1 Major .2 Minor. 3 Patch

[[Desired State Configuration (DSC)]] Configuration management platform that allows us to manage the state of our environment.

[[Build Agents]] are computing infrastructure with software dedicated to running jobs begun by your pipeline.
There are two types of build agents, [[Microsoft Hosted]] or [[Self hosted]]

[[Build triggers]] Use triggers to run a pipeline automatically.
There are different types of triggers such as Pull Request validation, scheduled. etc

[[YAML]] A file where a build pipeline is defined, it is made up of triggers, agent pools, steps and tasks.

[[Pipeline Analytics]] allows you to monitor pipeline health. This accrues data about the health of your pipeline over time an reports on metrics and trends.

[[Parallel Jobs]] Allows you to run multiple jobs at the same time i.e release pipelines, feature pipelines and master pipelines though by default it is sequential

Managing self-hosted build agents
Interactive vs Service Mode
[[Interactive]] process with auto-logon enabled can be run once or run interactively
[[As a Service]] The service manager of the OS manages lifecycle and the agent starts automatically

[[Templates]] Let you define reusable content, logic and parameters often stored in [[YAML]] files and can be refrenced in your code under 
`- template:`

[[Task Groups]] allow you to encapsulate a sequence of already defined tasks into a single reusable task that can be added to a pipeline, like any other task

[[Variable Groups]] store values that you want to control and make available across multiple pipelines

[[Pipeline Caching]] can help reduce build time by allowing the outputs or downloaded dependencies from one run to be reused in later runs, thereby reducing or avoiding the cost to recreate or redownload the same files again. Caching is especially useful in scenarios where the same dependencies are downloaded over and over at the start of each run. This is often a time consuming process involving hundreds or thousands of network calls.