---
title: MLModelScope
summary: An open-source, framework and hardware agnostic, extensible and customizable, distributed platform design for evaluating and profiling ML models across datasets/frameworks/systems.
tags:
  - Deep Learning
  - GPU
  - Benchmarking
  - Tools

date: '2019-06-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link:

image:
  caption: /img/carml.png
  focal_point:
---

The current Deep Learning (DL) landscape is fast-paced and is rife with non-uniform models, hardware/software (HW/SW) stacks, but lacks a DL benchmarking platform to facilitate evaluation and comparison of DL innovations, be it models, frameworks, libraries, or hardware. Due to the lack of a benchmarking platform, the current practice of evaluating the benefits of proposed DL innovations is both arduous and error-prone — stifling the adoption of the innovations.

In this work, we first identify 10 design features which are desirable within a DL benchmarking platform. These features include: performing the evaluation in a consistent, reproducible, and scalable manner, being framework and hardware agnostic, supporting real-world benchmarking workloads, providing in-depth model execution inspection across the HW/SW stack levels, etc. We then propose CarML, a DL benchmarking platform design that realizes the 10 objectives. CarML proposes a specification to define DL model evaluations and techniques to provision the evaluation workflow using the user-specified HW/SW stack. CarML defines abstractions for frameworks and supports board range of DL models and evaluation scenarios. We implement CarML as an open-source project with support for all major frameworks and hardware architectures.
