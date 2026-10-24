# Awesome-A-B-Testing-Personalization-Platform

# Top A/B Testing & Personalization Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Experimentation, Feature Flagging & Self-Hosted Personalization Platforms*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **A/B Testing & Personalization**. These tools enable product, marketing, and engineering teams to run controlled experiments, roll out features safely, and personalize user experiences—ranging from visual editors aimed at marketers to warehouse-native platforms built for data teams.

**Examples** include Optimizely, VWO (AB Tasty), Adobe Target, LaunchDarkly, Statsig, Eppo, GrowthBook, PostHog, Unleash, and Flagsmith (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-MTU SaaS pricing, and controlling the experimentation pipeline. The open-source landscape is anchored by **GrowthBook** (the leading open-source, warehouse-native experimentation platform), **PostHog** (the all-in-one product analytics and experimentation suite with a generous free tier), **Unleash** (the mature feature flag standard), and **Flagsmith** (the open-source feature flag and remote config platform), with **FeatBit** and **dif.sh** serving specialized use cases.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Optimizely](https://www.optimizely.com/)** | Enterprise experimentation and feature flagging platform with a visual editor for marketers. | **Custom enterprise pricing only**. Median contract **~$50,000/year** based on verified purchases; range reported at $50K–$250K/month for large deployments. **2-year minimum commitment**, no downgrades mid-term, no free tier . | **No free tier** (eliminated in 2015). No trial available. |
| **[VWO / AB Tasty (Wingify)](https://vwo.com/)** | Merged entity combining VWO and AB Tasty; A/B testing and personalization with a visual editor. | **Quote-only**. Pricing depends on MAU, products selected, and scope. Existing contracts unchanged post-merger (announced January 2026) . | **Free trial** and a demo space with pre-populated data available . No permanent free tier. |
| **[Adobe Target](https://business.adobe.com/products/target/adobe-target.html)** | Enterprise personalization and experimentation within Adobe Experience Cloud. | Custom enterprise pricing; typically requires existing Adobe Experience Cloud investment. | No public free tier. Trial via sales engagement. |
| **[LaunchDarkly](https://launchdarkly.com/)** | Feature management and experimentation platform with enterprise audit trails and progressive delivery. | **Quote-based**; seat and MAU-based pricing. Experimentation is an add-on to the core feature flag platform . | No permanent free tier for full platform. Developer free tier available for feature flags. |
| **[Statsig](https://www.statsig.com/)** | Experimentation platform with sequential testing, multi-armed bandits, and a strong free tier. | Quote-based for paid plans; **generous free tier** noted as a key differentiator . | **Free tier** available with strong sequential testing capabilities . Exact limits not published in search results. |
| **[Eppo](https://www.geteppo.com/)** | Warehouse-native experimentation platform focused on rigor and statistical correctness. | Quote-based. Typical pricing for **5–10 seats: $20K–$40K/year**; **10–30 seats: $40K–$120K/year** . | No public free tier. Demo via sales engagement. |

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
