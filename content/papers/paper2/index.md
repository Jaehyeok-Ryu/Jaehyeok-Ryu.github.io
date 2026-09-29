---
title: "Futurism: Accelerating K-Means Clustering on Embedded Systems via Vector Engines"
# Crossref currently lists only the publication year (2026).
# Add date once the exact publication date is confirmed on IEEE Xplore.
tags: ["k-means","heterogeneous computing","SIMD","vector engines","embedded systems"]
author: ["**Jaehyeok Ryu**","Dowoong Kong","Yiseok Lee","Minseong Gil","Gunjae Koo","Myung Kuk Yoon","Yunho Oh"]
description: "An English summary and metadata for 'Futurism', a heterogeneous K-means clustering framework that uses CPU SIMD capabilities and dynamic CPU-GPU workload distribution to improve performance on embedded systems."
summary: "Futurism combines SIMD-based distance computation, a sample-wise data layout, and dynamic CPU-GPU workload distribution, achieving a 10% end-to-end speedup over prior CPU-GPU heterogeneous implementations on NVIDIA Jetson Orin AGX."
cover:
doi: "10.1109/LES.2026.3732530"
---

##### Summary

This paper presents Futurism, a heterogeneous K-means clustering framework for
mobile platforms operating under tight power and performance constraints. While
GPU-accelerated implementations offer substantial parallelism, they can leave
CPUs underutilized and spend significant time stalled on memory accesses. Earlier
CPU-GPU approaches use both processors but rely mainly on scalar CPU execution,
leaving the CPU's SIMD capabilities underused.

Key techniques include:

- Using SIMD instructions for distance computation on the CPU
- Organizing data in a sample-wise layout to improve CPU-side execution
- Dynamically distributing workloads across CPUs and GPUs to improve resource
  utilization

Together, these optimizations deliver a 10% end-to-end speedup over prior
CPU-GPU heterogeneous implementations on NVIDIA Jetson Orin AGX.

---

##### Download & Original

- IEEE Xplore page: https://ieeexplore.ieee.org/document/11690603

---

##### Copyright note

The full text of the paper is available from IEEE Xplore and is subject to IEEE
copyright. This page provides an original English summary and metadata only;
consult the IEEE PDF for the complete article.
