---
name: ts-bugfix
description: Final checklist before you finish a TypeScript bug fix.
---

# Before you finish

- [ ] Every requirement in the task maps to a line of code you changed or verified.
- [ ] Invalid input is rejected before any state changes.
- [ ] Repeating the same request gives the same result and changes nothing more.
- [ ] A final state cannot move back to an earlier state.
- [ ] The existing response shape (status codes, JSON fields) is unchanged.
- [ ] `npm test` passes and `npx tsc --noEmit` is clean.
- [ ] `git diff` touches only `src/`.
