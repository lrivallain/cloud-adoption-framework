---
title: What's new in the Microsoft Cloud Adoption Framework
description: Learn about recent updates to the Microsoft Cloud Adoption Framework for Azure.
author: Zimmergren
ms.author: tozimmergren
ms.date: 04/02/2024
ms.topic: conceptual
ms.custom: UpdateFrequency.5, historical
---

# What's new in the Microsoft Cloud Adoption Framework for Azure

We build the Microsoft Cloud Adoption Framework collaboratively with our customers, partners, and internal Microsoft Teams. We release new and updated content for the framework as it becomes available. These new releases pose an opportunity for you to test, validate, and refine the Cloud Adoption Framework guidance along with us.

Partner with us in our ongoing effort to develop the Cloud Adoption Framework.

## March 2024

### Updated articles

- [Azure governance design area](../ready/landing-zone/design-area/governance.md): Explore a new section for third-party tooling, including guidance for AzAdvertizer and Azure Governance Visualizer. 
- [Tools and templates](../resources/tools-templates.md): Find information about governance for AzAdvertizer.
- [Resource consistency decision guide](../decision-guides/resource-consistency/index.md): Check out our expanded information about basic grouping for resource groups.
- [Select Azure regions](../ready/azure-setup-guide/regions.md): We added guidance about how to plan Azure resource group deployments.  
- [Transition an existing Azure environment to the Azure landing zone conceptual architecture](../ready/enterprise-scale/transition.md): Find tip to help you reduce the impact of regional outages.
- [Security guidelines for Oracle on Azure Virtual Machines landing zone accelerator](../scenarios/oracle-iaas/oracle-security-guideline-landing-zone.md): Review new use cases for centralized identity management. These use cases include using Azure Key Vault to store credentials and using hardened operating system images.
- [Storage for Azure HPC in the finance sector](../scenarios/azure-hpc/finance/storage.md): Find new data to help you compare Azure Managed Lustre with Blob Storage, Azure Files, and Azure NetApp Files.
- [Network topology and connectivity for an SAP migration](../scenarios/sap/eslz-network-topology-and-connectivity.md): Explore design recommendations for Azure ExpressRoute.

## February 2024

### New articles

- [Application identity and access management](../ready/landing-zone/design-area/identity-access-application-access.md): Learn about recommendations that application owners and developers can use to design the identity and access management for cloud-native applications.  

### Updated articles

- [Hybrid identity with Active Directory and Microsoft Entra ID in Azure landing zones](../ready/landing-zone/design-area/identity-access-active-directory-hybrid-identity.md): We updated this article to include information about how to design and implement Microsoft Entra ID and hybrid identity for Azure landing zones. Microsoft Entra ID is a cloud-based identity and access management service that provides robust capabilities to manage users and groups. You can use it as a standalone identity solution or integrate it with a Microsoft Entra Domain Services infrastructure or an on-premises Active Directory Domain Services (AD DS) infrastructure.
- [Landing zone identity and access management](../ready/landing-zone/design-area/identity-access-landing-zones.md): Find out about considerations and recommendations for implementing identity and access control within Azure application and platform landing zones. This article has extensive new content.
- [Azure identity and access management design area](../ready/landing-zone/design-area/identity-access.md): Learn about the identity and access management design area, which provides best practices to establish the foundation of your public cloud architecture. This article has extensive new content.
- [Cloud adoption journey](../adopt/cloud-adoption.md): Learn about various types of cloud adoption journeys, including when to retire, replace, rearchitect, rebuild, rehost, or replatform your solution.
- [Azure migration tools decision guide](../migrate/azure-migration-guide/migration-tools-decision-guide.md): We added information about tools for application migration, modernization, replatforming, and rehosting.
- [Azure workload management and monitoring](../ready/landing-zone/design-area/management-workloads.md): Find new guidance about sovereign workloads.

## January 2024

### New articles

- [Define a sovereignty strategy](../strategy/define-sovereignty-strategy.md): Organizations that use cloud services can find guidance for meeting the sovereignty requirements for their countries/regions. We also updated several articles with sovereignty considerations, which you'll find under the "Updated articles" section for this month.

- [Advanced Azure Policy management](../ready/policy-management/enterprise-policy-as-code.md): Find out how to manage Azure Policy at scale by using the Enterprise Policy as Code (EPAC) open-source project and integrating IaC into your environment.

### Updated articles

- [Plan for IP addressing](../ready/azure-best-practices/plan-for-ip-addressing.md): We added information about IPv6 considerations. Find recommendations to help you plan for IPv6 and implement it in your existing Azure networks.

- [Network topology and connectivity for Azure Arc-enabled servers](../scenarios/hybrid/arc-enabled-servers/eslz-arc-servers-connectivity.md): Find updates about how to overcome the management challenges involved in using Private Link.

