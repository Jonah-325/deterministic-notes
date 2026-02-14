# Deterministic Execution

This repository explores deterministic execution as a structural alternative to speculation-driven processor architectures.
The focus is architectural: scheduling vs. speculation, effective vs. peak bandwidth, and execution determinism in latency-sensitive systems.

---
## Why Determinism Now?

Compute performance continues to scale, but memory latency and variability remain dominant constraints. Modern CPUs and GPUs rely heavily on speculative mechanisms to hide uncertainty. This repository examines an alternative: treating latency as a scheduled event rather than a hazard.

## Structure

## Essays

### Deterministic Execution
- [Reevaluating Speculative Execution in Real-Time Systems](deterministic-execution/reevaluating-speculation.md)

## Architectural Position

Deterministic execution does not reduce memory latency.
It removes execution uncertainty from the critical path.

That distinction defines the design space explored here.

