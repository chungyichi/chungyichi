# Hi, I'm Chung-Yi 👋

I mainly contribute to **Apache Kafka** and **Apache YuniKorn**.
I like distributed systems and schedulers, and I am learning formal verification and defensive security.

🌐 Website: [chungyichi.github.io](https://chungyichi.github.io)
🤝 I learn open source with the community [opensource4you](https://github.com/opensource4you) (源來適你, Apache Taipei).

## Apache Kafka

| Date | Change | Ticket |
|---|---|---|
| 2026-11-15 | [#24231](https://github.com/apache/kafka/pull/24231): remove `GroupConfigManager#close` | MINOR (no ticket) |
| 2026-11-12 | [#23946](https://github.com/apache/kafka/pull/23946): use the ZK controller epoch when writing partition state znodes (ZK to KRaft migration) | KAFKA-20488 |
| 2024-07-16 | [#16588](https://github.com/apache/kafka/pull/16588): unit test for an immutable return value | KAFKA-17133 |

## Apache YuniKorn

| Date | Change | Ticket | Status |
|---|---|---|---|
| 2026-11-26 | [b964ac3ef](https://github.com/apache/yunikorn-release/commit/b964ac3ef): run `make perf-tools` in the pre-commit check | [YUNIKORN-3553](https://issues.apache.org/jira/browse/YUNIKORN-3553) | Merged |
| 2026-11-26 | [ea8adfd5a](https://github.com/apache/yunikorn-k8shim/commit/ea8adfd5a): e2e tests for application completion and app ID reuse | [YUNIKORN-3529](https://issues.apache.org/jira/browse/YUNIKORN-3529) | Merged |
| 2026-11-23 | [99d32b491](https://github.com/apache/yunikorn-k8shim/commit/99d32b491): e2e tests for application rejection | [YUNIKORN-3528](https://issues.apache.org/jira/browse/YUNIKORN-3528) | Merged |
| 2026-10-27 | [c85430617](https://github.com/apache/yunikorn-site/commit/c85430617): remove an outdated docs tip about `quota.preemption.delay` | [YUNIKORN-3526](https://issues.apache.org/jira/browse/YUNIKORN-3526) | Merged |
| | Update the perf-tools build path in the performance tutorial | [YUNIKORN-3604](https://issues.apache.org/jira/browse/YUNIKORN-3604) | Assigned, no PR yet |

## Other contributions

- 2024-07-29, Apache Gravitino: [#4102](https://github.com/apache/gravitino/pull/4102) support partition events for the event listener
- 2020-08-27, VS Code Python: [#13439](https://github.com/microsoft/vscode-python/pull/13439) remove "no-reload" from the default debug configurations

## What I'm learning

- How Kafka's ZK to KRaft migration keeps its state consistent
- How YuniKorn schedules pods (placement rules, queues, gang scheduling)
- Formal verification and defensive code review
