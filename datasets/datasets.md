# Datasets

Datasets and benchmarks useful for evaluating reliability, verification, tool use, and failure detection in Agentic AI systems.

## 1. GAIA

**Source:** Hugging Face / GAIA Benchmark

GAIA is a benchmark for general AI assistants that evaluates tasks requiring reasoning, tool use, search, and different levels of autonomy. It is directly relevant to evaluating whether agentic systems can complete complex tasks reliably.

[Dataset](https://huggingface.co/datasets/gaia-benchmark/GAIA)

> Note: The GAIA dataset has access restrictions. Do not copy or redistribute its test data in this repository. :contentReference[oaicite:0]{index=0}

## 2. AgentBench

**Source:** THUDM / Tsinghua University

AgentBench is a benchmark for evaluating LLM-based agents across multiple environments, including operating systems, databases, knowledge graphs, web shopping, and web browsing. It is useful for studying agent reliability and failure across different environments.

[Dataset and Benchmark](https://github.com/THUDM/AgentBench)

The project provides Dev and Test splits and supports evaluation of agents operating in diverse environments. :contentReference[oaicite:1]{index=1}

## 3. WebArena

**Source:** Carnegie Mellon University

WebArena is a realistic, self-hostable web environment designed for evaluating autonomous agents on realistic web-based tasks. Its tasks involve interacting with websites and tools, making it useful for studying agent behavior, task completion, and functional correctness.

[Dataset and Environment](https://webarena.dev/)

WebArena also provides annotated programs that can be used to validate the functional correctness of task execution. :contentReference[oaicite:2]{index=2}
