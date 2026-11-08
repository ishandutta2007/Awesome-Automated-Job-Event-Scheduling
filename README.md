# Awesome-Automated-Job-Event-Scheduling

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **"Zoho Scheduler" is not a distinct product**, and the open-source side is stronger than your SaaS list suggests.



## The data problems



**"Zoho Scheduler" does not exist as a standalone product.** Zoho's scheduling capability is embedded in Zoho Creator—and schedules only execute on **paid plans**; you can save schedules on free, but cannot switch them on . There is no separate "Zoho Scheduler" SKU or pricing page. **Remove it or reframe as "Zoho Creator (scheduling feature)."**



**RunMyJobs (Redwood) has no published price.** Software Advice confirms pricing is **on request**, with a free trial but no free version . Do not fabricate a figure.



**Stonebranch UAC's listed "starting price" of $0.01 is a placeholder**, not a real price. The page shows "US$0.01" with no context . Treat as quote-only.



**Tidal Software has no published price.** Its own site advertises "straightforward pricing" but publishes nothing ; third-party sources confirm "not published" and "quote on request" . Its model is **adapter-based licensing**, meaning costs grow with each integration .



## What the search results actually contain



**SaaS pricing (usable):**



| Platform | Entry pricing | Verified detail |

|---|---|---|

| **Control-M (BMC)** | **Starter Pack SaaS from $2,400/month** billed annually; Enterprise contact  | Full cloud/hybrid orchestration, GitOps, 24x7 support  |

| **JAMS Scheduler** | **From $833/month** billed annually; fixed per-agent or usage per-job  | Transparent published starting price  |

| **ActiveBatch** | **$10,000 one-time** (Software Advice)  | No free version listed  |

| **Automic (Broadcom)** | **$1,145,359 per license** (CDW)  | No public list price; renewals follow Broadcom's pattern  |

| **RunMyJobs** | **Pricing on request**  | Free trial, no free version  |

| **Stonebranch UAC** | **Quote-only** (placeholder $0.01)  | Free trial available  |

| **Tidal** | **Quote-only**  | Adapter-based licensing  |

| **AWS EventBridge** | **¥6.75/million custom/partner events ingested**; ¥0.34/million delivered to same account services  | Management events free  |

| **CronHub** | **$19/month** (SourceForge); **$5/month Starter** (SaaSworthy, 2020 data)  | Conflicting figures  |



**Open-source projects (usable):**



| Project | Stars | What it actually does |

|---|---|---|

| **Dagu** | **~4k stars**  | YAML-based DAG workflow engine; single binary, **no database required**; Web UI + CLI; Docker, HTTP, SSH executors; cron scheduling; local-first for small teams  |

| **gocron** | Not surfaced | Go-based distributed scheduler; Web UI; second-level precision; **HA via database-lock leader election**; 2FA; MySQL/PostgreSQL/SQLite; Docker Compose  |

| **cronn** | Not surfaced | Enhanced cron with templates, retries, notifications (Slack/Telegram/Webhook), conditional execution (CPU/memory/disk), auto-resume  |



**What is missing:**

- **No star counts** for gocron or cronn.

- **No revenue or valuation** for any vendor.

- **No verified current pricing** for CronHub (figures conflict across sources and one is from 2020).



## What I recommend



**Remove "Zoho Scheduler"**—it is not a distinct product; Zoho Creator scheduling requires a paid plan .



**Split into three honest categories:**



**1. Enterprise Workload Automation** (proprietary, quote/seat-priced): Control-M ($2,400/mo Starter) , JAMS ($833/mo) , ActiveBatch ($10K one-time) , Automic ($1.1M/license) .



**2. Cloud Event Bus** (proprietary, usage-priced): AWS EventBridge (¥6.75/M custom events) .



**3. Open-Source Schedulers** (strong section): **Dagu** (~4k stars, no DB, YAML DAGs) , **gocron** (HA, Web UI) , **cronn** (enhanced cron with conditional execution) .



**Flag the pricing model differences explicitly:** per-month SaaS (Control-M, JAMS), one-time license (ActiveBatch), per-license enterprise (Automic), and per-event usage (EventBridge) produce incomparable costs at the same job volume. A reader choosing between them needs that context.



**Mark RunMyJobs, Stonebranch, and Tidal as "quote-only"**—do not cite Stonebranch's $0.01 placeholder  or invent figures for the others.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not list "Zoho Scheduler" as a product, cite Stonebranch's $0.01 as a real price, or fabricate RunMyJobs/Tidal pricing.
