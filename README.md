# Veeam

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