- New sovereignty considerations can be found in the following updated articles:
  - [Select Azure regions for a migration](../migrate/azure-best-practices/multiple-regions.md)
  - [Azure migration tools decision guide](../migrate/azure-migration-guide/migration-tools-decision-guide.md)
  - [Select Azure regions](../ready/azure-setup-guide/regions.md)
  - [Security design in Azure](../ready/landing-zone/design-area/security.md)

- We also added information about application migration tools and strategies. Find updates in these articles:

  - [Cloud adoption journey](../adopt/cloud-adoption.md): Learn about rearchitecting or rebuilding applications that can't be replaced by SaaS or low-code solutions.
  - [Migration tools decision guide](../migrate/azure-migration-guide/migration-tools-decision-guide.md): Explore tools for application migration and modernization and tools for replatforming or rehosting.

## December 2023

### New articles

Find new guidance about Azure landing zones:

- [Manage application development environments in Azure landing zones](../ready/landing-zone/design-area/management-application-environments.md)
- [Modify an Azure landing zone architecture to meet requirements across multiple locations](../ready/landing-zone/landing-zone-multinational.md)
- [Incorporate Zero Trust practices in your landing zone](../ready/landing-zone/design-area/security-zero-trust.md)

### Updated articles

In the following articles, find updated guidance about workload discovery processes that help you understand the many dimensions involved in migrating a workload. You can use that information to help you effectively migrate cloud workloads to another region.

- [Evaluate a cloud workload for relocation](../relocate/evaluate.md)
- [Migrate a cloud workload to another region](../relocate/migrate.md)
- [How to initiate a cloud relocation project](../relocate/initiate.md)

In [Centralized security operations with external identities for multitenant defense organizations](../scenarios/defense/identity/multi-tenant/security-operations.md), we updated our guidance for centralized security operations. 

In [Identity and access management for Azure Virtual Desktop](../scenarios/azure-virtual-desktop/eslz-identity-and-access-management.md), we added updates for Azure Virtual Desktop design considerations and supported identity scenarios.

## November 2023

### Sovereignty requirements

This new article describes how to meet digital sovereignty requirements when you adopt cloud computing. The Azure landing zone FAQ has been updated with material that corresponds to the sovereignty considerations article.

- [Sovereignty considerations for Azure landing zones](../ready/landing-zone/sovereign-landing-zone.md)

- [Azure landing zone FAQ](../ready/enterprise-scale/faq.md)

## October 2023

### HPC baseline computing

HPC baseline computing updates and new articles describe the benefits of Azure HPC OnDemand Platform (AzHop), compare the features of Azure Batch and Azure CycleCloud, and provide a large-scale HPC architecture for the finance industry.

- [Azure landing zone for HPC](../scenarios/azure-hpc/ready.md)

- [Finance HPC Azure identity and access management](../scenarios/azure-hpc/finance/identity-access-management.md)
- [Run large-scale HPC application workloads for the finance industry on Azure virtual machines](../scenarios/azure-hpc/finance/compute.md)
- [Big compute in the manufacturing industry](../scenarios/azure-hpc/manufacturing/compute.md)

### Brownfield alignment scenarios

This series starts with an introduction that describes recommendations for transitioning an existing Azure environment into an Azure landing zone conceptual architecture. It includes considerations for moving resources and subscriptions. There are four distinct articles that describe transitioning scenarios based on the existing Azure environment. The final article provides guidance about maintaining a cloud environment over time.

- [Transition an existing Azure environment to the Azure landing zone conceptual architecture](../ready/enterprise-scale/transition.md)
- [Scenario: Transition a single subscription with no management groups to the Azure landing zone conceptual architecture](../ready/landing-zone/align-scenario-single-subscription.md)
- [Scenario: Transition management groups to the Azure landing zone conceptual architecture](../ready/landing-zone/align-scenario-multiple-management-groups.md)
- [Scenario: Transition a regional organization environment to the Azure landing zone conceptual architecture](../ready/landing-zone/align-scenario-regional-org.md)
- [Scenario: Transition an environment by duplicating a landing zone management group](../ready/landing-zone/align-approach-duplicate-brownfield-audit-only.md)
- [Journey toward the target architecture](../ready/landing-zone/landing-zone-journey.md)

### Updated CAF Azure regions decision guide

Learn how to [select Azure regions for your cloud footprint](../ready/azure-setup-guide/regions.md) by considering the characteristics of each region, like availability zones, region pairs, available services, and nonfunctional requirements, like region proximity and capacity. We’ve also provided new guidance about operating across multiple Azure regions. As part of this change, we simplified the [guidance about selecting Azure regions for migrations](../migrate/azure-best-practices/multiple-regions.md).

### Network topology and connectivity for Azure Virtual Desktop

The [updates to the Network topology and connectivity for Azure Virtual Desktop article](../scenarios/azure-virtual-desktop/eslz-network-topology-and-connectivity.md) describe two new scenarios to help you understand how to manage network topology and connectivity at scale in Azure Virtual Desktop. The first scenario describes a hub-and-spoke architecture with hybrid connectivity over managed networks. The second scenario describes a hub-and-spoke architecture with public networks. Both scenarios use Remote Desktop Protocol Shortpath (RDP Shortpath).

