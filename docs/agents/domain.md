# Domain Docs

Single-context layout.

| File | Purpose |
|------|---------|
| `CONTEXT.md` | Domain language, key concepts, and terminology |
| `docs/adr/` | Architectural Decision Records |

## How to use

- Before any implementation task, read `CONTEXT.md` for domain terminology. Use its terms in code, comments, and issue titles.
- Before making architectural decisions, scan `docs/adr/` to avoid re-litigating settled choices and to understand the reasoning behind existing ones.
- New ADRs use the filename pattern `docs/adr/NNNN-title-in-kebab-case.md` and follow the existing format.

## Notes

- `CONTEXT.md` does not exist yet — create it once you have core domain concepts worth documenting.
- `docs/adr/` does not exist yet — create it when you make your first architectural decision worth recording.
