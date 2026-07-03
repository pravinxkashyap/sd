# System Design Learning Path

A level-wise collection of GitHub repositories for mastering system design — from absolute beginner to advanced, with an AI engineering focus.

---

## Structure

```
system_design/
├── 01_beginner/          # Start here — no prerequisites
├── 02_intermediate/      # After you grasp the basics
├── 03_ai_engineer/       # ML/AI-specific system design (for you)
└── 04_advanced/          # Deep dives & real-world case studies
```

---

## 01_beginner

| Repo | What you'll learn |
|------|-------------------|
| **[system-design-101](01_beginner/system-design-101)** | Visual explanations of architecture patterns, communication protocols, microservices, cloud infra. Best entry point. |
| **[system-design-primer](01_beginner/system-design-primer)** | The #1 resource (335k+ stars). Covers scalability, caching, DBs, load balancing, CDNs, DNS, CAP theorem. Has Anki flashcards & interview prep. |

**Goal after this level:** Understand what system design is, key terminology, and common patterns.

---

## 02_intermediate

| Repo | What you'll learn |
|------|-------------------|
| **[system-design](02_intermediate/system-design)** | Structured course-like path: distributed systems, service communication, data storage strategies, reliability patterns (circuit breakers, retries, bulkheads). |
| **[system-design-academy](02_intermediate/system-design-academy)** | Distributed systems, event-driven architecture, network fundamentals, published through a structured curriculum. |

**Goal after this level:** Design a medium-scale system independently.

---

## 03_ai_engineer

| Repo | What you'll learn |
|------|-------------------|
| **[machine-learning-systems-design](03_ai_engineer/machine-learning-systems-design)** | Chip Huyen's ML systems design booklet. Covers project setup → data pipeline → modeling → serving/deployment. Includes 27 open-ended ML system design questions with community answers. |
| **[dmls-book](03_ai_engineer/dmls-book)** | Repo for "Designing Machine Learning Systems" (O'Reilly 2022). Full ML lifecycle: feature stores, model deployment, monitoring, infrastructure, MLOps. |
| **[agentic-design-patterns](03_ai_engineer/agentic-design-patterns)** | 29 essential agentic design patterns for building intelligent AI systems. Interactive HTML tutorial. Covers prompt chaining, routing, multi-agent collaboration, reflection, tool use, planning, and more. |

**Goal after this level:** Design production ML/AI systems and agentic architectures.

---

## 04_advanced

| Repo | What you'll learn |
|------|-------------------|
| **[awesome-scalability](04_advanced/awesome-scalability)** | Curated case studies from Google, Netflix, Uber, Amazon, Twitter, etc. Real architecture breakdowns of how the biggest systems work. |
| **[system-design-resources](04_advanced/system-design-resources)** | Deep dives on rate limiting, API gateways, distributed logs, database sharding, messaging systems. |

**Goal after this level:** Reason about trade-offs in real-world large-scale systems architecture.

---

## Suggested Learning Order

1. `01_beginner/system-design-101` — get the big picture visually
2. `01_beginner/system-design-primer` — build fundamentals
3. `02_intermediate/system-design` — structured intermediate path
4. `03_ai_engineer/machine-learning-systems-design` + `dmls-book` — AI-specific design
5. `03_ai_engineer/agentic-design-patterns` — cutting-edge AI agent architectures
6. `02_intermediate/system-design-academy` — fill remaining gaps
7. `04_advanced/awesome-scalability` + `system-design-resources` — real-world case studies
