# Awesome-API-Event-Webhooks-Integration

# Awesome-API-Event-Webhooks-Integration

**Top API Event Webhooks Integration (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Outbound Webhook Infrastructure, Event Destinations, Webhook Testing & Event-Driven Integration*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **API Event Webhooks & Integration**. These tools enable developers to emit events from their applications, deliver webhooks reliably with retries and signing, route events to multiple destinations, and debug incoming webhooks—from fully managed webhook infrastructure with user portals and observability to self-hosted gateways and event destination platforms that give teams complete control over their event delivery pipelines.



**Examples** include Svix, Hookdeck, Zapier, Make, Webhook.site, Segment, Pipedream, Amazon EventBridge, Tray.io, and HubSpot Webhooks (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, webhook delivery, and open event infrastructure. **Critical note**: The open-source webhook space has matured significantly—**Svix**, **Hookdeck Outpost**, and **Convoy** are production-grade options with enterprise features. However, no open-source project matches Zapier's 7,000+ app ecosystem or Segment's customer data platform breadth; those are integration platforms, not webhook infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The broader Integration Platform as a Service (iPaaS) and Event-Driven Architecture (EDA) market is estimated between **$15B and $20B+**, growing rapidly as real-time event streaming and automation become enterprise standards. The overall space is **moderately concentrated** at the enterprise middleware and event bus tier—anchored by cloud hyperscalers and major automation leaders—while the specialized outbound webhook delivery and developer gateway niche remains **fragmented**, with nimble startups and open-source projects innovating rapidly.

## SaaS/Hosted Platforms

| Company / Product | Category & Best For | Pricing (Starting Tier) | Free Tier / Trial Limits | Company Scale (Valuation / Revenue) |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon EventBridge](https://aws.amazon.com/eventbridge/)** | **Serverless event bus** for routing events between AWS services & SaaS apps. Best for AWS-centric scalable event routing. | **$1.00 / million custom events** (billed in 64 KB increments); $0.20 / million API Destination invocations | **Permanently Free**: Unlimited AWS service management events + 14M invocations/mo for EventBridge Scheduler + 5M ingested events/mo for Schema Discovery | **Parent Market Cap: ~$2.2T** (Amazon / AWS; AWS ARR >$105B) |
| **[HubSpot Webhooks](https://developers.hubspot.com/)** | **Native webhook subscriptions** for CRM events (contact created, deal updated). Best for reacting to CRM state changes. | **$0 / month** (included with Free CRM & Developer Portal); paid Hubs start at **$15/seat/month** | **Free Forever Plan**: 100 requests per 10 seconds burst limit, capped at 250,000 API requests/day | **Market Cap: ~$12B–$13.5B** (NYSE: HUBS; Revenue: ~$3.1B ARR) |
| **[Make](https://www.make.com/)** | **Visual automation platform** with 3,000+ app connectors. Best for visual flows and multi-step webhook triggers. | **$9 / month** billed annually ($10.59/mo monthly) for Core Plan (10,000 credits/mo) | **Free Forever Plan**: 1,000 operations/credits per month, 2 active scenarios, 15-minute minimum run interval | **Parent Valuation: ~$13B** (Celonis; Make subsidiary ARR estimated >$50M) |
| **[Zapier](https://zapier.com/)** | **No-code automation platform** with 7,000+ app integrations. Best for connecting apps without managing webhook infrastructure. | **$19.99 / month** billed annually ($29.99/mo monthly) for Professional Plan (750 tasks/mo) | **Free Forever Plan**: 100 tasks/month, 2-step single-trigger Zaps only, 15-minute polling interval | **Valuation: ~$5.0B** (Bootstrapped / secondary sale; Revenue: ~$310M ARR) |
| **[Segment](https://segment.com/)** | **Customer data platform (CDP)** routing events via webhooks & destinations. Best for collecting & syncing user event streams. | **$120 / month** for Team Plan (up to 10,000 Monthly Tracked Users) | **Free Forever Plan**: 1,000 Monthly Tracked Users (MTUs), 2 data sources, 1 data warehouse destination (daily sync) | **Acquisition Valuation: $3.2B** (Acquired by Twilio; Unit ARR >$150M) |
| **[Tray.io](https://tray.io/)** | **Enterprise automation platform** with advanced webhook triggers. Best for enterprise-grade low-code workflows. | **~$500–$700 / month** starting for Pro Plan (sales-led; median enterprise contract ~$37,600/year) | **14-day Free Trial** (or custom PoC) with starter task credit allotment; no permanent free tier | **Valuation: ~$600M** (Total venture funding: ~$160M) |
| **[Pipedream](https://pipedream.com/)** | **Developer-first automation platform** with code steps & webhook triggers. Best for code-level control over event workflows. | **$29 / month** for Basic Plan ($49/mo for Advanced) | **Free Forever Plan**: 100 credits/month (strict daily ceilings), 3 active workflows, 3 connected accounts, 300s execution limit | **Valuation: ~$70M–$100M est.** (Series A; Total funding: ~$22.4M; ARR: ~$5M) |
| **[Svix](https://www.svix.com/)** | **Webhooks-as-a-service platform** (managed cloud for open-source Svix). Best for turnkey outbound webhook infrastructure. | **$490 / month** for Pro Plan (includes 30-day trial and 50,000 messages/mo + $0.0008/msg) | **Free Forever Plan**: 50,000 messages/month, 50 messages/second rate limit, 99.9% uptime SLA | **Valuation: ~$40M–$60M est.** (Series A; Total funding: ~$13.1M; ARR: ~$1M–$5M) |
| **[Hookdeck](https://hookdeck.com/)** | **Event gateway & webhook infrastructure** (managed platform & Outpost). Best for reliable inbound/outbound event delivery. | **$39 / month** for Team Gateway Plan; Outpost outbound plans start at **$10 per million events** | **Free Forever Plan**: 10,000 events/requests per month, 3-day log retention, 5 events/second throughput | **Valuation: ~$15M–$25M est.** (Seed; Total funding: ~$3M; ARR: ~$1M est.) |
| **[Webhook.site](https://webhook.site/)** | **Webhook testing & debugging tool** with unique inspection endpoints. Best for inspecting payloads and testing integrations. | **$9 / month** ($90/year) for Basic Plan ($19/mo for Pro) | **Free Forever Plan**: 50 requests per instant URL, 50 requests history, URLs expire after 7 days | **Revenue: ~$400k ARR** (Bootstrapped / Micro-SaaS; traffic >700M reqs/day) |

## Open-Source GitHub Projects



- **[Svix](https://github.com/svix/svix-webhooks)**

  **Open source and enterprise-ready webhooks service** (Rust, ~2,953 stars) — **the most mature open-source webhook delivery platform**, used as the core of the commercial Svix service . **Features**: Webhook subscription management, signing with HMAC, retry logic, delivery attempt history, and a user portal for managing endpoints. The commercial Svix adds enterprise features (observability, SLA support) on top of this open-source core. **Tech stack**: Rust. **Deploy**: Self-hosted (Docker) or Svix Cloud. **Trade-off**: The open-source version lacks some commercial features (advanced observability, dedicated support); for full-featured managed service, use Svix Cloud. **Best for**: developers wanting production-grade webhook infrastructure they can self-host, with a clear upgrade path to managed service if needed.



- **[Hookdeck Outpost](https://github.com/hookdeck/outpost)**

  **Open Source Outbound Webhooks and Event Destinations Infrastructure** (Go, ~968 stars, Apache-2.0) — **the most feature-complete open-source event destination platform** found in this research . **Features**: **Event topics and topic-based subscriptions**; publish events via API or queue; **at-least-once delivery guarantee**; **event fanout** to multiple endpoints; automatic and manual retries; **multi-tenant support**; **user portal** for customers to view metrics and manage destinations; **delivery failure alerts**; OpenTelemetry integration; **destination types**: Webhooks, Hookdeck Event Gateway, Amazon EventBridge, AWS SQS, AWS S3, GCP Pub/Sub, RabbitMQ, and Kafka; webhook best practices (idempotency headers, signatures, rotation); **SDKs and MCP server** (Go, Python, TypeScript) . **Tech stack**: Go, Redis, PostgreSQL. **Deploy**: Docker Compose, Railway one-click, or self-hosted . **Trade-off**: **Event destination platform, not a general automation tool**—it routes events you publish to destinations you configure; it does not connect to third-party SaaS apps or provide no-code builders. **Best for**: teams building a platform that needs to offer outbound webhooks/event destinations to their customers—with multi-tenancy, user portals, and broad destination support.



- **[Convoy](https://github.com/frain-dev/convoy)**

  **Cloud Native Webhooks Gateway** (Go, ~2,698 stars) — **the most enterprise-oriented open-source webhook gateway** . **Features**: Webhook ingestion and delivery with retries, signing, and observability; designed for cloud-native deployments; supports multiple event sources and destinations. **Tech stack**: Go. **Deploy**: Self-hosted (Kubernetes-native). **Trade-off**: **Gateway-focused**—it receives and delivers webhooks but does not provide the user portal and multi-tenant customer-facing experience of Outpost. **Best for**: platform teams wanting a Kubernetes-native webhook gateway with enterprise reliability features.



- **[webhook-tester](https://github.com/tarampampam/webhook-tester)**

  **Free and self-hosted alternative to webhook.site** (Go, ~v2.2.4) — **the best open-source webhook debugging tool** . **Features**: Unique randomly generated URLs for capturing requests; **customizable response code, headers, and body**; response delay; **built-in UI** (ReactJS compiled into binary); **WebSocket support** for real-time notifications; **storage drivers**: memory, Redis, or filesystem; **tunneling via ngrok** to capture external webhooks; auto-create sessions; multi-architecture Docker image; runs as unprivileged user . **Tech stack**: Go, ReactJS. **Deploy**: Binary download, Docker, or `curl` install script . **Trade-off**: **Testing tool, not delivery infrastructure**—it captures and displays webhooks for debugging; it does not deliver events to your customers or manage subscriptions. **Best for**: developers wanting a self-hosted webhook inspection tool without sending data to a third-party service like webhook.site.



- **[WebhookX](https://github.com/webhookx-io/webhookx)**

  **Open-source webhook gateway for receiving, validating, transforming, and delivering events at scale** (Go, ~v1.2.0) — **the most feature-rich open-source webhook gateway with plugin support** . **Features**: **Admin API** (RESTful); reliable delivery with automatic retries; **fan out** to multiple endpoints by event type; **rate limiting**; **declarative configuration** (GitOps-oriented); multi-tenancy (license required); **plugins**: signature (HMAC SHA-256), **wasm** (AssemblyScript/Rust/TinyGo transforms), function (JavaScript for inbound logic), event validation (JSON Schema), and security plugins (HMAC auth, basic auth, key auth—license required); **observability** (OpenTelemetry); secret management (license required) . **Tech stack**: Go, PostgreSQL, Redis. **Deploy**: Docker Compose, Homebrew, or binary . **Trade-off**: **Some features require a license** (multi-tenancy, secret management, advanced security plugins)—check the license program. **Active development with breaking changes possible before v1.0.0** . **Best for**: teams wanting a plugin-extensible webhook gateway with declarative configuration and GitOps workflows.



- **[Relay](https://github.com/rajputomsingh/Relay)**

  **Reliable webhook delivery infrastructure** (Go, ~recent) — **a focused, developer-friendly delivery engine with clear semantics** . **Features**: **Idempotency-Key enforcement** for duplicate submission prevention; **at-least-once delivery** with explicit acknowledgment that exactly-once is not guaranteed; **retry classification** (5xx, network errors, timeouts retried; 4xx terminal except 408/429); **delivery attempt history**; **event replay** for terminal failures; **lease fencing** for worker crash recovery; **Node.js/TypeScript SDK**; MongoDB persistence . **Tech stack**: Go, MongoDB. **Deploy**: Docker Compose or manual (`go run ./cmd/relay`) . **Trade-off**: **Delivery engine only**—no user portal, no multi-tenancy, no destination types beyond webhooks. Newer project with limited community validation. **Best for**: developers wanting a straightforward, well-documented webhook delivery engine with clear at-least-once semantics and idempotency.



### Additional Strong Open-Source Options



- **webhook** (ronixa) — Secure multi-tenant webhook system with in-memory, Redis, or Kafka backends and exponential backoff (TypeScript, ~1 star). **Note**: Early-stage; limited validation . **Best for**: developers wanting a lightweight multi-tenant webhook foundation.

- **HookStack** — Store webhooks until you are ready to retrieve them (HTML, ~6 stars). **Note**: Narrow "webhook inbox" tool, not delivery infrastructure . **Best for**: developers wanting to buffer incoming webhooks for later processing.



**Frameworks for building custom systems**: Combine **Hookdeck Outpost** as the event destination platform with **Svix** for webhook subscription management, **webhook-tester** for debugging during development, and **WebhookX** or **Relay** as delivery engines—creating a webhook infrastructure stack. **None of these provide Zapier's app ecosystem or Segment's customer data platform**; those are integration platforms, not webhook infrastructure.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Webhook platforms handling event data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate signing, authentication, and payload validation. Webhook endpoints are a common attack surface—validate signatures and sanitize payloads.

- **The "webhook delivery infrastructure" vs. "event destination platform" vs. "testing tool" vs. "integration platform" distinction is critical.** **Svix, Convoy, WebhookX, and Relay** are **webhook delivery infrastructure**—they deliver events reliably to endpoints. **Hookdeck Outpost** is an **event destination platform**—it adds multi-tenancy, user portals, and destination types beyond webhooks (SQS, Kafka, etc.) . **webhook-tester** is a **testing tool**—it captures and inspects webhooks, not delivers them . **Zapier, Make, Segment, and Pipedream** are **integration platforms**—they connect apps and route data, but are not webhook delivery infrastructure. **Choose based on whether you need to send webhooks to customers, receive and debug them, or connect third-party apps.**

- **Svix is unique as open-core webhook infrastructure**—the core is open source and self-hostable, with a commercial cloud service for teams wanting managed reliability and support . **Hookdeck Outpost is the most complete open-source event destination platform** with multi-tenancy, user portals, and broad destination support (SQS, Kafka, EventBridge, etc.) . **Convoy** is the Kubernetes-native gateway choice.

- **Zapier and Make are not webhook infrastructure.** They are integration platforms that can trigger on or act via webhooks, but they do not provide delivery guarantees, signing, retry logic, or subscription management for your own events . **Do not confuse an automation tool with webhook delivery infrastructure.**

- **Webhook.site is a testing tool, not a delivery service.** Use it to debug what your application is sending, not to deliver webhooks to your customers. **webhook-tester** is the self-hosted alternative for teams wanting data sovereignty .

- **Pricing opacity varies.** Svix, Hookdeck, Zapier, Make, Segment, Pipedream, and Tray.io publish tiered pricing. Webhook.site has a free tier. Amazon EventBridge is pay-per-event. HubSpot webhooks are included with CRM. **Validate with direct vendor conversations against your event volume and destination count.**

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL, Redis for most), signing secret management, and ongoing maintenance. **Event payloads may contain sensitive data**—ensure your deployment meets your organization's security standards before delivering production events.



---



**Made for developers, platform teams, and organizations building transparent webhook and event integration solutions.**

Let's make API Event Webhooks & Integration more open, data-driven, and event-reliable.
