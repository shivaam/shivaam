### Hi, I'm Shivam 👋

📍 **Seattle** | 💼 **SDE @ Amazon** | 🎓 **MS CS, Indiana University Bloomington**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![Apache Flink](https://img.shields.io/badge/-Flink-E6526F?style=flat-square&logo=apache-flink&logoColor=white)
![AWS CDK](https://img.shields.io/badge/-CDK-FF9900?style=flat-square&logo=amazon-web-services&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white)

> Building developer tools and contributing to the Apache ecosystem. Focused on making Airflow's AWS providers more reliable, debuggable, and delightful to use.

---

## Open Source

### Apache Airflow — 10 merged PRs, 8 in review

I contribute across **AWS providers**, **scheduler reliability**, **UI**, and **developer tooling**.

**Merged**

- 🔧 **[Fix duplicate deadline callbacks with HA scheduler replicas](https://github.com/apache/airflow/pull/64737)** — fixed race condition causing duplicate alerts across scheduler replicas
- 🔍 **[Improve debuggability of SQS, Lambda, EC2, and RDS hooks](https://github.com/apache/airflow/pull/64661)** — added debug logging and exception chaining to 4 AWS hooks
- 🔍 **[Add debug logging and fix exception handling in DynamoDB hook](https://github.com/apache/airflow/pull/64629)** — same treatment for DynamoDB
- 🤖 **[Auto-triage: flag UI PRs missing screenshots from new contributors](https://github.com/apache/airflow/pull/64516)** — GitHub Actions bot for PR quality
- 🐛 **[Fix AwsBaseWaiterTrigger losing error details on deferred task failure](https://github.com/apache/airflow/pull/64085)** — error messages were being swallowed silently
- 🐛 **[Fix GlueJobOperator verbose logs not showing in deferrable mode](https://github.com/apache/airflow/pull/63086)** — logs were silently dropped
- 🐛 **[Replace expunge_all with expunge in MetastoreBackend](https://github.com/apache/airflow/pull/63080)** — prevented unintended session state corruption
- 🐛 **[Fix backfill marked complete before DagRuns are created](https://github.com/apache/airflow/pull/62561)** — backfills were lying about being done
- 🐛 **[Filter kwargs in AthenaSQLHook to prevent TypeError](https://github.com/apache/airflow/pull/62227)** — unexpected kwargs were crashing the hook
- 🌙 **[Add dark theme support for FAB Security pages](https://github.com/apache/airflow/pull/60908)** — dark mode for the security UI

**In Review**

- 🔧 **[Fix callback queueing skipping bundle init](https://github.com/apache/airflow/pull/64942)** — Scheduler
- 🔧 **[Fix backfill params not overriding existing DAG run conf](https://github.com/apache/airflow/pull/64939)** — Scheduler
- 🧪 **[Add deadline alert coverage to DAG endpoint tests](https://github.com/apache/airflow/pull/64815)** — Tests
- ⌨️ **[Make required params positional for airflowctl commands](https://github.com/apache/airflow/pull/64812)** — CLI
- 🎨 **[Rework Monaco editor theme to match Chakra UI palette](https://github.com/apache/airflow/pull/64748)** — UI
- ☁️ **[Add ExecuteCallback support to AWS ECS Executor](https://github.com/apache/airflow/pull/63657)** — AWS Providers

### Apache Flink

- 🐳 **[Bump testcontainers to 1.21.4 for Docker API compatibility](https://github.com/apache/flink-connector-aws/pull/242)** — flink-connector-aws

---

## Projects

- 🛠️ **[openapi-cli-gen](https://github.com/shivaam/openapi-cli-gen)** — Generate typed Python CLIs from OpenAPI specs with Pydantic model flattening into CLI flags
- ⚙️ **[miniflow](https://github.com/shivaam/miniflow)** — Build a workflow orchestrator from scratch — learn distributed systems, scheduling, and state machines
- 🚀 **[airflow-ec2](https://github.com/shivaam/airflow-ec2)** — Deploy Apache Airflow 3.x on EC2 in minutes with AWS CDK
- 💬 **[babblebox](https://github.com/shivaam/babblebox)** — Async real-time chat app with Whisper transcription, Django, and Apache Pulsar
- 🎬 **[one-take](https://github.com/shivaam/one-take)** — Cross-platform video recording and editing app
- 📱 **[onetake-ios](https://github.com/shivaam/onetake-ios)** — iOS client for One Take built with Swift
- 🍺 **[homebrew-tap](https://github.com/shivaam/homebrew-tap)** — Homebrew formulae for my developer tools

---

## GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/shivaam)

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=shivaam&show_icons=true&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shivaam&hide_border=true" alt="GitHub Streak" height="165" />
</p>

---

## What I'm Working On

- **Apache Airflow** — earning committer status through sustained contributions to AWS providers, scheduler, and UI
- **Apache Flink** — early-stage contributor to Flink AWS connectors
- **Developer tools** — building CLI tools that generate code from specs
- **Learning in public** — miniflow teaches distributed systems by building Airflow from scratch

---

## Connect

[![GitHub](https://img.shields.io/badge/-shivaam-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shivaam)
[![LinkedIn](https://img.shields.io/badge/-Shivam_Rastogi-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shivaamrastogi)

