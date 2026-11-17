<img align="right" width="112" src="https://raw.githubusercontent.com/cncf/people/main/images/artur-mkrtychian.jpg" alt="Artur Mkrtychian">

# Artur Mkrtychian

**Senior Platform / DevOps Engineer · CNCF Kubestronaut**

I build tooling around Kubernetes, AWS, and data platforms. My recent work includes database performance diagnostics, infrastructure automation, and upstream contributions to Trino.

[LinkedIn](https://www.linkedin.com/in/mkrtychian/) · [Technical writing](https://dev.to/arturmkr)

## Open-source contributions

- **Trino** — Added configurable field exclusion to HTTP query events so operators can send smaller payloads. [Merged PR #31585](https://github.com/trinodb/trino/pull/31585)
- **Trino Gateway** — Added optional HikariCP connection pooling so operators can bound database connection usage. [Merged PR #791](https://github.com/trinodb/trino-gateway/pull/791)
- **Trino Gateway CI** — Raised the build timeout from 20 to 30 minutes to address intermittent CI failures. [Merged PR #953](https://github.com/trinodb/trino-gateway/pull/953)
- **Testcontainers for Go** — Proposed a Trino Gateway module with managed or external PostgreSQL and helpers for integration tests. [Open PR #4056](https://github.com/testcontainers/testcontainers-go/pull/4056)

## Selected projects

| Project | What it does |
| --- | --- |
| [QuerySentinel](https://github.com/arturmkr/querysentinel) | Detects PostgreSQL query slowdowns and errors. An AI agent investigates findings with read-only database tools. MCP clients can inspect findings and trigger scans. |
| [Terraform AWS Ephemeral Secrets](https://github.com/arturmkr/terraform-aws-ephemeral-secrets) | Generates and versions AWS Secrets Manager values without writing secret values to Terraform plans or state. Includes separate environment deployment workflows. |
| [Resource Coordinator](https://github.com/arturmkr/resource-usage-app) | Gives people and CI jobs time-limited leases on shared test resources. PostgreSQL row locking prevents concurrent claims from taking the same resource. |
| [Mask Sensitive Data](https://github.com/arturmkr/mask-sensitive-data) | Redacts credentials and tokens from test reports and other GitHub Actions artifacts before publishing. |

## Labs and writing

- [OpenTelemetry lab](https://github.com/arturmkr/otel-fastapi-poc) — FastAPI instrumentation, an agent-to-gateway Collector setup, and examples of head and tail sampling.
- [JaCoCo guide](https://dev.to/arturmkr/how-to-measure-code-coverage-in-a-running-java-application-using-jacoco-5b13) — Collecting Java code coverage from a running application during functional tests. [Runnable example](https://github.com/arturmkr/jacoco-code-coverage-demo)
