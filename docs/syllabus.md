---
title: Syllabus
nav_order: 3
---

# Syllabus

## Tutorial goals

- Introduce the fundamentals of GPU-accelerated data science and the RAPIDS ecosystem.
- Perform GPU-accelerated data loading, cleaning, and feature engineering using cuDF and Dask.
- Apply GPU-based machine learning workflows using cuML and GPU-enabled XGBoost.
- Conduct graph analytics workflows with cuGraph.
- Apply distributed hyperparameter optimization using Ray Tune for model selection.
- Highlight practical performance trade-offs between CPU and GPU workflows.
- Give attendees reusable materials they can continue working with after the tutorial.

## Intended audience

This tutorial is aimed at intermediate-level students, researchers, and practitioners in data science, AI, and scientific computing, including attendees interested in scaling model selection and tuning workflows.

## Prerequisites

- working knowledge of Python and notebooks
- familiarity with pandas or NumPy and basic machine learning concepts
- basic command line familiarity is recommended
- a laptop with internet access

## Format

Half-day, hands-on tutorial with about 3 hours of instruction, a 10-minute break, guided theory segments, and notebook-based exercises.

## Detailed schedule

| Session | Topic | Duration | Details |
| --- | --- | ---: | --- |
| 0 | Environment setup | 15 min | Access cloud GPU notebooks, verify dependencies and datasets, and review the collaboration workflow |
| 1 | RAPIDS Core I: DataFrames at scale | 40 min | RAPIDS architecture, CPU-to-GPU mapping, cuDF transformations, Dask-enabled execution, and timing comparisons |
| - | Break | 10 min | Short break |
| 2 | RAPIDS Core II: ML on GPUs | 40 min | GPU-native ML workflows, hands-on cuML exercises, and GPU-enabled XGBoost evaluation |
| 3 | RAPIDS Core III: Graph analytics | 30 min | Graph analytics use cases for scientific data and cuGraph algorithms |
| 4 | Advanced extension: Distributed HPO | 30 min | Search strategies, pruning, Ray Tune integration, and an optional Skorch/PyTorch tuning demo |
| 5 | Wrap-up and Q&A | 15 min | Workflow recap, key takeaways, discussion, and questions |

## Learning outcomes

By the end of the session, participants should be able to:

- explain the role of GPUs in modern data science workflows
- identify core RAPIDS libraries and their use cases
- use Dask, XGBoost, and Ray Tune in the context of GPU-accelerated workflows
- run and adapt the provided notebooks in a cloud environment
- compare CPU-style workflows with GPU-accelerated alternatives
