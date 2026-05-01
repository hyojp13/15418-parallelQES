---
title: Parallel Quadric Error Simplification
---


**Eugene Lee** (eugenel), **Hyojae Park** (hyojaep)

[Summary](#summary) | [Proposal](#proposal) | [Milestone](#milestone) | [Final Report](#final-report)

---

## Summary

We are going to implement a parallel version of Quadric Error Metric (QEM)
mesh simplification using OpenMP and SIMD vectorization. Our project will
focus on effective mesh partitioning, robust handling of boundary conflicts, ef-
ficient recombination of mesh partitions, and the design of relaxed or batched
priority queue strategies to enable scalable parallel edge collapses while preserv-
ing mesh quality. We will analyze parallel performance and scalability and its
tradeoffs with mesh quality.

## Proposal

<iframe src="./proposal.pdf" width="100%" height="800px">
</iframe>
[direct link](./proposal.pdf)

## Milestone

<iframe src="./milestone.pdf" width="100%" height="800px"> </iframe> [direct link](./milestone.pdf)

## Final Report

<iframe src="./final.pdf" width="100%" height="800px"> </iframe> [direct link](./final.pdf)