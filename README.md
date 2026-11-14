# Awesome-Digital-Wallet-Virtual-Corporate-Cards

## Top Digital Wallet & Virtual Corporate Cards Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Spend Management, Virtual Card Issuance & Expense Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Wallet & Virtual Corporate Cards**. These tools help businesses issue corporate cards, automate expense tracking, enforce spend policies, and manage budgets—covering everything from all-in-one spend management platforms to card-issuing APIs for developers.

**Examples** include Ramp, Brex, BILL Spend & Expense (Divvy), Stripe Issuing, Marqeta, Airbase, Spendesk, Pleo, Mercury, and Zoho Wallet (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted expense management, open-source spend workflows, and community-driven card program tooling—ideal for organizations seeking data sovereignty and avoiding per-seat SaaS fees. The open-source landscape is genuinely thin for **card issuance** (which requires banking partnerships and regulatory compliance), but functional for **expense management and approval workflows**: **FinPilot** provides enterprise-grade expense claims with multi-level approvals , and **Extend** offers a Python SDK for managing virtual cards programmatically .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global business spend management software market is valued at approximately $25–30 billion (growing at ~10–11% CAGR), while commercial and corporate card transaction volume exceeds $4–6 trillion globally ($25–48B in direct card processing revenues). The market structure is bifurcated: highly concentrated at the enterprise core where legacy banking networks (Visa, Mastercard, Amex, Chase) and incumbent ERP/T&E giants dominate, but moderately fragmented in the mid-market and SME modern fintech space where modern software-led card disruptors compete and actively consolidate via M&A.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
|---------|-----------------------------------|-------------|-------------------------|--------------------------|
| **[Stripe Issuing](https://stripe.com/issuing)** | **~$91.5B–$159B valuation** / ~$6.8B net revenue | Developer-first card issuance API allowing platforms and businesses to create, distribute, and programmatically manage physical and virtual card programs. | **$0.10/virtual card**; **$3.50/physical card** (pay-per-card issuance, $0 platform fee) | **Free test environment**: Unlimited API testing and card simulation in test mode with zero issuance fees; no live-mode free card allotment |
| **[Ramp](https://ramp.com/)** | **~$60B valuation** / ~$2B+ ARR | All-in-one spend management platform combining corporate cards, automated expense reconciliation, accounts payable, and procurement workflows. | **$0/user/month** (Free tier); Plus tier starts at **$15/user/month** (+ team platform fee) | **Free forever plan**: $0/user for unlimited physical/virtual corporate cards, 1.5% cashback, basic rules, and accounting sync (requires ~$25K US business bank balance) |
| **[Mercury](https://mercury.com/)** | **~$5.2B valuation** / ~$1B+ revenue | Full-stack digital business banking and fintech platform featuring built-in virtual/physical debit and credit cards, custom spend controls, and API access. | **$0/month** (Standard plan); Mercury Plus at **$29.90/month**; Mercury Pro at **$299/month** | **Free forever plan**: $0/month for checking & savings accounts, unlimited physical and virtual cards, custom employee spend controls, and zero account minimums |
| **[Brex](https://www.brex.com/)** | **$5.15B acquisition** (Capital One) / ~$500M revenue | Corporate credit cards and unified spend management engine providing multi-currency global expense management, dynamic limits, and travel booking. | **$0/user/month** (Essentials plan); Premium starts at **$12/user/month** | **Free forever plan**: $0/user for Essentials (global corporate cards, automated receipts, basic spend limits, API access); **30-day free trial** for Premium tier |
| **[Pleo](https://www.pleo.io/)** | **~$4.7B valuation** / ~$140M–$150M revenue | European smart corporate card and spend management solution offering automated receipt matching, mileage claims, and multi-tier approval workflows. | **£8 / €8 per user/month** (Start plan, billed monthly); Build plan starts at **£14 / €14 per user/month** | **21-day free trial**: Full access to card issuing, receipt capture, accounting sync, and approval workflows across Start and Build plans; no permanent free tier |
| **[BILL Spend & Expense (Divvy)](https://www.bill.com/)** | **~$4.2B market cap** (NYSE: BILL) / ~$1.65B revenue | Integrated spend management and corporate card solution enabling proactive budget allocation, smart virtual cards, and automatic expense categorization. | **$0/user/month** (core software free, monetized via card interchange); AP/AR add-ons start at **$45/user/month** | **Free forever plan**: $0/month and $0/user for unlimited virtual & physical cards, real-time budgeting, receipt scanning, and reimbursements (subject to credit approval) |
| **[Marqeta](https://www.marqeta.com/)** | **~$1.9B market cap** (NASDAQ: MQ) / ~$690M revenue | Cloud-native, open-API modern card issuing and transaction processing engine powering custom fintech, embedded finance, and on-demand corporate card infrastructure. | **Custom enterprise contract** (platform minimums + transaction processing fees; interchange-sharing models) | **Free forever public sandbox**: Unlimited free developer sandbox access for API testing, simulated authorizations, and virtual card lifecycle experiments; no free production tier |
| **[Spendesk](https://www.spendesk.com/)** | **~$1.1B valuation** / ~$52M+ ARR | 7-in-1 spend management platform combining company physical/virtual cards, invoice approval automation, budget tracking, and automated pre-accounting. | **£199/month (~€230–€299/mo)** starting platform fee (Starter/Essential tier with 100 transactions) | **No free tier**: Requires booking a custom guided product demo with the sales team; temporary sandbox environment provided upon sales qualification |
| **[Airbase](https://www.airbase.com/)** | **$325M acquisition** (Paylocity) / ~$600M prior peak val. | Procure-to-pay and spend management suite integrating guided procurement, AP invoice automation, corporate cards, and real-time ERP synchronization. | **~$1,250–$2,500/month** (Standard plan billed annually at ~$15,000–$30,000/yr minimum quote) | **No free tier**: Self-guided interactive product tours available online; live enterprise trial environments require scheduling a demo with sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FinPilot (Cajachica)](https://github.com/arnx-global/cajachica)** | [![Stars](https://img.shields.io/github/stars/arnx-global/cajachica?style=social&color=white)](https://github.com/arnx-global/cajachica/stargazers) | **The most complete open-source expense management and approval workflow platform.** Enterprise-grade with **smart claim submission, receipt OCR, multi-currency support, and configurable multi-level approval chains** based on amount thresholds. Role-based access for Employee, Manager, HR, and Finance. Real-time notifications, bulk operations, interactive dashboards, and **audit trails for GDPR compliance**. React/TypeScript frontend + Node.js/Express/PostgreSQL backend. JWT authentication with bcrypt password hashing. **Best for teams wanting self-hosted expense approval workflows** without per-seat SaaS fees . |
| **[Extend Python SDK](https://pypi.org/project/paywithextend/)** | — | **Python client for the Extend API for managing virtual cards programmatically.** Create and manage virtual cards, handle recurring card operations, track transactions, and integrate expense management into custom applications. **Not a self-hosted platform**—a developer SDK for the Extend commercial service . |

**Frameworks for building custom systems**: The open-source path to corporate cards is **limited by regulatory reality**—card issuance requires banking partnerships and compliance infrastructure that no open-source project provides. The practical approach is: use **Stripe Issuing** (pay-per-card, no platform fee) or **Marqeta** for card issuance, **FinPilot** for self-hosted expense approval workflows, and **Mercury** for free business banking with virtual cards. **FinPilot provides the expense management layer** (claims, approvals, audit trails) that can complement a commercial card program—but it is **not a card issuer** .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Corporate card and spend management platforms handle payment credentials and financial data; enforce PCI DSS compliance, strong authentication, and least-privilege card controls. **Virtual cards should have merchant locks and spend limits** to reduce fraud risk.
- **Pricing transparency varies dramatically and platform fees hide in the fine print.** Ramp's Plus tier has an **unquantified platform fee based on team size** —the published $15/user rate is a floor, not a final price . Brex Premium is straightforward at $12/user with no hidden platform fee . **BILL charges per-user for AP** (the "approver tax" where a manager who logs in twice a month costs the same as a full-time AP clerk) . Spendesk charges platform + transaction fees with **no active user fees** . **Open-source card issuance does not exist**—Stripe Issuing charges $0.10/virtual card with no monthly fee, making it the most accessible programmatic option . **FinPilot provides expense approval workflows but not card issuance**—validate its audit trail and GDPR compliance against your regulatory requirements before production use.

---

**Made for finance teams, operations managers, and developers building spend management infrastructure.**  
Let's make digital wallets and virtual corporate cards more open, transparent, and cost-predictable.
