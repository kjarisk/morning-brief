---
date: 2026-05-06
slug: pytorch-xla-2-7-jax-bridge-vllm
title: "PyTorch/XLA 2.7: call JAX functions inside PyTorch, 5× vLLM TPU speedup"
category: ml-engineering
source_name: "PyTorch"
source_url: "https://pytorch.org/blog/pytorch-xla-2-7-release-usability-vllm-boosts-jax-bridge-gpu-build/"
tags: [pytorch, jax, xla, vllm, tpu, ml-engineering, open-source]
top_story: false
---

PyTorch/XLA 2.7 ships with three noteworthy additions for ML practitioners running workloads on TPUs. First, a new JAX bridge API lets you call JAX functions directly inside PyTorch models running on XLA — useful for accessing JAX-exclusive kernels like `jax.experimental.shard_alike` for improved sharding propagation. Second, a new Pallas-based ragged paged attention kernel supports mixed prefill-and-decode operations and delivers up to 5× speedup over the previous padded multi-query paged attention implementation for Llama-3-8B on vLLM TPU. Third, GPU build support is extended for workloads that span both GPU and TPU hardware.

The vLLM integration is the most practically impactful change for teams serving large models. The ragged paged attention kernel substantially increases inference throughput for variable-length sequences — a common real-world pattern — without requiring changes to model code. It is used in the `torchprime` project to enable support for the SplashAttention Pallas kernel.

Read more at [PyTorch Blog](https://pytorch.org/blog/pytorch-xla-2-7-release-usability-vllm-boosts-jax-bridge-gpu-build/).
