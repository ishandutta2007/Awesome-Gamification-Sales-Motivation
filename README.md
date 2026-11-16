# Awesome-Gamification-Sales-Motivation

## Top Gamification & Sales Motivation Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Sales Contests, Leaderboards & Self-Hosted Motivation Engines*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Gamification & Sales Motivation**. These tools help revenue teams drive performance through competitions, real-time leaderboards, and recognition—covering everything from AI-powered seller activation platforms to open-source gamification engines that bring points, badges, and challenges to your own applications.

**Examples** include Ambition, LevelEleven, Spinify, Hoopla, Centrical, SmartWinnr, GAME (Goals And Motivation Engine), and Gami.Fied (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted gamification, open-source motivation engines, and community-driven sales contests—ideal for organizations seeking data sovereignty and avoiding per-user SaaS pricing that compounds across sales teams. The open-source landscape is genuinely functional: **GAME** provides a FastAPI/PostgreSQL engine for goals and rewards , **Gami.Fied** offers a self-hostable gamification platform with a TypeScript SDK for events, XP, leaderboards, and achievements , and **Odoo's CRM Gamification** module brings goal definitions and challenges directly into an existing ERP .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Ambition](https://ambition.com/)** | **AI-powered seller activation platform that goes beyond traditional gamification.** **Bracket Competitions (March 2026)** pair head-to-head matchups with coaching, accountability, and org-wide visibility—tied to high-value behaviors like meetings set or pipeline created, not just activity for activity's sake . CEO Jared Houghton states "gamification as we know it is broken"—Ambition embeds competition inside a broader execution system. | Quote-only | No free tier; demo via sales |
| **[LevelEleven (Ascent Cloud)](https://www.ascentcloud.io/)** | **Sales motivation and coaching platform.** **Brackets (March 2026)**: tournament-style, head-to-head competitions (4–64 users) built natively inside LevelEleven, powered by CRM data with **no custom development** . Managers spin up a tournament in minutes; reps see "You vs. one rival" rather than a distant leaderboard rank . | Quote-only | No free tier; demo via sales |
| **[Spinify](https://spinify.com/)** | **Sales gamification with real-time leaderboards and TV displays.** **Per-user pricing**; administrators require additional licenses to create content, but **Fans have free access to view competitions** without participating . **No hidden fees**—pricing includes all features, integrations, and support . | Quote-only (per-user, monthly available; no long-term contracts required) | No free tier; demo via sales |
| **[Hoopla](https://hoopla.net/)** | **Gamification via dynamic TV broadcasts and CRM-connected leaderboards.** Connects directly to Salesforce, HubSpot, and other CRMs to broadcast live metrics—YTD revenue, pipeline, meetings booked, and live call battles . **Newsflashes** trigger on closed deals or quota hits, pushing recognition to Slack and Microsoft Teams . **30-day fully supported free trial** for all sales team members . | Quote-only | **30-day free trial** (no-cost, fully supported) |
| **[Centrical](https://centrical.com/)** | **AI performance platform for retail and sales teams.** Gamified goals, peer challenges, and store-level competitions paired with microlearning and coaching. **Documented outcomes**: 27% increase in protection plan attach rates, 32% boost in TV sales, and 19% increase in sales for highly active users . | Quote-only | No free tier; demo via sales |
| **[SmartWinnr](https://smartwinnr.com/)** | **Sales excellence platform combining AI roleplays, gamified microlearning, and sales contests.** Gartner Peer Insights: annual revenue **$50M–$250M**, 51–200 employees . Customers report scaling across **25 countries in 12 languages** with fast ROI . | Quote-only | No free tier; demo via sales |
| **[Arcade](https://www.arcade.co/)** | **AI-powered sales training and gamification.** Turns top performers into coaches and managers into multipliers—peer-to-peer learning at scale. **150,000+ hours of sales roleplay completed**, **40%+ improved new hire retention** . Positioned for retail and field sales enablement. | Quote-only | No free tier; demo via sales |
| **[Gametize](https://gametize.com/)** | **Gamification platform for community engagement, learning, and sales training.** Create games in **5 minutes with zero coding**—quizzes, predictions, photo challenges, and more. Points, badges, and rewards awarded for every interaction . | Free account available | **Free account** available for project administrators |
| **[Playvox](https://www.playvox.com/)** | **Quality management with gamification for support teams.** Points, rewards, and badges based on quality scores and coaching sessions. **Karma store** for incentives; community tab for peer recognition. Zendesk Marketplace integration available . | Quote-only | No free tier; demo via sales |
| **[Zoho Gamescope](https://www.zoho.com/crm/performance/gamification.html)** | **Gamification within Zoho CRM.** Earn badges and trophies for daily activities—quick follow-ups, lead conversion, deal closures. **Sales reps don't need manager approval to start a game**—they choose opponents or form teams. Popup notifications track progress toward goals . | Included with Zoho CRM | Bundled with Zoho CRM subscription |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[GAME (Goals And Motivation Engine)](https://github.com/fvergaracl/GAME)** | — | **The most complete open-source gamification engine for goal-driven motivation.** **FastAPI/Python + PostgreSQL**, managed via Poetry. **Keycloak integration** for authentication and RBAC. **Points-to-coins conversion system** with configurable rate. **Kubernetes-ready** with TLS configuration, namespace isolation, and ingress routing . **Docker image available** (`fvergaracl/game`) . **Best for teams wanting a self-hosted gamification backend** that can be embedded into custom sales or employee applications. |
| **[Gami.Fied](https://www.npmjs.com/package/@gami.fied/sdk)** | — | **Open-source, self-hostable gamification infrastructure with a strictly-typed TypeScript SDK.** **Isomorphic**—runs in Node.js, Next.js, Express, Bun, Deno, and browsers . **Core primitives**: **Events** (track user actions and trigger rules), **XP & Ledgers** (award/deduct points with audit trail), **Leaderboards** (global/project, with user rank), **Achievements & Challenges** (badges, multi-step quests), **Notifications**, and **Webhooks** . **Automatic exponential backoff retries** on transient errors; typed exceptions for auth/validation/rate-limit failures . **Zero external runtime dependencies**—built on native `fetch` . **Best for developers embedding gamification into a product** without building XP and leaderboard logic from scratch . |
| **[Odoo CRM Gamification](https://github.com/alexmalab/odoo_addons/blob/723c057910d8a7e083f5ce28258064a13c6e2e34/Sales/CRM/gamification_sale_crm.md)** | — | **CRM gamification module for Odoo (LGPL-3).** Defines **goal definitions and challenges** tied directly to CRM data: total invoices, new leads, lead qualification time, and days to close a deal. **Batch assignment by salesperson** via `batch_distinctive_field` and `batch_user_expression` . **Best for organizations already on Odoo** wanting built-in sales gamification without a separate platform . |
| **[Odoo Sales Team Gamification: Targets & Rewards](https://apps.odoo.com/apps/modules/19.0/digi_sales_gamification_target)** | — | **Third-party Odoo module for real-time target tracking.** **Flexible targets** (monthly/yearly/custom) for individual salespersons. **Dynamic progress bar** appears on Quotations and Sales Orders—salespeople see exactly how close they are to their goal on every deal . **Role-based security** (only Sales Managers/Admins configure targets). **100% free and open source** (LGPL-3) . **Best for Odoo sales teams** wanting lightweight, visual target tracking without a full gamification platform . |
| **[Meeds DAO](https://github.com/meeds-io/)** | — | **Open-source Web3 community engagement platform with gamification, kudos, and token rewards.** **LGPL-3.0**, Vue.js/Vuetify/Java/Docker. **Gamification module** attributes points to community activity; **Kudos** enables peer-to-peer recognition; **Token Engine** converts points into redeemable tokens; **Wallet** manages payouts . **Docker setup** deploys in minutes . **Best for Web3 communities and DAOs** wanting to reward contributors with on-chain incentives. |
| **[ohcnetwork/leaderboard](https://github.com/ohcnetwork/leaderboard)** | — | **Flexible, plugin-based open-source leaderboard for tracking contributor activities.** **Plugin architecture** for adding data sources; **multiple views** (leaderboards, profiles, timelines); **MCP Server** for querying with AI assistants; **static export** for deployment anywhere; **fully self-hosted** . **Best for open-source projects and communities** wanting to recognize contributors without a SaaS tool. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[NAV-Rewards](https://pypi.org/project/nav-rewards/0.1.1/)** | — | **Python-based rewards engine with six badge types.** **Manual** (peer-assigned), **Automated** (system-triggered), **Achievement** (rule-based thresholds), **Computed** (lottery/random), **Workflow** (multi-step), and **Nomination** (voting-based, e.g. Employee of the Month). Configurable rules for login streaks, attendance, birthdays, and work anniversaries. Cron scheduling for automated awards. PostgreSQL . **Best for teams wanting a customizable rules engine** that can model complex recognition logic. |
| **[digi_sales_gamification_target](https://apps.odoo.com/apps/modules/19.0/digi_sales_gamification_target)** | — | **Lightweight Odoo module for sales target tracking.** Progress bar on quotations and orders, flexible target periods, role-based configuration. **141 lines of code**—minimal footprint, LGPL-3 . **Best for quick Odoo deployments** where a simple visual target bar is sufficient. |

**Frameworks for building custom systems**: Choose **GAME** for a self-hosted gamification backend with Keycloak auth and Kubernetes support , **Gami.Fied** for a TypeScript SDK to embed XP, leaderboards, and achievements into your own product , or **Odoo CRM Gamification** if you're already on Odoo and want goal definitions tied to CRM data .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Gamification platforms handle employee performance data and potentially sensitive behavioral metrics; enforce transparent rules, avoid gamifying metrics that incentivize harmful behavior, and comply with applicable employment regulations.
- **Sales gamification is evolving beyond simple points and leaderboards.** **Ambition's CEO explicitly states "gamification as we know it is broken"** —point systems and leaderboards alone struggle to drive lasting change; bracket-style competitions tied to coaching and real behaviors are the emerging alternative . **LevelEleven's Brackets** and **Ambition's Bracket Competitions** both launched in March 2026, suggesting a category shift toward tournament formats that create urgency through head-to-head matchups rather than distant rankings . **Pricing transparency varies**: Spinify publishes per-user pricing without long-term contracts and offers free "Fan" access for viewers , Hoopla offers a **30-day fully supported free trial** , and Gametize has a **free account tier** . **Open-source options are genuinely functional but require engineering**: GAME needs FastAPI, PostgreSQL, and Keycloak , Gami.Fied requires embedding its SDK into your application , and Odoo modules work only within the Odoo ecosystem . **Validate whether you need a turnkey SaaS platform (Ambition, Spinify, Hoopla) or a self-hosted engine (GAME, Gami.Fied)** before committing.

---

**Made for sales leaders, revenue operations teams, and developers building motivation infrastructure.**  
Let's make gamification and sales motivation more open, effective, and data-driven.
