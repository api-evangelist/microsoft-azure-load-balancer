# Azure Load Balancer (microsoft-azure-load-balancer)
Azure Load Balancer is a high-performance, low-latency layer-4 load balancing service for distributing inbound and outbound network traffic across virtual machines and other Azure resources. It supports public and internal load balancers, health probes, NAT rules, and HA scenarios.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-load-balancer/refs/heads/main/apis.yml)

## Tags:

 - Azure, High Availability, Layer 4, Load Balancing, Network

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-04-28

## APIs

### Azure Load Balancer REST API
Azure Load Balancer REST API provides management of layer-4 load balancers for distributing network traffic across virtual machines. It supports configuring frontend IPs, backend pools, health probes, load balancing rules, and inbound NAT rules.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/load-balancer/](https://learn.microsoft.com/en-us/rest/api/load-balancer/)

#### Tags:

 - High Availability, Layer 4, Load Balancing, Network

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/load-balancer/)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/load-balancer/)
- [Authentication](https://learn.microsoft.com/en-us/rest/api/azure/)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-public-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/load-balancer/)
- [Python SDK](https://learn.microsoft.com/en-us/python/api/overview/azure/network)
- [.NET SDK](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.network-readme)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Documentation](https://learn.microsoft.com/en-us/azure/load-balancer/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/load-balancer/)
- [StatusPage](https://status.azure.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/)
- [Support](https://azure.microsoft.com/en-us/support/)
- [TermsOfService](https://azure.microsoft.com/en-us/support/legal/)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)

## Features

| Name | Description |
|------|-------------|
| Layer-4 Load Balancing | Distribute TCP and UDP traffic across virtual machines and resources with high performance and low latency. |
| Public and Internal Load Balancers | Support both public-facing and internal load balancing scenarios for diverse network architectures. |
| Health Probes | Monitor backend instance health with configurable TCP, HTTP, and HTTPS probes for automatic failover. |
| NAT Rules | Configure inbound NAT rules to forward traffic to specific backend instances on designated ports. |
| High Availability Ports | Load balance all TCP and UDP flows on all ports simultaneously for network virtual appliance scenarios. |
| Cross-Region Load Balancing | Distribute traffic across Azure regions for global high availability and disaster recovery. |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application High Availability | Distribute traffic across multiple web servers for improved reliability and uptime. |
| VM Scale Set Load Balancing | Automatically balance traffic across virtual machine scale sets with auto-scaling capabilities. |
| Network Virtual Appliance Distribution | Distribute traffic across multiple firewall or NVA instances using HA ports. |

## Integrations

| Name | Description |
|------|-------------|
| Azure Virtual Machines | Distribute network traffic across pools of Azure virtual machines. |
| Azure Virtual Machine Scale Sets | Integrate with VMSS for automatic scaling and load distribution. |
| Azure Monitor | Monitor load balancer health, performance metrics, and diagnostic logs. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
