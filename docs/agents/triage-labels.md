# Triage Labels

| Role | Label |
|------|-------|
| Maintainer needs to evaluate | `needs-triage` |
| Waiting on reporter | `needs-info` |
| Fully specified, AFK-agent-ready | `ready-for-agent` |
| Needs human implementation | `ready-for-human` |
| Will not be actioned | `wontfix` |

## Bootstrap labels in a new GitHub repo

Run once to create the labels in your repo:

```shell
gh label create "needs-triage"    --color "#e11d48" --description "Maintainer needs to evaluate"
gh label create "needs-info"      --color "#f59e0b" --description "Waiting on reporter"
gh label create "ready-for-agent" --color "#10b981" --description "AFK-agent-ready"
gh label create "ready-for-human" --color "#3b82f6" --description "Needs human implementation"
gh label create "wontfix"         --color "#6b7280" --description "Will not be actioned"
```
