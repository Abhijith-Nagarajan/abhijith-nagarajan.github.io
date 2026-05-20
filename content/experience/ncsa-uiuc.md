---
title: "National Center for Supercomputing Applications"
track: "work"
placement: "top"
role: "Research Assistant, Generative & Agentic AI"
location: "Champaign, IL"
date: 2025-07-01
start: "2025-07"
end: "2025-12"
period: 4
periodLabel: "Jul 2025 – Dec 2025"
description: "Biomedical reasoning research on causal links between genetic perturbations and cancer phenotypes."
metric: "100K+ Neo4j triples · 0.64 F1 on BioASQ"
logo: "uiuc.svg"
tags:
  - "Biomedical AI"
  - "Biomedical NLP"
  - "Knowledge Graphs"
  - "Neo4j"
  - "Relation Extraction"
  - "LLM Reasoning"
  - "Multi-Hop Reasoning"
  - "ReAct Agents"
  - "LangGraph"
  - "HuggingFace"
  - "Transformers"
  - "PyTorch"
  - "Fine-Tuning"
  - "RAG"
  - "Ontologies"
---

## Context
At NCSA, I worked on improving reasoning and retrieval in biomedical AI systems by incorporating knowledge graphs into LLM workflows. The research focused on building a structured knowledge base of genes, phenotypes, and biomedical relationships to support causal question-answering over CRISPR perturbation data.

## What I Built
I built a Neo4j knowledge graph with 100K+ biomedical triples by harmonizing Monarch ontology data, creating a structured layer for multi-hop reasoning over biomedical entities.

I then developed a ReAct agent using LangGraph and DeepSeek-R1 to traverse the graph and support reasoning between genetic perturbations and phenotypic outcomes.

To expand the graph with new structured relationships, I fine-tuned HuggingFace REBEL on BioRED for biomedical relation extraction, achieving 0.64 F1 on BioASQ-style evaluation.

## Challenges
The main challenge was connecting unstructured biomedical information with structured reasoning. Biomedical entities and relationships are noisy, domain-specific, and spread across ontologies and literature, so the system needed a structured representation that LLM workflows could reason over more reliably.

## Impact & Takeaways
This experience strengthened my work in knowledge graphs, biomedical NLP, relation extraction, RAG-style reasoning, and agentic AI systems for scientific question-answering.
