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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Ramp](https://ramp.com/)** | Spend management platform with corporate cards, expense automation, and bill pay. **Free tier: $0/user/month** with 1.5% cashback, custom rules, and QuickBooks/Xero sync. **Plus: $15/user/month** adds AI coding, advanced approvals, and deeper ERP integrations—**plus an unquantified platform fee based on team size** . | Free: **$0/user/month**; Plus: **$15/user/month** + undisclosed platform fee  | **Free**: $0/user, 1.5% cashback, custom rules, basic accounting sync; eligibility requires ~$25K US business bank balance  |
| **[Brex](https://www.brex.com/)** | Corporate cards and spend management. **Essentials: $0/user/month** with global card acceptance, AI-powered rules, and Brex API access. **Premium: $12/user/month** adds multiple expense policies, dynamic approval chains, and multi-entity support. Enterprise: custom . | Essentials: **$0/user/month**; Premium: **$12/user/month**  | **Free (Essentials)**: $0/user, global cards, basic rules, API access; **30-day Premium trial** (one per lifetime)  |
| **[BILL Spend & Expense (Divvy)](https://www.bill.com/)** | Spend management with corporate cards and expense tracking. SourceForge lists starting price at **$45/user/month** (likely BILL's broader AP product); Divvy is positioned as free for spend management . | ~**$45/user/month** (BILL listing); Divvy free for core spend management  | Divvy free tier available; BILL paid plans for AP automation  |
| **[Stripe Issuing](https://stripe.com/issuing)** | Card-issuing API for developers. Create virtual or physical cards programmatically. **Virtual cards: $0.10 each** (US/UK/EU); **Physical cards: $3.50 each** . No monthly platform fee. | Virtual: **$0.10/card**; Physical: **$3.50/card**  | No free tier; pay-per-card issuance |
| **[Marqeta](https://www.marqeta.com/)** | Modern card issuing platform for developers. Powers card programs for fintechs and enterprises. API-first with extensive documentation. | Quote-only (enterprise contract) | No free tier; developer sandbox available |
| **[Airbase](https://www.airbase.com/)** | Spend management with corporate cards, bill pay, and expense tracking. **Custom pricing** (no public list rates) . | Quote-only (custom)  | No free tier; demo via sales |
| **[Spendesk](https://www.spendesk.com/)** | Spend management with corporate cards, approvals, and accounting sync. **No active user fees**—pricing based on platform fee + transaction fees. Help-center example: **€299/month with 100 transactions** (not a standard rate) . | Quote-only (platform fee + transaction fees); example €299/month  | No free tier; demo via sales |
| **[Pleo](https://www.pleo.io/)** | Spend management with company cards (plastic/virtual). Public tariffs plus user-dependent fees. **Legacy UK pricing** includes card fees, FX fees (2% on international POS), and ATM fees . | Quote-only (public tariffs + user fees)  | No free tier; demo via sales |
| **[Mercury](https://mercury.com/)** | Business banking with virtual and physical debit/credit cards, custom spend limits, merchant-locked cards, and duplicate subscription detection. **Mercury: $0/month**; Plus: **$29.90/month** (waived until Dec 31, 2026); Pro: **$299/month** . | Mercury: **$0/month**; Plus: **$29.90/month**; Pro: **$299/month**  | **Free (Mercury)**: $0/month banking + cards with spend controls; no monthly fees  |

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
