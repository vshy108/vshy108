# Ho Peng Hou

I build, ship, and operate production-ready systems — Rust and Go backends, typed React web frontends, React Native mobile, and deployable services with full observability. My goal is to be a top-tier full-stack engineer who can reason about, measure, and recover production systems under real failure conditions.

---

## What I've Built

### Primary Portfolio

| Repo | Stack | What it proves |
|------|-------|----------------|
| [passengerResourceManagementRust](https://github.com/vshy108/passengerResourceManagementRust) | Rust · Axum · React · PostgreSQL | Full-stack Rust: layered architecture, spec-driven domain, auth, rate limiting, OpenAPI, React thin client, PostgreSQL persistence, Docker packaging |
| [inventoryReservationSystem](https://github.com/vshy108/inventoryReservationSystem) | Go · PostgreSQL | Go backend: idiomatic domain logic, PostgreSQL transactions, idempotency keys, OpenAPI contracts, concurrency correctness |
| [inventoryReservationSystemRust](https://github.com/vshy108/inventoryReservationSystemRust) | Rust | Rust domain correctness: reservation invariants, concurrency behavior, idempotency, persistence smoke tests |
| [benchmark_lab](https://github.com/vshy108/benchmark_lab) | Go · Rust · JVM · TypeScript · k6 | Measured performance: Go vs Rust vs JVM vs TypeScript under read-heavy, write-heavy, and same-SKU contention — real numbers, stated caveats |
| [system_design_playground](https://github.com/vshy108/system_design_playground) | Architecture docs · Diagrams | System design depth: CQRS, outbox, saga, service boundaries, C4/sequence diagrams, trade-off docs connected to benchmark evidence |
| [learn_chaos](https://github.com/vshy108/learn_chaos) | Toxiproxy · Pumba · stress-ng · k6 | Reliability proof: 10 deliberate failure experiments — container kill, network partition, latency injection, DB failover, bad rolling deploy, DNS failure, clock skew — with runbooks and RTO measurement |

### Supporting Portfolio

| Area | Repos |
|------|-------|
| Frontend | [TypeScriptReact](https://github.com/vshy108/TypeScriptReact) · [learn_react](https://github.com/vshy108/learn_react) · [learn_nextjs](https://github.com/vshy108/learn_nextjs) · [learn_react_native](https://github.com/vshy108/learn_react_native) · [learn_ui_systems](https://github.com/vshy108/learn_ui_systems) |
| DevOps / Cloud | [learn_devops](https://github.com/vshy108/learn_devops) · [learn_kubernetes](https://github.com/vshy108/learn_kubernetes) · [learn_aws_platform](https://github.com/vshy108/learn_aws_platform) · [learn_terraform](https://github.com/vshy108/learn_terraform) |
| Observability | [learn_opentelemetry](https://github.com/vshy108/learn_opentelemetry) · [learn_prometheus](https://github.com/vshy108/learn_prometheus) |
| Distributed systems | [event_streaming_lab](https://github.com/vshy108/event_streaming_lab) · [payment_platform_lab](https://github.com/vshy108/payment_platform_lab) · [learn_workflow_orchestration](https://github.com/vshy108/learn_workflow_orchestration) |
| Data / ML | [learn_data_engineering](https://github.com/vshy108/learn_data_engineering) · [learn_ai_engineering](https://github.com/vshy108/learn_ai_engineering) · [computer_vision_media_lab](https://github.com/vshy108/computer_vision_media_lab) |
| Security | [learn_security](https://github.com/vshy108/learn_security) |
| Languages | Rust · Go · TypeScript · Python · Java · Kotlin · Swift · Scala · Elixir · Haskell · OCaml · Clojure · Zig · C · C++ · C# · F# · 10+ more |

---

## Three-Layer Portfolio Signal

> **Measured it** → `benchmark_lab` captures Go vs Rust vs JVM vs TypeScript throughput, latency, and memory under real workloads with stated caveats.
>
> **Designed it** → `system_design_playground` connects each architecture pattern (CQRS, outbox, saga) to measured evidence and trade-off docs.
>
> **Broke it and it recovered** → `learn_chaos` proves the deployed services survive container kills, network partitions, DB failovers, and bad rolling deploys — with measured RTO per experiment.

---

## Stack

```
Backend      Rust (Axum) · Go
Frontend     React + TypeScript · React Native
Database     PostgreSQL · Redis
Deploy       Docker · Kubernetes · Terraform · GitHub Actions
Observe      Prometheus · Grafana · OpenTelemetry · Jaeger
Reliability  Toxiproxy · Pumba · stress-ng · k6
```

---

*Contact: [LinkedIn](https://linkedin.com/in/ho-peng-hou) · hopenghou@gmail.com*
