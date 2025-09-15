# Azure Copilot in Action: Automating and Optimizing Azure Workflows

### Introduction  📖 

* Microsoft Azure Copilot brings AI-powered assistance directly into the Azure Portal, helping cloud engineers, developers, and enterprise users manage services more effectively. With Copilot, you can:

* Get contextual guidance for managing Azure resources.

* Automate common workflows with natural language.

* Explore new services without leaving the portal.

* Simplify monitoring, troubleshooting, and optimization.

* This tutorial repository demonstrates how to use Azure Copilot to automate and optimize Azure workflows with real, practical examples.

---

### Workflow Overview  🔄 

#### Why Azure Copilot?  🚀 

#### Azure’s ecosystem is vast — from virtual machines, databases, storage, Kubernetes, and AI services. Copilot helps you:

* Save time → No need to click through endless menus.

* Automate tasks → Use plain English commands instead of scripts.

* Customize experience → Switch settings (like Dark Mode) instantly.

*  Enhance productivity → Get quick insights on costs, compliance, and architecture.

--- 

### Using Azure Copilot  🖥️ 

### Azure Workflow Diagram

<img width="1589" height="1010" alt="Image" src="https://github.com/user-attachments/assets/a50f7d5b-b246-4bf3-8668-a787b769e4ef" />

---

#### 1. Start Copilot

* Click on the Copilot button in the Azure Portal top bar.

* This opens a side panel where you can type or select prompts.

#### 2. Managing Services with Copilot

* Ask Copilot to perform administrative actions, such as switching your theme to Dark Mode.

#### Example prompts:

* “Change my theme to dark mode”

* “Show me my active resource groups”

* “List all storage accounts in my subscription”

#### 3. Automating Real-Time Event Processing

* Copilot can explain how to implement solutions like real-time event processing using Azure Functions, Event Grid, and SignalR.

### Example prompts:

* “How can I process real-time events in my application with Azure?”

* “How do I integrate Azure Event Hubs with Power BI?”

* “What are the costs associated with using Azure Functions for real-time processing?”

---

### Best Practices for Using Copilot  📚 

Be specific → Instead of “show me resources,” ask “Show me all my VM instances in Resource Group X.”

Iterate with prompts → Refine queries based on Copilot’s response.

Combine with automation → Use Copilot as a guide, then automate via ARM templates, Bicep, or Terraform.

Check responses → Remember, Copilot may generate incorrect information — always validate before applying changes.

---

### Scaling Beyond Basics  🔮

* Azure Copilot can help accelerate more complex enterprise workflows, such as:

* DevOps automation → Deploy CI/CD pipelines with natural language assistance.

* Security & Compliance → Quickly query non-compliant services.

* Cost Optimization → Identify underutilized resources and suggest savings.

* AI & Data → Build, deploy, and monitor AI models using Azure AI Foundry.

---

### Conclusion  📌

* Azure Copilot is not just a chatbot — it’s a cloud co-pilot that helps streamline operations, boost productivity, and reduce friction when managing Azure services.

* This repo demonstrates practical examples of how to start, manage, and optimize workflows with Azure Copilot.
  
* By following these steps, you’ll unlock faster and smarter ways of working in the Azure ecosystem.


### Tutorial & Examples Snapshots  📷 

### Starting Copilot

* To start using Copilot click on Copilot button
  
* After clicking you will get the Copilot Prompt

  <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/1fd652ea-de91-48ea-b371-f4e7705cb624" />

  <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/2848f1aa-35b1-4465-b29e-52349a48d126" />
  
---

### Managing Services & Switching Themes
* Use copilot to manage services in Azure, change my theme to dark mode

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/b392dd9d-aeb0-4cde-a4b6-ea180695c721" />

---

### Processing Real-Time Events

* How can I process real-time events in Azure?

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a5bb15ac-52c7-4d19-be4c-7e4ee97ce4e6" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/ecc36407-3c15-4c83-a524-69c843dbc354" />

### Monitoring Alerts
* Monitor critical alerts

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/81649565-bb5e-44ed-a0ff-a06bd8479e55" />

---

### Monitoring Resources

* Which VMs are runing in my Azure services right now?

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8673c102-1d83-4269-b0ec-afd098903388" />

* Which VMs are currently not running but are in my Azure services?

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/5ff6ca3d-f4d7-4fc9-8131-3fc0199d63dc" />

* Which resources in my Azure services are non-compliant right now?
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/4f86b811-26a5-406c-8e0d-784a39b9d247" />

* List resources that have been created or modified in the last 24 hours

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/77b16ffb-4748-4e69-9bee-fbde02339ed8" />

* How does our cost this month compares to our subscription cost last 1 month?
* 
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8daeaa50-5afd-449c-8ab2-025e37393782" />

---

### Creating Azure Services 
* Create a cheat sheet for managing VMs with CLI

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/2b42085a-c5f0-48fa-9712-da3816d09286" />




* Create a virtual network with 2 subnets using the address space of 10.0.0.0 slash 16 using az cli
  
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/04c27710-a544-4530-a0e3-2ae1632f4692" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/fce3665a-e1c2-4dbb-a7ff-8af3d3ccbddd" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/d39b0a56-269e-468d-ba9b-c45d109fdc9b" />

* How can I create a new resource group using Powershell?

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/365f8780-21ac-4ecc-b73e-cbffb2fe676f" />

* Provide me with a detailed guide on deploying an AKS clusetr on Azure

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/19828aed-f54f-4cb9-b4db-dd5346379ef2" />

* Provide me with a detailed guide on deploying an AKS cluster on Azure

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/597c378d-46a9-4329-90fc-85abdd865540" />


---




✅ You can now experiment with Copilot in your own Azure Portal and extend these workflows into enterprise automation pipelines.
