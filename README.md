# DevOpsBox
DevOps In A Box is a project to develop an Azure Blueprint that will build out a DevOps environment suitable for use by most development teams.

We use best practices in Azure Governance to create a governed environment with commonly used controls baked in.

# Rationale
We found teams spending a considerable amount of time spinning up essentially identical base environments, and for a large customer, that can amount to a significant spend on identical work on every major development effort. Dev Ops In A Box&trade; will allow a customer to create identical DevOps environments
below a Management Group, allowing each subscription in that Management Group to have a complete set of
resources deployed.

# What is Deployed
Dev Ops In A Box deploys:
* Resource Groups: 3 (Management, Development and Staging)
* Resource Manager Templates: For resources like VNets, a Strorage Account, etc.
* Azure Policy: Things like Region and SKU restrictions will be provided
* Azure RBAC: A few key roles used across the three resource groups will be enforced

# Current State
* Three Resource Groups Created
* Three VNets created in each Resource Group
* Storage Account deployed in Management Resource Group
