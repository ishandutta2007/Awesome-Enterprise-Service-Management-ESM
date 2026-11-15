# Awesome-Enterprise-Service-Management-ESM

# Top Enterprise Service Management (ESM) Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Cross-Department Workflows, Shared Service Portals & Self-Hosted ITSM Platforms*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Service Management (ESM)**. These tools extend IT service management practices beyond IT—bringing HR, Finance, Facilities, Legal, and other business teams onto a shared service platform with unified request intake, automated workflows, and cross-department visibility [citation:7][citation:10].

**Examples** include ServiceNow, Jira Service Management, Freshservice, BMC Helix, SysAid, TOPdesk, TeamDynamix, and open-source alternatives like ITSM (heidsoft) and OTRS (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted ESM, open-source ITIL service management, and community-driven cross-department workflow platforms—ideal for organizations seeking data sovereignty and avoiding per-agent or per-requester SaaS pricing. The open-source landscape is genuinely thin for **full ESM** (cross-department service catalogs with AI and BPMN orchestration), but functional for **ITIL-aligned ITSM foundations**: **ITSM (heidsoft)** provides an AI-native Apache-2.0 platform covering tickets, CMDB, and BPMN [citation:11], while **OTRS** remains the battle-tested open-source ticket management standard.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[ServiceNow](https://www.servicenow.com/)** | **The enterprise ESM benchmark.** Over 85% of the Fortune 500 runs ServiceNow ITSM, with native AI built into the platform foundation rather than bolted on [citation:2]. **Enterprise Service Management** extends ITSM workflows to HR, Finance, Legal, and Facilities. **Flow by ServiceNow** is a conversational AI-native service desk for organizations of any size with no implementation required [citation:2]. Unified data model connects incidents, assets, and knowledge across departments. | Quote-only (enterprise contract) | No free tier; demo via sales. **Flow** offers instant deployment for smaller organizations [citation:2]. |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | **The most accessible enterprise ESM for Atlassian shops.** Any business team—HR, Marketing, Legal, Finance, Facilities—can create its own service portal with drag-and-drop workflow templates [citation:3]. **Service Collection** bundles JSM with Customer Service Management, Assets, and Rovo AI agents [citation:3]. **Delegated permissions** let project owners administer their own service desks while IT retains governance visibility [citation:3]. 5,000+ Marketplace integrations. | Premium: **~$55/agent/month** (from prior research); quote-only for Enterprise | **Free**: 3 agents, unlimited customers; paid plans for advanced automation and AI |
| **[Freshservice](https://www.freshworks.com/freshservice/business-teams/esm/)** | **AI-powered ESM with secure segmented workspaces.** Manage a multi-department service desk on a single Freshservice instance with **complete data segregation, privacy, and administrative autonomy**—HR data stays isolated from IT data while maintaining enterprise-wide visibility [citation:12]. **Freddy AI Agent** resolves routine requests before they reach agents, auto-generates knowledge articles from past tickets, and provides conversational request intake [citation:12]. | Quote-only (tiered by agents) | **14-day free trial** (no credit card); no permanent free tier [citation:12]. |
| **[BMC Helix ESM](https://www.bmc.com/)** | **AI-powered automation across IT and non-IT lines of business.** Pre-built workflows for HR Service Management (employee onboarding), Workplace Service Management (facilities), Security Incident Management, and Business Workflows on a no-code/low-code platform [citation:5]. **BMC HelixGPT** applies AI agents to request fulfillment, knowledge management, and change risk evaluation [citation:5]. | Quote-only (enterprise contract) | No free tier; demo via sales. |
| **[SysAid](https://www.sysaid.com/)** | **AI-powered service for all teams with zero-trust data segregation.** Every department—IT, HR, Finance, Facilities, Legal—gets its own **secure service space** with separate data pools, knowledge bases, and AI guardrails to minimize hallucinations [citation:7]. **Cross-team ticket routing** with one-click handoffs while keeping confidential data isolated. **Unlimited AI** across departments with department-specific workflows [citation:7]. | Quote-only (tiered by agents) | No free tier; demo via sales. |
| **[TOPdesk](https://www.topdesk.com/)** | **Ready-to-use ESM platform with fast time-to-value.** Based on ITIL and 30 years of experience—works right out of the box with forms, fields, and workflows adjustable without developers [citation:9]. **Most customers go live within 3 months, some in as little as 3 weeks** [citation:9]. 100+ integrations, SOC 2 certified, 99.9% average uptime [citation:9]. | Quote-only (three plans; cloud or on-premises) | No free tier; demo via sales. |
| **[TeamDynamix](https://www.teamdynamix.com/)** | **ESM focused on project management and service delivery convergence.** Research shows 34% of organizations use ESM for better project management and prioritization, 42% for improved cross-business collaboration, and 46% for simplified workflows [citation:10]. Positioned for higher education and mid-market organizations. | Quote-only | No free tier; demo via sales. |
| **[HaloITSM](https://haloitsm.com/)** | **Enterprise-wide service management with a fresh, dynamic interface.** RSPB case study: consolidated asset management, IT stock, service catalogues, and call-logging into a single system used by Digital Technology, HR, Finance, and Facilities [citation:6]. **Cross-team ticket passing** with visibility of workload and multi-team solutions [citation:6]. | Quote-only | No free tier; demo via sales. |
| **[InvGate Service Management](https://invgate.com/)** | **No-code ITSM with configurable help desks, levels, and escalation paths.** Assignment methods: Round Robin, Workload, Free, or Manual [citation:8]. **Virtual Service Agent** for conversational request creation across Teams and WhatsApp [citation:8]. **AI-powered SLA risk detection** identifies requests likely to breach [citation:8]. | Quote-only | No free tier; demo via sales. |
| **[Cherwell (Ivanti)](https://www.ivanti.com/)** | **No-code ESM platform acquired by Ivanti in 2021.** 11 built-in PINK-verified ITIL best practices for Incident Management, Asset Management, and more [citation:4]. **Concurrent licensing** at no extra cost for portal users [citation:4]. 175+ mergeable applications for ERP, MES, QMS, and CS integration [citation:4]. | Quote-only (Ivanti enterprise contract) | No free tier; demo via sales. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ITSM (heidsoft)](https://github.com/heidsoft/itsm)** | [![Stars](https://img.shields.io/github/stars/heidsoft/itsm?style=social&color=white)](https://github.com/heidsoft/itsm/stargazers) | **The most complete open-source ESM platform covering ITIL processes with AI-native architecture.** Apache-2.0. **Covers tickets, incidents, problems, changes, releases, service requests, service catalogs, knowledge, SLA, CMDB, and BPMN orchestration** [citation:11]. **AI is embedded into triage, summarization, knowledge retrieval, workflow recommendations, audit trails, and controlled tool execution**—not bolted on [citation:11]. **RBAC, tenant isolation, and MSP foundations** for multi-tenant service delivery. Connectors for Feishu, WeCom, DingTalk, and Webhook. Docker Compose deployment. **Status: v1.1 hardening phase**—validate security, backup, SSO, and monitoring before production [citation:11]. **Best for organizations wanting a ServiceNow-class open-source alternative** with modern Go/Next.js stack and AI-native design. |
| **[OTRS (Znuny)](https://github.com/znuny/Znuny)** | [![Stars](https://img.shields.io/github/stars/znuny/Znuny?style=social&color=white)](https://github.com/znuny/Znuny/stargazers) | **The battle-tested open-source ticket management standard (LTS fork of OTRS Community Edition).** GPL-3.0. **Audit-proof ticketing**—communications are unchangeable, all modifications documented with who/what/when [from prior research]. **SAML authentication** added in v7.3.1. **Best for IT service management and regulated environments** requiring immutable audit trails. Mature but focused on IT rather than full cross-department ESM. |
| **[OTRS (OTOBO)](https://github.com/rotheross/otobo)** | [![Stars](https://img.shields.io/github/stars/rotheross/otobo?style=social&color=white)](https://github.com/rotheross/otobo/stargazers) | **Open-source ticketing and ITSM system forked from OTRS.** **ITSM add-on packages are free to download**—CMDB, service catalog, and process management included [from prior research]. **Production servers need 8–16 GB RAM**. Vendor support from €3,900/year. **Best for IT teams wanting OTRS-style service desk without licence fees** and with optional commercial support. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | **Modern open-source customer service platform built on Frappe framework.** SLAs with business hours, auto-assignment by priority/type/team/workload, **unlimited agents with no seat fees**, Google/Microsoft/OIDC sign-in, and customer sync with ERPNext [from prior research]. **Best for organizations already on Frappe/ERPNext** wanting service management with ERP integration. |
| **[FreeScout](https://github.com/freescout-help-desk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-help-desk/freescout?style=social&color=white)](https://github.com/freescout-help-desk/freescout/stargazers) | **Lightweight open-source shared inbox with no user/ticket limits.** PHP/Laravel, runs on 1–2 GB RAM. **SLA management is a paid module** [from prior research]. **Best for small teams** wanting basic ticketing without per-agent fees, not full ESM. |

**Frameworks for building custom systems**: Choose **ITSM (heidsoft)** for the most complete open-source ESM foundation with ITIL processes, CMDB, BPMN, and AI-native design [citation:11]. For organizations needing audit-proof IT ticketing specifically, **Znuny** provides the mature OTRS standard. **No open-source project matches ServiceNow or Jira Service Management for cross-department service catalogs with AI orchestration**—expect to assemble components or accept narrower scope.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ESM platforms handle employee PII, service requests, and potentially sensitive departmental data; enforce role-based access, data segregation between business units, and compliance with applicable data protection regulations.
- **Enterprise ESM pricing is quote-only and scales per-agent.** **ServiceNow** is the enterprise benchmark with 85%+ Fortune 500 penetration [citation:2], but pricing is opaque. **Jira Service Management** offers a genuine free tier (3 agents) and is the most accessible enterprise ESM for Atlassian shops [citation:3]. **Freshservice** provides segmented workspaces for multi-department isolation without separate instances [citation:12]. **SysAid** emphasizes zero-trust data segregation with department-specific AI guardrails [citation:7]. **TOPdesk** claims fast time-to-value—3 weeks to 3 months for go-live [citation:9]. **Open-source ESM is genuinely emerging but not yet enterprise-ready**: **ITSM (heidsoft)** is the most ambitious with AI-native design and full ITIL coverage, but is still in **v1.1 hardening phase** [citation:11]. **Znuny/OTOBO** provide mature IT ticketing but not cross-department ESM. **Validate whether you need full ESM (ServiceNow, JSM, Freshservice) or IT-focused ticketing (Znuny, OTOBO)** before committing.

---

**Made for IT service managers, platform teams, and organizations extending service management beyond IT.**  
Let's make enterprise service management more open, cross-departmental, and employee-centric.
