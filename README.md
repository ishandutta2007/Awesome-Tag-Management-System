# Awesome-Tag-Management-System

## Top Tag Management Systems Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Client-Side & Server-Side Tag Management, Marketing Pixel Control, Consent-Aware Loading & Analytics Orchestration*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Tag Management Systems (TMS)**. These tools let marketers and developers deploy, manage, and version tracking tags, pixels, and scripts on websites and apps without constant code releases — while supporting consent, performance, and data-governance requirements.

**Examples** include Google Tag Manager, Adobe Experience Platform Tags, Tealium iQ, Ensighten, Commanders Act, Matomo Tag Manager, Piwik PRO Tag Manager, Qubit Tag Manager, Signal Tag Manager, and TagCommander (the category leaders).

**Open-source emphasis**: Fully featured open-source tag managers are fewer than commercial options, but **Matomo Tag Manager** is the leading production-ready open solution, complemented by emerging projects such as Scale8 and server-side open alternatives. This section is expanded with the strongest available open-source options.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Starting Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- |
| **[Google Tag Manager](https://tagmanager.google.com/)** | Free ($0/mo standard); GTM 360 starts at ~$150,000/year (~$12,500/mo) | **Free forever** with up to 3 workspaces per container and 200 KB container size limit. | The dominant tag management system for web and mobile, offering a visual interface, versioning, consent mode, and Google ecosystem integration. |
| **[Cloudflare Zaraz](https://www.cloudflare.com/application-services/products/zaraz/)** | $5/mo per 1M additional events (after free allocation) | **Free forever** up to 1,000,000 Zaraz events/month with all tools, rules, and privacy triggers included. | Edge-based server-side tag manager executed in Cloudflare Workers to eliminate client-side script overhead and improve page speed. |
| **[Stape.io](https://stape.io/)** | $20/mo ($17/mo billed annually) for up to 500k requests | **Free forever** up to 10,000 server requests/mo and 5 free sGTM containers; 7-day free trial on CAPI Gateways. | Turnkey server-side Google Tag Manager (sGTM) and Conversions API hosting infrastructure with custom loaders and global CDN. |
| **[Piwik PRO Tag Manager](https://piwik.pro/)** | €35/mo (~$38/mo) for Business plan (up to 2M actions/mo); Enterprise from €366/mo | **30-day free trial** of Business plan (full feature access up to 2M actions, 25-month data retention, no credit card required). | Privacy-centric tag management component of the Piwik PRO Analytics Suite, designed for strict GDPR/HIPAA compliance and consent workflows. |
| **[Matomo Cloud](https://matomo.org/pricing/)** | $26/mo (€29/mo) for up to 50,000 monthly hits | **21-day free trial** with full feature access up to 50k hits (no credit card required); 100% free forever if self-hosted (Matomo On-Premise). | Hosted tag manager bundled within the Matomo analytics platform providing full data ownership and cookieless tracking options. |
| **[RudderStack](https://www.rudderstack.com/pricing/)** | $265/mo for Growth plan (1M events/month) | **Free forever** up to 250,000 events/mo, 16+ SDK sources, and 200+ destinations; 30-day trial for Growth plan. | Warehouse-native tag and customer data orchestration platform with declarative event routing and governance. |
| **[Twilio Segment](https://segment.com/pricing/)** | $120/mo for Team plan (up to 10,000 MTUs) | **Free forever** up to 1,000 MTUs (Monthly Tracked Users), 2 sources, and unlimited destinations. | Customer data platform and tag routing system that consolidates marketing pixels and client scripts into a single API pipeline. |
| **[Tealium iQ](https://tealium.com/products/tealium-iq-tag-management/)** | ~$30,000–$75,000/year (~$2,500–$6,250/mo) depending on MUV volume | **14-day guided proof-of-concept** sandbox upon sales consultation (no public self-serve free plan). | Enterprise tag management platform with 1,300+ turnkey integrations, robust data-layer management, and consent controls. |
| **[Adobe Experience Platform Tags](https://experienceleague.adobe.com/docs/experience-platform/tags/home.html)** | Included with Adobe Experience Cloud (packages start at ~$30,000+/year) | **Included at $0 extra cost** for active Adobe Experience Cloud licensees; 30-day sandbox via enterprise account rep. | Adobe’s enterprise tag deployment engine (formerly Launch) integrated with Adobe Analytics, Target, and Experience Platform Edge Network. |
| **[Commanders Act](https://www.commandersact.com/)** | ~€18,000–€36,000/year (~€1,500–€3,000/mo) | **30-day staging pilot** via enterprise sales inquiry (no self-serve free plan). | European tag management and customer data platform (TagCommander) with built-in consent orchestration and server-side tracking. |
| **[CHEQ Ensighten](https://www.ensighten.com/)** | ~$75/mo (basic monitoring); Enterprise tag governance from ~$1,500/mo (~$18,000/year) | **14-day proof-of-concept trial** upon sales request (no public self-serve free plan). | Security-focused enterprise tag management and data governance platform providing client-side script containment and zero-trust protection. |
| **[Coveo (formerly Qubit)](https://www.coveo.com/)** | Enterprise packages starting at ~$30,000/year (~$2,500/mo) | **14-day free trial** with access to core platform indexing and personalization prototypes (no credit card required). | Personalization and experience tag management capabilities within the broader Coveo Relevance Cloud platform. |

## Open-Source GitHub Projects
- **[Matomo Tag Manager](https://github.com/matomo-org/tag-manager)**  
  Free, open-source tag manager that provides a simple, privacy-friendly way to manage and maintain third-party tags on websites. Fully integrated with the Matomo analytics platform and self-hostable.

- **[Scale8 Tag Manager & Analytics](https://github.com/scale8/scale8-tag-manager-and-analytics)**  
  Open-source tag manager and privacy-friendly analytics platform designed as a Google Tag Manager alternative. Supports custom platforms, SPA tracking, and GDPR/CCPA compliance.

- **[walkerOS](https://github.com/elbwalker/walkerOS)**  
  Open-source, developer-oriented tag manager that treats tagging as code, with declarative configuration and strong support for data sovereignty and server-side patterns.

- **[Tagmux (server-side tag management)](https://tagmux.com/)**  
  Emerging open-source server-side tag management / proxy solution aimed at recovering data blocked by ad blockers and improving first-party data collection.

- **[Custom container and data-layer libraries](https://github.com/)**  
  Open JavaScript libraries and patterns for implementing a lightweight data layer and tag-loading logic without a full commercial TMS.

- **[Consent-management open components](https://github.com/)**  
  Open CMP and consent-signal libraries that integrate with self-hosted tag managers to respect user choices before firing tags.

- **[Server-side tracking proxies and collectors](https://github.com/)**  
  Open projects that receive browser events and forward them to analytics or marketing endpoints, reducing client-side tag burden.

- **[GTM-compatible open templates and community containers](https://github.com/)**  
  Community-maintained templates, custom templates, and example containers that can be adapted for open or hybrid deployments.

- **[Privacy-first analytics + tagging stacks](https://github.com/)**  
  Combinations of Matomo, Plausible, Umami, or similar open analytics tools with lightweight tag-loading scripts.

- **[SPA and event-tracking open helpers](https://github.com/)**  
  Libraries that simplify history-change and virtual-pageview tracking for single-page applications when using open tag managers.

### Additional Strong Open-Source Options
- Self-hosted Matomo instances with the official Tag Manager plugin enabled.
- Open data-layer specifications and validation tools.
- Browser-extension and debugging helpers for inspecting tag behavior.
- Integration examples connecting open tag managers to open analytics, CDPs, or warehouse pipelines.
- Community documentation and migration guides from GTM to Matomo Tag Manager.

**Frameworks for building custom systems**: Deploy **Matomo Tag Manager** (or Scale8) as the core container, maintain a clean data layer, and enforce consent before any marketing or analytics tags fire. For higher resilience and privacy, add a server-side collection layer (open proxy or collector) that receives events and fans them out to destinations. This stack gives full ownership of tagging logic and data while remaining compatible with most marketing and analytics endpoints — at the cost of more hands-on maintenance than fully managed commercial TMS platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Tag management systems control third-party scripts that can affect privacy, performance, and security. Open-source solutions provide transparency and data ownership but still require careful configuration of consent, content-security policies, and ongoing tag audits. Always ensure tagging practices comply with applicable privacy regulations (GDPR, CCPA/CPRA, ePrivacy, etc.).
- Test thoroughly in staging before deploying tag changes to production.

---
**Made for marketing technologists, analytics engineers, and privacy-conscious teams seeking controllable tag infrastructure.**
Let's make tag management more transparent, privacy-respecting, and self-hostable.
