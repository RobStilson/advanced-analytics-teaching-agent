# 0004 — Lesson 4 Complete: Bundling with {workflows}

**Date:** 2026-06-11
**Lesson:** 0004-workflows.html
**Score:** 3/3

## What Was Taught

- The preprocessing amnesia problem — silent errors from inconsistent preprocessing on new data
- workflow() as a container bundling preprocessor + model spec
- Building a workflow: add_model(), add_formula(), fit(), predict()
- Fitted workflow stores training-set preprocessing parameters automatically
- update_model() for fair algorithm comparisons
- saveRDS/readRDS as the production deliverable pattern

## Key Insights

- Learner correctly identified preprocessing consistency as the primary benefit
- Learner correctly identified that predict() applies preprocessing automatically
- Learner correctly identified add_formula() vs add_recipe() distinction (column selection vs full feature engineering)

## Zone of Proximal Development

Four consecutive 3/3 scores. Learner is ready for {recipes}: the hands-on,
HR-data-specific feature engineering lesson. Key steps: recipe(), step_dummy(),
step_normalize(), step_zv(), and plugging the recipe into a workflow via add_recipe().
