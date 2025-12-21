# Azure Compute Decision Helper

An interactive web application designed to simplify the process of choosing the right Azure compute service for your application workload. 

## 🚀 Overview
This tool is a functional companion to the official **Microsoft Azure Compute Decision Tree**. It converts a static flowchart into a step-by-step interactive wizard, guiding users through critical architectural questions to find the most suitable hosting model.

### Key Features
* **Interactive Logic:** Navigates both the **Migrate** and **Build New** paths defined by Azure architectural guidance.
* **Service Definitions:** Provides crisp, "AI-overview" style definitions for every recommended service, from **Azure Functions** to **Azure Kubernetes Service (AKS)**.
* **Fluent Design UI:** Styled using Microsoft's Fluent Design system for a native portal experience.
* **Exportable Decision Path:** Users can instantly copy their architectural trail to their clipboard for use in Jira, emails, or Architecture Design Records (ADRs).
* **Official Documentation:** Includes direct links to Microsoft Learn for deeper technical analysis.

## 🛠️ Technical Stack
* **HTML5/CSS3:** Utilizes modern CSS variables and Fluent UI aesthetics.
* **Vanilla JavaScript:** A lightweight, single-file implementation with no external dependencies or backend required.
* **SVG Integration:** Uses official Azure service icons for immediate visual recognition.

## 🧠 Logic Flow
The tool accurately maps the decision points found in the Azure Architecture Center:
* **Migration Strategies:** Handles **Lift and Shift** (rehosting) and **Cloud Optimized** (refactoring) workloads.
* **Containerization:** Specialized paths for container-exclusive and container-compatible services.
* **Control vs. Management:** Evaluates the trade-off between **IaaS** (Virtual Machines), **PaaS** (App Service), and **Serverless** (Functions).

## 🙏 Attribution
This tool was inspired by the excellent architectural research and flowcharts published on **Microsoft Learn** and the **ITOpsTalk** community.

**Original Article:** [Choose an Azure compute service](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree)

## 📄 License
This project is open-source and available under the MIT License.
