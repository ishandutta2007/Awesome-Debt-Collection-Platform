# Awesome-Debt-Collection-Platform

## Top Debt Collection Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Collections Workflow Automation, Payment Negotiation & Compliance Management*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Debt Collection**. These tools help collection agencies, lenders, and financial institutions automate recovery workflows, manage payment arrangements, and maintain compliance.



**Examples** include TrueAccord, Collect!, Katabat, Quantrax, Finvi, Centrex, Casper365, Indebted, Credgenics, Receeve, CollectAI, CGI Collections, Experian Tallyman, Qualco, Pair Finance, InterProse ACE, CollectOne, CollBox, Collenda, and Paylink Solutions (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom collection workflows, and transparent debt data — ideal for agencies that need full control over their recovery operations without per-account SaaS fees or vendor lock-in.



Contributions welcome! Open an Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[TrueAccord](https://www.trueaccord.com/)**  

  Digital-first debt collection platform using machine learning for personalized recovery journeys. Provides digital channel engagement, payment negotiation, and compliance automation.



- **[Collect!](https://www.collect.org/)**  

  Collection agency software for managing accounts, payments, and correspondence. Provides workflow automation, payment processing, and reporting.



- **[Katabat](https://katabat.com/)**  

  Debt collection and recovery platform with predictive analytics and omni-channel engagement.



- **[Quantrax](https://quantrax.com/)**  

  AI-powered collection and recovery platform for financial institutions. Provides decisioning, analytics, and workflow automation.



- **[Finvi](https://finvi.com/)**  

  Collections and recovery platform for healthcare, financial services, and government. Provides workflow automation, payment portals, and compliance tools.



- **[Centrex](https://centrexsoftware.com/)**  

  Debt collection software for agencies. Provides case management, payment processing, and reporting.



- **[Casper365](https://casper365.com/)**  

  Microsoft Dynamics 365-based debt collection and credit management platform.



- **[Indebted](https://indebted.co/)**  

  AI-powered debt collection platform using behavioral analytics for recovery optimization.



- **[Credgenics](https://credgenics.com/)**  

  Debt collection and resolution platform for banks and NBFCs. Provides AI-driven recovery strategies, digital lending, and legal workflows.



- **[Receeve](https://receeve.com/)**  

  Collections and recovery platform for fintechs and lenders. Provides intelligent automation and payment solutions.



- **[CollectAI](https://collect.ai/)**  

  AI-driven collections platform for digital receivables management. Provides intelligent dunning and payment solutions.



- **[CGI Collections](https://www.cgi.com/)**  

  Enterprise collections and recovery solution. Provides workflow management, payment processing, and compliance.



- **[Experian Tallyman](https://www.experian.com/)**  

  Collections and recovery platform from Experian. Provides decisioning, segmentation, and workflow automation.



- **[Qualco](https://qualco.com/)**  

  Software and analytics for credit and debt management. Provides collection platforms and recovery analytics.



- **[Pair Finance](https://pairfinance.com/)**  

  Digital debt collection platform for B2C receivables. Provides AI-driven recovery and payment solutions.



- **[InterProse ACE](https://interprose.com/)**  

  Collections and recovery platform. Provides workflow automation, payment processing, and compliance tools.



- **[CollectOne](https://collectone.com/)**  

  Collection software for agencies and creditors. Provides case management, payment processing, and reporting.



- **[CollBox](https://collbox.co/)**  

  Debt collection solution for small businesses. Connects businesses with collection agencies and provides workflow tools.



- **[Collenda](https://collenda.com/)**  

  Credit management and collections software. Provides collections workflow, payment processing, and reporting.



- **[Paylink Solutions](https://paylinksolutions.co.uk/)**  

  Digital debt collection and payment platform. Provides payment portals, IVAs, and debt management solutions.



## Open-Source GitHub Projects



### Collection Platforms & Workflows



- **[OpenAR Collective](https://www.opensourceforu.com/2026/08/openar-collective-foundation-debut/)**  

  **Non-profit foundation creating a vendor-neutral, Apache-licensed collections platform for the ARM industry.** Launched August 2026 under founder Rob Grafrath. **Production-grade collections platform** distributed under Apache License 2.0. Designed to ensure small agencies and enterprises have equal access to enterprise-grade technology. **Self-hosted**, customizable workflows, publicly hosted codebase . **Apache-2.0**.



- **[Darj Smart Collection System](https://github.com/mym1359/darj-smart-collection)**  

  **AI-powered debt collection system for banking environments.** **Behavioral Analysis** predicts repayment likelihood using machine learning. **Smart Recommendations** suggest optimal actions (call, warning, legal) based on customer profile. **Automated Reminders** track promises and trigger follow-ups. **Action Logging** records all interactions for audit. **Branch & User Dashboards** visualize collection performance. **Letter Generation** automates official warnings. **Tech stack**: Streamlit + FastAPI + SQLite, XGBoost-based ML model. **Expandable** for PostgreSQL migration and external banking APIs .



- **[NADI (wahfix)](https://packagist.org/packages/wahfix/nadi)**  

  **Laravel-based loan and collection management system.** **16 Eloquent models**, **12 service classes** including `CollectionService` for collection dashboards and activities. **PaymentAllocationService** handles payment allocation (fines → interest → principal). **PaymentReversalService** for symmetric reversal and balance restoration. **Role-based access** (ADMIN, LO, LC, CASHIER, COLLATERAL OFFICER, IDENTITY VERIFIER, AUDITOR). **LoanStatusService** with 11-state machine. **Audit logging** included .



- **[BrassLedger](https://github.com/rhamenator/BrassLedger)**  

  **Open-source cross-platform accounting and business management system with receivables and cash application.** **GPL-3.0 licensed**. **Receivables support** for customer invoices, statements, balances, and cash application. **General ledger** workspaces for journal activity, balances, and month-end review. **Payables** for vendor bills, approvals, and disbursement preparation. Cross-platform .NET application with installers for Windows, macOS, and Linux. Current prerelease `v0.1.0-pre.6` .



### Receivables & Follow-Up



- **[Orvaket](https://github.com/Akam1123/orvaket)**  

  **Free, local-first accounts receivable follow-up workspace for small B2B service firms.** **Import QuickBooks/Xero AR CSV exports**. Review open invoices and record **reason, owner, next action, and promise date**. Filter board for overdue work. Prepare **contextual follow-up email drafts** for human review. **Export CSV or encrypted JSON backup**. **Local-first**—no account, no cloud sync, no server-side backup. Optionally encrypt local saves with **AES-256-GCM**. Open `index.html` to run offline .



- **[api-consulta-v2](https://github.com/acthiago/api-consulta-v2)**  

  **Brazilian debt and boleto management API.** **OAuth2 + JWT authentication**. **Client debt queries** by CPF. **Boleto generation** with multiple debts in one boleto. **Installment support** (max 5 installments, min R$ 50 per installment). **Automatic interest and fines** based on time. **Debt status lifecycle**: Active → Overdue → Delinquent. **Boleto cancellation** restores debts. **Prometheus metrics**, structured logging, and audit trails. **Tech stack**: Python 3.11+, FastAPI, MongoDB Atlas .



### Specialized Collection Systems



- **[FSSP-Tracker](https://github.com/Serx17/fsps-tracker-mvp)**  

  **MVP system for automatic tracking of enforcement proceedings (FSSP) with CRM and bot integration.** **Low-code solution** for banks and microfinance organizations. **Business value**: 70% reduction in operational costs for lawyers. **Features**: FSSP status checks via aggregators; **CRM integration** (Bitrix24, AmoCRM) via webhooks; **bot platform notifications** (Aimylogic, ChatFuel); background processing. **Compliance**: 152-FZ compliance with data minimization, log anonymization, and secure storage. **Tech stack**: Python 3.10+, FastAPI, SQLite (PostgreSQL-ready) .



- **[Préstamos Gota a Gota](https://github.com/ChrithianC5Develop/prestamos-gota-a-gota)**  

  **Professional loan management system with collection and notification features.** **Collection system with routes** for field collectors. **Multi-channel notifications**. **User roles** (admin, collector). **Loan creation** with automatic payment schedule generation. **Daily/monthly reports** by collector. **Tech stack**: FastAPI, MySQL, JWT Auth, Streamlit frontend, Kotlin Multiplatform for mobile/desktop. **MIT licensed** .



- **[GT-DAYN](https://discourse.aosus.org/t/topic/5277/5)**  

  **Open-source debt and expense management tool designed for Arabic users.** **Fully offline**—all data stays on device. **PWA support** for mobile installation. **Two-way debt tracking** (owed to me / I owe) with net statistics. **Partial payments** and future payment scheduling. **Person profiles** with per-person statistics. **Monthly budget** with income and expense categories. **Privacy-focused**: local data, app lock, encrypted backups. **27 currencies supported** .



### Additional Strong Open-Source Options



- **Enterprise Loan/Collection**: **Apache Fineract** (loan management with delinquency buckets, charge-off, asset sales) , **Frappe Lending** (loan lifecycle with collection management module) .

- **AI Collection**: **Darj Smart Collection** (XGBoost behavioral analysis), **DebtGPT** (8B-parameter negotiation model, research) .

- **AR Follow-Up**: **Orvaket** (local-first, encrypted), **BrassLedger** (receivables + cash application) .

- **Debt Settlement**: Multiple GitHub projects under `debt-settlement` topic for optimizing peer-to-peer transaction settlement .



**Frameworks for building custom systems**: Combine **OpenAR Collective** for the vendor-neutral collections platform foundation (once available), **Darj Smart Collection** for AI-powered behavioral analysis and action recommendations, **NADI** or **Frappe Lending** for loan lifecycle and payment allocation, **Orvaket** for AR follow-up workflows, and **BrassLedger** for receivables and cash application. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Debt collection platforms handle sensitive financial and personal data; ensure compliance with FDCPA, GDPR, and applicable regional collection regulations.

- **Open-source reality**: The open-source ecosystem for debt collection is **emerging but fragmented**. **OpenAR Collective** (launched August 2026) is the most significant initiative—a non-profit foundation building a vendor-neutral, Apache-licensed collections platform specifically for the ARM industry . **Darj Smart Collection** provides AI-powered behavioral analysis for banking collections . **NADI** and **Frappe Lending** offer loan lifecycle and payment allocation foundations . **Orvaket** delivers a local-first AR follow-up workspace . However, **commercial platforms** (TrueAccord, Collect!, Finvi, Credgenics) provide **integrated omni-channel engagement, compliance automation, and enterprise-scale recovery optimization** that open-source alternatives cannot yet match. The open-source path is most viable for **small agencies, AR follow-up, or organizations with strong engineering capacity** seeking full data ownership.



---



**Made for collection agency operators, recovery managers, AR specialists, and financial institution technologists.**

Let's make debt collection more open, transparent, and compliant.
