# n8n Cloud vs Self-Hosted

**Topic:** n8n Hosting and Local Environment Setup  
**Type:** Concept Learning  
**Status:** Studied

## 1. Overview

Learned about the different deployment options available for n8n, including managed cloud hosting and self-hosted installations.

Also explored how Node.js and npm can be used to run n8n locally for development and testing.

## 2. What is n8n Cloud?

n8n Cloud is a managed hosting option where the infrastructure and platform operations are handled by the service provider.

**Advantages:**
- No manual server installation.
- Managed infrastructure and updates.
- Faster initial setup.
- Suitable for teams that prefer managed hosting.

**Considerations:**
- Subscription and usage-based limits.
- Less control over underlying infrastructure.
- Hosting configuration depends on the selected plan.

## 3. What is Self-Hosted n8n?

Self-hosted n8n allows developers to run n8n on their own computer, server, or cloud infrastructure.

**Advantages:**
- Greater control over infrastructure and configuration.
- Flexibility to integrate with internal services.
- Ability to manage data storage and deployment architecture.
- Useful for local development and experimentation.

**Considerations:**
- Requires installation and maintenance.
- Security, backups, and updates are your responsibility.
- Infrastructure resources and hosting may have costs.
- Execution capacity depends on the available hardware and configuration.

## 4. Cloud vs Self-Hosted Comparison

| Feature | n8n Cloud | Self-Hosted |
|---|---|---|
| Setup | Managed | Manual |
| Infrastructure | Provider-managed | Developer-managed |
| Maintenance | Mostly managed | Self-managed |
| Configuration control | Limited by service | More flexible |
| Data management | Provider environment | Chosen infrastructure |
| Costs | Subscription | Infrastructure and maintenance |
| Best suited for | Quick managed setup | Custom development and hosting control |

## 5. Local Installation Using Node.js

### Prerequisites

- A supported Node.js version.
- npm package manager.
- Internet connection for installation.
- A local development environment.

### Check Node.js and npm

```bash
node -v
npm -v
```

### Install n8n

```bash
npm install -g n8n
```

### Start n8n

```bash
n8n start
```

### Access the Dashboard

Open the following URL in a browser:

```text
http://localhost:5678
```

**Note:** Verify Node.js version compatibility using the official n8n documentation before installation.

## 6. Basic Local Architecture

```text
Developer
    ↓
Web Browser
    ↓
localhost:5678
    ↓
Local n8n Instance
    ↓
Workflow Execution
    ↓
APIs / Databases / AI Services
```

## 7. Key Learnings

- Understood the differences between managed and self-hosted n8n.
- Explored hosting costs, maintenance, privacy, and infrastructure responsibilities.
- Learned the role of Node.js and npm in local installation.
- Understood the basic local execution architecture.
- Reviewed the commands required to install and start n8n.

## 8. Next Steps

- Install and verify the local n8n environment.
- Explore the workflow editor.
- Create and execute the first basic workflow.
- Document installation issues and solutions.

**Implementation Status:** Installation and workflow execution are not yet verified in this document.
