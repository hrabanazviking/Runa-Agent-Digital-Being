# Python Craft Corpus — INDEX

**50 technical documents** on building the most robust, error-correcting, self-healing, crash-proof, efficient, and stable Python software possible.

**Status:** Setup-stage. Numbers reserved for all 50; docs land in batches. See `TASK_runa_python_craft.md` for batch status.

**Read with:** `README.md` (template + reading guide), `docs/research/` (the conceptual companion corpus), `docs/architecture/{ARCHITECTURE,DOMAIN_MAP}.md` (the subsystems that will use these techniques).

---

## Robustness Fundamentals

| # | Title | Status |
|---|---|---|
| 01 | Exception design and error hierarchies in Python | pending |
| 02 | Result types vs exceptions: when to use which | pending |
| 03 | Defensive programming and Design by Contract | pending |
| 04 | Preconditions, postconditions, invariants | pending |
| 05 | Idempotency design and safe retries | pending |
| 06 | Retry strategies, exponential backoff, jitter | pending |
| 07 | Circuit breaker pattern in Python | pending |
| 08 | Bulkhead pattern and failure isolation | pending |
| 09 | Timeout patterns and deadline propagation | pending |
| 10 | Graceful degradation strategies | pending |

## Self-Healing & Supervision

| # | Title | Status |
|---|---|---|
| 11 | Crash-only software design | pending |
| 12 | Supervisor trees in Python | pending |
| 13 | Watchdog timers and liveness detection | pending |
| 14 | Health checks: liveness, readiness, startup | pending |
| 15 | Self-repair systems and reconciliation loops | pending |
| 16 | State machines for reliability | pending |
| 17 | Saga pattern and compensating transactions | pending |
| 18 | Chaos engineering and fault injection | pending |

## Concurrency Mastery

| # | Title | Status |
|---|---|---|
| 19 | asyncio advanced patterns: TaskGroup, timeout, cancellation | pending |
| 20 | Thread safety in Python: GIL, locks, atomics | pending |
| 21 | multiprocessing deep-dive: spawn vs fork, IPC | pending |
| 22 | concurrent.futures patterns: pools, futures, executors | pending |
| 23 | Async cancellation and shielded operations | pending |
| 24 | Queue and channel patterns | pending |

## Type Safety & Validation

| # | Title | Status |
|---|---|---|
| 25 | Type hints mastery: PEPs and idioms | pending |
| 26 | mypy strict mode and gradual typing | pending |
| 27 | Pydantic for runtime validation | pending |
| 28 | Protocol classes and structural typing | pending |
| 29 | Dataclasses, NamedTuple, attrs — when to use which | pending |

## Testing

| # | Title | Status |
|---|---|---|
| 30 | pytest mastery: fixtures, parameterization, marks, conftest | pending |
| 31 | Property-based testing with Hypothesis | pending |
| 32 | Mutation testing | pending |
| 33 | Snapshot and golden-file testing | pending |
| 34 | Integration and e2e testing patterns | pending |
| 35 | Test doubles: mocks, stubs, fakes, spies | pending |

## Performance

| # | Title | Status |
|---|---|---|
| 36 | Profiling Python: cProfile, py-spy, scalene, austin | pending |
| 37 | Memory profiling: tracemalloc, memray, objgraph | pending |
| 38 | Caching strategies and memoization | pending |
| 39 | Lazy evaluation patterns | pending |
| 40 | C extensions, Cython, Rust via PyO3 | pending |

## Architecture Patterns

| # | Title | Status |
|---|---|---|
| 41 | Dependency injection without frameworks | pending |
| 42 | Hexagonal architecture (ports & adapters) | pending |
| 43 | Event sourcing in Python — implementation | pending |
| 44 | Plugin architecture patterns | pending |
| 45 | Configuration management: Pydantic Settings, dynaconf | pending |

## Observability & Operations

| # | Title | Status |
|---|---|---|
| 46 | Structured logging in Python: structlog, loguru, stdlib | pending |
| 47 | Distributed tracing with OpenTelemetry (Python-side) | pending |
| 48 | Metrics: Prometheus exposition, OpenTelemetry metrics | pending |
| 49 | Graceful shutdown and signal handling | pending |
| 50 | Long-running process patterns: daemons, supervisors, restarts | pending |

---

## Batches

This corpus is being written in batches of 5. When a batch lands, the `Status` column above updates to its commit hash. See `TASK_runa_python_craft.md` for the operational plan.
