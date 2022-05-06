# Choose the best tools to help organizations build better solutions

## **Identify the product options**

### Azure DevOps Services

- Is a suite of services that address every stage in software development lifecycle
- Azure Repos -> Centralized open source repository: code, reviews, and collaboration.
- Azure Boards -> agile management suite, include: Kanban boards, reports, tickets, and high level epics.
- Azure Pipelines -> is a CI/CD pipeline automation tool
- Azure Artifacts -> repository for hosting artifacts (compiled source code)
- Azure Test Plans -> automated test tool that can be used in a CI/CD pipeline to ensure quality code
- Azure DevOps is a mature tool who begins as on-premise server and now evolved into a SaaS offered by Azure.

### GitHub and GitHub Actions

- Most popular code repository for open-source software
- Github is a hosted version of Git
- Shared source-code repository, include tools to perform code reviews, add comments and questions.
- Facilitates project management including Kanban boards.
- Supports issue reporting, discussion and tracking.
- It features CI/CD pipeline automation tooling
- Includes a Wiki for collaborative documentation
- It can be run from cloud or on-premise

GitHub actions provides workflow automation with triggers for many lifecycle events

A toolchain is a combination of software tools that aid in the delivery, development, and management of software applications throughout a system's development lifecycle. The output of one tool in the toolchain is the input of the next tool in the toolchain. Typical tool functions range from performing automated dependency updates to building and configuring the software, delivering the build artifacts to various locations, testing, and so on.

### Azure DevTest Labs

- Provide an Automated Tool for building and testing your code among different environments provisioned by VMs

## **Analyze the decision criteria**

- Do you need to automate and manage test-lab creation?
  - Use Azure DevTest Labs
  - You can automate the provision of new labs by using Azure Pipelines or GitHub Actions
- Are you building open-source software?
  - Use GitHub
  - Your choices aren't limited to Azure DevOps Services or GitHub and GitHub Actions. In practice, you can mix and match these services as needed. For example, you can use GitHub repos with Azure Boards for work-item tracking.
- Regarding source-code management and DevOps tools, what level of granularity do you need for permissions?
  - If you need a high level on granularity permissions is a better choice use Azure DevOps
- Regarding source-code management and DevOps tools, how sophisticated does your project management and reporting need to be?
  - If you're looking for sophisticated tools to manage a project choice Azure DevOps
- Regarding source-code management and DevOps tools, how tightly do you need to integrate with third-party tools?
  - Microsoft doesn't provide specific recommendations
  - It's likely that most vendors that create DevOps tools create hooks or APIs that can be used by both Azure Pipelines and GitHub Action
