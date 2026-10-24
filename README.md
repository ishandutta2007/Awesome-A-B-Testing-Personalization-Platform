# Awesome-A-B-Testing-Personalization-Platform

## Top A/B Testing & Personalization Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Experimentation, Feature Flagging & Self-Hosted Personalization Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **A/B Testing & Personalization**. These tools enable product, marketing, and engineering teams to run controlled experiments, roll out features safely, and personalize user experiences—ranging from visual editors aimed at marketers to warehouse-native platforms built for data teams.



**Examples** include Optimizely, VWO (AB Tasty), Adobe Target, LaunchDarkly, Statsig, Eppo, GrowthBook, PostHog, Unleash, and Flagsmith (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-MTU SaaS pricing, and controlling the experimentation pipeline. The open-source landscape is anchored by **GrowthBook** (the leading open-source, warehouse-native experimentation platform), **PostHog** (the all-in-one product analytics and experimentation suite with a generous free tier), **Unleash** (the mature feature flag standard), and **Flagsmith** (the open-source feature flag and remote config platform), with **FeatBit** and **dif.sh** serving specialized use cases.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
  - [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

### Sector Overview & Market Dynamics

The global A/B testing and digital experimentation software market is estimated between **$1.5B to $2.5B+** (expanding beyond **$8B+** when including broader AI personalization and customer experience optimization suites), growing at a compound annual growth rate (CAGR) of ~12% to 15%. The sector is **moderately fragmented**: enterprise digital experience suites (Adobe, Optimizely) command large enterprise accounts alongside major feature management vendors, but the market is not winner-take-all—specialized CRO/visual testing platforms (VWO/AB Tasty) and agile modern warehouse-native platforms (Statsig, Eppo) hold strong, defensible positions across developers and data teams.

| Product | Description | Company Size / Valuation / Revenue | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Target](https://business.adobe.com/products/target/adobe-target.html)** | Enterprise personalization and experimentation within Adobe Experience Cloud. | **Market Cap: ~$105B+**; Adobe annual revenue **$21B+** | Starts at **~$40,000–$80,000/year** (annual contract required; metered by annual server calls/impressions). | **No free tier**; no public trial (enterprise sales-guided POC sandbox only). |
| **[LaunchDarkly](https://launchdarkly.com/)** | Feature management and experimentation platform with enterprise audit trails and progressive delivery. | **Valuation: ~$3B** (Series D); ARR **~$100M+** | Paid Foundation tier starts at **$12/user/month** (metered by context MAUs and service connections; experimentation add-on scales based on monthly evaluated keys). | **Perpetual Free Plan (Developer)**: Unlimited seats and feature flags across 1 project & 3 environments; strictly capped at **1,000 context MAUs/month** and 5 service connections. |
| **[Optimizely](https://www.optimizely.com/)** | Enterprise experimentation, CMS, and feature flagging platform with marketer visual editor. | **Valuation: ~$1.5B–$2B** (PE-backed by Insight Partners); ARR **$400M+** | Starts at **~$36,000–$50,000/year** (custom annual/2-year enterprise commitment; scales to $150K+/year by traffic volume). | **No free tier** (eliminated in 2015); no self-serve free trial (guided sales POC sandboxes only). |
| **[Statsig](https://www.statsig.com/)** | Cloud and warehouse-native experimentation platform with sequential testing and product analytics. | **Valuation: ~$1.1B** (Series C unicorn); ARR **~$40M+** | Free tier available; paid Pro tier starts at **$150/month** (includes 5M events, additional events at $0.05/1K events). | **Perpetual Free Plan (Developer)**: **2,000,000 metered events/month**, 50,000 session replays/month, unlimited seats, and unlimited flag checks. |
| **[VWO / AB Tasty (Wingify)](https://vwo.com/)** | Merged entity combining VWO and AB Tasty; A/B testing and personalization with visual editor. | **Valuation: ~$200M** (Everstone Capital buyout); Wingify revenue **~$50M/year** | Starter/Growth plans start at **~$200–$314/month** billed annually (scales up by Monthly Tracked Users starting from 10,000–50,000 MTUs). | **No permanent free tier**; provides a **30-day full-featured free trial** across testing, heatmaps, and personalization modules. |
| **[Eppo](https://www.geteppo.com/)** | Warehouse-native experimentation platform focused on rigor and statistical correctness. | **Valuation: ~$138M** (Series B post-money); Total funding **$51.3M** | Custom quote-based entry tiers typically start at **$15,000–$20,000/year** for small teams (5–10 seats), scaling to $40K–$120K/year for larger seat counts. | **No permanent free tier**; no public self-service trial (evaluation via sales-guided pilot / data warehouse POC). |

## Open-Source GitHub Projects



- **[GrowthBook](https://github.com/growthbook/growthbook)** [![GitHub Stars](https://img.shields.io/github/stars/growthbook/growthbook?style=social&color=white)](https://github.com/growthbook/growthbook/stargazers)  

  **The leading open-source, warehouse-native experimentation platform.** **Bayesian-first** statistics that are easier to interpret and tolerant of peeking, with **warehouse-native** architecture—connects directly to BigQuery, Snowflake, or Databricks to query experiment data without moving it . **Deployment**: fully self-hostable for free; cloud tier available with a free tier (3 users, 5 active experiments) . **Strengths**: combines feature flags and experimentation; avoids vendor lock-in; free plan includes **1 million events/month** for the managed warehouse . Best for data teams wanting rigorous, self-hosted experimentation with full control over their data warehouse.



- **[PostHog](https://github.com/PostHog/posthog)** [![GitHub Stars](https://img.shields.io/github/stars/PostHog/posthog?style=social&color=white)](https://github.com/PostHog/posthog/stargazers)  

  **The all-in-one product analytics and experimentation suite.** **Default for engineering-led teams in 2026** . **Experiments are bundled with Feature Flags**—same billing, same free tier . **Generous free tier**: **1M events/month**, **1M feature flag requests/month**, 5K session recordings, 100K exceptions, 1,500 survey responses—**97% of companies use PostHog for free** . **Trade-offs**: broader product surface than pure experimentation tools; best when you also want analytics, replays, and error tracking. Best for teams wanting a single platform for product analytics, feature flags, and A/B testing with a free tier that scales.



- **[Unleash](https://github.com/Unleash/unleash)** [![GitHub Stars](https://img.shields.io/github/stars/Unleash/unleash?style=social&color=white)](https://github.com/Unleash/unleash/stargazers)  

  **The mature feature flag standard.** **Open Source edition is free and self-hosted with no seat limit**, covering core feature flagging with limits of **1 project, 2 environments, and 5,000 feature flags per instance** . **Enterprise features** (SSO, SCIM, granular RBAC, change approvals, support SLA) require paid tiers. **Pay-As-You-Go**: **$75/seat/month** with a 14-day free trial, 53M API requests/month, unlimited client-side MAU, and flag evaluations never billed . Best for teams that need a proven, scalable feature flag platform and can accept the open-source edition's limits or pay for enterprise governance.



- **[Flagsmith](https://github.com/Flagsmith/flagsmith)** [![GitHub Stars](https://img.shields.io/github/stars/Flagsmith/flagsmith?style=social&color=white)](https://github.com/Flagsmith/flagsmith/stargazers)  

  **The open-source feature flag and remote config platform.** Combines feature flags, remote configuration, and A/B testing in one self-hostable package. **Free plan** available with request-based limits; **Start-Up** at **$45/month for 1M requests** . **SDK requests are not rate-limited** by design—only plan limits apply, with a 7-day warning before blocking . **Limitation**: RBAC, SSO, and advanced audit trails are gated behind a paid Enterprise license . Best for teams wanting a feature flag platform with remote config that can start free and scale affordably.



- **[FeatBit](https://github.com/featbit/featbit)** [![GitHub Stars](https://img.shields.io/github/stars/featbit/featbit?style=social&color=white)](https://github.com/featbit/featbit/stargazers)  

  **The 100% open-source feature flags platform.** Scalable and fast, empowering teams to deliver, control, experiment with, and monetize their software. **AGPL-3.0 licensed** with a free personal tier available . Best for teams wanting a fully open-source alternative to LaunchDarkly without proprietary limits.



- **[dif.sh](https://github.com/dif-sh/dif)** [![GitHub Stars](https://img.shields.io/github/stars/dif-sh/dif?style=social&color=white)](https://github.com/dif-sh/dif/stargazers)  

  **The Git-native experimentation tool.** Every flag and experiment is a **Markdown file checked into git** next to the code it changes—reviewed in a pull request, with history in git. When done, the decision and learnings go in the same file. **Positioned as the best open-source Optimizely alternative** . Best for teams that want experimentation artifacts to live alongside code and follow standard review workflows.



### Additional Strong Open-Source Options



- **Replane** — Open-source, self-hosted feature flags and dynamic configuration with sub-second propagation via Server-Sent Events. Best for teams needing real-time config changes without redeploys .

- **Wasabi A/B Testing Service** — Real-time, enterprise-grade, 100% API-driven experimentation. Apache-2.0 licensed. Best for teams wanting full data ownership with minimal instrumentation .

- **OpenFlags** — Lightweight, developer-first feature flagging built with Bun and TypeScript, focused on local evaluation and performance. Best for developers wanting a fast, no-dependency flagging solution .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **SaaS pricing for enterprise experimentation is opaque and expensive**: Optimizely has a **2-year minimum** and median **$50K/year** contract with no free tier ; Eppo ranges **$20K–$120K/year** for 5–30 seats ; Adobe Target requires enterprise engagement. Open-source alternatives (GrowthBook, PostHog, Unleash) eliminate these commitments.

- **"Open-source" editions have limits**: Unleash Open Source caps at 1 project, 2 environments, and 5,000 flags per instance ; Flagsmith gates RBAC and SSO behind paid Enterprise . Verify limits before production deployment.

- **PostHog's free tier is exceptionally generous**: 1M events and 1M flag requests monthly—**97% of companies use it for free** . It's the pragmatic default for teams starting out, though it's a broader platform than pure experimentation tools.

- **AB Tasty and VWO merged in January 2026** under the Wingify brand; pricing remains quote-only and existing contracts are unchanged . Verify the current product roadmap before committing.



---



**Made for product managers, growth engineers, and data teams building experimentation cultures.**  

Let's make A/B testing and personalization more open, statistically rigorous, and accessible.
