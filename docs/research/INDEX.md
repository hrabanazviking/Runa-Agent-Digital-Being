# Research Corpus — INDEX

**50 technical research documents** covering the cutting-edge AI / CS / cognitive-science work most directly relevant to Runa's architecture.

**Status:** **COMPLETE 2026-05-17** — all 50 docs landed across 10 batches. Closing ADR: `docs/decisions/0003-research-corpus-2026-05-17.md`.

**Read with:** `README.md` (template + reading guide), `docs/architecture/{ARCHITECTURE,DOMAIN_MAP,DATA_FLOW}.md` (the subsystems each doc maps to), `docs/AI_OS_Research/AI_OS_RESEARCH_2026.md` (Volmarr's companion 2026 market landscape).

---

## Memory & Knowledge Storage (Muninn — `core/memory/`)

| # | Title | Commit |
|---|---|---|
| 01 | MemGPT and OS-style memory hierarchies for LLMs | 7d37de1 |
| 02 | Episodic memory architectures for AI agents | 7d37de1 |
| 03 | Vector embedding models: BGE, E5, Nomic, GTE, jina | 7d37de1 |
| 04 | RAG evolution: classic, hybrid, GraphRAG, agentic RAG | 7d37de1 |
| 05 | Long-context windows vs. retrieval: when each wins | 7d37de1 |
| 06 | Knowledge graphs for AI memory: triplets, ontologies, neuro-symbolic | 4cf9d72 |
| 07 | Memory consolidation and forgetting in artificial agents | 4cf9d72 |
| 08 | `sqlite-vss` and embedding-in-database approaches | 4cf9d72 |

## Agent Architectures (Hirð — `core/subagents/` — and kernel)

| # | Title | Commit |
|---|---|---|
| 09 | ReAct: reasoning + acting interleaved | 4cf9d72 |
| 10 | Reflexion: linguistic self-criticism for agents | 4cf9d72 |
| 11 | AutoGen and multi-agent orchestration frameworks | f3438b7 |
| 12 | Voyager: lifelong learning in open-ended environments | f3438b7 |
| 13 | Tree-of-Thoughts, Graph-of-Thoughts, structured reasoning | f3438b7 |
| 14 | Constitutional AI and the policy stack | f3438b7 |

## LLM Techniques (kernel + Heimskringla)

| # | Title | Commit |
|---|---|---|
| 15 | Prompt engineering: CoT, few-shot, structured outputs, system prompts | f3438b7 |
| 16 | Quantization for local inference: GPTQ, AWQ, GGUF, exllamav2 | 8fab2e5 |
| 17 | Mixture-of-Experts architectures | 8fab2e5 |
| 18 | Long-context attention: RoPE, YaRN, sliding window, attention sinks | 8fab2e5 |
| 19 | RLHF, DPO, KTO, and modern preference optimization | 8fab2e5 |
| 20 | Speculative decoding and inference acceleration | 8fab2e5 |

## Event-Driven & Concurrency (VERÐANDI)

| # | Title | Commit |
|---|---|---|
| 21 | Actor model and Erlang-style supervision trees | 43dfa62 |
| 22 | Event sourcing and CQRS for stateful AI systems | 43dfa62 |
| 23 | asyncio internals and structured concurrency in Python 3.11+ | 43dfa62 |
| 24 | Multiprocessing patterns and worker pools for AI workloads | 43dfa62 |

## World Modeling (WYRD bridge + core)

| # | Title | Commit |
|---|---|---|
| 25 | World models in RL: Dreamer, MuZero, IRIS | 43dfa62 |
| 26 | Entity-Component-System architectures for AI worlds | 3b4465b |
| 27 | Belief states and POMDPs | 3b4465b |
| 28 | Procedural generation and emergent narrative | 3b4465b |
| 29 | Embodied AI and grounded language | 3b4465b |

## Local & Edge Inference (Heimskringla)

| # | Title | Commit |
|---|---|---|
| 30 | llama.cpp and the GGML/GGUF ecosystem | 3b4465b |
| 31 | Edge LLM deployment on Raspberry Pi 5 (16 GB) | 7997f3c |
| 32 | Knowledge distillation: small models from big teachers | 7997f3c |
| 33 | Model routing and ensembles across local + cloud | 7997f3c |

## Voice & Multimodal (Rödd)

| # | Title | Commit |
|---|---|---|
| 34 | Wake-word detection: Porcupine, openWakeWord | 7997f3c |
| 35 | Modern neural TTS: VITS, StyleTTS2, XTTS, Piper, Kokoro | 7997f3c |
| 36 | Streaming ASR: Whisper, faster-whisper, Conformer | b957a26 |

## Safety, Trust, Sandboxing (policy + plugins)

| # | Title | Commit |
|---|---|---|
| 37 | Plugin sandboxing: in-process, subprocess, WASM via wasmtime | b957a26 |
| 38 | Prompt injection defenses | b957a26 |
| 39 | Output filtering, content moderation, jailbreak resistance | b957a26 |
| 40 | Audit logging and replay for AI agents | b957a26 |

## Cognitive Architecture & Neuroscience (kernel + identity + Eldhugi)

| # | Title | Commit |
|---|---|---|
| 41 | Global Workspace Theory applied to AI architecture | defcc20 |
| 42 | Predictive coding and the free-energy principle | defcc20 |
| 43 | Hofstadter's strange loops and self-reference | defcc20 |
| 44 | Sleep, replay, and memory consolidation analogues | defcc20 |

## Self-Improvement & Continual Learning (Eir + Hirð)

| # | Title | Commit |
|---|---|---|
| 45 | Continual learning: EWC, replay buffers, catastrophic forgetting | defcc20 |
| 46 | Automated prompt optimization: DSPy, OPRO | 96dd49f |
| 47 | Self-play and learned curricula | 96dd49f |

## SWE for AI Systems (runtime + Smiðja)

| # | Title | Commit |
|---|---|---|
| 48 | Testing AI agents: snapshot, property, simulation | 96dd49f |
| 49 | Observability for LLM systems: traces, evals, token accounting | 96dd49f |
| 50 | Local agent orchestration: Hermes, OpenClaw, MCP servers | 96dd49f |

---

## Companion material (not part of the 50-doc corpus)

| File | Author | Notes |
|---|---|---|
| `../AI_OS_Research/AI_OS_RESEARCH_2026.md` | Volmarr Wyrd, 2026-05-17 | 2026 market landscape for AI OS as consumer platform, agent runtime, protocol layer, and OS-research direction. Substantively complements the agent-architecture focus of this corpus with current industry signals (Google Gemini/Googlebook, Microsoft Copilot+, Apple Foundation Models, MCP/AAIF, the OS-shaped research frontier). |

---

## Batch history

| Batch | Commit | Docs |
|---|---|---|
| P0 | 3d1f1fc | TASK + INDEX + folder README |
| B1 | 7d37de1 | 01–05 (Memory part 1) |
| B2 | 4cf9d72 | 06–10 (Memory part 2 + Agent part 1) |
| B3 | f3438b7 | 11–15 (Agent part 2 + LLM part 1) |
| B4 | 8fab2e5 | 16–20 (LLM part 2) |
| B5 | 43dfa62 | 21–25 (Concurrency + World part 1) |
| B6 | 3b4465b | 26–30 (World part 2 + Local part 1) |
| B7 | 7997f3c | 31–35 (Edge + Voice part 1) |
| B8 | b957a26 | 36–40 (Voice part 2 + Safety) |
| B9 | defcc20 | 41–45 (Cognitive + Self-improvement part 1) |
| B10 | 96dd49f | 46–50 (Self-improvement part 2 + SWE) |
| Closing | (this commit) | INDEX update + ADR-0003 + memory |

Total: ~370 KB across 50 documents, ~7 KB average. Each doc structured per the seven-section template in `README.md`.
