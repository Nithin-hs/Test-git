# AI Model Release Tracker

Daily log of new AI model releases from around the world and what they're good for. Updated automatically once a day.

---

## 2026-09-23

### OpenAI — GPT-6 Sol & GPT-6 Luna (Sep 22, 2026)
Cheaper, faster siblings of the flagship **GPT-6 Astra**, trained with the same methods.
- **GPT-6 Sol**: Best for complex coding and multi-step/multi-tool agentic tasks. ~half the mistake rate of GPT-5.6 Sol. Priced at $2/$10 per MTok (in/out).
- **GPT-6 Luna**: Built for high-volume, low-cost work — fact extraction, text classification, structured summarization. Optimized for fast responses. Priced at $0.10/$0.50 per MTok.
- **GPT-6 Astra** (flagship, referenced for context): State-of-the-art on computer use, browsing, software engineering, cybersecurity and professional work; saturates FrontierMath Tier 4 (98%) and ARC-AGI-3 (99.9%).

### Anthropic — Claude Opus 5.5 (Sep 22, 2026)
First model in the new 5.5 family. Performs on par with Claude Fable 5.1 on most tasks while costing **40% less** to run than Opus 5, with 30%+ faster output.
- Good for: general-purpose flagship reasoning/coding work where cost-efficiency matters; long-context tasks (1M token context window, 128k max output); always-on adaptive thinking; agentic workflows needing inline tool calls mid-conversation.
- Pricing: $4/$20 per MTok (20% cheaper than Opus 5); cache reads at $0.20/MTok (-60%).
- Ships with "preserved thinking" anti-distillation safeguards. Sonnet 5.5 and Haiku 5.5 expected within weeks.

### xAI — Grok 4.7 (Sep 21, 2026)
xAI's most capable model yet for coding, agentic tasks, and knowledge work.
- Good for: long-running coding tasks (500k context window), self-verification-heavy agentic workloads, tasks that take hours to complete.
- Benchmarks: 46.3% on CursorBench 4.0 (vs 40.4% for Grok 4.6); 71.0% on DeepSWE v1.1 high-effort (vs 65.2%).
- Same price as Grok 4.6: $2/$6 per MTok. Live in the Grok app, Cursor, Grok Build, xAI API, and rolling out to GitHub Copilot.

### Google — Gemini 3.8 Flash (Sep 2, 2026)
Google's most intelligent Flash-tier model yet — third Flash release in six weeks.
- Good for: long-horizon software engineering, autonomous agents, complex enterprise workflows (finance/legal analysis — beats larger frontier models on Vals Finance Agent V2 and Harvey's Legal Agent Benchmark).
- 1M token context, 64k max output, tunable thinking levels (low/medium/high) to trade off latency vs. reasoning depth.
- Scores 90.8% on Terminal-Bench 2.1 (up from 81.6%). Pricing held at $0.75/$3.75 per MTok through end of 2026.
- Also new: **Gemini 3.8 Flash TTS / Flash-Lite TTS** — text-to-speech supporting 100+ languages.

### Other notable releases this month
- **Sakana AI — Fugu Max** (Sep 11, 2026)
- **DeepSeek — V4.1 Flash** (Sep 10, 2026)
- **MiniMax — H3 Max** (Sep 8, 2026)
- **Meta — Muse Spark 1.3** (Sep 2, 2026)

### Takeaway
The frontier labs (OpenAI, Anthropic, Google, xAI) are converging on the same playbook this cycle: ship a flagship, then rapidly follow up with cheaper/faster distilled variants at similar or better capability, aimed squarely at agentic coding and long-horizon tool-use workloads.

**Sources:**
- [New AI Model Releases — September 2026 Timeline (LLM Gateway)](https://llmgateway.io/timeline)
- [AI Updates Today (September 2026) — llm-stats.com](https://llm-stats.com/llm-updates)
- [Introducing GPT-6 Sol and Luna — OpenAI](https://openai.com/index/introducing-gpt-6-sol-and-luna/)
- [GPT-6 Astra: A new generation of intelligence — OpenAI](https://openai.com/index/gpt-6-astra/)
- [OpenAI launches GPT-6 Sol and Luna — TechCrunch](https://techcrunch.com/2026/09/22/openai-launches-gpt-6-sol-and-luna/)
- [Introducing Claude Opus 5.5 — Anthropic](https://www.anthropic.com/claude-opus-5-5)
- [Anthropic upgrades Claude with new Opus 5.5 model — 9to5Mac](https://9to5mac.com/2026/09/22/anthropic-upgrades-claude-with-new-opus-5-5-model-details-here/)
- [xAI Launches Grok 4.7 — Decrypt](https://decrypt.co/378824/xai-launches-grok-4-7)
- [SpaceXAI Releases Grok 4.7 — MarkTechPost](https://www.marktechpost.com/2026/09/21/spacexai-releases-grok-4-7/)
- [Gemini 3.8 Flash: Features, Benchmarks, and Pricing — DataCamp](https://www.datacamp.com/blog/gemini-3-8-flash-cyber)
- [What's new in Gemini 3.8 Flash — Google AI for Developers](https://ai.google.dev/gemini-api/docs/latest-model)

