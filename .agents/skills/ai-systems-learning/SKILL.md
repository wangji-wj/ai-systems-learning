---
name: ai-systems-learning
description: Organize, implement, verify, and document low-level AI algorithm and systems learning materials in this repository. Use when adding or revising topics involving mathematics, neural networks, PyTorch internals, LLM fine-tuning, C++/Linux, CUDA kernels, or LLM inference and benchmarking.
---

# Maintain AI systems learning content

## Choose the destination

- Put mathematics in `01-math/`.
- Put model architectures and from-scratch neural network implementations in `02-deep-learning/`.
- Put PyTorch mechanisms and training tools in `03-pytorch/`.
- Put fine-tuning and alignment methods in `04-finetuning/`.
- Put C++, concurrency, and Linux exercises in `05-cpp-linux/`.
- Put CUDA kernels and GPU optimization in `06-cuda/`.
- Put serving, caching, scheduling, and inference benchmarks in `07-llm-inference/`.
- Put cross-cutting notes and reviews in `notes/`.

## Build a topic

1. State the problem, assumptions, notation, and learning objective.
2. Derive the key idea and track tensor shapes or memory layouts where relevant.
3. Add the smallest correct, runnable implementation.
4. Verify it against a trusted reference, numerical check, or focused test.
5. Add an optimized implementation only after establishing correctness.
6. Document commands, dependencies, results, limitations, and follow-up questions.

## Benchmark responsibly

- Record CPU/GPU model, OS, compiler, CUDA, framework, and driver versions.
- Record data type, input shape, batch size, warm-up, synchronization, and repetition count.
- Compare equivalent workloads and separate compile time from steady-state execution.
- Report correctness together with speed and memory results.
- Avoid unsupported performance claims; retain raw commands or scripts needed to reproduce them.

## Keep the repository clean

- Keep examples locally scoped; add per-topic dependencies rather than a premature global environment.
- Use Markdown and LaTeX for explanations and prefer primary references.
- Do not commit secrets, datasets, weights, checkpoints, profiler captures, or generated outputs.
- Preserve `.gitkeep` until a directory contains tracked learning material.

