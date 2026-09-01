<div align="center">
  <a href="https://halios.ai">
    <img src="https://halios.ai/apple-touch-icon.png" width="96" height="96" alt="HaliosAI Logo" />
  </a>

  # HaliosAI

  **Evals for any agent in minutes.**

  <p align="center">
    <a href="https://halios.ai">Website</a> ·
    <a href="https://docs.halios.ai">Documentation</a> ·
    <a href="https://app.halios.ai">Dashboard</a>
  </p>
</div>

Halios brings evals to your coding agent. Add the open-source Halios skill to Codex, Claude Code,
Cursor, or another coding agent, then create scenarios, run fresh multi-turn trials, investigate
failures, and verify improvements from your repository.

```bash
npx skills add HaliosAI/halios --skill halios
```

## Open source

| Repository | What it is |
| :--- | :--- |
| [**`HaliosAI/halios`**](https://github.com/HaliosAI/halios) | The primary entry point: CLI and Agent Skill for building and running AI agent evals from your coding agent. |
| [**`HaliosAI/sample-agents`**](https://github.com/HaliosAI/sample-agents) | Example AI agents for trying scenario-based, multi-turn evaluations with Halios. |
| [**`HaliosAI/haliosai-python-sdk`**](https://github.com/HaliosAI/haliosai-python-sdk) | Python client for runtime guardrails, trace inspection, and programmatic evaluation runs. |

Halios uses standard OpenTelemetry and keeps scenarios and checks in your repository, so the same
evaluation workflow can move from local development to CI and production.

Issues and pull requests are welcome. Report security vulnerabilities privately to
[security@halios.ai](mailto:security@halios.ai).
