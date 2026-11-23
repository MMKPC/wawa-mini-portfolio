# AYO Mini

AYO Mini is Matthew E. Mitchell’s local document-retrieval capstone at MMKPC Studios. The GitHub repository name remains wawa-mini-portfolio because the project began as WAWA Mini; the continuation is named AYO Mini, and older coursework keeps its original name.

## What it demonstrates

- Persistent keyword search with SQLite FTS5.
- Local semantic retrieval using Nomic embeddings through Ollama.
- A hybrid search path that combines ranked results with reciprocal rank fusion.
- Source-linked results: the Rafy demonstration lets a viewer select a frame and inspect its associated scene note and documented cue.

The prototype returns source passages for a person to inspect. It does not generate final answers, edit projects, or act as an autonomous agent.

## Public evidence

- [AYO Mini project journal and demo site](https://mmkpc.github.io/wawa-mini-portfolio/)
- [AYO Mini case study on MMKProspects](https://mmkprospects.com/case-studies/ayo-mini/)
- [Capstone reflection and Rafy demonstration](https://mmkpc.github.io/wawa-mini-portfolio/posts/capstone-reflection.html)
- [MMKPC Studios portfolio](https://mmkprospects.com/)

This repository contains the public project journal and showcase pages, not the private application source or production notes.

## Evaluation snapshot

On the October 23, 2026 synthetic fixture, the OR/BM25 keyword path recorded 0.980 macro Recall@5 and 1.000 MRR@5, with a 0.96 ms median ranking time. The fixture contains 50 synthetic notes and 25 answerable queries. The labels were not independently validated by human reviewers, so these numbers describe that fixture only; they do not establish performance on real studio documents.

## Contribution and development

I framed the retrieval problem, set the source-preserving behavior and evaluation questions, and shaped the Rafy frame-to-note demonstration. AI coding assistance contributed during implementation; I directed the project decisions and reviewed the observed results. The capstone was defended on November 20, 2026.

## Naming

WAWA Mini was the original coursework project. AYO Mini is its continued portfolio identity. Existing submissions and historical artifacts retain the WAWA Mini name.
