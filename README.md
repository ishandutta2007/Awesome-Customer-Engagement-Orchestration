# Awesome-Customer-Engagement-Orchestration

# Top Customer Engagement Orchestration Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cross-Channel Journeys, Real-Time Segmentation & Event-Triggered Messaging*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Engagement Orchestration**. These tools enable growth teams to build automated cross-channel journeys—email, SMS, push, WhatsApp, and in-app messages—triggered by user events, with real-time segmentation and personalization.

**Examples** include Salesforce Engagement Engine, Braze, Iterable, CleverTap, MoEngage, Airship, OneSignal, Customer.io, Klaviyo, and Blueshift (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom journey builders, and open messaging infrastructure — ideal for growth engineers, product teams, and developers seeking transparent, vendor-independent customer engagement.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Engagement Engine](https://www.salesforce.com/)**  
  Real-time interaction orchestration across marketing, sales, and service channels. Enables event-triggered campaigns with Einstein AI for personalization.

- **[Braze](https://www.braze.com/)**  
  Customer engagement platform for cross-channel messaging (email, push, SMS, in-app). Features Canvas journey builder, real-time segmentation, and AI-powered send-time optimization.

- **[Iterable](https://iterable.com/)**  
  Cross-channel growth marketing platform with visual journey builder, real-time segmentation, and A/B testing. Strong developer tools including SDKs and API.

- **[CleverTap](https://clevertap.com/)**  
  Mobile-first engagement platform with real-time analytics, segmentation, and multi-channel messaging. Features A/B testing and personalization.

- **[MoEngage](https://www.moengage.com/)**  
  Customer engagement platform for mobile and web with AI-powered orchestration, segmentation, and analytics.

- **[Airship](https://www.airship.com/)**  
  Customer engagement platform specializing in push notifications, in-app messaging, and SMS. Used by 1M+ developers and marketers .

- **[OneSignal](https://onesignal.com/)**  
  Push notification and customer engagement platform with generous free tier. Supports mobile, web, email, and SMS with automation and analytics .

- **[Customer.io](https://customer.io/)**  
  Behavioral messaging platform for product-led growth. Features event-triggered email, push, SMS, and webhooks with a visual workflow builder.

- **[Klaviyo](https://www.klaviyo.com/)**  
  E-commerce marketing automation platform with email, SMS, and push. Features segmentation, A/B testing, and revenue attribution.

- **[Blueshift](https://blueshift.com/)**  
  AI-powered customer data and engagement platform. Features real-time segmentation, cross-channel orchestration, and predictive recommendations.

## Open-Source GitHub Projects

- **[Laudspeaker](https://github.com/laudspeaker/laudspeaker)**  
  Open-source customer journey automation and Braze/Iterable alternative (AGPL-3.0). Features visual no-code journey builder, event-triggered cross-channel messages (email, SMS, Firebase push), time delays, time windows, user segments, PostgreSQL/CSV imports, and PostHog integration. Self-hostable with full data control .

- **[Dittofeed](https://github.com/dittofeed/dittofeed)**  
  Developer-focused open-source customer engagement platform (MIT). Features drag-and-drop journey builder, segmentation interface, web-based template editor, git-based workflows, testing SDK, OpenTelemetry integration, and self-hosting. Sends email, SMS, push, WhatsApp, Slack. Positioned as Customer.io/Iterable/Klaviyo alternative with large cost savings via self-hosting .

- **[Helio](https://github.com/achref-soua/helio)**  
  Open-source, AI-native growth platform (AGPL-3.0). Unifies CDP, segmentation, cross-channel journeys (email/SMS/push/WhatsApp), and analytics on Temporal workflow engine. Features natural-language segments, predictive scoring, brand-voice content generation, and MCP server for AI agents. Self-hostable via Docker, Helm, or cloud-init. Sustains ~20,000 events/s at p95 81ms .

- **[MessageBirds](https://github.com/Mullassery/MessageBirds)**  
  Open-source, event-driven Customer Data & Engagement Platform (license varies) built with Rust + TypeScript. Features identity resolution, real-time audiences, governance, durable journeys, and Web/iOS/Android SDKs. Includes edge ingestion gateway, audience activation via PyReverseETL, and Next.js viewer UI .

- **[Mautic](https://github.com/mautic/mautic)**  
  The world's first open-source marketing automation platform (GPL-3.0). 100% community-owned with no commercial entity behind it. Features multi-channel campaigns (email, SMS, social, web tracking), intelligent automation, unlimited segmentation, A/B testing, and full data sovereignty. Self-hosted with unlimited contacts, no license costs, no vendor lock-in. Supports GDPR compliance .

- **[OpenClix](https://github.com/OpenClix/openclix)**  
  Open-source mobile app retention and engagement automation platform (MIT). Config-driven engagement rules with on-device logic orientation. Keeps more logic in the app codebase rather than sending every decision through a vendor. Built with TypeScript, Next.js, Dart, Kotlin, Swift .

- **[Fusion](https://github.com/fusion-hq/fusion)**  
  Open-source all-in-one user analytics and engagement platform (license varies) similar to CleverTap & Sprig. Features low-code Mixpanel-like analytics, built-in live-chat, push notifications, email/micro-surveys, and real-time engagement triggers. Positioned as lightweight alternative for startups .

### Additional Strong Open-Source Options

- **[Apache Unomi](https://github.com/apache/unomi)** — Open-source customer data platform (Apache-2.0) with profile management and segmentation.
- **[RudderStack](https://github.com/rudderlabs/rudder-server)** — Open-source customer data pipeline (AGPL-3.0) for collecting and routing events.
- **[Jitsu](https://github.com/jitsucom/jitsu)** — Open-source data collection and CDP (MIT) for event streaming.
- **[Metarank](https://github.com/metarank/metarank)** — Open-source personalization and ranking engine (Apache-2.0).
- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation with messaging channel nodes for custom orchestration.
- Community **PostHog** plugins for event-triggered messaging.

**Frameworks for building custom systems**: Combine **Laudspeaker** or **Dittofeed** as the journey orchestration engine with **Helio** for AI-native segmentation and CDP, **MessageBirds** for identity resolution and audience management, **Mautic** for broader marketing automation, and **PostgreSQL + ClickHouse** for event storage — creating a fully self-hosted, enterprise-grade customer engagement platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer engagement platforms handling personal data must comply with data protection regulations (GDPR, CCPA, CAN-SPAM, etc.).
- Self-hosted open-source solutions require proper security hardening, email deliverability configuration, and ongoing maintenance for production reliability.

---

**Made for growth teams, product marketers, CRM engineers, and developers building transparent customer engagement solutions.**  
Let's make customer engagement orchestration more open, data-driven, and efficient.
