# 0002 — Lesson 2 Complete: Splitting Your HR Data

**Date:** 2026-06-11
**Lesson:** 0002-splitting-data-rsample.html
**Score:** 3/3

## What Was Taught

- The data budget metaphor — test set is a one-shot finite resource
- `initial_split()` with `prop` and `strata` arguments
- Why attrition data (16% imbalance) requires stratified splitting
- `training()` and `testing()` extraction functions
- `initial_time_split()` for time-ordered HR data (engagement surveys, headcount)
- The "test set is sacred" rule — touch once, at the very end

## Key Insights

- Learner correctly identified strata as preserving class proportions (not controlling split size)
- Learner correctly identified that test set evaluation happens once, after all decisions are finalized
- Learner correctly identified `initial_time_split()` for temporal data

## Zone of Proximal Development

Two perfect scores in a row — learner is absorbing concepts cleanly.
Ready for parsnip: model type / engine / mode, fit(), predict() with probabilities.
