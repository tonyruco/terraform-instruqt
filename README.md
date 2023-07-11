# Terraform Cloud with Azure
Terraform Cloud enables infrastructure automation for provisioning, compliance, and management of any cloud, data center, and service.

Work with the devops team at ACME as they go from manual provisioning with Terraform to a fully automated devops workflow with code reviews, testing, and automated provisioning in Azure Cloud.

1. Run infrastructure as code remotely: Store state and execute Terraform runs in an SOC2 compliant and reliable environment.

2. Establish Cloud compliance and management: Set up permissions and governance features across any resource managed by Terraform. Add capabilities for policy enforcement.

3. Create self-service infrastructure with a private registry: Standardize infrastructure across your provisioning processes using your own private registry.



### hashicat-azure output
Hashicat: A terraform built application for use in Hashicorp workshops.

Includes the "Meow World" website. 😻

## Getting Started - Explore the lab
Get to know your working environment.

### Introduction
Welcome to your first day as an infrastructure admin at ACME Inc. After employee orientation, you sit down at your workstation and start your workday.

In your workstation, there are two folders where you interact during the exercise:

    The hashicat-azure folder contains Terraform code for the application deployment.

    The terraform-cloud folder provides utility code to set up your Terraform Cloud resources.

There are other folders that contain utilities for the exercises. We exclude them from the Code Editor for simplicity. You do not need to edit anything in them.

    The terraform-github folder contains Terraform code to automate management tasks in your GitHub organization.
    The terraform-api folder contains Terraform code and JSON templates to automate API exercises.
    The scripts folder contains interactive Bash scripts to assist you in select exercises.

### Code editor
- Use the Code Editor tab to work with your Terraform code.

- Find the notification for recommended extensions in your code editor.

- Install and explore the extensions for this project.

- Close all the tabs when you are ready to move on.
Move back to the Explorer.

- Expand the hashicat-azure folder and open the file README.md.

- Add some text at the bottom, then close and re-open the file.

- Note that your code editor is pre-configured with Auto Save to keep your changes automatically.

- Please explore the Terraform code for the hashicat-azure application.

### Terminal
- Explore the Terminal tab where you execute Terraform commands.
- Copy and paste the following command: terraform


Congratulations, you are familiar with the lab environment.

<br/>
With your Terraform Cloud account

Create a new Terraform Cloud Organization
Enable 30-day Trial Plan of "Team & Governance" features
Create a new personal account token
Create a dedicated workspace