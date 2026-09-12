---
title: "LeanStream"
subtitle: "GPU-Centric LLM Runtime for Compute-I/O Scheduling"
collection: portfolio
date: 2026-09-01
venue: "ACM MobiCom 2026"
permalink: /research/leanstream/
paperurl: "https://arxiv.org/pdf/2609.03079"
---

LeanStream is a GPU-centric LLM inference runtime for models whose weights do not fit in GPU memory. It continuously refines weight priorities from partial GPU results, asynchronously streams high-priority weights from storage, and executes loaded weights as they arrive to overlap I/O with computation. On edge SoCs, fine-grained CPU-GPU coordination through unified memory and custom GPU kernels delivers up to 2.1× higher token-generation throughput and 7.5× lower memory usage. A server-side extension using persistent GPU kernels for remote weight streaming is in development.
