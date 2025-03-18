# n8n-coolify-mcp-tools

A collection of n8n tools for interacting with Coolify via MCP (Model Context Protocol).

## Tools

This package provides 25 tools for managing your Coolify infrastructure:

### Version & Health
- Get Version - Get Coolify version information
- Health Check - Check Coolify API health status

### Teams Management
- List Teams - List all teams
- Get Team - Get details of a specific team
- Get Current Team - Get details of the current team
- Get Current Team Members - Get members of the current team

### Server Management
- List Servers - List all servers
- Create Server - Create a new server
- Validate Server - Validate a server configuration
- Get Server Resources - Get server resource usage information
- Get Server Domains - Get domains configured for a server

### Service Management
- List Services - List all services
- Create Service - Create a new service
- Start Service - Start a service
- Stop Service - Stop a service
- Restart Service - Restart a service

### Application Management
- List Applications - List all applications
- Create Application - Create a new application
- Start Application - Start an application
- Stop Application - Stop an application
- Restart Application - Restart an application
- Execute Command Application - Execute a command in an application container

### Deployment Management
- List Deployments - List all deployments
- Get Deployment - Get deployment details

### Security
- List Private Keys - List all private keys
- Create Private Key - Create a new private key

## Usage

1. Install the n8n MCP Client node
2. Import the tools configuration from `coolify-tools.json`
3. Configure your Coolify MCP credentials
4. Use the tools in your workflows

Each tool is configured to use AI-assisted parameter filling via the `$fromAI()` function, making it easier to provide correct values based on context.

## Requirements

- n8n v1.0.0 or later
- n8n MCP Client node
- Coolify instance with API access

## Related Projects

- [Coolify MCP Server](https://github.com/wrediam/coolify-mcp-server) - The MCP server implementation for Coolify integration
