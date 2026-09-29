# Awesome-Billing

# Top Billing Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Subscription Management, Usage-Based Billing & Revenue Operations*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Billing**. These tools manage recurring subscriptions, usage-based pricing, invoicing, payment collection, dunning, and revenue recognition for SaaS companies, AI/API businesses, and digital service providers.

**Examples** include Stripe Billing, Chargebee, Zuora, Recurly, Maxio, Orb, m3ter, Lago, BillingPlatform, and Ordway (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom pricing models, and transparent billing data — ideal for startups, developers, and enterprises building vendor-independent billing infrastructure. The open-source ecosystem for subscription billing and metering has matured significantly, with production-grade platforms handling complex usage-based pricing at scale.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Stripe Billing](https://stripe.com/billing)**  
  Comprehensive subscription and recurring billing infrastructure with metered billing, invoicing, and revenue recovery. 0.5%–0.8% of revenue pricing model .

- **[Chargebee](https://www.chargebee.com/)**  
  Subscription management and recurring billing platform with usage-based billing, ML-powered dunning, and 100+ integrations. From ~$599/mo .

- **[Zuora](https://www.zuora.com/)**  
  Enterprise-grade subscription economy platform covering billing, revenue recognition, and financial operations.

- **[Recurly](https://recurly.com/)**  
  Subscription billing platform with automated invoicing, payment recovery, and revenue optimization.

- **[Maxio](https://www.maxio.com/)**  
  Billing and financial operations platform for SaaS companies, combining subscription management with revenue analytics.

- **[Orb](https://www.withorb.com/)**  
  Usage-based billing platform designed for AI, API, and infrastructure companies with flexible pricing models.

- **[m3ter](https://www.m3ter.com/)**  
  Usage-based pricing and billing platform with real-time metering and complex pricing logic.

- **[Lago](https://www.getlago.com/)**  
  Open-source metering and usage-based billing platform with managed cloud option. AGPL-3.0 licensed core .

- **[BillingPlatform](https://billingplatform.com/)**  
  Enterprise billing and revenue management platform for complex business models.

- **[Ordway](https://ordwaylabs.com/)**  
  Billing and revenue automation platform for subscription and usage-based businesses.

## Open-Source GitHub Projects

- **[Kill Bill](https://github.com/killbill/killbill)**  
  The leading open-source subscription billing and payments platform, with 15+ years of production use and 5,600+ GitHub stars. Apache-2.0 licensed and highly modular, enabling you to disable functionality you don't need or replace components with existing systems . Features plan/trial/add-on management via versioned XML catalog, multi-phase subscription engine with automatic proration, usage-based metering, and a plugin framework for custom tax, fraud, and ERP integrations. The Kaui admin dashboard provides MRR tracking, billing timeline visualization, and full audit history .

- **[Lago](https://github.com/getlago/lago)**  
  Open-source metering and usage-based billing API with 10,000+ stars. AGPL-3.0 licensed, built in Go for high-volume event ingestion . Designed for AI, cloud, and API companies needing flexible monetization with consumption tracking, subscription management, and revenue analytics.

- **[OpenMeter](https://github.com/openmeterio/openmeter)**  
  Real-time metering and billing engine for AI, agentic, and DevTool monetization with 1,170+ stars. Apache-2.0 licensed, built in Go with Kafka, ClickHouse, and PostgreSQL . Features usage metering via CloudEvents, tiered/graduated/flat-fee pricing, entitlements, prepaid credits, and first-class LLM token cost tracking. Self-hosted via Docker Compose or Kubernetes Helm chart.

- **[Recurso](https://github.com/recurso-dev/recurso)**  
  Open-source billing engine for SaaS with MIT license, built in Go with PostgreSQL . Unique feature: built-in double-entry financial ledger with ASC 606 revenue recognition (optional TigerBeetle mirror for throughput). Supports 8 aggregations and 7 charge models with exact rational math, bandit-retry dunning engine, India GST depth (Place of Supply, HSN, TDS, e-invoicing via GSP), and self-serve importers from Stripe + Chargebee.

- **[UniBee](https://github.com/UniBee-Billing/unibee)**  
  Open-source universal billing software for SaaS businesses, AGPLv3 licensed. Offers community and enterprise versions with subscription management, invoicing, billable metrics, product/plan management, webhooks, and transaction management . Docker Compose deployment for quick self-hosting.

- **[FlexPrice](https://github.com/flexprice/flexprice)**  
  Open-source pricing and billing infrastructure supporting any pricing model from usage-based to subscription. Features no-code UI, real-time usage metering, credits and top-ups, and feature access control. Cloud or self-hosted .

- **[Lotus](https://github.com/uselotus/lotus)**  
  Open-source pricing and packaging infrastructure with 1,730+ stars. Python-based, designed for teams wanting to launch, test, and scale complex billing models with metering, invoicing, and real-time data .

- **[Paymenter](https://github.com/Paymenter/Paymenter)**  
  Open-source billing and client management platform designed for hosting businesses, MIT licensed. Self-hosted alternative to WHMCS, Blesta, and HostBill with integrations for Pterodactyl, cPanel, Plesk, DirectAdmin, and Virtualizor . Automates subscription billing, invoice generation, and service provisioning.

- **[SolidInvoice](https://github.com/SolidInvoice/SolidInvoice)**  
  Open-source invoicing platform for freelancers and small businesses, MIT licensed. Built on Symfony 7 and PHP 8.4 with quotes-to-invoices, recurring invoices, multi-currency, multi-tax, 2FA, REST API, and MCP server for AI agent automation . Self-hosted free or hosted at $8/month.

- **[Hyperswitch](https://github.com/juspay/hyperswitch)**  
  Open-source payment orchestration platform from Juspay with 43,000+ stars, Apache-2.0 licensed . Connects to 120+ payment processors through a single API with intelligent routing, revenue recovery via retries, PCI-compliant card vault, and automated reconciliation. Modular architecture allows deploying individual components.

- **[Meteroid](https://github.com/meteroid-oss/meteroid)**  
  Rust-based open-source billing platform with modern architecture for product-led growth companies. AGPL-3.0 licensed with 1,089+ stars .

- **[Autumn](https://github.com/useautumn/autumn)**  
  Simple Stripe integration layer for AI startups with 2,644+ stars, Apache-2.0 licensed . Three functions, zero webhooks — build pricing plans in 30 minutes with usage tracking, credits, and feature controls.

### Additional Strong Open-Source Options

- **Laravel Cashier** — Official Laravel subscription billing integration for Stripe and Paddle with 2,531+ stars, MIT licensed .
- **Wallos** — Personal subscription tracker for managing recurring expenses, Docker-deployable with multi-currency and notification support .
- **Paymenter** — Hosting billing platform with 2,300+ stars, MIT licensed, 3 days since last commit .
- **Crater** — AI-driven invoicing workflows and working capital tools with 8,346+ stars .
- **Venn** — Modern self-hosted billing platform written in Clojure .

**Frameworks for building custom billing solutions**: Combine **Kill Bill** for enterprise-grade subscription management with plugin extensibility , **Lago** or **OpenMeter** for usage-based metering at scale , and **Hyperswitch** for payment orchestration across multiple processors . For AI/DevTool monetization, **OpenMeter** offers first-class LLM token cost tracking . For teams needing a built-in financial ledger with ASC 606 compliance, **Recurso** provides double-entry accounting out of the box . For simple invoicing without subscription complexity, **SolidInvoice** offers a modern Symfony-based platform .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Billing platforms must comply with financial regulations, tax laws (VAT, GST, sales tax), and PCI DSS requirements for payment card handling.
- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance. Financial ledgers and revenue recognition features require accounting expertise to configure correctly.

---

**Made for SaaS founders, finance teams, developers, and revenue operations professionals.**  
Let's make billing infrastructure more open, transparent, and flexible.
