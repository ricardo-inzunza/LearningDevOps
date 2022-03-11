# Objective Domain 2
[[## Manage Source Control]]
You can have [[MonoRepo]] or [[Multiple Repos]]
Two types of version control systems
[[Centralized]] or [[Decentralized]]
Centralized means there is a single source of truth
Decentralized each developer has a copy of the source repo on their dev machine

Types of Authentication strategies
[[Personal Access Token]] Can be easily generated from the Azure DevOps website
[[SSH]] Mostly for MAC or Linux users, Windows users will need SSH tools

[[Git LFS]] Git Large File system allows you to maintain and use your large binary files that you would normally have in your .gitignore
[[Workflow Hooks]] Hooks are a mechanism that allows arbitrary code to be run before, or after, certain Git Lifecycle events that occur

Define Branch Strategy
[[Feature Branches]] Use feature branches for all new features and bug fixes. New branch every time a new feature is implemented.
[[Release Branch]] Use release branches and port changes back to the main branch. Could have multiple features possibly within a time period like a sprint that is then merged to master.

Design and implement a [[pull request]] (PR) workflow

Configure Repositories
[[Git Tags]] Tags are useful for marking important points in your history such as releases.

Files can be ignored with the .gitignore file or removed from your repo with git rm, but if needed you can also delete an entire repo within Azure DevOps

Integrate Source Control with tools
[[Pipelines]] enable continuous integration and continuous delivery practices for your applications, and require your source code to be in a version control system like GitHub

[[GitOps]] is the practice for using Git functionality to review, configure and automatically deploy infrastructure.

[[GitHub Codespaces]] are a cloud-hosted, containerized, and customizable VS Code environment available tightly integrated with GitHub repos