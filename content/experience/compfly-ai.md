---
title: "CompFly AI"
track: "work"
role: "Software Engineer, Applied AI"
location: "Livermore, CA"
date: 2025-12-01
start: "2025-12"
end: "present"
period: 5
periodLabel: "Dec 2025 – Present"
description: "Developed AI evaluation frameworks, red-teaming workflows, and inference systems to improve the reliability, safety, and robustness of agentic AI applications."
metric: "+15% detection coverage · sub-10–150 ms inference"
logo: "compfly.svg"
tags:
  - "Agentic AI"
  - "LLM Evaluation"
  - "AI Safety"
  - "Red Teaming"
  - "Multi-Agent Systems"
  - "LangGraph"
  - "CrewAI"
  - "MCP"
  - "Python"
  - "FastAPI"
  - "Kubernetes"
  - "GKE"
  - "CI/CD"
  - "Model Inference"
  - "Runtime Reliability"
  - "MLOps"
---

## Context
At CompFly AI, I work as an Applied AI Engineer across AI agent evaluation, model validation, runtime security, and agent workflow development.

My work centers on a core product question: how do we measure whether an AI security system behaves deterministically before release? In agentic systems, reliability is not just about a single model response. It depends on how the system behaves across tools, memory, multi-step workflows, runtime protections, and adversarial scenarios.

## What I Built
I built a 0-to-1 Python/FastAPI evaluation framework that generates 100+ synthetic adversarial scenarios and evaluates model behavior using confusion-matrix metrics, pass-rate analysis, and benchmark-driven scoring.

I also designed sampling experiments across multiple benchmark datasets to tune confidence thresholds for internal detection metrics, reducing false positives and improving detection coverage by 15%.

In parallel, I built and tested LangGraph and CrewAI agents with MCP servers, validating product behavior across tool use, memory handling, and multi-step LLM interactions. I also supported automated adversarial evaluations through Snapshot ID tracking and GitHub Actions CI/CD pipelines.

## Challenges
The main challenge was making agent behavior measurable. Agentic workflows can fail in subtle ways: tool misuse, memory poisoning, inconsistent detection, objective drift, runtime instability, or regressions that only appear across multi-turn interactions.

Another challenge was reliability under deployment conditions. I resolved pod failures, concurrency bottlenecks, and memory issues for 10+ LangGraph/CrewAI agents deployed on Kubernetes/GKE.

## Impact & Takeaways
The evaluation framework became the product's core validation layer, helping evaluate model behavior before release. False positives dropped and detection coverage improved by 15%, while the deployment work ensured 10+ agents ran reliably on GKE.

This experience taught me how to turn ambiguous AI product risks into measurable evaluation systems and build infrastructure that makes agent behavior easier to test, debug, and improve.
