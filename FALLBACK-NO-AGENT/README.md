# Use My Copilot Framework Without an Agent

The fallback works, but requires more manual context selection.

## In normal Copilot Chat

1. Start a new work-grounded chat.
2. Add or reference the smallest relevant framework files.
3. Ask Copilot to combine those files with current work context available to it.
4. Review the answer.
5. Ask for a ready-to-paste framework update when something deserves preservation.

## Context recipes

- Today planning: Me + Current Focus.
- Project recovery: specific project + Decision Log if relevant.
- Idea development: Idea Backlog + Current Focus.
- Weekly review: Current Focus + active projects + current work evidence.
- Career reflection: Career Vision + Growth & Learning + Personal Brand.

## Reusable prompt

```text
Treat the attached My Copilot Framework files as my curated personal context. Distinguish recorded context from current organisational evidence and from your suggestions. Do not invent missing facts. When something deserves preservation, propose the target framework file and ready-to-paste Markdown, but do not claim it was saved.
```
