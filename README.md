# Mike Flynn

Cloud architect who enjoys getting hands-on, from the network design to the deployment code.

I build Azure platforms, reusable infrastructure and delivery automation. My work brings together Terraform, Kubernetes, Linux and networking, with a focus on making systems understandable, repeatable and practical to operate. I'm also building several software projects and exploring what AI-assisted engineering makes possible.

## Start here

My public Azure platform examples connect three layers: **infrastructure → cluster services → application delivery**. You can follow the design through to the scripts, configuration and tests.

| Project | What to explore |
| --- | --- |
| [Terraform delivery templates](https://github.com/MikeeeGit/terraform-delivery-templates) | Reusable Azure DevOps and GitHub Actions pipelines, OIDC identities, saved plans and matching Bash/PowerShell helpers. |
| [AKS delivery templates](https://github.com/MikeeeGit/aks-delivery-templates) | Build-once image promotion, independently managed platform services, Kustomize and direct or Argo CD delivery across two cluster slots. |
| [AKS platform demo](https://github.com/MikeeeGit/aks-platform-demo) | A small application with executable deployment, HTTPS, rollback and recovery rehearsals on two disposable Kubernetes clusters. |
| [Azure network foundation](https://github.com/MikeeeGit/azure-network-foundation) | Hub-and-spoke networking, private DNS, environment configuration and CSV-driven network policies. |
| [Azure AKS foundation](https://github.com/MikeeeGit/azure-aks-foundation) | Independent private AKS clusters, workload identity and explicit infrastructure-to-application handoffs. |
| [Reusable network module](https://github.com/MikeeeGit/terraform-azurerm-network-foundation) | Composable VNet, DNS, subnet, NSG and route modules with examples and mocked-provider tests. |

## A closer look

- **Architecture:** [the three-tier deployment system](https://github.com/MikeeeGit/aks-delivery-templates/blob/main/docs/three-tier-deployment-system.md) and [the complete Azure platform scenario](https://github.com/MikeeeGit/terraform-delivery-templates/blob/main/docs/azure/hub-spoke-platform.md).
- **Engineering evidence:** [deployment and recovery testing](https://github.com/MikeeeGit/aks-delivery-templates/blob/main/docs/deployment-testing-system.md), including recorded direct and Argo CD acceptance results.
- **Operational decisions:** [direct pipelines versus Argo CD](https://github.com/MikeeeGit/aks-delivery-templates/blob/main/docs/delivery-methods.md), [gateway migration](https://github.com/MikeeeGit/aks-delivery-templates/blob/main/docs/ingress-migration.md) and [the Azure sandbox runbook](https://github.com/MikeeeGit/terraform-delivery-templates/blob/main/docs/azure/sandbox-deployment.md).

The public examples use synthetic configuration and carry Apache-2.0 licences. Their documentation distinguishes configuration tests and disposable-cluster acceptance from the separate checks needed for live Azure deployment.

## Around the web

[LinkedIn](https://www.linkedin.com/in/michael-flynn-8821a58) · [X / @mikeflynntech](https://x.com/mikeflynntech)
