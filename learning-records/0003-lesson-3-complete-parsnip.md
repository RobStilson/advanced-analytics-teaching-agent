# 0003 — Lesson 3 Complete: Specifying Models with {parsnip}

**Date:** 2026-06-11
**Lesson:** 0003-model-specification-parsnip.html
**Score:** 3/3

## What Was Taught

- The fragmented base R modeling landscape and why parsnip solves it
- The three-component model spec: type + engine + mode
- `logistic_reg() %>% set_engine("glm") %>% set_mode("classification")`
- `fit()` with formula interface against training data
- `predict()` with `type = "prob"` for attrition risk scores
- Why probabilities beat class predictions for stakeholder presentations
- Engine swapping: rand_forest/ranger, boost_tree/xgboost — same downstream calls

## Key Insights

- Learner correctly identified type + engine + mode as the three components
- Learner correctly identified that only the spec lines change when swapping algorithms
- Learner correctly identified probability scores as more useful than class predictions for HR leadership

## Zone of Proximal Development

Three perfect scores — strong pattern of clean conceptual absorption.
Ready for {workflows}: bundling recipe + model spec into one object so preprocessing
and fitting always travel together. This is the lesson where the pieces start connecting.
