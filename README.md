# Awesome-Tag-Management-System

## Top Subscription Billing Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Recurring Billing, Subscription Lifecycle, Usage-Based Pricing, Invoicing, Dunning & Revenue Operations*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Subscription Billing**. These systems manage plan catalogs, recurring charges, usage metering, upgrades/downgrades, invoicing, payment recovery (dunning), and related revenue operations for SaaS, digital products, and subscription businesses.



**Examples** include Chargebee, Recurly, Maxio, Paddle, Stripe Billing, Zuora, Billsby, ChargeOver, Fusebill, and Sticky.io (the category leaders).



**Open-source emphasis**: Subscription billing has one of the strongest open-source ecosystems in fintech. **Kill Bill**, **Lago**, **Meteroid**, **FOSSBilling**, and related projects enable fully self-hosted recurring and usage-based billing. This section is heavily expanded with these alternatives.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Chargebee](https://www.chargebee.com/)** | Leading subscription management and monetization platform for mid-market SaaS, supporting complex plans, usage pricing, dunning, and revenue recognition workflows. | Free Starter plan ($0/mo up to $250k lifetime billing; then 0.75% overage); paid Performance plan starts at **$599/month** (billed annually, includes up to $100k/mo billing + 0.75% overage). | **Free forever** Starter plan for up to $250,000 in cumulative lifetime billing volume (0.75% overage fee applies thereafter); 14-day free trial on higher tiers. |
| **[Recurly](https://recurly.com/)** | Subscription billing platform optimized for high-volume subscriber management, retention, and intelligent payment recovery. | Starter plan starts at **$249/month** + 0.9% of revenue over $40,000/month (first $40k/month included at no extra charge). | **90-day free trial** for the Starter plan with full core subscription management and sandbox access (no free forever plan). |
| **[Maxio](https://www.maxio.com/)** | Billing and financial operations platform for B2B SaaS, combining subscription management with revenue metrics and reporting. | Build plan is **$0/month** (developer sandbox); paid Grow plan starts at **$599/month** (billed annually, for up to $100k monthly billing). | **Free forever** "Build" developer sandbox plan (unlimited testing time, full API/SDK access, no live billing); 30-day free trial for the Grow plan. |
| **[Paddle](https://www.paddle.com/)** | Merchant-of-record platform that handles payments, taxes, and compliance globally for digital products and SaaS. | Pay-as-you-go starting at **5% + $0.50 per successful transaction** (no monthly recurring platform subscription fee). | **Free forever** account with zero monthly platform fees (pay only on successful transactions; includes unlimited sandbox testing environment). |
| **[Stripe Billing](https://stripe.com/billing)** | Developer-first billing engine integrated with Stripe Payments, supporting subscriptions, usage-based pricing, and flexible models. | Starts at **0.7% of recurring billing volume** (in addition to standard Stripe payment processing fees of 2.9% + $0.30 per transaction). | **Free forever** access with zero monthly recurring base platform fees (includes first 100 million usage meter events/month free and unlimited test mode / sandbox environment). |
| **[Zuora](https://www.zuora.com/)** | Enterprise quote-to-cash and subscription billing system of record for large, multi-product revenue operations. | Enterprise contracts start at **~$50,000/year** (~$4,166/month, billed annually based on required modules, users, and billing volume). | **No free forever operational tier**; provides free developer sandbox environment access for API/integration testing and free Essentials course access via Zuora University. |
| **[Billsby](https://www.billsby.com/)** | Subscription billing platform focused on simplicity and rapid setup for growing subscription businesses. | Core plan starts at **$45/month** (+ 0.4% on revenue over $15,000/month); Pro plan starts at **$135/month** (+ 0.5% on revenue over $15,000/month). | **Free forever** testing plan ($0/month with unlimited setup time, full feature access, and no user limits before going live); 30-day free trial on paid plans. |
| **[ChargeOver](https://chargeover.com/)** | Recurring billing and invoicing solution for service and subscription companies needing flexible payment collection. | Flat-rate plan starts at **$229/month** (includes subscription management, customer portal, accounting sync, and 0% revenue cut). | **14-day free trial** with full sandbox and live testing features (no credit card required; no free forever plan). |
| **[Fusebill](https://www.fusebill.com/)** | Subscription billing and revenue management platform for mid-market and enterprise recurring revenue needs (now Stax Bill). | Growth plan starts at **$499/month** (billed annually, includes up to $85,000/month in billing volume). | **30-day free trial** / interactive demo sandbox available via sales consultation (no free forever plan). |
| **[Sticky.io](https://www.sticky.io/)** | Subscription and recurring commerce platform frequently used in e-commerce and direct-to-consumer models. | Entry tier starts at **$250/month** base fee + tiered revenue fee (1.0% on gross volume up to $500k/month, scaling down to 0.25% for >$10M/month). | **14-day free trial** / sandbox access upon request to test subscription flows and campaign configurations (no free forever plan). |



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
