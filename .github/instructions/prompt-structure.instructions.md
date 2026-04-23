---
applyTo: "jailbreaks/prompts/**"
description: "Use when inspecting or editing jailbreak prompt folders, especially to find missing files or compare prompt-directory completeness."
---

# Prompt Folder Structure

- Treat `jailbreaks/prompts/<category>/<technique>/` as the unit of comparison.
- The default expected contents of a technique folder are `direct-prompt.md`, `malicious-prompt.md`, `google-gemma-4-26b-a4b/`, and `gpt-oss-20b-medium-reasoning/`.
- Inside each model directory, expect `direct/` and `malicious/`. Treat `analysis.md` as optional unless sibling folders in the same slice consistently include it.
- When checking for missing files, compare against sibling technique folders in the same category before declaring something absent.
- If documentation conflicts with the filesystem, prefer the on-disk structure over `jailbreaks/prompts/README.md`, which still documents an older flat `.txt` layout.
- Do not create placeholder prompt or analysis files unless the user explicitly asks for them.