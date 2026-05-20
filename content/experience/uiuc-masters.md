---
title: "University of Illinois Urbana-Champaign"
track: "education"
role: "Master's in Statistics"
location: "Urbana-Champaign, IL"
date: 2023-08-01
start: "2023-08"
end: "2025-05"
period: 3
periodLabel: "Aug 2023 – May 2025"
description: "LLM research on Information Retrieval focused on entity relation extraction."
logo: "uiuc.svg"
tags:
  - "Statistics"
  - "Machine Learning"
  - "Information Retrieval"
  - "LLM Research"
  - "Entity Relation Extraction"
  - "NLP"
  - "Biomedical AI"
  - "Knowledge Graphs"
  - "RAG"
  - "Python"
  - "Statistical Modeling"
  - "Data Science"
---

## Context
For my UIUC research project, I worked on **SHERPA**, a semi-structured RAG framework designed to improve retrieval and reasoning by combining unstructured biomedical text with structured knowledge graphs.

Traditional RAG systems rely heavily on vector search over unstructured documents. Our goal was to explore whether adding structured memory through entity-relation extraction and knowledge graph construction could improve retrieval fidelity, reasoning, and answer quality for biomedical question answering.

## What I Built
My contribution focused on two components: **query classification** and **NER / relation extraction for triplet generation**.

For query classification, I worked on identifying whether biomedical queries were extractive or abstractive based on the level of reasoning required. I explored features such as query keywords, dependency depth, entity mentions, entity types, and query complexity. I also compared LLM-based classification with traditional machine learning methods such as Random Forest and XGBoost, achieving an F1 score of 0.64.

For knowledge graph construction, I worked on biomedical entity and relation extraction to convert unstructured PubMed-style text into structured triplets of the form `<entity, relation, entity>`. I experimented with relation extraction approaches and fine-tuned REBEL on BioRED to extract biomedical relation triplets that could be integrated into the downstream knowledge graph.

## Challenges
The main challenge was bridging unstructured biomedical text with structured reasoning. Biomedical queries often contain long entity names, nested clauses, and relationships that require more than direct keyword matching. This made query classification difficult because the system needed to distinguish between questions that could be answered directly and questions requiring multi-hop or abstract reasoning.

Another challenge was relation extraction quality. Extracted triplets needed to be accurate enough to support graph construction, but biomedical relation extraction is noisy due to entity ambiguity, relation label complexity, and long scientific sentence structures.

## Impact & Takeaways
This project gave me hands-on experience building components for a hybrid RAG system that combines vector retrieval with structured knowledge representation. My work on query classification helped reason about user intent and retrieval complexity, while the relation extraction pipeline supported the construction of a biomedical knowledge graph for downstream semantic retrieval.

The project strengthened my skills in biomedical NLP, query classification, dependency parsing, relation extraction, knowledge graph construction, RAG, and model evaluation. It also shaped how I think about retrieval systems: better answers require not only better embeddings, but also better understanding of query intent and structured relationships in the underlying knowledge.

For the full technical write-up — including the complete approach funnel and the REBEL fine-tuning setup — see the [SHERPA project page](/projects/sherpa-semi-structured-rag/).
