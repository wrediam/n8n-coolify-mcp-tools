# Coolify MCP Workflow

🚀 **Automate Coolify Management with n8n!**

This workflow leverages the [Community n8n MCP Client](https://github.com/n8n-nodes-mcp) and my new [Coolify MCP Server](https://github.com/coolify-mcp-server) to interact with your Coolify infrastructure using **MCP (Model Context Protocol)**. It enables seamless management of teams, servers, services, applications, and deployments directly within your n8n workflows. 

## 🎯 Why I Created This Setup
I built this workflow to **automate the management of my Coolify infrastructure using AI**. With AI-assisted parameter filling and automated execution, this setup simplifies and streamlines infrastructure management without extensive manual setup.

Additionally, I plan to **release another workflow integrating Telegram**, allowing interaction with a Telegram bot for even more convenient Coolify management.

## 🔥 Coolify MCP Server – The Backbone of This Setup
To make this workflow possible, I put together the **Coolify MCP Server**. I used the documentation from [Coolify](https://coolify.io/docs/api-reference/authorization) and used the API endpoints I know I would use most to build out the tooling. This server acts as a bridge between Coolify and n8n, enabling:

- **Seamless API communication** between Coolify and n8n
- **Efficient command execution** for managing servers, services, and applications
- **Scalability** to handle multiple infrastructure tasks simultaneously
- **AI-driven decision-making**, allowing smart automation without manual input

This server is the heart of this automation setup, ensuring that every command runs smoothly and effectively. If you're using Coolify and want to unlock true automation potential, this server is a game-changer! 🚀

## 📌 Features

This workflow provides **25 powerful tools** to control various aspects of Coolify:

### 🔍 Version & Health Checks
- **Get Version** - Retrieve Coolify version details
- **Health Check** - Verify Coolify API health status

### 👥 Teams Management
- **List Teams** - Display all teams
- **Get Team** - Fetch details of a specific team
- **Get Current Team** - Retrieve details of the active team
- **Get Current Team Members** - List members in the current team

### 🖥️ Server Management
- **List Servers** - Show all available servers
- **Create Server** - Deploy a new server
- **Validate Server** - Check server configuration validity
- **Get Server Resources** - Monitor server resource usage
- **Get Server Domains** - List domains associated with a server

### ⚙️ Service Management
- **List Services** - Show all registered services
- **Create Service** - Deploy a new service
- **Start Service** - Launch a service
- **Stop Service** - Halt a running service
- **Restart Service** - Restart a service

### 📦 Application Management
- **List Applications** - Show all applications
- **Create Application** - Deploy a new application
- **Start Application** - Launch an application
- **Stop Application** - Stop an application
- **Restart Application** - Restart an application
- **Execute Command Application** - Run commands inside an application container

### 🚀 Deployment Management
- **List Deployments** - Show all deployments
- **Get Deployment** - Fetch deployment details

### 🔐 Security
- **List Private Keys** - Show all stored private keys
- **Create Private Key** - Generate a new private key

## 🔧 Setup Instructions

1. **Install Required Nodes:**
   - [Community n8n MCP Client](https://www.npmjs.com/package/n8n-nodes-mcp)
   - [Coolify MCP Server](https://www.npmjs.com/package/coolify-mcp-server)

2. **Import Configuration:**
   - Add this workflow to your n8n instance.

3. **Configure Coolify MCP Credentials:**
   - Ensure your Coolify instance has API access and set up the required authentication credentials in n8n.


## 🛠️ Requirements

- [**Community n8n MCP Client**](https://www.npmjs.com/package/n8n-nodes-mcp)
- [**Coolify MCP Server**](https://www.npmjs.com/package/coolify-mcp-server)
- [**Coolify**](https://coolify.io) with API access

---

With this setup, you can effortlessly manage your Coolify infrastructure directly from n8n! 🎯 Stay tuned for the upcoming **Telegram bot integration** for even easier automation. 🤖

