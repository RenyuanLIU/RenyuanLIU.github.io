---
title: "TokenFlow"
subtitle: "Responsive LLM Serving via Preemptive Scheduling"
collection: portfolio
date: 2026-04-27
venue: "EuroSys 2026"
permalink: /research/tokenflow/
paperurl: "https://dl.acm.org/doi/pdf/10.1145/3767295.3769328"
---

TokenFlow is a responsive LLM serving system with buffer-aware preemptive scheduling built on SGLang. Its scheduler tracks each request's buffered tokens and target consumption rate, pausing requests that are overproducing and resuming those running low to maintain responsive streaming under bursty workloads. Proactive KV cache migration between GPU and CPU memory overlaps cache movement with computation, improving effective throughput by up to 82.5% and reducing P99 time to first token by up to 80.2%.
