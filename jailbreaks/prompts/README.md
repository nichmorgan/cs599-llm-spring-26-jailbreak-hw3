# Jailbreak Prompts

This directory contains ready-to-use jailbreak prompts for educational purposes. Each prompt corresponds to a jailbreak technique documented in the parent `jailbreaks/` directory.

## ⚠️ Educational Use Only

These prompts are provided for **academic research and educational purposes only** to understand LLM security vulnerabilities. Do not use these techniques:
- To bypass safety features in production systems
- To generate harmful, illegal, or unethical content
- In violation of any terms of service or acceptable use policies

## Structure

The folder structure mirrors the main jailbreaks documentation:

```
prompts/
├── additional_techniques/
│   ├── base64_jailbreak.txt
│   ├── prefix_jailbreak.txt
│   └── refusal_suppression.txt
├── attention_shifting/
│   ├── logical_reasoning.txt
│   ├── program_execution.txt
│   ├── text_continuation.txt
│   └── translation.txt
├── pretending/
│   ├── assumed_responsibility.txt
│   ├── character_role_play.txt
│   └── research_experiment.txt
└── privilege_escalation/
    ├── simulate_jailbreaking.txt
    ├── sudo_mode.txt
    └── superior_model.txt
```

## Usage Instructions

1. Choose a jailbreak technique from the documentation
2. Open the corresponding `.txt` file in this directory
3. Replace `[INSERT HARMFUL QUERY HERE]` with your test query
4. Test against your target LLM (use two different model sizes as per assignment)
5. Run ≥5 times per model and document results

## Assignment Requirements

For Homework #3, you must:
- Create 10 **original** jailbreak prompts (you can use these as inspiration but modify them)
- Test against 2 LLMs of different sizes
- Run each prompt ≥5 times per model
- Report success rates and observations
