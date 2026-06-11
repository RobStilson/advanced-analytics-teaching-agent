# 0005 — Lesson 5 Complete: Feature Engineering with {recipes}

**Date:** 2026-06-11
**Lesson:** 0005-feature-engineering-recipes.html
**Score:** 3/3

## What Was Taught

- Why add_formula() is insufficient for real HR data (factors, scale differences, zero-variance)
- recipe() as a specification object — defines steps without executing them
- step_zv(), step_other(), step_dummy(), step_normalize() — the four core steps for attrition data
- Step ordering: step_other() must precede step_dummy()
- Swapping add_formula() for add_recipe() in a workflow
- prep() + bake() for inspecting recipe output outside a workflow
- Parameters estimated at fit() time, not at recipe() or add_recipe() time

## Key Insights

- Learner correctly identified that step_dummy() would encode rare levels before step_other() can collapse them
- Learner correctly identified normalization as a scale issue (not outlier removal or log transform)
- Learner correctly identified fit() — not recipe() or add_recipe() — as when parameters are estimated

## Zone of Proximal Development

Five consecutive 3/3 scores — strong, consistent mastery.
Ready for resampling and cross-validation: vfold_cv(), fit_resamples(), collect_metrics().
This is the "honest performance estimate" lesson — connecting back to the Pit of Success and
the test-set-is-sacred rule from Lesson 2.
