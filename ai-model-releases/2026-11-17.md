# New AI Model Releases: Daily Report for 2026-11-17

Covers releases from roughly **Nov 1 to Nov 17, 2026**. These are the newest models from labs around the world and what each one is for.

> Confidence: **Confirmed** = an official vendor post or several major outlets agree. **Reported** = mostly from aggregators or trackers, so check with the vendor before relying on it.

## Headline releases

| Model | Org (country) | Date | Type | Good for | Confidence |
|---|---|---|---|---|---|
| **Qwen4-Max (Preview)** | Alibaba (China) | Nov 11 preview; trackers list Nov 16 API | LLM, closed | Coding and autonomous agents; 1M-token context; image and video input; built-in web search, function calling and JSON-schema output. No official benchmarks or weights yet, and the preview trial ends Nov 25. | Reported |
| **Gemini 4 Hydrogen** | Google (USA) | Nov 12 | LLM, closed (Flash successor) | Fast, low-cost agent workflows, everyday coding, and Search/Gemini app use. Google says it is 2.5x faster than Gemini 3.8 Flash. Scores 51–54 on the AA Intelligence Index. About $1.10–1.50 in / $7.50 out per 1M tokens. A robotics variant adds Embodied Reasoning skills. | Confirmed |
| **Gemini 4 Carbon** | Google (USA) | ~Nov 10 | LLM, closed (frontier) | Deep, long-horizon reasoning, between Hydrogen and the flagship **Gemini 4 Argon**. Argon (GA Oct 1) targets software engineering, finance, legal work and cybersecurity. | Reported |
| **Claude Fable 5.2 / Mythos 5.2** | Anthropic (USA) | Nov 9 | LLM, closed | Coding and agentic work. Up to 30% faster output than 5.1 and lower API prices. Mythos 5.2 is the same model with fewer restrictions, offered only to vetted cybersecurity and life-sciences organizations. Available on the API, AWS, GCP and Azure. | Confirmed |
| **Muse Ember 1.0** | Meta (USA) | Nov 9–10 | LLM, closed, low cost | Cheap sub-agent work, tool calls, routing and repetitive tasks. 1M context, 512K output. Takes text, image, video, audio and PDF input. About $0.10 in / $0.50 out per 1M tokens. | Reported |
| **GPT-Image-2.6 (Sunburst & Flare)** | OpenAI (USA) | Nov 4 | Image generation | Image generation and editing, 50% faster than 2.5. New: SVG output, animated GIFs, adjustable complexity, markup editing. Sunburst is for quality and consistent edits, Flare for speed. Live in ChatGPT, including the free tier. | Confirmed |
| **Mistral Large 4** | Mistral AI (France) | Nov 5 listing (preview Oct 6) | LLM, open weights | Strong general-purpose model you can run yourself, released under the Mistral open-weight license. | Reported |
| **Olala mini 7A1B** | OVHcloud (France) | Announced Nov 17, launches Nov 19 | Small LLM, open (Apache 2.0) | Lightweight European model: 7B parameters with ~1B active (MoE). Runs in 8 GB of GPU memory or on a CPU at ~50 tokens/s. Good for on-device and private use. | Reported |
| **Gemini Omni 1.2 Flash** | Google (USA) | Nov 5 GA | Video and audio generation | 15-second videos with synchronized audio and speech dialogue, about $0.07 per second. | Reported |

## Smaller speech and voice releases
- **Woof** (Underdog): tiny English text-to-speech model, a ~32–41 MB file that runs on a laptop CPU.
- **Rumble-2-Flash** (Reson8): fast, small speech-to-text model covering 40+ languages.
- **GPT-Live-1** (OpenAI): full-duplex voice model, now offered for phone agents through Retell AI.

## Mentioned but not confirmed (watch list)
- **Kimi K3 / K3.1 Pro** (Moonshot, China): reported 2.8–3T-parameter open model with 1M context. The weights release is unverified.
- **Grok 4.7** (xAI): appears in roundups, but there is no official announcement.
- **DeepSeek V4.1 Flash** updates: the dates conflict, and the Nov 9 "uncensored" variant comes from a third party, not DeepSeek.

## Quick take
- **Trend:** labs are releasing fast, cheap "worker" models (Gemini 4 Hydrogen, Muse Ember) to run under frontier "planner" models, and **1M-token context** is now standard.
- **Best for coding/agents:** Claude Fable 5.2, Gemini 4 Argon/Carbon, Qwen4-Max.
- **Best budget option:** Muse Ember 1.0, Gemini 4 Hydrogen.
- **Best open or self-hosted option:** Mistral Large 4, Olala mini.
- **Best for images and video:** GPT-Image-2.6, Gemini Omni 1.2 Flash.

## Sources
- https://llmgateway.io/timeline
- https://www.promptzone.com/ai-model-releases
- https://hermes-ai.net/news/alibaba-launches-qwen4-max-with-agent-first-coding-and-1m-token-support/
- https://alphasignal.ai/news/alibaba-launches-qwen4-max-with-agent-first-coding-and-1m-token-support
- https://www.orcarouter.ai/blog/qwen-4-max-lineup-announced-apsara-2026
- https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/
- https://developers.googleblog.com/gemini-hydrogen-for-robotics/
- https://venturebeat.com/technology/google-launches-gemini-4-hydrogen-a-faster-smarter-pricier-flash-successor
- https://www.datacamp.com/blog/gemini-4-hydrogen
- https://axios.com/2026/09/30/google-gemini-4
- https://9to5mac.com/2026/11/09/anthropic-upgrades-claude-with-new-fable-5-2-model-details-here/
- https://www.testingcatalog.com/anthropic-launches-claude-fable-5-2-and-mythos-5-2/
- https://thenewstack.io/anthropic-fable-coding-upgrade/
- https://www.gradually.ai/en/ai-models/meta-muse-ember-1.0/
- https://www.llmreference.com/model/muse-ember
- https://openai.com/index/introducing-images-2-6/
- https://aiwiki.ai/wiki/gpt_image_2_6
- https://www.clone-systems.com/blog/new-ai-models-november-2026-release-guide-and-security
- https://www.tldl.io/guides/latest-model-releases
- https://itpro.com/software/open-source/ovhcloud-launches-european-trained-open-source-ai-model
- https://pasqualepillitteri.it/en/news/34406/ovhcloud-launches-olala-mini-open-model-8-gb-gpu
- https://af.net/realtime/google-debuts-gemini-omni-1-2-flash-with-15-second-video-at-0-07-sec/
- https://www.voiceaispace.com/news/voice-ai-news-2026-11-08-w45

_Note: some tracker sites (llm-stats.com, benchlm.ai, opper.ai) could not be fetched directly because of this session's network policy. This report was built from web search results._
