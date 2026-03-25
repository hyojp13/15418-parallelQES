---
title: Parallel Quadric Error Simplification
---

# Parallel Quadric Error Simplification


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

[Read the proposal](./proposal.pdf)

## Milestone

[Read the milestone report](./milestone.pdf)

## Final Report

[Read the final report](./final_report.pdf)