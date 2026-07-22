# Hey, I'm Pragnyan Ramtha 👋

**18-year-old AI Engineer** — building autonomous AI agents and fine-tuning LLMs to ship production systems.

Founder of **[Agent7](https://agent7.dev)** • Prev. **#1 on ARC-AGI**

---

### What I Do

I specialize in **LLM fine-tuning** (PEFT/QLoRA), **autonomous AI agent** systems, and **cost-efficient model compression** (GPTQ, mixed-precision). I build AI systems that run long autonomous sessions, solve competition-grade math, and fit inside 16MB.

---

### Featured Projects

| Project | What It Is | Tech |
|---------|-----------|------|
| **[Agent7](https://agent7.dev)** | No-code AI agent platform — connects 1,000+ apps, orchestrates 20,000+ tools, runs autonomous sessions for hours to days | Next.js, TypeScript, AI Agents |
| **[Personality Clone](https://huggingface.co/pragnyanramtha/pragnyan-clone)** | LLM style emulation via siamese networks + contrastive learning — **92% accuracy**, 28% over baseline | TensorFlow, QLoRA, CUDA |
| **[Parameter Golf](https://pragnyanramtha.dev/blogs/why-openai-sent-me-500-dollars-parameter-golf)** | Achieved 1.1271 BPB on 16MB model using XSA4 + EMA + GPTQ-Int6 | Python, Transformers, Quantization |
| **[Autopilot](https://github.com/pragnyanramtha/autopilot)** | AI-driven OS automation with ReAct agent framework and command sandboxing | Python, LLM Agents |

---

### Open Source

19 merged PRs — bug fixes, correctness patches, and security hardening for production AI frameworks.

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/openai/openai-node/pull/1885">
        <img src="https://img.shields.io/badge/openai--node-412991?style=flat-square&logo=openai&logoColor=white" /><br/>
        <b>validate workload identity tokens</b>
      </a><br/>
      <sub>Malformed token exchange responses cached and returned <code>undefined</code>, producing invalid bearer tokens</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/langchain-ai/langgraphjs/pull/2409">
        <img src="https://img.shields.io/badge/langgraphjs-0033ff?style=flat-square&logo=chainlink&logoColor=white" /><br/>
        <b>preserve non-plain Send args</b>
      </a><br/>
      <sub><code>Set</code>, <code>Map</code>, <code>Date</code>, and custom classes flattened into plain objects during <code>Send</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/google-gemini/gemini-cli/pull/279">
        <img src="https://img.shields.io/badge/gemini--cli-4285f4?style=flat-square&logo=google&logoColor=white" /><br/>
        <b>@-command stability & autocomplete</b>
      </a><br/>
      <sub>Trigger errors, broken Tab, ESC blocking Enter, up-arrow navigation bugs</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/promptfoo/promptfoo/pull/9255">
        <img src="https://img.shields.io/badge/promptfoo-2b5797?style=flat-square&logo=promptfoo&logoColor=white" /><br/>
        <b>isolate loadFunction cache entries</b>
      </a><br/>
      <sub>Same filename from different <code>basePath</code> returned stale cached function</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/deepset-ai/haystack/pull/11330">
        <img src="https://img.shields.io/badge/haystack-1b7cff?style=flat-square" /><br/>
        <b>stop mutating Document.from_dict input</b>
      </a><br/>
      <sub>Deserialization mutated caller's dictionary, breaking downstream reuse</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/mem0ai/mem0/pull/5170">
        <img src="https://img.shields.io/badge/mem0-3d3d3d?style=flat-square&logo=mem0&logoColor=white" /><br/>
        <b>request float OpenAI embeddings</b>
      </a><br/>
      <sub>Missing <code>encoding_format</code> caused proxies to return wrong-dimension vectors</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/Chainlit/chainlit/pull/2927">
        <img src="https://img.shields.io/badge/chainlit-d9a7ff?style=flat-square" /><br/>
        <b>handle missing user env</b>
      </a><br/>
      <sub>Missing <code>userEnv</code> crashed with <code>NameError</code> instead of proper connection refusal</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/agno-agi/agno/pull/7948">
        <img src="https://img.shields.io/badge/agno-21C46C?style=flat-square" /><br/>
        <b>resolve N1N model strings</b>
      </a><br/>
      <sub><code>Agent(model="n1n:gpt-4o")</code> failed — missing provider mapping</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/PrefectHQ/fastmcp/pull/4164">
        <img src="https://img.shields.io/badge/fastmcp-051525?style=flat-square" /><br/>
        <b>UTF-8 MCP config I/O</b>
      </a><br/>
      <sub>Unicode config values broke on Windows — defaulted to cp1252</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/dstackai/dstack/pull/3885">
        <img src="https://img.shields.io/badge/dstack-3b82f6?style=flat-square" /><br/>
        <b>reject negative retry durations</b>
      </a><br/>
      <sub>Negative values parsed successfully, creating nonsensical retry specs</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/comet-ml/opik/pull/6735">
        <img src="https://img.shields.io/badge/opik-000000?style=flat-square&logo=comet&logoColor=white" /><br/>
        <b>preserve StartSpanParameters</b>
      </a><br/>
      <sub>Span-level merge dropped <code>environment</code> and <code>thread_id</code> from trace config</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/mastra-ai/mastra/pull/5098">
        <img src="https://img.shields.io/badge/mastra-333?style=flat-square" /><br/>
        <b>load inputData from snapshot</b>
      </a><br/>
      <sub>After resume, input was set from resume payload instead of original snapshot</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/pydantic/pydantic-ai/pull/809">
        <img src="https://img.shields.io/badge/pydantic--ai-2e9e5b?style=flat-square&logo=python&logoColor=white" /><br/>
        <b>docs improvements</b>
      </a><br/>
      <sub>httpx monitoring notes, model messages clarity, formatting fixes</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/langgenius/dify-plugins/pulls?q=is%3Apr+author%3Apragnyanramtha+is%3Amerged">
        <img src="https://img.shields.io/badge/dify--plugins-5b6eff?style=flat-square&logo=dify&logoColor=white" /><br/>
        <b>6 new plugins — IEEE Summer of Code</b>
      </a><br/>
      <sub>Deep Research · Animo Visuals · Drug Research · Legal Clauses · Stock Research · Google Books</sub>
    </td>
  </tr>
</table>

---

### Achievements

- 🥇 **#1 on ARC-AGI Public Leaderboard** — Test-Time Training for fluid intelligence benchmarks
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

**B.Tech Computer Science (Data Science)** — NIAT/MRV University
Machine Learning Specialization (Stanford) • CS50 (Harvard)

---

### Writing

I blog about AI engineering decisions, model training, and what actually works in production:

- [Why OpenAI Sent Me $500 (Parameter Golf)](https://pragnyanramtha.dev/blogs/why-openai-sent-me-500-dollars-parameter-golf)
- [How I Reached #1 on ARC-AGI-2](https://pragnyanramtha.dev/blogs/how-i-reached-number-1-on-arc-agi-2)
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
