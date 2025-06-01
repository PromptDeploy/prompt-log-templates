### How to Use This Prompt Log

This log helps you track prompts that actually work — and learn from the ones that don’t.

You don’t need to log every prompt. Just capture the **ones that saved time, solved a real problem, or taught you something useful**.

Start with:

- Dev tasks you repeat often (tests, PRs, debugging, docs)
- Prompts that took multiple tries to get right
- Any AI-assisted win that feels worth reusing or scaling

Each row = 1 prompt session. Keep it simple. Add notes if future-you might forget why it worked.

Think of this as your personal “AI memory” — not a performance tracker.

| Prompt Name | Date | Task Type | Tool Used | Prompt Pattern | Final Prompt Used | Reuse Score (1–5) | Outcome Impact | Notes & Learnings |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| e.g. `auth.ts test coverage` | 2025-06-01 | Test Gen | Claude 3 | Role-based | “You are a dev tool…” | 4 | High | Needed to add more test detail for edge cases |
|  |  |  |  |  |  |  |  |  |

### Field Explanations

- **Prompt Name**: A short label to help you identify it again.
- **Date**: When you used it — useful for retros.
- **Task Type**: What the prompt was used for (e.g., test generation, bug fix, UI copy, component scaffold).
- **Tool Used**: AI tool used (Claude, GPT-4, Cursor, etc.).
- **Prompt Pattern**: What style of prompting? (role-based, chain-of-thought, system prompt, etc.).
- **Final Prompt Used**: The actual production-ready prompt.
- **Reuse Score (1–5)**:
    - 5 – Ready for reuse across projects with no change
    - 4 – Usable with light context edits
    - 3 – Works only in this codebase/project
    - 2 – Needs a lot of rework to be reused
    - 1 – Didn’t work or was highly specific
- **Outcome Impact**:
    - High – Shipped something faster, unblocked a problem
    - Medium – Helped with docs/tests/performance
    - Low – Saved time but not critical
- **Notes & Learnings**: What you’d change next time, or what made it work well.
