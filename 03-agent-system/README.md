# 03 — 🤖 Agent & System

> When the model can act: tools, plugins, outputs and resources.
>
> [⬅ Back to AI Hacking Dashboard](../README.md)

## Modules

| Module | OWASP | Status | Notes |
|--------|:-----:|:------:|:-----:|
| [Excessive Agency (Tool & Function Abuse)](./excessive-agency.md) | LLM06:2025 | ⬜ | [📖](./excessive-agency.md) |
| [Improper Output Handling](./improper-output-handling.md) | LLM05:2025 | ⬜ | [📖](./improper-output-handling.md) |
| [Unbounded Consumption (DoS / Wallet Attacks)](./unbounded-consumption.md) | LLM10:2025 | ⬜ | [📖](./unbounded-consumption.md) |

## 🎯 Domain Goal

```text
Model Output / Tool Call
      ↓
Missing Validation
      ↓
Privileged Action
      ↓
System Impact
```

## Readiness Checklist

- [ ] Explain the underlying concepts
- [ ] Identify attack opportunities
- [ ] Execute the relevant techniques
- [ ] Troubleshoot when the obvious approach fails
- [ ] Document commands and evidence
- [ ] Apply the technique in an unfamiliar environment
- [ ] Combine it with other skills

---

[⬅ Back to AI Hacking Dashboard](../README.md)
