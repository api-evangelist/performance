# Performance (performance)
An index and topic collection covering API and web performance, including load testing, performance benchmarking, real user monitoring (RUM), Core Web Vitals measurement, latency profiling, distributed tracing, and application performance monitoring (APM). Performance engineering ensures that APIs and web applications meet latency, throughput, and reliability expectations under realistic and adversarial load. This collection brings together open-source load generators like k6, Apache JMeter, Locust, Gatling, and Artillery; managed load and chaos platforms like StormForge and Speedscale; synthetic and real-user measurement tools like Google PageSpeed, Pingdom, and Akamai; and APM and tracing platforms like Datadog, New Relic, Dynatrace, AppDynamics, Sentry, Honeycomb, Instana, Lightstep, SigNoz, Uptrace, OpenTelemetry, Jaeger, Grafana Tempo, Google Cloud Profiler, Google Cloud Trace, and AWS X-Ray.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Performance, Load Testing, Performance Testing, Real User Monitoring, Core Web Vitals, APM, Distributed Tracing, Latency

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Load Test Run Schema](https://raw.githubusercontent.com/api-evangelist/performance/refs/heads/main/json-schema/performance-load-test-run-schema.json)
- [JSONSchema - Web Vital Sample Schema](https://raw.githubusercontent.com/api-evangelist/performance/refs/heads/main/json-schema/performance-web-vital-sample-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/performance/refs/heads/main/json-ld/performance-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/performance/refs/heads/main/vocabulary/performance-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Load and Stress Testing | Open-source and managed load generators like k6, Apache JMeter, Locust, Gatling, and Artillery simulate concurrent users and traffic patterns against APIs to characterize throughput, error rate, and latency under load. |
| Performance Benchmarking | Repeatable, scripted benchmark runs establish performance baselines and detect regressions in CI/CD pipelines using tools like k6 Cloud, BlazeMeter, and StormForge. |
| Real User Monitoring (RUM) | RUM products like Akamai mPulse, Datadog RUM, New Relic Browser, Sentry Performance, and Pingdom capture latency, errors, and Core Web Vitals from real browser sessions in production. |
| Synthetic Monitoring and Web Vitals | Synthetic checks and lab-based audits from Google PageSpeed (Lighthouse), WebPageTest, and Pingdom measure Core Web Vitals (LCP, INP, CLS) and uptime from controlled environments. |
| Distributed Tracing | OpenTelemetry, Jaeger, Grafana Tempo, Honeycomb, Lightstep, Google Cloud Trace, and AWS X-Ray collect distributed traces across microservice calls to attribute latency to specific spans. |
| Application Performance Monitoring (APM) | APM platforms like Datadog APM, New Relic, Dynatrace, AppDynamics, Instana, SigNoz, and Uptrace correlate traces, metrics, and logs to surface slow transactions and code-level bottlenecks. |
| Profiling and Code Hotspots | Continuous profilers like Google Cloud Profiler and Datadog Continuous Profiler identify CPU, memory, and lock contention hotspots in running services. |
| Traffic Replay and Chaos | Tools like GoReplay and Speedscale capture production traffic and replay it against staging or new versions to validate performance and behavior before release. |

## Use Cases

| Name | Description |
|------|-------------|
| Pre-Release Load Testing in CI/CD | Engineering teams run k6 or JMeter scenarios on every pull request to verify that p95 latency and error rates stay within service-level objectives before merging. |
| Core Web Vitals Optimization | Web teams use Google PageSpeed, WebPageTest, and RUM data to optimize LCP, INP, and CLS to meet Google ranking and user-experience thresholds. |
| Capacity Planning and Scalability Validation | Platform teams use StormForge and BlazeMeter to drive sustained load tests against staging environments to determine maximum sustainable throughput and right-size infrastructure. |
| Latency Regression Detection | APM platforms like Datadog, New Relic, and Dynatrace alert on p95 and p99 latency regressions per endpoint or trace span after each deploy. |
| Production Traffic Replay | Teams use GoReplay or Speedscale to record real production traffic and replay it against release candidates to find performance and correctness regressions before rollout. |
| Distributed Trace Root-Cause Analysis | SREs use Honeycomb, Lightstep, Jaeger, or Grafana Tempo to drill into slow distributed traces and pinpoint the service, query, or downstream call responsible for tail latency. |
| Continuous Profiling of Hot Paths | Backend teams use Google Cloud Profiler or Datadog Continuous Profiler to identify CPU and memory hotspots in running services without rebuilding or redeploying. |

## Integrations

| Name | Description |
|------|-------------|
| k6 | Open-source Grafana Labs load testing tool that uses JavaScript test scripts to drive load against HTTP, gRPC, and WebSocket APIs, with optional k6 Cloud for distributed runs. |
| Apache JMeter | Open-source Apache Software Foundation load testing tool for HTTP, REST, databases, JMS, and more, widely used for protocol-level performance testing. |
| Gatling | High-throughput, Scala-based open-source load testing tool with code-as-test scenarios and detailed HTML reports. |
| Artillery | Modern Node.js load testing toolkit with YAML and JavaScript scenarios, designed for serverless and Kubernetes-native workloads. |
| StormForge | Performance and load testing platform that uses machine learning to optimize Kubernetes resource configurations and validate scalability. |
| Datadog | Observability and APM platform offering distributed tracing, real user monitoring, synthetic monitoring, and continuous profiling. |
| New Relic | Full-stack observability platform with APM, browser-based RUM, synthetic monitoring, distributed tracing, and infrastructure metrics. |
| OpenTelemetry | Vendor-neutral CNCF standard for collecting traces, metrics, and logs, used to instrument applications for any compatible APM or tracing backend. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Load Test Run Schema](json-schema/performance-load-test-run-schema.json)
- [Web Vital Sample Schema](json-schema/performance-web-vital-sample-schema.json)

### JSON Structure

- [Load Test Run Structure](json-structure/performance-load-test-run-structure.json)
- [Web Vital Sample Structure](json-structure/performance-web-vital-sample-structure.json)

### JSON-LD

- [Performance Context](json-ld/performance-context.jsonld)

## Vocabulary

- [Performance Vocabulary](vocabulary/performance-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across load testing, RUM, Core Web Vitals, and APM/tracing platforms

## Network

This index references the following API and web performance repositories:

- [k6](https://github.com/api-evangelist/k6)
- [Apache JMeter](https://github.com/api-evangelist/apache-jmeter)
- [Locust](https://github.com/api-evangelist/locust)
- [Gatling](https://github.com/api-evangelist/gatling)
- [Artillery](https://github.com/api-evangelist/artillery)
- [StormForge](https://github.com/api-evangelist/stormforge)
- [Speedscale](https://github.com/api-evangelist/speedscale)
- [GoReplay](https://github.com/api-evangelist/goreplay)
- [Google PageSpeed](https://github.com/api-evangelist/google-pagespeed)
- [Pingdom](https://github.com/api-evangelist/pingdom)
- [Akamai](https://github.com/api-evangelist/akamai)
- [Datadog](https://github.com/api-evangelist/datadog)
- [New Relic](https://github.com/api-evangelist/new-relic)
- [Dynatrace](https://github.com/api-evangelist/dynatrace)
- [AppDynamics](https://github.com/api-evangelist/appdynamics)
- [Instana](https://github.com/api-evangelist/instana)
- [Sentry](https://github.com/api-evangelist/sentry)
- [Honeycomb](https://github.com/api-evangelist/honeycomb)
- [Lightstep](https://github.com/api-evangelist/lightstep)
- [SigNoz](https://github.com/api-evangelist/signoz)
- [Uptrace](https://github.com/api-evangelist/uptrace)
- [OpenTelemetry](https://github.com/api-evangelist/opentelemetry)
- [Jaeger](https://github.com/api-evangelist/jaeger)
- [Grafana Tempo](https://github.com/api-evangelist/grafana-tempo)
- [Google Cloud Profiler](https://github.com/api-evangelist/google-cloud-profiler)
- [Google Cloud Trace](https://github.com/api-evangelist/google-cloud-trace)
- [AWS X-Ray](https://github.com/api-evangelist/aws-x-ray)
- [Grafana](https://github.com/api-evangelist/grafana)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
