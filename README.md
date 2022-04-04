# GitHub only SDLC

Demo project to test how much of SDLC (Software Development Life Cycle) pipeline I can set up and comfortable use without integrating with other services.

Goals, to use only:
* GitHub Projects and Issues instead of Jira or similar services
* GitHub actions for tests instead of TravisCI, Jenkins...
* GitHub environments for complex deployment rules and protections

What I intend to use:
* [Cloudcraft](https://cloudcraft.co) and [Terragrunt](https://terragrunt.gruntwork.io) for IaC (Infrastructure as Code)
* AWS as cloud provider
* [Next js](https://nextjs.org/learn/basics/create-nextjs-app) default app as site base.

## Roadmap

- [ ] Demo app: Have fun with Next.js
- [ ] IaC: Configure AWS with Terraform/Terragrunt
- [ ] IaC: Automation for “apply” on push, “plan” on PR
- [ ] CI/CD: automatize with GitHub actions

Fun features to have:

- [ ] IaC: auto-create QA environments for feature-branches
- [ ] IaC: Try Pulumi alternative to Terraform
- [ ] IaC: Deployment history (audit logs)
- [ ] IaC: policy-as-code
- [ ] IaC: granular role based access controls (RBAC)
- [ ] IaC: Drift detection
- [ ] IaC: Security scanning
- [ ] IaC: Cost estimation
