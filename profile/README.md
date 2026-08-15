# Halios

**Build reliable AI agents with evidence, not guesswork.**

Halios brings OpenTelemetry-native traces, repeatable multi-turn evaluations, runtime guardrails,
CI release gates, production-failure analysis, and regression-safe prompt optimization into one
developer workflow.

[Website](https://halios.ai) · [Documentation](https://docs.halios.ai) ·
[Open Halios](https://app.halios.ai)

## Open-source developer tools

| Project | What it provides |
| --- | --- |
| [`HaliosAI/halios`](https://github.com/HaliosAI/halios) | The `halios` CLI and cross-harness Agent Skill for configuring, running, and investigating AI-agent evaluations |
| [`HaliosAI/haliosai-python-sdk`](https://github.com/HaliosAI/haliosai-python-sdk) | An explicit async Python client for inline guardrails, trace inspection, and immutable evaluation runs |

## Get started

Install the CLI:

```bash
uv tool install haliosai-cli
halios --version
```

Give your coding agent the Halios workflow:

```bash
npx skills add HaliosAI/halios --skill halios
```

Or add explicit runtime intervention from Python:

```bash
python -m pip install haliosai
```

The CLI and Agent Skill guide repository setup, OpenTelemetry instrumentation, evaluation design,
fresh scenario execution, CI gates, failure diagnosis, and prompt optimization. Applications emit
production telemetry through standard OpenTelemetry; the SDK is reserved for explicit inline
request or response checks and programmatic evaluation operations.

## Contributing and security

Issues and pull requests are welcome in the relevant public repository. Please report security
issues privately to [security@halios.ai](mailto:security@halios.ai), not through a public issue.
