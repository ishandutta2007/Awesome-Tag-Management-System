# Awesome-Tag-Management-System

# Top Subscription Billing Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Recurring Billing, Subscription Lifecycle, Usage-Based Pricing, Invoicing, Dunning & Revenue Operations*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Subscription Billing**. These systems manage plan catalogs, recurring charges, usage metering, upgrades/downgrades, invoicing, payment recovery (dunning), and related revenue operations for SaaS, digital products, and subscription businesses.

**Examples** include Chargebee, Recurly, Maxio, Paddle, Stripe Billing, Zuora, Billsby, ChargeOver, Fusebill, and Sticky.io (the category leaders).

**Open-source emphasis**: Subscription billing has one of the strongest open-source ecosystems in fintech. **Kill Bill**, **Lago**, **Meteroid**, **FOSSBilling**, and related projects enable fully self-hosted recurring and usage-based billing. This section is heavily expanded with these alternatives.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Chargebee](https://www.chargebee.com/)**  
  Leading subscription management and monetization platform for mid-market SaaS, supporting complex plans, usage pricing, dunning, and revenue recognition workflows.

- **[Recurly](https://recurly.com/)**  
  Subscription billing platform optimized for high-volume subscriber management, retention, and intelligent payment recovery.

- **[Maxio](https://www.maxio.com/)**  
  Billing and financial operations platform for B2B SaaS, combining subscription management with revenue metrics and reporting.

- **[Paddle](https://www.paddle.com/)**  
  Merchant-of-record platform that handles payments, taxes, and compliance globally for digital products and SaaS.

- **[Stripe Billing](https://stripe.com/billing)**  
  Developer-first billing engine integrated with Stripe Payments, supporting subscriptions, usage-based pricing, and flexible models.

- **[Zuora](https://www.zuora.com/)**  
  Enterprise quote-to-cash and subscription billing system of record for large, multi-product revenue operations.

- **[Billsby](https://www.billsby.com/)**  
  Subscription billing platform focused on simplicity and rapid setup for growing subscription businesses.

- **[ChargeOver](https://chargeover.com/)**  
  Recurring billing and invoicing solution for service and subscription companies needing flexible payment collection.

- **[Fusebill](https://www.fusebill.com/)**  
  Subscription billing and revenue management platform for mid-market and enterprise recurring revenue needs.

- **[Sticky.io](https://www.sticky.io/)**  
  Subscription and recurring commerce platform frequently used in e-commerce and direct-to-consumer models.

## Open-Source GitHub Projects
- **[Kill Bill](https://github.com/killbill/killbill)**  
  The leading open-source subscription billing and payments platform with over a decade of production use. Supports complex subscription models, payments, invoicing, plugins, and high scalability. Apache 2.0 licensed.

- **[Lago](https://github.com/getlago/lago)**  
  Open-source usage-based billing and metering platform designed as a direct alternative to Chargebee, Recurly, and Stripe Billing. Handles plans, usage events, invoicing, and integrates with external payment processors.

- **[Meteroid](https://github.com/meteroid-oss/meteroid)**  
  Open-source pricing and billing infrastructure for product-led SaaS, covering subscription management, usage-based billing, invoicing, quotes (CPQ), and revenue analytics.

- **[FOSSBilling](https://github.com/FOSSBilling)**  
  Free, open-source billing and client management system popular with hosting providers and adaptable for software licensing and subscription services.

- **[Flexprice](https://github.com/flexprice/flexprice)**  
  Open-source billing platform focused on flexible usage metering, credit management, and subscription billing with full developer control.

- **[Servicebot](https://github.com/service-bot/servicebot)**  
  Open-source subscription management and billing automation system that links service templates to Stripe and manages the full subscription lifecycle.

- **[Custom metering and event-ingestion pipelines](https://github.com/)**  
  Open components for high-throughput usage event collection and aggregation that feed billing engines.

- **[Invoice and PDF generation libraries](https://github.com/)**  
  Open tools commonly paired with billing cores to produce professional invoices and credit notes.

- **[Dunning and smart-retry open workflows](https://github.com/)**  
  Scripts and services implementing intelligent payment recovery on top of open billing platforms.

- **[Self-hosted subscription trackers and spend tools](https://github.com/)**  
  Lighter open projects for tracking recurring payments and internal SaaS spend.

### Additional Strong Open-Source Options
- Integration of Kill Bill or Lago with open CRM/ERP systems (Odoo, ERPNext) for end-to-end customer and billing flows.
- Stripe, Adyen, or other payment-processor SDKs used as the collection layer under an open billing core.
- Open revenue analytics, cohort analysis, and MRR/ARR dashboards built on billing event streams.
- Feature-flag and entitlement services that enforce plan limits inside product code.
- Containerized and Kubernetes-native deployment patterns for the above billing stacks.

**Frameworks for building custom systems**: Deploy **Kill Bill** or **Lago** / **Meteroid** as the core subscription and usage-billing engine, connect a payment processor (Stripe, etc.) for collection, and expose customer portals and invoices through open or custom front-ends. Store all billing events in your own database for complete auditability and analytics. This approach delivers full control over pricing logic, data ownership, and cost structure — ideal for companies with engineering capacity or strict data-residency needs — while commercial platforms remain attractive for rapid launch, pre-built tax/MoR features, and managed operations.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Subscription billing systems handle payments, customer funds, and financial records. Open-source solutions provide transparency and ownership but still require careful security, PCI considerations (when handling card data), tax compliance, and rigorous testing of rating and invoicing logic before production use.
- Always ensure billing calculations, refunds, and dunning practices comply with applicable consumer protection and financial regulations.

---
**Made for SaaS founders, billing engineers, and revenue teams seeking flexible, self-hostable subscription infrastructure.**
Let's make recurring revenue systems more open, controllable, and developer-friendly.
