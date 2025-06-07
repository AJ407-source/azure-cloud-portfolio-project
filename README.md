# Azure Cloud Portfolio Project
# Azure Web App Monitoring & Diagnostic Project

This repository documents my end-to-end implementation of a hands-on Azure project completed as part of my cloud engineering portfolio. It includes tasks across IaaS, PaaS, networking, security, IoT, automation, and monitoring.

## 🚀 Tech Stack
- **Cloud Platform:** Microsoft Azure
- **Monitoring Tools:** Azure Monitor, Application Insights, Log Analytics Workspace
- **Automation:** Azure Workbooks, Alerts, Diagnostic Settings
- **Query Language:** KQL (Kusto Query Language)
- **Storage & Hosting:** Azure Storage (Blob), Azure Web Apps
- **Visualization:** Azure Dashboards, Charts, Metrics Explorer
- **Tools Used:** Azure Portal, GitHub, Markdown
- **Azure Services**: VMs, IoT Hub, App Services, Blob Storage, SQL DB, Stream Analytics, Power BI, Key Vault
- **Automation**: ARM Templates, Azure CLI, PowerShell
- **Machine Learning**: Azure ML Studio, AutoML
- **Monitoring**: Azure Monitor, Power BI
- **Security**: RBAC, NSG, Key Vault

---

## 📎 License

This project is for demonstration and educational purposes only.



## 📘 Project Overview

## 🔷 Chapter 3: Azure Core Infrastructure

- **3.1 Resource Groups**: Created resource groups to logically contain and manage related Azure resources.
- **3.2 Virtual Machine & Web Server**: Deployed a Linux VM, connected via SSH, installed Apache web server, and verified webpage accessibility.
- **3.3 Azure Container Instance**: Pulled and ran a container image in ACI to demonstrate lightweight deployment.
- **3.4 Virtual Network Setup**: Created a virtual network, deployed two VMs, and tested connectivity with private IPs.
- **3.5 Blob Storage**: Configured Azure Storage Account and tested blob upload and access.
- **3.6 Azure SQL Database**: Created a managed SQL database and tested connection and query execution.

## 🌐 Chapter 4: Platform Services and Automation

- **4.1 IoT Hub & Device Simulation**: Created IoT Hub and simulated a device using the Raspberry Pi emulator.
- **4.2 Azure Functions**: Deployed an HTTP-triggered Azure Function that logs and responds to web requests.
- **4.3 Azure App Services**: Deployed a simple web app and tested its availability via public endpoint.
- **4.4 ARM Template VM Deployment**: Used gallery templates to automate VM deployment via ARM.
- **4.5 PowerShell-based VM Deployment**: Used Azure PowerShell from Cloud Shell to deploy a VM.
- **4.6 Azure CLI-based VM Deployment**: Repeated VM deployment using Azure CLI commands.

## 🔐 Chapter 5: Security, Policies & Access Management

- **5.1 Network Security Groups**: Created inbound and outbound rules to restrict access to the VMs.
- **5.2 Azure Key Vault**: Set up secure secret storage in Key Vault.
- **5.3 Azure Policy**: Created a policy to restrict deployment to specific regions.
- **5.4 RBAC**: Assigned roles to users and verified permission effects.
- **5.5 Resource Locks**: Tested resource lock functionality by attempting to delete locked resources.
- **5.6 Tagging**: Assigned metadata tags to resources for cost management.
- **5.7 Trust Center**: Explored Azure’s compliance and trust portals.

## ⚙️ Chapter 7: Azure IoT Edge

- **7.1 IoT Edge Runtime on VM**: Created IoT Hub and deployed IoT Edge runtime to a Windows VM.
- **Module Deployment**: Deployed a simulated module to process telemetry from the edge device.

## 🤖 Chapter 8: Azure Machine Learning with AutoML

- **8.1 Azure ML Studio**: Created a workspace, imported datasets, and used AutoML to create a classification model.
- **Model Deployment**: Deployed the best performing model as a REST endpoint.

## 📊 Chapter 9: Real-time Monitoring with Power BI

- **9.1 IoT + Stream Analytics + Power BI**:
  - Added consumer group to IoT Hub
  - Created a Stream Analytics job with defined input/output
  - Wrote KQL-style query to process streaming data
  - Connected output to Power BI
  - Published a real-time dashboard
  - 📈 **Power BI Report**: [Click to View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiN2U5NWUzNjQtZGI0NC00NzI0LWFlMGEtMTdlOTUxMWFhZDY0IiwidCI6ImFjNzllNWE4LWUwZTQtNDM0Yi1hMjkyLTJjODliNWMyODM2NiIsImMiOjF9)

Updated README with full Azure project documentation

