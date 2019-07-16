# TRANQUILITY BASE
The opensource multi-cloud infrastructure as code Landing Zone
A self-service portal for automating the provisioning of a set of DevOps-ready reference architectures

# Landing Zones
- A consistent multi-cloud Landing Zone for Google Cloud Platform, Azure and Amazon Web Services.
- Built using modularised, versionable Infrastructure as Code templates with Terraform using the underlying CSP APIs.
- A shared services layer including Networking, Account Management, Security, IAM, Logging, Alerting and Billing.

# Self-service developer portal
- Enables administrators to define which Activators can be deployed into Dev/PoC/Production based on several criteria, including technology maturity, regulatory environment and data restrictions
- Enables development teams to quickly provision infrastructure by deploying pre-approved Activators
- Track and control production changes with versionable IaC that is stored in Repos.
- Provision infrastructure in minutes, with the IaC being part of the application build process (high DevOps maturity)

# Launch Activators
- Activators are a combination of a reference application architecture and devops pipelines provisioned using IaC templates.
- Activators can be created by Admins with policy-based controls defining where they can be deployed and by whom.
- Activator provisioning includes linking to the Shared Services VPC to benefit from consistent deployment and controls.
- Activators include provisioning of the latest monitoring and observation tooling.

# Deploy DevOps pipeline
- Pipelines can be defined for each Activator using either Jenkins running on K8S or cloud native tooling.
- Pipelines can be defined using several release strategies – Canary, Blue/Green, Rolling Blue/Green and Release Train.
- Pipelines include ITIL practices including release notes, change control, auditing, pre and post release testing and automated rollbacks.
- Pipelines support both CI/CD and also Continuous Deployment (release-at-will).
