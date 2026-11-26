# New AI Model Releases: Daily Report for 2026-11-26

Covers releases from roughly **Nov 1–26, 2026**, with the most recent first where dates are known.
> ⚠️ Most of this comes from trackers, aggregators and benchmark sites, not from vendor announcements. Some dates and names conflict between sources (noted below), so check the vendor's page before relying on any specific detail.

## 🔥 Headline (frontier) models

| Date | Company | Model | Access | What it's good for |
|---|---|---|---|---|
| Nov 9 | Anthropic (US) | **Claude Fable 5.2** (+ Mythos 5.2, limited to verified orgs) | API / closed | Anthropic's new top model, above Opus 5.5. It leads most third-party indexes: Artificial Analysis Intelligence Index 65, FrontierSWE v2 69.9%, FrontierCode 2.0 49.1%, Terminal-Bench 4.0 65.2%. Best for **hard coding, long-running agents and complex reasoning**. |
| Nov 10–18 | Google (US) | **Gemini 4 Carbon / Hydrogen / Neon** | API / closed | Carbon is the flagship and leads AutomationBench (**workflow automation**). Neon is the **fast, cheap** tier: about $0.75 per task vs $3.10 for Fable 5.2, and the fastest per task. Neon also beats Fable 5.2 on Legal Research Bench (**legal and research work**). |
| Nov 17 | OpenAI (US) | **GPT-6.2 Astra / GPT-6.2 Sol** | API / ChatGPT | Astra is the flagship, strong on coding (FrontierSWE v2 65.5%). Sol is the mid-tier, **general-purpose** model (AA index 57). *The naming differs between sources: some list "GPT-6 Astra" instead.* |
| Nov 16 | Alibaba (China) | **Qwen4-Max** | API only (no weights) | Flagship Qwen model, reported at about $1.50 / $4.50 per million input/output tokens. Good for **low-cost, high-capability general use and multilingual (especially Chinese) work**. |
| Nov 20 | Moonshot AI (China) | **Kimi K3.1 Pro Prime** | API | An upgrade to Kimi K3.1 Pro, whose weights went up on Hugging Face in early Nov under a custom license. Known for **long-context work and agentic tool use**. |
| Nov 4 / Nov 16 | Tencent (China) | **Hy4** / **Hy4 Flash** | API; Flash weights promised | General assistant models. Flash is the **fast, low-latency** variant. |
| Nov 24 | S1 | **S1 Fast** | API | A **speed-focused** model. Few details are available yet. |

## 🔓 Open-weight releases (download and run yourself)

| Date | Company | Model | What it's good for |
|---|---|---|---|
| Nov 22 | Sarvam AI (India) | **Sarvam-105B-1711** | **Customer support and voice agents**, plus Indian languages. A 65 GB NVFP4 version runs on a single workstation GPU. |
| Nov 20 | Thinking Machines Lab (US) | **Inkling 2 Mini** (~26B) | A small, efficient open model, also hosted on Tinker. Good for **fine-tuning and research**. *One calendar lists "Inkling 2 Small" on Nov 5 instead.* |
| Nov 15 | Agnes | **Agnes 2.5 Pro Theta** | General open model. |
| Nov 12 | AutoArk | **Edge0-145B / Edge0-120B** | Aimed at **on-device / edge** deployment. |
| Nov 10 | Meituan (China) | **LongCat-2.5** (MIT license) | **Long-context** work. The MIT license is permissive for commercial use. |
| Nov 5 | Baidu (China) | **ERNIE 5.5 Flash Base** (280B total, 14B active MoE) | An efficient MoE base model to **fine-tune** from. |
| Nov 5 | Preferred Networks (Japan) | **PLaMo 3 Translate** | **Japanese↔English translation**. |

Note: none of the US frontier labs (Anthropic, OpenAI, Google) released open weights this month.

## 🎨 Image / video / audio models

| Date | Company | Model | What it's good for |
|---|---|---|---|
| Nov 4 | OpenAI | **Images 2.6** | Image generation, adding **animated GIFs, SVG export and persistent reference images**. Useful for designers and consistent branding. |
| Nov 5 | Google | **Gemini Omni 1.2 Flash** | Text- or image-to-**video with native audio**, up to 15 s. Can also edit and extend clips. |
| Nov (recent) | Black Forest Labs | **FLUX 3** | The first FLUX that makes **images plus video with audio (up to 20 s)** from one prompt. Limited release, API and partners only. |
| Recent | Kuaishou | **Kling VIDEO 4.0 Flash** | 720p text-to-video, image-to-video and video editing. Fast and cheap. |
| Recent | ByteDance / MiniMax | **Seedance 2.5**, **MiniMax H3** | Video creation and omni-modal (text, image, video, audio) generation. |
| Upcoming | Meta | Muse Video | Announced, not yet launched. |

## 🧭 Quick picks
- **Best overall / coding agents:** Claude Fable 5.2
- **Best value and speed among frontier models:** Gemini 4 Neon
- **Workflow automation:** Gemini 4 Carbon
- **Cheap API outside the US labs:** Qwen4-Max
- **Self-hosted / open:** Sarvam-105B (voice and support), LongCat-2.5 (MIT), ERNIE 5.5 Flash Base
- **Video with sound:** FLUX 3, Gemini Omni 1.2 Flash

## Sources
- https://llmgateway.io/timeline
- https://opper.ai/model-releases
- https://www.llm-releases.com/reports/release-calendar
- https://llmlearner.com/models/releases
- https://convika.com/guides/chinese-ai-models/
- https://hongkongaipodcast.com/blog/chinese-ai-models-november-2026
- https://smartscope.blog/en/blog/gemini-4-carbon-claude-fable-5-2-gpt-2026/
- https://www.vals.ai/comparison?m=claude-fable-5-2
- https://artificialanalysis.ai/models/comparisons/claude-fable-5-2-vs-gemini-4-neon
- https://venturebeat.com/technology/black-forest-labs-launches-flux-3-capable-of-generating-images-and-20-second-video-with-audio-but-in-limited-release-to-start
- https://runware.ai/docs/changelog
