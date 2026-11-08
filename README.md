# Awesome Automated Job & Event Scheduling [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome automated job and event scheduling solutions, workload automation platforms, cloud event brokers, and open-source scheduling engines.

---

## Sector Overview & Market Dynamics

The global workload scheduling and automation (WLA / SOAP) market is valued between **$4.5 billion and $6.8 billion** and is growing at an estimated CAGR of **6% to 8%**. The market structure is **moderately fragmented**: while a vast long tail of open-source tools and niche SaaS startups cater to developer-centric cron and workflow needs, the enterprise tier exhibits strong concentration at the top where five to six major software conglomerates (such as Amazon, Broadcom, BMC Software, Fortra, and Redwood Software) control roughly half of the total market revenue.

---

## SaaS & Commercial Platforms

| Platform | Company Valuation / Revenue | Starting Price | Free Tier Limits | Primary Focus |
|---|---|---|---|---|
| **[AWS EventBridge](https://aws.amazon.com/eventbridge/)** | **~$2.7 Trillion** Market Cap (~$790B TTM Revenue) | **$1.00 / million events** (Custom Event Bus) | **14,000,000 invocations/month** free (EventBridge Scheduler); AWS service management events free | Serverless cloud event bus and scheduled invocation router |
| **[Automic SaaS](https://www.broadcom.com/products/software/automation/automic)** (Broadcom) | **~$1.5 Trillion** Market Cap (~$89B TTM Revenue) | **Quote-based subscription** ($1,145,359/license perpetual list on CDW) | **No public free tier**; Evaluation available via assisted PoC / enterprise demo | Enterprise hybrid cloud workload orchestration and automation |
| **[Control-M](https://www.bmc.com/it-solutions/control-m.html)** (BMC Software) | **~$8.3 Billion** Valuation (~$2B Annual Revenue) | **$2,400 / month** (billed annually for SaaS Starter Pack) | **14-day free trial** (for on-prem/software evaluation) or guided interactive sandbox | Enterprise workload automation, batch scheduling, and data pipeline orchestration |
| **[ActiveBatch](https://www.advsyscon.com/en-us/activebatch/)** (Redwood Software) | **~$2.5 Billion** Acquisition Valuation (~$100M–$500M ARR) | **$10,000 one-time** (Software Advice baseline) | **30-day free trial** with full platform feature access; no permanent free tier | Centralized enterprise IT workload automation and job scheduling |
| **[RunMyJobs](https://www.redwood.com/runmyjobs/)** (Redwood Software) | **~$2.5 Billion** Acquisition Valuation (~$100M–$500M ARR) | **Consumption-based quote** (priced by execution volume) | **30-day free trial** upon introductory evaluation; no permanent free tier | Cloud-native IT process automation and SAP-certified job scheduling |
| **[Tidal Software](https://www.tidalsoftware.com/)** (Redwood Software) | **~$2.5 Billion** Acquisition Valuation (~$100M–$500M ARR) | **Custom quote** (adapter- and environment-based licensing) | **30-day free trial**; no permanent free tier | Enterprise cross-platform workload automation and business application integration |
| **[JAMS Scheduler](https://www.jamsscheduler.com/)** (Fortra) | **~$500M–$800M** Revenue (Private PE-backed) | **$833 / month** (billed annually; fixed per-agent or per-job tier) | **14-day free trial** with full access to workflow scheduling features; no permanent free tier | Cross-platform enterprise workload automation and job management |
| **[Stonebranch UAC](https://www.stonebranch.com/)** | **~$25M–$45M** ARR (PE-backed by EMH Partners) | **Custom quote** (transaction/task-volume based licensing) | **No self-service free tier**; Guided demonstration & evaluation PoC upon request | Service orchestration and real-time hybrid IT automation |
| **[EasyCron](https://www.easycron.com/)** | Bootstrap / Indie SaaS (<$5M Revenue) | **$24 / year** (~$2/month for Individual plan) | **200 executions/day**, max 5 cron jobs, 20-min minimum interval, 5-sec timeout | Web-based cron service and HTTP webhook scheduling |
| **[Upstash QStash](https://upstash.com/docs/qstash/overall/overview)** | Venture-backed Seed/Series A (<$10M Revenue) | **$1.00 / 100k messages** (Pay-as-you-go) | **1,000 messages/day**, 1 MB max message size, 3-day log retention | Serverless HTTP-based messaging and task scheduling |

---

## Open-Source Schedulers & Workflow Engines

| Project | Stars | Language | Highlights |
|---|---|---|---|
| **[Dagu](https://github.com/dagucloud/dagu)** | ~4.4k | Go | Declarative YAML-based DAG workflow engine. Single binary with zero database dependencies, built-in Web UI, Docker/SSH execution, and cron scheduling. |
| **[gocron (ouqiang)](https://github.com/ouqiang/gocron)** | ~6.3k | Go | Distributed timed task management system with Web UI, second-level precision, HA via database-lock leader election, 2FA, and Docker support. |
| **[gocron (go-co-op)](https://github.com/go-co-op/gocron)** | ~7.2k | Go | Fluent, embeddable in-process Go job scheduling library supporting cron syntax, intervals, and distributed execution locks. |
| **[cronn](https://github.com/umputun/cronn)** | ~120 | Go | Extended cron service with customizable templates, Slack/Telegram notifications, retries, and conditional execution based on CPU/memory/disk loads. |

---

## License

Contents released under the [MIT License](LICENSE).
