<div align="center">
  <a href="https://halios.ai">
    <img src="https://halios.ai/apple-touch-icon.png" width="96" height="96" alt="HaliosAI Logo" style="border-radius: 20px;" />
  </a>
  
  # HaliosAI
  
  **Fastest way to build agent evaluations!**
  
  <p align="center">
    <a href="https://halios.ai">Website</a> ·
    <a href="https://docs.halios.ai">Documentation</a> ·
    <a href="https://app.halios.ai">Dashboard</a> ·
    <a href="https://docs.halios.ai/prompts/prompting-guide">Prompting Guide</a> ·
    <a href="https://docs.halios.ai/concepts/evaluation-concepts">Evaluation Concepts</a>
  </p>
</div>

---

**Build reliable AI agents with OpenTelemetry-native evaluations, guardrails, CI gates, and prompt optimization.**

Halios brings OpenTelemetry-native traces, repeatable multi-turn simulations, runtime guardrails, CI release gates, production-failure analysis, and regression-safe prompt optimization into one unified developer workflow.

### ⚡ Evals for any agent in minutes — right inside your coding agent
Halios is built around a **coding-agent-led workflow**. Instead of stitching together disconnected eval frameworks or managing fragile static test datasets, you install one universal agent skill and prompt your coding agent (Codex, Claude Code, Cursor, Copilot, Antigravity) to build scenarios, simulate multi-turn trials, diagnose failures, and optimize prompts directly in your codebase.

---

## 🎯 Why HaliosAI

* **🤖 Coding-Agent Native**: Your AI coding agent is the interface. It uses full repository context to create scenarios, define checks, run evals, and investigate root-cause failures.
* **🔄 Scenarios, Not Static Datasets**: Tests agent behavior dynamically with fresh multi-turn simulations against live tools, rather than re-scoring brittle saved transcripts.
* **📦 Repo-Native & Versioned**: Evaluation suites (`.halios/`) live directly in Git alongside the agent code. Branch, PR, and review evaluations together.
* **🔭 OpenTelemetry First**: Native OTel telemetry ingestion. Instrument your agent with standard OpenTelemetry or let your coding agent add it automatically.
* **🚦 Local → CI → Production**: Run the exact same scenarios during local development, as CI release quality gates, and against live production traffic.

---

## 🛠️ Open-Source Ecosystem

| Repository | Description |
| :--- | :--- |
| [**`HaliosAI/halios`**](https://github.com/HaliosAI/halios) | The `halios` CLI and universal Agent Skill for configuring, simulating, and evaluating AI agents from any coding harness. |
| [**`HaliosAI/sample-agents`**](https://github.com/HaliosAI/sample-agents) | Curated open-source sample agents (e.g. `demo-shopper-agent`) designed for benchmarking and multi-turn evaluation. |
| [**`HaliosAI/haliosai-python-sdk`**](https://github.com/HaliosAI/haliosai-python-sdk) | Async Python client for inline guardrails, trace inspection, and programmatic evaluation runs. |

---

## 🚀 Get Started

### 1. Equip your AI coding agent with the Halios skill

Add the Halios skill to your favorite coding assistant:

```bash
npx skills add HaliosAI/halios --skill halios
```

### 2. Prompt your coding agent to set up evals

Open your agent project and run:

> *"Run `npx skills add HaliosAI/halios --skill halios`, then use the Halios skill to set up evals for this agent."*

### 3. Install the Halios CLI (Optional)

```bash
uv tool install haliosai-cli
halios --version
```

### 4. Or use the Python SDK for inline guardrails

```bash
pip install haliosai
```

---

## 📚 Learn More

* [Evaluation Concepts](https://docs.halios.ai/concepts/evaluation-concepts) — Understand metrics, rubrics, and simulation design.
* [Prompting Guide & Cookbook](https://docs.halios.ai/prompts/prompting-guide) — Explore agent evaluation recipes and best practices.
* [Evaluation Types & Scenarios](https://docs.halios.ai/evaluation/eval-types) — Design deterministic checks and LLM-as-a-judge rubrics.
* [Why Halios Uses Scenarios Instead of Datasets](https://halios.ai/blog/why-halios-uses-scenarios-instead-of-eval-datasets) — Deep dive into scenario-based agent simulation.

---

## 🤝 Contributing & Security

Issues and pull requests are welcome across our open-source repositories. Please report any security vulnerabilities privately to [security@halios.ai](mailto:security@halios.ai).
