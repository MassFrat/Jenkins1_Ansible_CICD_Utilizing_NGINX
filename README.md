# Ansible + Jenkins NGINX Integration (CI/CD)
<br/>

## Guidelines:
Automatically deploy NGINX to multiple servers
Configure NGINX with custom settings
Manage deployments through Jenkins pipelines
Ensure consistent server configurations across environments

<br/>

# Prerequisites

<br/>

## Jenkins Requirements

Jenkins server with administrative access
Jenkins plugins installed:
Ansible Plugin
SSH Agent Plugin (for private key management)
Pipeline Plugin (for Jenkinsfile support)

<br/>

## Ansible Requirements

Ansible installed on Jenkins server or dedicated Ansible control node
SSH access to target servers
Python installed on target servers

<br/>

## Target Server Requirements

SSH access configured
Sudo privileges for the deployment user
Supported OS: Ubuntu/Debian, CentOS/RHEL, or similar

<br/>
