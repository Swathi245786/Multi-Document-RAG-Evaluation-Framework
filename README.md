# Multi-Document RAG Evaluation Framework

A research-oriented project exploring multi-document Retrieval-Augmented Generation (RAG), retrieval strategies, and top-k context selection.

## Project Overview

This repository contains research documentation, configuration examples, and presentation materials related to evaluating multi-document RAG systems.

The research discusses:
- TF-IDF and BM25 retrieval
- Hybrid retrieval
- Maximum Marginal Relevance (MMR)
- Retrieval and reranking
- Multi-document evidence coverage
- Answer-quality evaluation

## Repository Structure

- `configs/` — Example pipeline configurations
- `src/` — JavaScript scripts for generating project reports and presentations
- `reports/` — Research paper, presentations, diagrams, and supporting documents
- `results/` — Intended location for evaluation outputs
- `requirements.txt` — Listed Python dependencies
- `package.json` — Node.js project dependencies

## Research Documents

- `reports/main.pdf` — Research paper
- `reports/final_summary_report.pdf` — Summary report
- `reports/presentation.pptx` — Project presentation
- `reports/pipeline_flowchart.svg` — Pipeline diagram

## Evaluation Metrics Discussed

- Recall@k
- Mean Reciprocal Rank (MRR)
- Multi-document hit rate
- Answer exact match
- Answer F1

## Implementation Status

This repository currently includes research artifacts, configuration examples, and JavaScript report-generation scripts.

The Python evaluation pipeline referenced in earlier project documentation (`src/run_real_pipeline.py` and `src/rag_pipeline/`) is not included in this repository.

The configuration files are provided as examples. A runnable end-to-end Python RAG benchmark is not currently available here.

## Future Work

- Add the Python RAG evaluation pipeline
- Integrate HotpotQA and RAMDocs datasets
- Generate reproducible evaluation results
- Compare retrieval and reranking strategies
