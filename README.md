
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:080F25,35:142D59,70:2457A6,100:00A6A6&height=210&section=header&text=UNSPLASH%20IMAGE%20AGENT&fontSize=38&fontColor=FFFFFF&fontAlignY=40&desc=INTELLIGENT%20IMAGE%20SEARCH%20AUTOMATION&descSize=14&descAlignY=65" width="100%" alt="Unsplash Image Agent Project Banner"/>

# 🖼️ Unsplash Image Agent

### Intelligent Image Search Automation with n8n & Unsplash API

<img src="https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/>
<img src="https://img.shields.io/badge/Unsplash-API-111111?style=for-the-badge&logo=unsplash&logoColor=white" alt="Unsplash"/>
<img src="https://img.shields.io/badge/HTTP-Request-2563EB?style=for-the-badge" alt="HTTP Request"/>
<img src="https://img.shields.io/badge/AI-Workflow-0F766E?style=for-the-badge" alt="AI Workflow"/>

[Overview](#-project-overview) •
[Features](#-key-features) •
[Workflow](#-workflow-architecture) •
[Setup](#-installation--setup) •
[Demo](#-project-demo)

</div>

---

## 📌 Project Overview

**Unsplash Image Agent** is an automated image-search project built using **n8n** and the **Unsplash API**.

The goal of this project is to simplify image searching through API integration and workflow automation.

By connecting n8n with the Unsplash API using an HTTP Request, the workflow can retrieve image-related information based on search queries.

This project demonstrates practical implementation of:

- Workflow Automation
- API Integration
- HTTP Requests
- JSON Data Handling
- External API Connectivity

## ✨ Key Features

- 🔎 Search images using keywords.
- 🔗 Unsplash API integration.
- ⚙️ Automated HTTP requests using n8n.
- 📥 Retrieve image information and image URLs.
- 🧩 Visual workflow automation.
- 🧪 API request testing.
- 🔄 Reusable automation workflow.

## 🛠️ Technologies Used

| Technology | Purpose |
|:---|:---|
| **n8n** | Workflow Automation |
| **Unsplash API** | Image Search |
| **HTTP Request** | API Integration |
| **JSON** | Data Exchange and Configuration |

## 🔄 Workflow Architecture

<div align="center">

```text
       SEARCH KEYWORD
             |
             ▼
        n8n WORKFLOW
             |
             ▼
        HTTP REQUEST
             |
             ▼
        UNSPLASH API
             |
             ▼
        JSON RESPONSE
             |
             ▼
      IMAGE DATA / URLs
```

</div>

## ⚙️ How It Works

**01 — Search Input**

A search keyword is provided through the input configured in the workflow.

**02 — Workflow Execution**

The n8n workflow executes the automation process.

**03 — API Request**

The HTTP Request node communicates with the Unsplash API.

**04 — Response Retrieval**

The Unsplash API returns image-related information in JSON format.

**05 — Image Data**

The workflow retrieves image information and URLs from the API response.

## 🖥️ Workflow Preview

<div align="center">

### n8n Automation Workflow

[📂 Open Workflow Screenshot Folder](./Screenshot/)

</div>

The repository's `Screenshot` folder contains the visual reference for the automation workflow.

## 🧪 API Testing

API testing resources are maintained separately in the dedicated `API Test` folder.

<div align="center">

### API Test Resources

<a href="./API%20Test/">
<img src="https://img.shields.io/badge/OPEN-API%20TEST%20FOLDER-0D9488?style=for-the-badge&logo=github&logoColor=white" alt="Open API Test Folder"/>
</a>

<p><em>Click above to explore the API testing resources.</em></p>

</div>

## 📂 Workflow Files

The exported n8n workflow is available in the `Workflow` folder.

<div align="center">

<a href="./Workflow/">
<img src="https://img.shields.io/badge/VIEW-WORKFLOW%20JSON-2563EB?style=for-the-badge&logo=json&logoColor=white" alt="View Workflow JSON"/>
</a>

</div>

### Repository Structure

```text
Unsplash-Image-Agent/
│
├── API Test/
│   └── API testing resources
│
├── Screenshot/
│   └── Workflow screenshots
│
├── Workflow/
│   └── Exported n8n JSON
│
└── README.md
```

## 🚀 Installation & Setup

### Prerequisites

Before using this workflow, you need:

- An n8n account or self-hosted n8n instance.
- An Unsplash Developer Account.
- Unsplash API Access Key.
- The exported workflow JSON file.

### Setup Instructions

**Step 1 — Open n8n**

Open your n8n workspace.

**Step 2 — Import Workflow**

Import the JSON workflow from the `Workflow` folder.

**Step 3 — Configure API Credentials**

Set up the Unsplash API credentials required by the workflow.

**Step 4 — Configure HTTP Request**

Check the API endpoint, request parameters, and authorization settings.

**Step 5 — Execute Workflow**

Provide the search input configured in the workflow and execute it.

**Step 6 — Review Results**

Inspect the API response and retrieved image data.

### 🔐 Security

- Never upload private API keys or access tokens to GitHub.
- Store credentials securely in n8n.
- Follow Unsplash API usage guidelines.

## 🎬 Project Demo

Watch the project demonstration video:

<div align="center">

<a href="https://drive.google.com/file/d/15qy8bcjd1KAtG2nv5sKB9L661pqoucPs/view?usp=drive_link">

<img src="https://img.shields.io/badge/▶%20WATCH%20PROJECT%20DEMO-GOOGLE%20DRIVE-2563EB?style=for-the-badge&logo=googledrive&logoColor=white" alt="Watch Project Demo"/>

</a>

<p><strong>Unsplash Image Agent — Project Demonstration</strong></p>

</div>

## 🎯 Learning Outcomes

Through this project, I developed practical experience in:

- Building automation workflows with n8n.
- Integrating external APIs.
- Configuring HTTP Request nodes.
- Understanding API requests and responses.
- Working with JSON data.
- Testing API integrations.
- Organizing and documenting GitHub projects.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:00A6A6,50:2457A6,100:080F25&height=100&section=footer" width="100%" alt="Project Footer"/>

## 🔗 LET'S CONNECT

I'm open to connecting with AI enthusiasts, automation developers, and professionals interested in intelligent workflow automation.

<br/>

<a href="https://wa.me/8801344551939">
<img src="https://img.shields.io/badge/WHATSAPP-CONNECT%20WITH%20ME-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
</a>

<br/><br/>

<a href="https://github.com/yasirarafathctg">
<img src="https://img.shields.io/badge/GITHUB-FOLLOW%20ME-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/WECHAT-YASIRARAFATHCTG-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat"/>

**WeChat ID:** `YASIRARAFATHCTG`

<br/>

### LEARN • BUILD • AUTOMATE • INNOVATE

**Developed by [Yasir Arafath](https://github.com/yasirarafathctg)**

AI Automation | API Integration | Intelligent Workflows

</div>
