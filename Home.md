**The xRM Continuous Integration (CI) Framework is a set of tools that makes it easy and quick to automate builds and deployment of your CRM components.**

This will allow you to setup a fully automated DevOps pipeline so you can deliver CRM more frequently in a consistent and reliable way.

![Build->Deploy->Test->Release](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Docs/Images/BuildDeployTestRelease.png)

## VSTS Build & Release Tasks

The **xRM CI Framework** provides you with VSTS Build and Release tasks. You can combine these tasks with other tasks to create build and release definitions to meet your project needs.

Below is a list of tasks that is included with the **xRM CI Framework**

![Task Catalog](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Xrm.Framework.CI/Xrm.Framework.CI.VSTS.BuildTasks/Extension/Images/TaskCatalog.png)

## Sample PowerShell Scripts for Dynamics CRM

These are sample scripts demonstrate how to use some of the PowerShell Cmdlets provided with this framework and the Dynamics CRM SDK. You can execute these scripts from your workstation, from your Build/CI System (VSTS, Jenkins, etc...) and from your Release Automation Tools (VSTS, CA Lisa, etc...)

Below is a list of some of the main sample scripts:
* [Import Solution](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Xrm.Framework.CI/Xrm.Framework.CI.PowerShell.Scripts/ImportSolution.ps1) - Imports a CRM solution, including error handling, downloading import logs and checking existing versions
* [Deploy Package](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Xrm.Framework.CI/Xrm.Framework.CI.PowerShell.Scripts/DeployPackage.ps1) - Deploy a Dynamics CRM Deployment Package
* [Export Solution](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Xrm.Framework.CI/Xrm.Framework.CI.PowerShell.Scripts/ExportSolution.ps1) - Export a CRM solution from your environment and extracts the contents into your local folder bound to your source control system
* [Pack Solution](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Xrm.Framework.CI/Xrm.Framework.CI.PowerShell.Scripts/PackSolution.ps1) Packs a solution using the SolutionPackager.exe

## Custom PowerShell Cmdlets for Dynamics CRM

**PowerShell** allows you to **automate** various processes by scripting the tasks that are normally performed manually on servers and applications.

The **xRM CI Framework** provides you with PowerShell “Cmdlets” to allow you to script some of the task that are normally executed manually during the build and/or deployment of your Dynamics CRM Solutions. The most commonly used actions would be things like exporting your CRM solutions. Below is a list of Cmdlets available now.

![PowerShell Cmdlets](https://github.com/WaelHamze/xrm-ci-framework/blob/master/CRM365/Docs/Images/PowerShellCommands.png)

These are the generic commands/actions that you can then combine together in PowerShell scripts to implement the right process for your project needs.