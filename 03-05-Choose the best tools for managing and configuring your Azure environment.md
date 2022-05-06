# Choose the best tools for managing and configuring your Azure environment

Administration tools allow developers and administrator interact with the cloud environment.

- Can deploy dozens or hundreds of resources at a time
- Configure individual services programmatically
- Viewing rich reports across usage, health, costs, and more.

## **Identify the product options**

### The Azure portal

- Web based interface
- You can access to all resources: create new services, configure your services, and view reports
- As your Azure usage grows you'll likely choose a more repeatable code-centric approach to managing your Azure resources.

### The Azure mobile app

- Mobile app Android & iOS
- Can monitor health and status of Azure resources
- Check alerts, diagnose and fix issues and restart services such as Web App and VMs
- Run Azure CLI or Azure PowerShell commands to manage programmatically Azure Resources

### Azure PowerShell

- Shell to execute commands, commands call Azure API to perform every possible management task in Azure
- Cmdlets can be executed independently or combined into a script file and executed together
- Capturing the commands in a script makes the process repeatable and automatable
- Available for Windows, Linux, and Mac, and you can access it in a web browser via Azure Cloud Shell.

### The Azure CLI

- Has the same capabilities that Azure PowerShell
- Bash syntax
- Depending on your expertise you use Azure CLI or Azure PowerShell
- Both run on Windows, Linux, and Mac, and can be accessed in a web browser via Cloud Shell

### Azure Resource Manager templates (ARM templates)

- You can describe the resources you want to use in a declarative format (JSON)
- ARM Template is verified before any code run, this ensure that resources will be created and connected correctly
- Resources creation is done in parallel
- Templates can execute PowerShell or Bash scripts before or after the resource has been set up

## **Analyze the decision criteria**

- Do you need to perform one-off management, administrative, or reporting actions?
  - All have capabilities to one-off management, but sometimes is a better choice agile tools like PowerShell, Azure CLI or Azure Portal.
  - The Azure Portal is ok when you're learning but PowerShell and CLI are desired tools for administrators
  - ARM Templates can use PowerShell and CLI Scripts, Although ARM templates aren't intended for one-off scenarios, it's possible to use them for this purpose
- Do you need a way to repeatedly set up one or more resources and ensure that all the dependencies are created in the proper order?
  - Use ARM Templates
  - PowerShell and CLI are capable but they are not the best choices
- When you're scripting, do you come from a Windows administration or Linux administration background?
  - Use Azure PowerShell if you have background with this
  - Use Azure CLI if you come from a Linux Administration
