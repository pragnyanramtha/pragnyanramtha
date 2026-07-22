# Hey, I'm Pragnyan Ramtha 👋

**18-year-old AI Engineer** — building autonomous AI agents and fine-tuning LLMs to ship production systems.

Founder of **[Agent7](https://agent7.dev)** • Prev. **#1 on ARC-AGI** • **AIMO-3 Solver Medalist** • **Top 5, OpenAI Parameter Golf**

---

### What I Do

I specialize in **LLM fine-tuning** (PEFT/QLoRA), **autonomous AI agent** systems, and **cost-efficient model compression** (GPTQ, mixed-precision). I build AI systems that run long autonomous sessions, solve competition-grade math, and fit inside 16MB.

---

### Featured Projects

| Project | What It Is | Tech |
|---------|-----------|------|
| **[Agent7](https://agent7.dev)** | No-code AI agent platform — connects 1,000+ apps, orchestrates 20,000+ tools, runs autonomous sessions for hours to days | Next.js, TypeScript, AI Agents |
| **[AIMO-3 Reasoning](https://huggingface.co/pragnyanramtha/phi-4-math-rplus)** | Fine-tuned Phi-4 (14B) to **90% accuracy** on mathematical reasoning benchmarks, rivaling 125B models | Phi-4, PEFT, CoT/TiR |
| **[Personality Clone](https://huggingface.co/pragnyanramtha/pragnyan-clone)** | LLM style emulation via siamese networks + contrastive learning — **92% accuracy**, 28% over baseline | TensorFlow, QLoRA, CUDA |
| **[Autopilot](https://github.com/pragnyanramtha/autopilot)** | AI-driven OS automation with ReAct agent framework and command sandboxing | Python, LLM Agents |

---

### Open Source Contributions

19 merged PRs across the AI/ML ecosystem — bug fixes, correctness patches, and security hardening for production frameworks.

| Repo | PR | What I Fixed | Branch |
|------|----|-------------|--------|
| [**openai-node**](https://github.com/openai/openai-node/pull/1885) | `fix: validate workload identity access tokens` | Malformed token exchange responses were cached and returned `undefined`, producing invalid bearer tokens downstream | `codex/validate-workload-access-token` |
| [**langgraphjs**](https://github.com/langchain-ai/langgraphjs/pull/2409) | `fix: preserve non-plain Send args` | `Set`, `Map`, `Date`, and custom class instances were flattened into plain objects when passed through `Send`/`Command` | `pragnyan/fix-send-non-plain-objects` |
| [**gemini-cli**](https://github.com/google-gemini/gemini-cli/pull/279) | `Refactor: Enhance @-command, Autocomplete, and Input Stability` | `@`-command trigger errors, broken Tab autocomplete, ESC blocking Enter, and up-arrow navigation between suggestions vs history | `adh/bugfix/input` |
| [**promptfoo**](https://github.com/promptfoo/promptfoo/pull/9255) | `fix: isolate loadFunction cache entries` | `loadFunction` returned stale functions when the same filename was loaded from different `basePath` values due to broken cache keys | `fix/load-function-cache-key` |
| [**haystack**](https://github.com/deepset-ai/haystack/pull/11330) | `fix: avoid mutating Document.from_dict input` | `Document.from_dict()` mutated the caller's dictionary — broke downstream reuse of serialized document data | `codex/document-from-dict-copy-input` |
| [**mem0**](https://github.com/mem0ai/mem0/pull/5170) | `fix(ts): request float OpenAI embeddings` | TypeScript embedder didn't specify `encoding_format: "float"`, causing OpenAI-compatible proxies to return wrong-dimension vectors | `codex/fix-openai-embedder-float-encoding` |
| [**chainlit**](https://github.com/Chainlit/chainlit/pull/2927) | `fix(socket): handle missing user env` | Missing `userEnv` payload caused `NameError`/`UnboundLocalError` instead of a proper `ConnectionRefusedError` | `codex/fix-load-user-env-none` |
| [**agno**](https://github.com/agno-agi/agno/pull/7948) | `[fix] Resolve N1N model strings` | `Agent(model="n1n:gpt-4o")` failed — missing provider mapping for the N1N provider in `get_model()` | `codex/n1n-model-string` |
| [**fastmcp**](https://github.com/PrefectHQ/fastmcp/pull/4164) | `fix(config): read MCP config files as UTF-8` | MCP config values with Unicode broke on Windows — `Path.read_text()` defaulted to cp1252 instead of UTF-8 | `codex/mcp-config-utf8-io` |
| [**dstack**](https://github.com/dstackai/dstack/pull/3885) | `Reject negative retry durations` | Negative values like `-1` parsed successfully for retry duration, creating nonsensical retry specs | `codex/reject-negative-retry-duration` |
| [**opik**](https://github.com/comet-ml/opik/pull/6735) | `fix: preserve StartSpanParameters when merging opik_args` | Span-level `opik_args` merging dropped trace-derived fields (`environment`, `thread_id`) by rebuilding the dataclass from a fixed subset | `pragnyanramtha/NA-preserve-opik-args-environment` |
| [**mastra**](https://github.com/mastra-ai/mastra/pull/5098) | `Fix: inputData should load from snapshot` | After workflow resume, `inputData` was set from the resume payload instead of the original input stored in the snapshot | `patch-1` |
| [**pydantic-ai**](https://github.com/pydantic/pydantic-ai/pull/809) | `Various docs improvements` | Clarified httpx monitoring in troubleshooting, fixed model messages docs, improved formatting across docs site | `general-docs-improvements` |

**6 Dify Plugins** — built and merged 6 new plugins under IEEE Summer of Code:

| Plugin | What It Does |
|--------|-------------|
| [**Deep Research**](https://github.com/langgenius/dify-plugins/pull/737) | Multi-source research with synthesis |
| [**Animo Visuals**](https://github.com/langgenius/dify-plugins/pull/788) | Visual content generation |
| [**Drug Research**](https://github.com/langgenius/dify-plugins/pull/791) | Pharmaceutical research tool |
| [**Legal Clause Research**](https://github.com/langgenius/dify-plugins/pull/792) | Legal document analysis |
| [**Stock Research**](https://github.com/langgenius/dify-plugins/pull/794) | Financial market research |
| [**Google Books Explorer**](https://github.com/langgenius/dify-plugins/pull/804) | Book search and discovery |

---

### Achievements

- 🥇 **#1 on ARC-AGI Public Leaderboard** — Test-Time Training for fluid intelligence benchmarks
- 🏅 **AIMO-3 Solver Medalist** — $2.2M Kaggle competition, 90% accuracy on IMO-level problems
- 🏆 **Top 5, OpenAI Parameter Golf** — 1.1271 BPB on 16MB model using XSA4 + EMA + GPTQ-Int6
- 🥇 **Winner, NIAT RAG Challenge**
- 🏆 **Winner, IEEE Summer of Code 2025**
- 🏆 **Winner, Empathy Encryption Hackathon 2025**
- 🏆 **Winner, Daydream Hyderabad @ Hackclub 2025**
- 🏅 **Top 0.5% Finalist, Shell AI Hackathon 2025**
- 🥈 **Finalist, Smallest AI × IIT G**

---

### The Stack

```
Languages:    Python · TypeScript · Rust · C · SQL · Bash · Go
AI/ML:        PyTorch · Transformers · Unsloth · PEFT/QLoRA · CUDA
Full-Stack:   Next.js · React · Node.js · Tailwind CSS · PostgreSQL
Infra:        GCP · Docker · Linux (Arch) · Nix · Git · CI/CD
Dev Tools:    Neovim · uv
```

---

### Experience

**Founder — [Agent7](https://agent7.dev)** · 2025–Present
> Shipped a no-code AI agent platform solo from zero to production. 1,000+ app connectors, 20,000+ tools, autonomous sessions running hours to days across research, outreach, CRM, and cross-app workflows.

**Software Engineer — [Learnable India](https://learnableindia.org)** · Apr 2026–Present
> Built assistive software for blind learners — learning portal with screen-reader compatible workflows and AI-powered assistance tools.

**Agentic AI Developer — [Reputation Dao](https://reputationdao.com)** · Aug 2025–Jan 2026
> GCP serverless backend (99.9% uptime), 50% inference latency reduction, RAG pipeline with semantic search.

**ML Engineer (Freelance) — Six Axis Studios** · Feb–May 2025
> World-model research for architecture workflows, CAD-style design generation pipelines.

---

### Education

**B.E. Computer Science & Design** — MRV University (GPA 9.0/10, Top 3 rank)
Machine Learning Specialization (Stanford) • CS50 (Harvard)

---

### Writing

I blog about AI engineering decisions, model training, and what actually works in production:

- [Why OpenAI Sent Me $500 (Parameter Golf)](https://pragnyanramtha.dev/blogs/why-openai-sent-me-500-dollars-parameter-golf)
- [How I Reached #1 on ARC-AGI-2](https://pragnyanramtha.dev/blogs/how-i-reached-number-1-on-arc-agi-2)
- [How I Won a Solver Medal at AIMO3](https://pragnyanramtha.dev/blogs/how-i-won-a-solver-medal-at-aimo3)
- [Fine-Tuning Smaller Models for Reasoning](https://pragnyanramtha.dev/blogs/what-fine-tuning-smaller-models-taught-me-about-reasoning)

---

### Connect

**[Portfolio](https://pragnyanramtha.dev)** • **[LinkedIn](https://linkedin.com/in/pragnyanramtha)** • **[Hugging Face](https://huggingface.co/pragnyanramtha)** • **[Email](mailto:pragnyanramtha@gmail.com)**

---

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=170 src="https://github-readme-stats-theta-fawn-44.vercel.app/api?username=pragnyanramtha&show_icons=true&theme=transparent" />
</a>
<a href="https://git.io/streak-stats">
  <img height=170 src="https://github-readme-streak-stats-eight.vercel.app?user=pragnyanramtha&theme=github-dark-blue" alt="GitHub Streak" />
</a>

[![Pragnyan's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=pragnyanramtha&bg_color=000000&color=4c6c9e&line=0033ff&point=403d3d&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
