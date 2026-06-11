# Issue Tracker: GitHub

Issues live in GitHub Issues. Use the `gh` CLI for all issue operations.

## Creating issues

```shell
gh issue create --title "Title" --body "Body" --label "needs-triage"
```

## Listing issues

```shell
gh issue list
gh issue list --label "ready-for-agent"
```

## Updating issues

```shell
gh issue edit <number> --add-label "needs-info" --remove-label "needs-triage"
gh issue close <number>
```

## Commenting on issues

```shell
gh issue comment <number> --body "Comment text"
```

## Notes

- Always apply `needs-triage` when creating a new issue
- Use the label vocabulary defined in `docs/agents/triage-labels.md`
- The `gh` CLI must be authenticated: run `gh auth status` to verify
