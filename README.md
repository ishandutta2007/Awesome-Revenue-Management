# Awesome-Revenue-Management

## Top Revenue Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Subscription Billing, Usage Metering & Revenue Recognition*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Revenue Management**. These tools enable organizations to manage subscription lifecycles, meter usage-based pricing, generate invoices, and recognize revenue in compliance with accounting standards—turning billing complexity into a controlled, auditable revenue engine.



**Examples** include Workday Revenue Management, Zuora, Stripe Billing, Chargebee, Maxio, Recurly, BillingPlatform, RightRev, Aptitude Software, and Conga Revenue Management (the category leaders).



**Open-source emphasis**: Revenue Management is a domain where open-source tooling is **maturing rapidly**. The strongest active projects are **Kill Bill** for comprehensive subscription billing (in production since 2010), **Lago** for usage-based metering and billing, and **OpenMeter** for real-time usage metering. Revenue recognition-specific open-source options remain limited—**eRev** is the only notable project addressing ASC 606/IFRS 15 compliance. Organizations needing full revenue recognition automation should evaluate commercial platforms or plan for custom development.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Revenue Management](https://www.workday.com/)**  

  Revenue recognition and management within Workday's financial suite, automating ASC 606/IFRS 15 compliance with multi-element arrangements, contract modifications, and real-time revenue reporting integrated with billing and ERP.



- **[Zuora](https://www.zuora.com/)**  

  Subscription management and revenue recognition platform for recurring revenue businesses; covers billing, collections, revenue recognition (RevPro), and analytics for subscription economy companies.



- **[Stripe Billing](https://stripe.com/billing)**  

  Subscription and usage-based billing infrastructure from Stripe; handles recurring payments, invoicing, proration, and revenue reporting with deep integration into Stripe's payment ecosystem.



- **[Chargebee](https://www.chargebee.com/)**  

  Subscription management and billing platform with revenue recognition (Chargebee RevRec), supporting complex billing models, dunning, and integration with major payment gateways and accounting systems.



- **[Maxio](https://www.maxio.com/)**  

  Financial operations platform for B2B SaaS combining subscription billing (Chargify) and revenue recognition (SaaSOptics) in one system.



- **[Recurly](https://recurly.com/)**  

  Subscription management and billing platform with revenue recognition capabilities, focused on reducing churn and automating recurring billing workflows.



- **[BillingPlatform](https://billingplatform.com/)**  

  Enterprise billing and monetization platform with revenue recognition, supporting complex pricing models and integration with ERP and CRM systems.



- **[RightRev](https://rightrev.com/)**  

  Revenue recognition automation platform for ASC 606/IFRS 15 compliance, integrating with billing systems and ERPs to streamline the close process.



- **[Aptitude Software](https://www.aptitudesoftware.com/)**  

  Financial management and revenue recognition platform with automated compliance for ASC 606/IFRS 15, subscription management, and financial control capabilities.



- **[Conga Revenue Management](https://conga.com/)**  

  Revenue lifecycle management within Conga's commercial operations suite, covering CPQ, billing, and revenue recognition for complex sales models.



## Open-Source GitHub Projects



- **[Kill Bill](https://github.com/killbill/killbill)**  

  The most mature open-source subscription billing and payments platform (Apache 2.0), in production since 2010; handles catalogs and pricing, subscriptions, usage metering, invoicing, payments across gateways, credits, tax, and dunning . Highly modular—you can disable or replace components. Runs on your own infrastructure with no vendor lock-in. An enterprise version (Aviate) adds support and advanced features. **The closest open-source equivalent to Zuora/Chargebee for subscription billing**, though revenue recognition is not a native module.



- **[Lago](https://github.com/getlago/lago)**  

  Open-source metering and usage-based billing platform (AGPLv3) positioned as an alternative to Stripe Billing, Chargebee, and Recurly for usage-based and hybrid pricing; features event-based usage metering, subscription management, price plans (pay-as-you-go, tiered, package), coupons, add-ons, invoicing, and prepaid credits . Deployable via Docker Compose or Railway; API-first with GraphQL support. **Strong for usage-based billing and metering**, but not a revenue recognition solution.



- **[OpenMeter](https://github.com/openmeterio/openmeter)**  

  Open-source monetization infrastructure for AI, API, and usage-based products (beta releases, but metering engine production-proven at billions of events); turns high-volume events into real-time usage, models plans and pricing, controls feature access and usage limits, and bills usage . API-first and composable—can own the full usage-to-invoice path or just the metering layer. **Best for real-time usage metering and access enforcement**, not revenue recognition.



- **[Flexprice](https://github.com/flexprice/flexprice)**  

  Open-source usage-based pricing and billing for developers (AGPL-3.0, ~6,800 GitHub stars); features real-time usage metering, credits and top-ups, feature access control, and a no-code UI; cloud or self-hosted deployment . **Usage metering and pricing-focused**, similar to OpenMeter in scope.



- **[UniBee](https://github.com/UniBee-Billing/unibee)**  

  Open-source universal billing software for SaaS businesses (AGPLv3); features subscription management, invoicing, billable metrics, product/plan management, webhooks, user management, reports, transaction management, and discounts . Positioned as an open-source alternative to Recurly, Chargebee, and Paddle. Docker-deployable. **Subscription billing-focused**, with a hosted cloud option.



- **[eRev](https://github.com/ChipmunkRPA/eRev)**  

  The only notable open-source **revenue recognition system** found; a pure Python package for ASC 606 and IFRS 15 compliance with a lightweight SQLite database and 13 buttons for operations . Designed for accountants who need local, secure revenue recognition without cloud dependency; Windows EFS encryption protects the database. Free tier covers full ASC 606/IFRS 15 functions, with premium features available for a fee. **Revenue recognition-specific**—does not handle billing or metering.



### Additional Strong Open-Source Options



- **Paymenter** — Open-source billing platform tailored for hosting companies (MIT); automates subscriptions, invoicing, and client management for hosting providers .

- **FOSSBilling** — Free, open-source billing and client management system (Apache 2.0, beta); supports invoicing, payments, and client communication for hosting and digital services .

- **BillKu** — Self-hosted billing and business management platform (NestJS/Next.js) with invoicing, recurring invoices, CRM, POS, HR, and financial reporting; Docker-ready and offline-capable .



**Frameworks for building custom systems**: Combine **Kill Bill** for mature subscription billing and payments, **Lago** or **OpenMeter** for usage-based metering and hybrid pricing, and **eRev** for ASC 606/IFRS 15 revenue recognition in a self-hosted revenue management stack. No single open-source platform covers the full revenue lifecycle (metering → billing → recognition) end-to-end; integration and custom development are required.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Revenue management platforms handling billing and financial data must comply with applicable accounting standards (ASC 606, IFRS 15), tax regulations, and payment card industry requirements (PCI DSS); audit trails and revenue recognition documentation are critical for financial reporting.

- **Open-source revenue management is fragmented**—Kill Bill and Lago cover billing and metering, while eRev addresses revenue recognition. No open-source platform provides the full end-to-end revenue lifecycle with native ASC 606/IFRS 15 automation. Organizations requiring complete revenue recognition should plan for commercial platforms like Zuora RevPro, RightRev, or Aptitude.

- Verify license terms for commercial use; Kill Bill uses Apache 2.0 , Lago uses AGPLv3 , OpenMeter is open-source , Flexprice uses AGPL-3.0 , and eRev has a free tier with premium options .



---



**Made for revenue operations teams, billing engineers, controllers, and finance systems architects.**  

Let's make revenue management more open, meterable, and recognition-ready.
