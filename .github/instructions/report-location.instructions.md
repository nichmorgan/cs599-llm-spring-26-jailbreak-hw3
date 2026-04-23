---
applyTo: "jailbreaks/reports/**"
description: "Use when creating or updating jailbreak model reports, category reports, or the full report, especially to keep report locations and naming consistent."
---

# Report Locations

- Save model aggregate reports under `jailbreaks/reports/models/<model>.md`.
- Save category or type aggregate reports under `jailbreaks/reports/categories/<category>.md`.
- Save the repo-wide report at `jailbreaks/reports/full-jailbreak-report.md`.
- If the user asks for a different output path, follow the user request and say that you are overriding the default location.
- Do not scatter aggregate reports inside technique folders under `jailbreaks/prompts/**`.
- Prefer one report per model, one report per category, and one final full report.
- If a report does not exist yet, create it at the default path instead of inventing a new naming scheme.
