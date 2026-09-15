# Awesome-Postgresql-Monitoring

### Top Policy Administration System (Insurance) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Policy Lifecycle, Product Configuration, Quoting, Issuance, Endorsements, Renewals & Core Insurance Operations*

**Last updated: September 2026**



This repository tracks notable **SaaS/enterprise platforms** and **open-source projects** for **Policy Administration Systems (PAS)** in insurance. These systems manage the full policy lifecycle — product definition, quoting, underwriting, issuance, endorsements, renewals, cancellations, and related core operations — for P&C, life, health, and specialty lines.



**Examples** include Guidewire PolicyCenter, Duck Creek Policy, Socotra, EIS PolicyCore, Sapiens IDITS, Insurity Policy Decisions, Majesco Policy, Oracle Health Insurance, Keylane, and Instanda (the category leaders).



**Open-source emphasis**: Full-featured, regulated policy administration systems are almost entirely commercial due to product complexity, rating engines, compliance, and integration requirements. A small number of open or open-core insurance platforms and experimental projects exist. This section lists the strongest available open resources and is realistic about the significant gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Guidewire PolicyCenter](https://www.guidewire.com/)**  

  Industry-standard enterprise policy administration system for large P&C carriers, part of the Guidewire InsuranceSuite.



- **[Duck Creek Policy](https://www.duckcreek.com/)**  

  Cloud-native policy administration platform with strong product configuration and rating capabilities for mid-to-large insurers.



- **[Socotra](https://www.socotra.com/)**  

  Cloud-native, API-first policy administration platform designed for rapid product launches and modern insurance operations.



- **[EIS PolicyCore](https://www.eisgroup.com/)**  

  Digital insurance platform including policy administration capabilities for carriers seeking modern core systems.



- **[Sapiens IDITS / CoreSuite](https://www.sapiens.com/)**  

  Comprehensive policy administration and core insurance solutions covering P&C and Life & Pensions lines.



- **[Insurity Policy Decisions](https://www.insurity.com/)**  

  Policy administration and related core systems focused on P&C insurers and MGAs.



- **[Majesco Policy](https://www.majesco.com/)**  

  Cloud insurance platform offering policy administration for multiple lines of business.



- **[Oracle Health Insurance](https://www.oracle.com/)**  

  Oracle’s health insurance policy and claims administration solutions for health carriers and payers.



- **[Keylane](https://www.keylane.com/)**  

  Policy administration and core systems with strong presence in European insurance markets.



- **[Instanda](https://www.instanda.com/)**  

  No-code/low-code insurance product and policy administration platform enabling rapid configuration and launch of insurance products.



## Open-Source GitHub Projects

- **[Open Insurance Platform (aposin)](https://github.com/aposin/openinsuranceplatform)**  

  Open-source core insurance platform aiming to cover policy, claims, billing, party management, and related capabilities across lines of business.



- **[open_insure and mutual/self-insurance open projects](https://github.com/daxaxelrod/open_insure)**  

  Open-source efforts focused on group or mutual-style policy management and claims handling.



- **[Experimental open policy administration platforms](https://github.com/)**  

  Community and initiative projects attempting to build modern, API-first PAS alternatives for smaller carriers or MGAs.



- **[Product configuration and rating open experiments](https://github.com/)**  

  Prototypes for defining insurance products, coverages, and simple rating logic outside full commercial engines.



- **[Policy lifecycle workflow open tools](https://github.com/)**  

  Lightweight systems for quoting, issuance, endorsement, and renewal workflows in non-regulated or educational contexts.



- **[Claims and policy data model open libraries](https://github.com/)**  

  Shared data models and reference implementations useful for insurance technology projects.



- **[ACORD and insurance standards open resources](https://github.com/)**  

  Tools and schemas supporting insurance data exchange standards that can integrate with open or custom PAS components.



- **[Low-code insurance form and portal open builders](https://github.com/)**  

  Components for building agent or customer portals that can sit in front of policy systems.



- **[Actuarial and pricing open notebooks](https://github.com/)**  

  Research and open tools for pricing models that may feed into policy administration logic.



- **[Documentation and reference architecture open repos](https://github.com/)**  

  Community collections of insurance core system patterns and integration examples.



### Additional Strong Open-Source Options

- Exploring the Open Insurance Platform and similar projects for research, education, or highly customized internal use.

- Using open data models and workflow tools as building blocks alongside commercial PAS.

- Building simple mutual or affinity insurance systems with open projects for non-traditional use cases.

- Accepting that production-grade product configuration, complex rating, regulatory compliance, multi-line support, and carrier-scale operations still require commercial platforms (Guidewire, Duck Creek, Socotra, Sapiens, Majesco, Instanda, etc.).

- Focusing open-source efforts on peripheral capabilities (portals, data exchange, analytics) rather than replacing the core PAS.



**Frameworks for building custom systems**: For non-regulated or experimental contexts, start with an open insurance platform core → define basic products and workflows → add quoting and policy issuance → integrate simple billing and claims. For real carriers and MGAs, commercial PAS platforms remain the practical and regulatory-preferred foundation; open components can supplement portals, analytics, or specific microservices.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Policy administration systems are core to regulated insurance operations. They must comply with insurance laws, data protection rules, financial reporting, and supervisory requirements. Open-source or self-built solutions require extensive validation, security, and legal review before any production use. Errors can create significant financial, regulatory, and customer harm. This list is not insurance, legal, or compliance advice.



---

**Made for insurance CIOs, core system architects, MGAs, and InsurTech teams who need reliable policy administration.**

Let's keep insurance technology modern, flexible, and as open as practical.
# Awesome-Postgresql-Monitoring

## Top PostgreSQL Monitoring Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Query Performance, Metrics, EXPLAIN Analysis, Health Checks, Alerting & Database Observability*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **PostgreSQL Monitoring**. These tools collect metrics, analyze query performance, capture EXPLAIN plans, track replication, and provide alerting and dashboards for PostgreSQL databases.



**Examples** include pganalyze, Postgres.ai, Percona Monitoring and Management, Datadog Database Monitoring, Checkmk, Redgate Monitor, ClusterControl, Sematext, Instana, and New Relic Database (the category leaders).



**Open-source emphasis**: PostgreSQL monitoring has an excellent open-source ecosystem. **pgwatch**, **PoWA**, **pgHero**, **pgBadger**, **postgres_exporter**, **Percona PMM**, and built-in extensions form a complete self-hosted stack. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[pganalyze](https://pganalyze.com/)**  

  Specialized PostgreSQL monitoring platform focused on query performance, index recommendations, EXPLAIN analysis, and schema insights.



- **[Postgres.ai](https://postgres.ai/)**  

  Platform offering database branching, thin cloning, and related tools that support performance testing and analysis workflows for PostgreSQL.



- **[Percona Monitoring and Management (PMM)](https://www.percona.com/software/pmm)**  

  Open-source monitoring and management platform (with commercial support options) for PostgreSQL, MySQL, and MongoDB.



- **[Datadog Database Monitoring](https://www.datadoghq.com/product/database-monitoring/)**  

  Part of Datadog’s observability suite, providing deep PostgreSQL metrics, query samples, EXPLAIN plans, and correlation with application traces.



- **[Checkmk](https://checkmk.com/)**  

  Infrastructure and application monitoring platform with strong PostgreSQL checks and alerting capabilities.



- **[Redgate Monitor](https://www.red-gate.com/products/dba/sql-monitor/)**  

  Database monitoring solution (historically strong on SQL Server, with PostgreSQL support) focused on performance and health.



- **[ClusterControl](https://severalnines.com/)**  

  Database operations platform that includes monitoring, management, and automation for PostgreSQL clusters.



- **[Sematext](https://sematext.com/)**  

  Observability platform offering infrastructure and database monitoring, including PostgreSQL metrics and logs.



- **[Instana](https://www.ibm.com/products/instana)**  

  Automated application performance monitoring with database visibility, including PostgreSQL.



- **[New Relic Database](https://newrelic.com/)**  

  Database monitoring capabilities within the New Relic observability platform for PostgreSQL and other databases.



## Open-Source GitHub Projects

- **[pgwatch / pgwatch2](https://github.com/cybertec-postgresql/pgwatch)**  

  Flexible self-hosted PostgreSQL metrics monitoring and dashboarding solution with Grafana integration and multiple storage backends.



- **[PoWA (PostgreSQL Workload Analyzer)](https://github.com/powa-team/powa)**  

  Open-source performance analysis tool that captures and analyzes PostgreSQL workload statistics, including query performance over time.



- **[pgHero](https://github.com/ankane/pghero)**  

  Simple, practical open-source performance dashboard for PostgreSQL that highlights slow queries, unused indexes, and other actionable issues.



- **[pgBadger](https://github.com/darold/pgbadger)**  

  Fast PostgreSQL log analyzer that generates detailed HTML reports from database logs for performance and activity analysis.



- **[postgres_exporter / pgexporter](https://github.com/prometheus-community/postgres_exporter)**  

  Prometheus exporter for PostgreSQL metrics, enabling integration with Prometheus and Grafana monitoring stacks.



- **[Percona Monitoring and Management (PMM)](https://github.com/percona/pmm)**  

  Fully open-source monitoring and management platform for PostgreSQL (and other databases) with Query Analytics and system metrics.



- **[pg_stat_statements and core extensions](https://www.postgresql.org/docs/current/pgstatstatements.html)**  

  Built-in PostgreSQL extension that tracks execution statistics of SQL statements — the foundation for most monitoring tools.



- **[pg_stat_monitor](https://github.com/percona/pg_stat_monitor)**  

  Enhanced query statistics extension from Percona providing time-bucketed stats and additional insights.



- **[Grafana PostgreSQL dashboards](https://grafana.com/grafana/dashboards/)**  

  Community and official dashboards for visualizing PostgreSQL metrics collected via exporters.



- **[Additional open monitoring helpers](https://github.com/)**  

  Tools for vacuum monitoring, bloat detection, replication lag tracking, and custom health checks.



### Additional Strong Open-Source Options

- Starting with **pg_stat_statements** as the baseline for any PostgreSQL monitoring setup.

- Deploying **pgwatch** or **Percona PMM** for comprehensive self-hosted monitoring and dashboards.

- Using **pgHero** for quick, actionable performance insights with minimal setup.

- Running **pgBadger** periodically for deep log-based analysis.

- Integrating **postgres_exporter** + Prometheus + Grafana when already operating a metrics stack.

- Accepting that managed query insights, automatic index recommendations at scale, and seamless multi-cloud observability still favor specialized SaaS platforms (pganalyze, Datadog, etc.).



**Frameworks for building custom systems**: Enable pg_stat_statements → deploy postgres_exporter or pgwatch → store metrics in Prometheus/TimescaleDB/Influx → visualize with Grafana → add pgHero or PoWA for query-level insights → schedule pgBadger for log analysis → configure alerts. This stack is fully open and production-proven. Commercial platforms remain convenient for teams that prefer zero-ops monitoring with deep PostgreSQL-specific intelligence and support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Database monitoring tools access sensitive performance and potentially query data. Ensure proper access controls, network security, and compliance with data policies. Self-hosted solutions require ongoing maintenance and capacity planning. This list is not operational or security advice.



---

**Made for DBAs, platform engineers, and developers who run PostgreSQL in production.**

Let's keep PostgreSQL observability transparent, actionable, and as open as practical.
