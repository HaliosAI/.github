<div align="center">
  <a href="https://halios.ai">
    <img src="https://halios.ai/apple-touch-icon.png" width="96" height="96" alt="HaliosAI Logo" style="border-radius: 20px;" />
  </a>
  
  # Halios
  
  **Build reliable AI agents with evidence, not guesswork.**
  
  <p align="center">
    <a href="https://halios.ai">Website</a> ·
    <a href="https://docs.halios.ai">Documentation</a> ·
    <a href="https://app.halios.ai">Dashboard</a> ·
    <a href="https://docs.halios.ai/prompts/prompting-guide">Prompting Guide</a> ·
    <a href="https://docs.halios.ai/concepts/evaluation-concepts">Evaluation Concepts</a>
  </p>
</div>

---

Halios brings OpenTelemetry-native traces, repeatable multi-turn simulations, runtime guardrails, CI release gates, production-failure analysis, and regression-safe prompt optimization into one unified developer workflow.

---

## 🛠️ Open-Source Ecosystem

| Repository | Description |
| :--- | :--- |
| [**`HaliosAI/halios`**](https://github.com/HaliosAI/halios) | The `halios` CLI and cross-harness Agent Skill for configuring, running, and investigating AI-agent evaluations. |
| [**`HaliosAI/sample-agents`**](https://github.com/HaliosAI/sample-agents) | Curated open-source sample agents (e.g. `demo-shopper-agent`) designed for benchmarking and multi-turn evaluation. |
| [**`HaliosAI/haliosai-python-sdk`**](https://github.com/HaliosAI/haliosai-python-sdk) | Explicit async Python client for inline guardrails, trace inspection, and immutable evaluation runs. |

---

## 🚀 Get Started

### 1. Give your AI coding agent the Halios workflow

Install the Halios skill into your coding agent (Claude Code, Cursor, Copilot, Antigravity, etc.):

```bash
npx skills add HaliosAI/halios --skill halios
```

### 2. Install the Halios CLI

```bash
uv tool install haliosai-cli
halios --version
```

### 3. Try with a Sample Agent

Clone the [sample-agents](https://github.com/HaliosAI/sample-agents) repository and prompt your coding agent:

> *"Run `npx skills add HaliosAI/halios --skill halios`, then use the Halios skill to set up evals for this agent."*

### 4. Or use the Python SDK for inline guardrails

```bash
pip install haliosai
```

---

## 📚 Learn More

* [Evaluation Concepts](https://docs.halios.ai/concepts/evaluation-concepts) — Understand metrics, rubrics, and simulation design.
* [Prompting Guide & Cookbook](https://docs.halios.ai/prompts/prompting-guide) — Explore agent evaluation recipes and best practices.
* [Evaluation Types & Scenarios](https://docs.halios.ai/evaluation/eval-types) — Design deterministic checks and LLM-as-a-judge rubrics.

---

## 🤝 Contributing & Security

Issues and pull requests are welcome in our public repositories. Please report any security vulnerabilities privately to [security@halios.ai](mailto:security@halios.ai).
