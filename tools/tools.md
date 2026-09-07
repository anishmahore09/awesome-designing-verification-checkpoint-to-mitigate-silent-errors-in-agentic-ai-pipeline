# Tools and Libraries

Useful frameworks and tools for developing, evaluating, monitoring, and verifying Agentic AI systems.

## 1. LangChain

LangChain is a framework for building applications and agents powered by language models. It provides components for tool calling, workflows, retrieval, memory, and agent orchestration.

[Official Website](https://www.langchain.com/)

[GitHub](https://github.com/langchain-ai/langchain)

## 2. LangGraph

LangGraph is a framework for building stateful, multi-step agent workflows as graphs. Its explicit workflow structure is useful for implementing checkpoints, validation stages, and controlled agent execution.

[Official Documentation](https://docs.langchain.com/oss/python/langgraph/)

[GitHub](https://github.com/langchain-ai/langgraph)

## 3. Microsoft AutoGen

AutoGen is a framework for building applications involving multiple AI agents that communicate and collaborate to complete tasks. It is useful for studying multi-agent workflows and verification between agents.

[Official Documentation](https://microsoft.github.io/autogen/)

[GitHub](https://github.com/microsoft/autogen)

## 4. LlamaIndex

LlamaIndex provides tools for connecting language models with external data and building agentic applications. It supports retrieval, tool use, workflows, and evaluation.

[Official Website](https://www.llamaindex.ai/)

[GitHub](https://github.com/run-llama/llama_index)

## 5. DeepEval

DeepEval is an evaluation framework for LLM applications. It provides metrics and testing capabilities that can be used to evaluate hallucination, factuality, correctness, and other failure modes.

[Official Documentation](https://deepeval.com/)

[GitHub](https://github.com/confident-ai/deepeval)

## 6. Local Model Calibration Kit

The Local Model Calibration Kit is a runtime verification checkpoint for local LLM code generation. It runs as an OpenAI-compatible proxy between an agent harness and the inference server, scoring each generation's likelihood of being wrong from per-token logprob statistics calibrated per model on the user's own tasks, and returning a verdict plus ranked recovery interventions before tests run. Silent wrongness in generated code is flagged at generation time rather than propagating to later stages, and a gate mode can regenerate likely-wrong responses. Methodology and calibration evidence are public in the repository.

[Evidence reports](https://charlesdvaught-hash.github.io/calibration-kit-public/)

[GitHub](https://github.com/charlesdvaught-hash/calibration-kit-public)