## September 2023

### Plan for IP addressing

This article was updated with relevant information about IPv4 exhaustion and IPAM (IP address management) tools.

- [Plan for IP addressing](../ready/azure-best-practices/plan-for-ip-addressing.md).

### Guidance for documenting and deploying alerts

To support the imminent general availability of Azure Monitor baseline alerts for an Azure landing zone, we have created Cloud Architecture Framework documentation about baseline alerts. Find out what baseline alerts are and where to go for more information about how to enhance your Azure platform by using Azure Monitor alerts.

-   [Monitor Azure platform landing zone components](../ready/landing-zone/design-area/management-monitor.md)

-   [Inventory and visibility considerations](../ready/landing-zone/design-area/management-platform.md)

### Azure VMware Solution network design guides

These guides describe the Microsoft-recommended approach to help you design network connectivity for Azure VMware Solution private clouds. They explore four design areas: connectivity with on-premises sites, connectivity with Azure virtual networks, inbound internet connectivity, and outbound internet connectivity. Each design area is covered in a dedicated article, which presents architectural options, including their pros and cons. There are also two articles that cover the basics of Azure VMware Solution networking and guidance on how to prioritize requirements and related design areas.

-   [Azure VMware Solution network design guide](../scenarios/azure-vmware/network-design-guide-intro.md)

-   [Azure VMware Solution network design guide: Inbound internet connectivity](../scenarios/azure-vmware/network-design-guide-internet-inbound-connectivity.md)

-   [Azure VMware Solution network design guide: Networking basics](../scenarios/azure-vmware/azure-vmware-solution-network-basics.md)

-   [Azure VMware Solution network design guide: Outbound internet connectivity](../scenarios/azure-vmware/network-design-guide-internet-outbound-connectivity.md)

-   [Azure VMware Solution network design guide: Connectivity with on-premises sites](../scenarios/azure-vmware/on-premises-connectivity.md)

-   [Azure VMware Solution network design guide: Connectivity with Azure virtual networks](../scenarios/azure-vmware/virtual-network-connectivity.md)

## July 2023

### Landing zone regions

This article explains how landing zones use Azure regions. It also explains how to add a region to an existing landing zone and considerations for migrating your Azure estate to a different region.

- [Landing zone regions](../ready/considerations/regions.md)

### Enhanced migration guidance

This article describes how to ensure that configurations are in place when you migrate your landing zone. It explores tasks, such as preparing your identity, enabling hybrid Domain Name System (DNS) services, and enabling subscription vending.

- [Readying your landing zone for migration](../migrate/azure-migration-guide/ready-alz.md)

### New best practices for SAP landing zone accelerator security on Azure

This series provides guidance for your SAP environment in Azure. You can find best practices for security operations to secure your SAP environment in Azure, security recommendations for SAP on Azure that runs on a SQL Server database, and guidance about the flow of SAP data from source SAP systems to downstream targets. Learn how to use Azure Synapse Analytics to build a modern data platform to ingest, process, store, serve, and visualize data from various sources.

- [SAP data integration example architecture](../scenarios/sap/sap-lza-data-example-architecture.md)

- [Data integration security for SAP on Azure](../scenarios/sap/sap-lza-data-integration-security.md)

- [SQL Server database security for SAP on Azure](../scenarios/sap/sap-lza-database-security.md)

- [Security operations for SAP on Azure](../scenarios/sap/sap-lza-security-operations.md)

- [Microsoft Sentinel for SAP on Azure](../scenarios/sap/sap-lza-sentinel-for-sap.md)

## June 2023

### Updated machine learning inference during deployment

Learn about the [best practices for deploying machine learning models in production environments](../innovate/best-practices/ml-deployment-inference.md) by using Azure Machine Learning. Explore architectural considerations and deployment methods (real time and batch inference). Learn how to ensure consistency, monitor performance, implement security measures, and create a plan for updates.

### New landing zone sandbox environments

This article describes how to use a sandbox environment, including configuring networking, enabling audit logging, assigning a budget, and setting an expiration date.

- [Landing zone sandbox environments](../ready/considerations/sandbox-environments.md)

## April 2023

### Network topology and connectivity for Azure VMware Solution

When you use a VMware software-defined datacenter (SDDC) with an Azure cloud ecosystem, you have a unique set of design considerations to follow for both cloud-native and hybrid scenarios. This article provides [key considerations and best practices](../scenarios/azure-vmware/eslz-network-topology-connectivity.md) for networking and connectivity to, from, and within Azure and Azure VMware Solution deployments.

### Network considerations for Azure VMware Solution dual-region deployments

Learn how to configure network connectivity when Azure VMware Solution private clouds are deployed in two Azure regions for disaster resiliency. If there are partial or complete regional outages, the [network topology in this article](../scenarios/azure-vmware/eslz-dual-region-network-topology.md) allows unaffected components (private clouds, Azure-native resources, and on-premises sites) to maintain connectivity with each other and with the internet.

<!-- docutune:ignoreNextStep -->
