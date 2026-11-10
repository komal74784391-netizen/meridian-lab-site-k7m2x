---
title: "Event-Rate Adaptive Sampling for Low-Power Depth Sensing"
authors: "R. Oyelaran, J. Marchetti, H. Sato"
venue: "International Conference on 3D Vision (3DV)"
year: 2024
status: "published"
codeurl: "https://github.com/komal74784391-netizen/evsampler-k7m2x"
abstract: >-
  Event cameras report brightness changes asynchronously and with very low
  latency. We show that coupling an event-rate controller with a sparse depth
  completion network cuts sensor-side power by roughly 40% while preserving
  depth accuracy on indoor benchmarks.
---

This paper introduces a closed-loop sampling policy that adapts the event camera bias to the observed event rate, plus a lightweight depth completion backbone trained on the resulting stream. The reference implementation is maintained in the lab's code account.
