---
layout: news-item
date: 2026-08-06
title: "AI4SE summer highlights"
tracks: [ 1, 2, 3, 4, 5 ]
---

From mid-May to early August 2026, the AI4SE collaboration between TU Delft and JetBrains Research continued to advance research across all five tracks. During this period, people presented work at international conferences, developed new benchmarks and evaluation methods, progressed several user studies, and expanded its work on the reliability of AI agent systems.

Highlights include:

- **Publications and conference presentations.** Ali Asgari from track 1 presented [*A Metamorphic Testing Approach to Diagnosing Memorization in LLM-Based Program Repair*](https://arxiv.org/abs/2604.21579) at QRS 2026. Ali’s work on test-case selection for code language models was also accepted at ISSTA 2026. [Ali’s work on why AI agents fail](https://arxiv.org/abs/2510.25423) got accepted at the Journal of Systems and Software. Daniele Cipollone from track 2 presented [*LibEvoBench*](https://arxiv.org/abs/2606.25402) and related code-world-model evaluation work at the [DL4Code](https://dl4c.github.io/) workshop at [ICML 2026](https://icml.cc/). Yuri Noviello from track 5 presented [*ANVIL: Analogies and Videos for Lecturers*](https://arxiv.org/abs/2605.16295) at AIED 2026 in Seoul and [*AI-Generated Traces for Novice Programmers*](https://arxiv.org/abs/2606.03288) at [ITiCSE 2026](https://iticse.acm.org/2026/) in Madrid.

- **More efficient evaluation of coding agents.** Ali Asgari from track 1 investigated whether the failure history of one coding agent can help identify difficult tasks for other agents. Preliminary results indicate that cross-agent transfer can reduce by approximately half the number of SWE-bench tasks needed to uncover 80% of an agent’s failures.

- **Testing the robustness of coding agents.** Andrei Dragoi from track 1 evaluated repository-level metamorphic transformations including identifier renaming, structural changes, and method reordering with Claude Code and Codex. Success rates remained broadly stable, although some transformations increased token usage and execution costs.

- **Adapting models to evolving software libraries.** Daniele Cipollone continued developing [*LibEvoBench*](https://arxiv.org/abs/2606.25402), a benchmark for evaluating whether code-generation models can correctly use APIs from different library versions. Alexandru Ojica used the benchmark to develop and evaluate version-specific LoRA specialists. His experiments showed that a model could learn an API introduced after its training cutoff, while also revealing possible interference with its knowledge of other APIs.

- **Understanding developer preferences and interactions.** Ilia Alenabi advanced the study of developer preferences for AI-generated software-engineering solutions. After refining the study design and moving to a participant-panel approach, the survey reached approximately 100 valid responses. Ziyou Li continued developing and evaluating ContextBranch, an interface for managing complex and non-linear AI coding conversations, while Agnia Sergeyuk worked with him on the user-study plan and survey. The team began participant onboarding and user testing.

- **Reliability and observability for multi-agent systems.** Tracks 3 and 4 — Roham Koohestani, Zahra Seyedghorban, Ioana Moruz and Egor Klimov — continued developing the Agentic Transfer Protocol and began bringing its capabilities to Koog, combining agent-to-agent communication with distributed OpenTelemetry trace collection. The team also extended its fault-injection infrastructure with semantic faults, early-failure-prediction experiments, and restart-based recovery strategies.

- **AI in computing education.** Yuri Noviello organized the Long-form Analogy Evaluation Challenge, which reached 17 participants, and began developing an explainable evaluator for analogical explanations.