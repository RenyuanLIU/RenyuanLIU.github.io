---
title: "DynaSpa"
subtitle: "Dynamic Sparse GPU Runtime"
collection: portfolio
date: 2024-11-04
venue: "ACM SenSys 2024"
permalink: /research/dynaspa/
paperurl: "https://dl.acm.org/doi/pdf/10.1145/3666025.3699348"
award: "Best Paper Award Nominee"
---

DynaSpa is a dynamic sparse GPU execution framework for convolution and attention. It selects custom GPU kernel variants for input-dependent sparsity patterns and uses sparsity-aware tiling to group irregular active regions into GPU-friendly work tiles, improving shared-memory/L1 reuse and reducing global-memory traffic. The system achieves up to 7.8× operator speedup.
