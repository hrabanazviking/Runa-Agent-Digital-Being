# Research Corpus — INDEX

**50 technical research documents** covering the cutting-edge AI / CS / cognitive-science work most directly relevant to Runa's architecture.

**Status:** Bootstrap-stage. Numbers reserved for all 50; docs land in batches. See `TASK_runa_research_corpus.md` for batch status.

**Read with:** `README.md` (template + reading guide), `docs/architecture/{ARCHITECTURE,DOMAIN_MAP,DATA_FLOW}.md` (the subsystems each doc maps to).

---

## Memory & Knowledge Storage (Muninn — `core/memory/`)

| # | Title | Status |
|---|---|---|
| 01 | MemGPT and OS-style memory hierarchies for LLMs | pending |
| 02 | Episodic memory architectures for AI agents | pending |
| 03 | Vector embedding models: BGE, E5, Nomic, GTE, jina | pending |
| 04 | RAG evolution: classic, hybrid, GraphRAG, agentic RAG | pending |
| 05 | Long-context windows vs. retrieval: when each wins | pending |
| 06 | Knowledge graphs for AI memory: triplets, ontologies, neuro-symbolic | pending |
| 07 | Memory consolidation and forgetting in artificial agents | pending |
| 08 | `sqlite-vss` and embedding-in-database approaches | pending |

## Agent Architectures (Hirð — `core/subagents/` — and kernel)

| # | Title | Status |
|---|---|---|
| 09 | ReAct: reasoning + acting interleaved | pending |
| 10 | Reflexion: linguistic self-criticism for agents | pending |
| 11 | AutoGen and multi-agent orchestration frameworks | pending |
| 12 | Voyager: lifelong learning in open-ended environments | pending |
| 13 | Tree-of-Thoughts, Graph-of-Thoughts, structured reasoning | pending |
| 14 | Constitutional AI and the policy stack | pending |

## LLM Techniques (kernel + Heimskringla)

| # | Title | Status |
|---|---|---|
| 15 | Prompt engineering: CoT, few-shot, structured outputs, system prompts | pending |
| 16 | Quantization for local inference: GPTQ, AWQ, GGUF, exllamav2 | pending |
| 17 | Mixture-of-Experts architectures | pending |
| 18 | Long-context attention: RoPE, YaRN, sliding window, attention sinks | pending |
| 19 | RLHF, DPO, KTO, and modern preference optimization | pending |
| 20 | Speculative decoding and inference acceleration | pending |

## Event-Driven & Concurrency (VERÐANDI)

| # | Title | Status |
|---|---|---|
| 21 | Actor model and Erlang-style supervision trees | pending |
| 22 | Event sourcing and CQRS for stateful AI systems | pending |
| 23 | asyncio internals and structured concurrency in Python 3.11+ | pending |
| 24 | Multiprocessing patterns and worker pools for AI workloads | pending |

## World Modeling (WYRD bridge + core)

| # | Title | Status |
|---|---|---|
| 25 | World models in RL: Dreamer, MuZero, IRIS | pending |
| 26 | Entity-Component-System architectures for AI worlds | pending |
| 27 | Belief states and POMDPs | pending |
| 28 | Procedural generation and emergent narrative | pending |
| 29 | Embodied AI and grounded language | pending |

## Local & Edge Inference (Heimskringla)

| # | Title | Status |
|---|---|---|
| 30 | llama.cpp and the GGML/GGUF ecosystem | pending |
| 31 | Edge LLM deployment on Raspberry Pi 5 (16 GB) | pending |
| 32 | Knowledge distillation: small models from big teachers | pending |
| 33 | Model routing and ensembles across local + cloud | pending |

## Voice & Multimodal (Rödd)

| # | Title | Status |
|---|---|---|
| 34 | Wake-word detection: Porcupine, openWakeWord | pending |
| 35 | Modern neural TTS: VITS, StyleTTS2, XTTS, Piper, Kokoro | pending |
| 36 | Streaming ASR: Whisper, faster-whisper, Conformer | pending |

## Safety, Trust, Sandboxing (policy + plugins)

| # | Title | Status |
|---|---|---|
| 37 | Plugin sandboxing: in-process, subprocess, WASM via wasmtime | pending |
| 38 | Prompt injection defenses | pending |
| 39 | Output filtering, content moderation, jailbreak resistance | pending |
| 40 | Audit logging and replay for AI agents | pending |

## Cognitive Architecture & Neuroscience (kernel + identity + Eldhugi)

| # | Title | Status |
|---|---|---|
| 41 | Global Workspace Theory applied to AI architecture | pending |
| 42 | Predictive coding and the free-energy principle | pending |
| 43 | Hofstadter's strange loops and self-reference | pending |
| 44 | Sleep, replay, and memory consolidation analogues | pending |

## Self-Improvement & Continual Learning (Eir + Hirð)

| # | Title | Status |
|---|---|---|
| 45 | Continual learning: EWC, replay buffers, catastrophic forgetting | pending |
| 46 | Automated prompt optimization: DSPy, OPRO | pending |
| 47 | Self-play and learned curricula | pending |

## SWE for AI Systems (runtime + Smiðja)

| # | Title | Status |
|---|---|---|
| 48 | Testing AI agents: snapshot, property, simulation | pending |
| 49 | Observability for LLM systems: traces, evals, token accounting | pending |
| 50 | Local agent orchestration: Hermes, OpenClaw, MCP servers | pending |

---

## Batches

This corpus is being written in batches of 5 (see `TASK_runa_research_corpus.md` §5). When a batch lands, the `Status` column above is updated to its commit hash.
