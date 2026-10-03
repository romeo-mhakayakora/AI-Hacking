# 02 — 🗄️ Data Layer

> Training data, RAG stores, embeddings and outputs you should never see.
>
> [⬅ Back to AI Hacking Dashboard](../README.md)

## Modules

| Module | OWASP | Status | Notes |
|--------|:-----:|:------:|:-----:|
| [Sensitive Information Disclosure](./sensitive-information-disclosure.md) | LLM02:2025 | ⬜ | [📖](./sensitive-information-disclosure.md) |
| [Data & Model Poisoning](./data-model-poisoning.md) | LLM04:2025 | ⬜ | [📖](./data-model-poisoning.md) |
| [Vector & Embedding Weaknesses (RAG Attacks)](./vector-embedding-weaknesses.md) | LLM08:2025 | ⬜ | [📖](./vector-embedding-weaknesses.md) |
| [Misinformation & Overreliance](./misinformation.md) | LLM09:2025 | ⬜ | [📖](./misinformation.md) |

## 🎯 Domain Goal

```text
Data Source
      ↓
Poison / Leak Point
      ↓
Retrieval / Inference
      ↓
Disclosure / Corruption
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
