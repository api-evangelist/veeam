# Veeam

Veeam is a backup and data management platform providing REST APIs for managing backup jobs, restore operations, protected workloads, and cloud backup policies across on-premises, virtual, and cloud environments. The Veeam platform covers Backup & Replication, Backup for Microsoft 365, Backup for AWS, Azure, and Google Cloud, Veeam ONE monitoring, Recovery Orchestrator, and Service Provider Console.

**Website:** https://www.veeam.com/  
**Developer Documentation:** https://helpcenter.veeam.com/category/development.html  
**GitHub:** https://github.com/VeeamHub  
**Blog:** https://www.veeam.com/blog/  
**Status:** https://vdcstatus.veeam.com/  
**LinkedIn:** https://www.linkedin.com/company/veeam-software  
**X:** https://x.com/veeam  

## APIs

This repository catalogs the following Veeam REST APIs:

1. **Veeam Backup & Replication REST API** — Core backup/restore/replication for VMware and Hyper-V environments
2. **Veeam Backup Enterprise Manager REST API** — Centralized enterprise management and reporting
3. **Veeam Backup for Microsoft 365 REST API** — Backup of Exchange Online, SharePoint, OneDrive, and Teams
4. **Veeam ONE REST API** — Monitoring, analytics, and capacity planning
5. **Veeam Backup for AWS REST API** — EC2, RDS, EFS, and VPC backup/restore
6. **Veeam Backup for Microsoft Azure REST API** — Azure VM and SQL backup/restore
7. **Veeam Backup for Google Cloud REST API** — GCE and Cloud SQL backup/restore
8. **Veeam Service Provider Console REST API** — MSP tenant management, billing, and licensing
9. **Veeam Recovery Orchestrator REST API** — DR plan orchestration and compliance

## Repository Structure

- `apis.yml` — APIs.json 0.19 provider index
- `plans/veeam-plans-pricing.yml` — Licensing tiers and pricing details
- `rate-limits/veeam-rate-limits.yml` — API throttling and rate limit documentation
- `finops/veeam-finops.yml` — FinOps Framework guidance for cost optimization

## Licensing

Veeam uses a Universal License (VUL) per-workload subscription model:

| Tier | Price | Key Addition |
|------|-------|--------------|
| Community Edition | Free | Up to 10 workloads |
| Standard | ~$250/workload/year | Unlimited workloads |
| Advanced | ~$350/workload/year | Adds Veeam ONE monitoring |
| Premium | ~$450/workload/year | Adds Recovery Orchestrator |

_Prices effective 2026. Cloud storage billed separately._

---

_Maintained by [Kin Lane](mailto:kin@apievangelist.com) for the [API Evangelist](https://apievangelist.com) catalog._
