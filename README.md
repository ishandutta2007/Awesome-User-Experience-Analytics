# Awesome-User-Experience-Analytics

## Top User Experience Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Session Replay, Product Analytics & Behavioral Insights*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **User Experience Analytics**. These tools help teams understand how users interact with digital products through session replay, heatmaps, funnels, retention analysis, and behavioral cohorts—turning raw interaction data into actionable UX improvements.



**Examples** include ServiceNow User Experience Analytics, FullStory, Pendo, Contentsquare, Hotjar, Mixpanel, Amplitude, LogRocket, Heap, and Glassbox (the category leaders).



**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted session replay, product analytics, and privacy-first UX intelligence—ideal for product teams, developers, and organizations building sovereign analytics infrastructure without per-event pricing or data leaving their infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow User Experience Analytics](https://www.servicenow.com/)**  

  UX analytics integrated into the Now Platform for monitoring employee and customer digital experiences, with journey mapping and interaction insights.



- **[FullStory](https://www.fullstory.com/)**  

  Digital experience analytics platform with session replay, autocapture, frustration signals, and journey analysis for product and UX teams.



- **[Pendo](https://www.pendo.io/)**  

  Product analytics and in-app guidance platform combining usage analytics, feature adoption tracking, NPS, and guided onboarding tours.



- **[Contentsquare](https://contentsquare.com/)**  

  Digital experience analytics platform with heatmaps, session replay, zone-based analysis, and AI-powered experience insights.



- **[Hotjar](https://www.hotjar.com/)**  

  Behavior analytics and user feedback tool with heatmaps, session recordings, surveys, and feedback widgets for website optimization.



- **[Mixpanel](https://mixpanel.com/)**  

  Product analytics platform focused on event tracking, funnels, retention, and cohort analysis with a self-serve model.



- **[Amplitude](https://amplitude.com/)**  

  Digital analytics platform with behavioral cohorting, experimentation, and predictive analytics for product teams.



- **[LogRocket](https://logrocket.com/)**  

  Session replay and frontend monitoring platform that pairs replay with console logs, network activity, and error tracking for debugging.



- **[Heap](https://heap.io/)**  

  Digital insights platform (now Contentsquare) with autocapture, retroactive analysis, and session replay for product and marketing teams.



- **[Glassbox](https://www.glassbox.com/)**  

  Digital experience analytics with session replay, journey analysis, and AI-driven insights for customer experience optimization.



## Open-Source GitHub Projects



- **[PostHog](https://github.com/PostHog/posthog)**  

  The most comprehensive open-source product analytics platform (MIT core, ~40k GitHub stars); includes autocapture events, session replay, feature flags, A/B testing, heatmaps, and surveys in one self-hostable stack; first 1M events/month free on cloud, or fully self-hosted .



- **[OpenReplay](https://github.com/openreplay/openreplay)**  

  Leading open-source session replay and product analytics platform (AGPL-3.0 core, ~13k GitHub stars); self-hosted alternative to FullStory and LogRocket with DOM replay, console/network/error capture, funnels, journeys, heatmaps, and dashboards; Docker/Compose deployable .



- **[Highlight.io](https://github.com/highlight/highlight)**  

  Open-source fullstack monitoring platform combining session replay and error monitoring; used in production by 2k+ developers; replays browser devtools context (network requests, errors) alongside user sessions .



- **[Matomo](https://github.com/matomo-org/matomo)**  

  Open-source web analytics platform (GPL-3.0) with heatmaps and session recording available as add-ons; strong privacy/GDPR positioning and full data ownership when self-hosted .



- **[smolanalytics](https://github.com/Arjun0606/smolanalytics)**  

  MIT-licensed, single-binary analytics toolkit combining web analytics, product analytics (funnels, retention, paths, cohorts), feature flags, A/B testing, click heatmaps, in-product surveys, and a session inspector; includes MCP server for querying analytics from your code editor .



- **[Factcat](https://github.com/factcat-dev/factcat)**  

  Open-source alternative to Amplitude and Mixpanel that runs entirely in your data warehouse (BigQuery, Snowflake, DuckDB, Postgres, ClickHouse, and more); generates SQL rather than ingesting data—no SDK, no copy of your data, no hosted service .



- **[UXWizz](https://www.uxwizz.com/)**  

  Self-hosted analytics and session recording tool with lightweight and full DOM recording modes, heatmaps, visitor segmentation, and basic A/B testing; one-time license pricing (Personal $299, Company $799) .



- **[UXlens](https://uxlens.com/)**  

  Developer-first session recording tool focused on UI and conversion insights; lightweight recordings, segment filtering, privacy-by-default input masking, and Docker-based self-hosting option .



### Additional Strong Open-Source Options



- **Nimbus Analytics** — Open-source, self-hosted alternative to Segment and Mixpanel with real-time event streaming, multi-tenant isolation, and Docker deployment; backend API is production-ready, dashboard UI coming Q1 2026 .

- **ux-events-inspector** — Lightweight JavaScript SDK and WebSocket backend for real-time click event capture and streaming; a minimal open-source alternative to LogRocket for live debugging .

- **Tester Telemetry** — Real-time multi-device tester telemetry with rage/dead click detection and direct-to-device intervention, built on Supabase for 100% data ownership .

- **Tour Kit** — Headless React library for building in-app product tours with analytics, surveys, and checklists as composable packages; MIT-licensed and sub-8KB .

- **Plausible Analytics** — Lightweight, privacy-focused web analytics (AGPL-3.0) without cookies; useful for traffic-level insights alongside dedicated UX tools .



**Frameworks for building custom systems**: Combine **PostHog** or **OpenReplay** for session replay and product analytics, **Factcat** for warehouse-native behavioral analysis, **smolanalytics** for an all-in-one lightweight stack, and **Matomo** for privacy-focused web analytics in a fully self-hosted UX analytics pipeline.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- UX analytics platforms handling user data must comply with applicable privacy regulations (GDPR, CCPA, etc.) and implement appropriate consent mechanisms.

- Self-hosted open-source solutions require proper security hardening, storage planning (session replay data grows quickly), and data retention policies.

- Verify license terms for commercial use; PostHog and Matomo use MIT/GPL cores with separately licensed enterprise features, while OpenReplay uses AGPL-3.0 for its core.



---



**Made for product managers, UX researchers, designers, and data-driven teams.**  

Let's make user experience analytics more open, privacy-respecting, and actionable.
