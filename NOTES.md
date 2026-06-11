# Notes

## User Preferences

- Prefers multiple choice questions when asked for clarifying information
- Wants to apply learning directly to People Analytics (ground all examples in HR data)
- Favors a practitioner orientation — the goal is stakeholder-ready deliverables, not academic depth

## Learner Profile

- R: Intermediate (tidyverse fluent)
- ML: Some hands-on (lm/glm experience, no systematic train/validate/test discipline yet)
- Role: People Analytics practitioner producing analyses for business stakeholders

## Teaching Notes

- Use IBM HR Attrition dataset as the running example wherever possible (familiar domain)
- Emphasize the WHY behind each tidymodels pattern — connect to problems they've hit before
- Chapter roadmap priority order for this mission:
  1. Ch 1 — Software for modeling (why tidymodels > caret/base R)
  2. Ch 5 — Data splitting (rsample)
  3. Ch 6 — parsnip (model specification)
  4. Ch 7 — workflows
  5. Ch 8 — recipes (feature engineering for HR data)
  6. Ch 9 — performance metrics (what matters for attrition models)
  7. Ch 10-11 — resampling and cross-validation
  8. Ch 12-13 — tuning
  9. Ch 18 — model explainability (essential for stakeholder presentations)
- Skip or skim: Ch 2 (user knows tidyverse), Ch 14-16 (advanced, lower priority for mission)
