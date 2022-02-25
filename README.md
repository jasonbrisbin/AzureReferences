# AzureReferences
A collection of resources which are useful in the design and deployment of Azure environments.

## Reference Architecture
- [Enterprise Scale](https://github.com/Azure/Enterprise-Scale) - A prescriptive solution for building and scaling Azure environments while aligning security boundaries with different enterprise roles.  There are multiple landing zone models which vary in complexity based on network topology and scaling needs.
- [AzOps](https://github.com/Azure/AzOps) - Is a tool for bootstrapping Infrastructure as Code within the context of deploying the Landing Zones reference architecture.  It provides useful templates and pipelines for achieving this.
- [AlwaysOn](https://github.com/Azure/AlwaysOn) - Provide a reference architecture for building applications that scale to multiple geographies.  It is a prescriptive architecture for designing and deploying infrastructure to support georedundancy.
- [Microsoft Patterns and Practices](https://github.com/mspnp) - This repository contains documentation and reference code for implementing many of the solutions from the [Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/) site.
- [AKS PCI/DSS Reference Architecture](https://github.com/mspnp/aks-baseline-regulated) - Provides a reference architecture and details alignment to specific PCI/DSS controls and how requirements are satisfied.


## Tools
- [PSRule](https://microsoft.github.io/PSRule/v1/) - This tool provides the ability to perform tests on infrastructure code prior to deployment as well as validation of resources post deployment.
- [ARM TTK](https://github.com/Azure/arm-ttk) - The ARM Test Toolkit is a powershell based testing framework to validate infrasucture code prior to deployment.


## Management
- [Azure ARC For Kubernetes](https://docs.microsoft.com/en-us/azure/azure-arc/kubernetes/overview) - This is a really interesting hybrid approach to Kubernetes by enabling a an Azure Resource to represent the cluster.  The result is being able to use Azure management/visability tools along with GitOps in the same manner as AKS in the cloud.
