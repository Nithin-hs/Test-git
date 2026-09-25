# AI Model Release Tracker

A daily log of newly released AI models from labs around the world, and what each one is good for. Newest entries are added at the top.

---

## 2026-09-25

### OpenAI — GPT-6 Sol & GPT-6 Luna
Released September 22, 2026, as cheaper follow-ups to GPT-6 Astra (which launched September 3–4).
- **Sol**: everyday work model with more reasoning capability; OpenAI says it makes "about half as many mistakes" as GPT-5.6 Sol. Priced at $2/M input, $10/M output tokens.
- **Luna**: an even cheaper, faster model tuned for high-volume, low-latency use. Priced at $0.10/M input, $0.50/M output tokens.
- **Good for**: everyday assistant tasks, coding, and agentic workflows in ChatGPT, Codex, and the API — Sol for harder reasoning tasks, Luna for cheap, fast, high-volume requests.
- Source: [OpenAI announcement](https://openai.com/index/introducing-gpt-6-sol-and-luna/), [VentureBeat](https://venturebeat.com/technology/openai-releases-gpt-6-sol-and-luna-models-slashing-api-costs-50-or-more)

### Anthropic — Claude Opus 5.5
Released September 22, 2026. Anthropic's most capable Opus model to date.
- Matches Claude Fable 5.1 on most work, has a 1M-token context window, and costs ~40% less to run than Opus 5.
- Pricing: $4/M input, $20/M output, $0.20/M cache reads.
- **Good for**: large-context work (long documents/codebases), complex reasoning and agentic tasks at a lower cost than the previous Opus generation.
- Source: reported across [Anthropic release notes](https://releasebot.io/updates/anthropic)

### xAI — Grok 4.7
Released September 21, 2026. 2.1 trillion parameters, 500K context window, text/image input with text-only output.
- Notable gains on enterprise-agent benchmarks (AA-Briefcase, GDPval), just behind Claude Fable 5.1 on both.
- Same price as Grok 4.6 ($2/M input tokens).
- **Good for**: coding, agentic tasks, and professional knowledge work; available in the Grok app, Cursor, Grok Build, GitHub Copilot, and the xAI API.
- Source: [Decrypt](https://decrypt.co/378824/xai-launches-grok-4-7), [GitHub Changelog](https://github.blog/changelog/2026-09-21-grok-4-7-is-now-available-in-github-copilot/)

### Google — Gemini 3.8 Flash
Released September 2, 2026 (with a Fairwind-gated "Cyber" variant), following Gemini 3.7 Flash's general availability in August.
- Positioned as Google's everyday workhorse model, strong on coding, web development, and agentic workflows.
- **Good for**: fast, cost-efficient everyday tasks and agentic/tool-use workflows.
- Note: Google says a full **Gemini 4** release is coming "as soon as possible," with an early post-training checkpoint expected before end of 2026.
- Source: [9to5Google](https://9to5google.com/2026/09/24/google-says-gemini-4-release-is-coming-as-soon-as-possible/)

### Meta — Muse Spark 1.3
Released September 2, 2026.
- ~20% fewer tool calls and ~25% fewer tokens used vs. Muse Spark 1.2 in Meta's internal benchmarks; better at sustaining longer, multi-step agentic work and asking clarifying questions.
- Same pricing as 1.2: $1.25/M input, $4.25/M output tokens.
- **Good for**: longer-horizon agentic and coding tasks that span multiple tool calls in a single thread.
- Source: [Bloomberg](https://www.bloomberg.com/news/articles/2026-09-02/meta-releases-more-powerful-ai-model-edging-closer-to-rivals), [Meta AI Research](https://research.meta.ai/blog/introducing-muse-spark-1-3)

### China — DeepSeek, Qwen, Kimi
- **DeepSeek V4-Pro**: reached general availability August 13, 2026 — strong, cost-efficient open-weight reasoning model.
- **Qwen 3.8-Max** (Alibaba): a 2.4-trillion-parameter model Alibaba positions as competitive with the best from Anthropic and OpenAI; good for general-purpose reasoning and coding at scale. A next-generation "Qwen 4" flagship is rumored to be in stealth testing.
- **Kimi K3** (Moonshot AI): released July 17, 2026, 2.8 trillion parameters, billed as the world's largest open-source model — useful where open weights and self-hosting matter.
- Source: [The Register](https://www.theregister.com/ai-and-ml/2026/08/03/china-turns-up-the-heat-with-open-model-blitz-as-us-model-makers-panic/5282526), [Coinmonks/Medium roundup](https://medium.com/coinmonks/chinas-top-ai-models-in-2026-deepseek-qwen-kimi-doubao-and-the-new-ai-race-08083866ac5a)

---

*This log is generated automatically from a daily web search. Model names, specs, and pricing are as reported by the sources linked above at the time of writing and may be revised as more official documentation appears.*
