# Awesome-Postgresql-Monitoring

### Top PostgreSQL Monitoring Platforms Ecosystem

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
