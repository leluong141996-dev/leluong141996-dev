### Hi, I'm Lượng (Smoky) 👋

I build open-source tools for AI agents: **shared memory**, **evaluation**, and **LLMs that are honest about what they know**. Based in Hanoi, Vietnam 🇻🇳. I work in Node.js and Python, mostly with local LLMs.

I publish the numbers that don't flatter me, too. Each project ships with a benchmark, and a release only goes out if the benchmark gate passes.

---

### 🧠 Featured: [Agent Brain Hub](https://github.com/leluong141996-dev/Agent-Brain-Hub)

**One shared, brain-inspired memory for many AI agents.** A travel agent, a repair agent and a finance agent talk to the same customer. Each one knows what the others learned, but private data (health, income) never crosses between them.

- **Memory over time.** Facts are invalidated, not deleted, so you can ask *"what did the brain believe last Tuesday?"*
- **Connected memory.** An entity graph lets *"my Civic"* find *"the car is in the shop"*, with no extra permissions.
- **Measured.** 37 multi-agent scenarios run in CI, plus LongMemEval-S retrieval.
- **Works offline** with zero config, or with Claude, GPT, Gemini, DeepSeek or a local model. Talk to it over REST, the JS SDK or MCP. UI in Vietnamese, English and Japanese.

| v0.6 (offline, no API keys) | |
|---|---|
| Benchmark pass rate | 97.3% (81.1% without the entity graph) |
| Private-data leak rate | **0%** |
| Recall latency at 100,000 memories | p50 0.6 ms |
| LongMemEval-S, evidence in top 4 | 52.8% *(room to grow)* |

<a href="https://github.com/leluong141996-dev/Agent-Brain-Hub"><img src="https://raw.githubusercontent.com/leluong141996-dev/Agent-Brain-Hub/main/docs/entity-graph.png" width="640" alt="Agent Brain Hub: the entity graph of one customer" /></a>

---

### 🔧 Other projects

| Project | What it does |
|---|---|
| [**Argus**](https://github.com/leluong141996-dev/Argus) | An open benchmark and evaluation platform for AI agents. It measures reasoning, planning, tool use, reliability, safety and cost. |
| [**Model-Identity-Skill**](https://github.com/leluong141996-dev/Model-Identity-Skill) | A model-agnostic system prompt that keeps LLMs honest about their identity, capabilities and knowledge cutoff. It searches the web instead of guessing. Comes with an eval harness. |
| [**Spawn-Point**](https://github.com/leluong141996-dev/Spawn-Point) | Describe a 2D game in one sentence and get a playable Godot 4 game. An autonomous game studio running a local, fine-tuned 7B model. |

---

### 🛠️ Tools I use

`Node.js` · `Python` · `SQLite` · `Docker` · `GitHub Actions` · `vLLM` · `Ollama` · `Qwen3` · `bge-m3` · `MCP` · `Godot 4`

---

### ✍️ Writing

I write about building these tools in public, bugs included, on [daily.dev](https://app.daily.dev/smoky1496).
- [Your agent's working memory is probably dropping turns. Mine was.](https://daily.dev/posts/your-agent-s-working-memory-is-probably-dropping-turns-mine-was--eummzloyr)

---

### 🤝 Contributing

Issues labelled [`good first issue`](https://github.com/leluong141996-dev/Agent-Brain-Hub/labels/good%20first%20issue) are a good place to start. Benchmark scenarios from real multi-agent failures are especially welcome. If memory went wrong between your agents, open an issue and it may become a test case.

<!--
Optional stats cards (uncomment when you like how they look):
<img src="https://github-readme-stats.vercel.app/api?username=leluong141996-dev&show_icons=true&hide_border=true" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=leluong141996-dev&layout=compact&hide_border=true" height="150" />
-->
