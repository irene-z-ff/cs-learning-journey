# CS Learning Journey

My long-term learning log for building strong software-systems fundamentals and understanding modern AI/LLM systems from software to GPU.

## Current Focus — next 4–6 weeks

### C++ Fundamentals — ~70%
Goal: move from following patterns in an existing C++ codebase to understanding what the code does and why.

Current path:
- syntax, functions, struct/class
- STL containers
- pointers and references
- const
- stack vs heap
- object lifetime
- RAII and ownership
- smart pointers
- move semantics
- templates, lambdas, iterators, concurrency later

### Stanford CS336 / LLM Systems — ~30%
Goal: understand language models from implementation and systems layers, not just use LLM APIs.

Path: tokenization → Transformer → training → GPU performance → Triton / FlashAttention → distributed training → scaling → data → post-training and evaluation.

## Long-term Map

| Area | Role | Status |
| --- | --- | --- |
| C++ | Current engineering foundation | Active |
| LLM / CS336 | Main AI-systems learning line | Active |
| Computer Systems / CSAPP | Memory, cache, process, VM, networking | On demand |
| Distributed Systems | RPC, replication, consistency, fault tolerance | Backlog |
| Database Systems | Indexes, transactions, MVCC, WAL, query execution | Backlog |
| AI Systems | GPU, CUDA, Triton, distributed training | Gradual |
| BCI / EEG | Research branch: non-invasive speech decoding | Research |

## Repository Structure

```text
cpp/
systems/
distributed-systems/
database/
ai-systems/
llm/cs336/
bci-eeg/
questions/
projects/
templates/
```

## Learning Loop

**Real question → understand it → write a tiny example → explain it in my own words → commit it.**

The goal is not to collect notes. The goal is to leave evidence that I actually understand and can use each concept.

## Public Repository Rule

Never include proprietary employer code, internal APIs, identifiers, architecture, data, screenshots, or confidential information. Work-inspired examples must be generalized or synthetic.
