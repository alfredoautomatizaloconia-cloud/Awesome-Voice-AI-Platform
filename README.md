# Awesome-Voice-AI-Platform

## Top Voice AI Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Conversational Voice Agents, Real-Time STT/TTS, Telephony Integration, Low-Latency Orchestration & Multimodal Voice Interfaces*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Voice AI**. These systems enable real-time conversational agents that combine speech-to-text, large language models, text-to-speech, turn-taking, telephony, and tool use for inbound/outbound voice experiences.



**Examples** include Retell AI, Vapi, Bland AI, PlayAI, Hume AI, Deepgram Voice Agent, LiveKit Cloud, Daily.co, Cartesia, and ElevenLabs Conversational AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted voice agents, real-time orchestration frameworks, local STT/TTS stacks, and full-duplex conversational systems — ideal for developers and organizations seeking control over latency, data, and cost.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Retell AI](https://www.retellai.com/)**  

  Full-stack AI voice agent platform optimized for natural turn-taking, telephony flexibility, and production inbound/outbound calling with balanced latency and pricing.



- **[Vapi](https://vapi.ai/)**  

  Developer-first voice AI infrastructure for building agents with flexible orchestration across STT, LLM, and TTS providers, strong API control, and telephony integrations.



- **[Bland AI](https://www.bland.ai/)**  

  AI-native voice agent platform strong in high-volume outbound campaigns, concurrency, and all-in per-minute pricing for production phone agents.



- **[PlayAI / Play.ai](https://play.ai/)**  

  Voice-focused platform emphasizing high-quality TTS and conversational voice experiences.



- **[Hume AI](https://www.hume.ai/)**  

  Empathic voice AI platform centered on expressive, emotionally intelligent speech synthesis and conversational models.



- **[Deepgram Voice Agent](https://deepgram.com/)**  

  Voice agent capabilities built on Deepgram’s high-performance speech-to-text, suitable for low-latency conversational pipelines.



- **[LiveKit Cloud](https://livekit.io/)**  

  Real-time WebRTC infrastructure and Agents framework for building multimodal and voice AI applications with strong developer tooling.



- **[Daily.co](https://www.daily.co/)**  

  Real-time video and audio infrastructure (with Pipecat framework roots) used as a transport and media layer for voice and multimodal agents.



- **[Cartesia](https://cartesia.ai/)**  

  Low-latency, high-quality generative voice and speech models optimized for real-time conversational AI.



- **[ElevenLabs Conversational AI](https://elevenlabs.io/)**  

  Conversational AI product built on ElevenLabs’ industry-leading TTS, offering natural voices, multilingual support, and agent orchestration.



## Open-Source GitHub Projects

- **[LiveKit Agents](https://github.com/livekit/agents)**  

  Open-source framework for building real-time voice and multimodal AI agents that run as participants over WebRTC, with strong Python/Node support.



- **[Pipecat](https://github.com/pipecat-ai/pipecat)**  

  Open-source Python framework (from the Daily.co ecosystem) for composing low-latency voice agent pipelines with pluggable STT, LLM, TTS, and transport layers.



- **[Dograh](https://github.com/dograh-hq/dograh)**  

  Open-source, self-hostable voice AI platform positioned as a Vapi/Retell alternative, featuring a visual workflow builder, telephony, and BYOK for STT/LLM/TTS.



- **[TEN Framework / TEN-Agent](https://github.com/TEN-framework/TEN-Agent)**  

  Open-source framework for real-time multimodal conversational AI agents with VAD, turn detection, and extensible agent examples.



- **[OpenLive](https://github.com/katipally/openlive)**  

  On-device open-source voice + vision layer for AI agents; runs the full speech loop (VAD, STT, TTS, barge-in) locally as an alternative to hosted realtime APIs.



- **[Stimm](https://github.com/stimm-ai/stimm)**  

  Open-source voice agent platform focused on ultra-low-latency pipelines and optimistic UI patterns over WebRTC/LiveKit.



- **[Local Voice AI starters](https://github.com/)**  

  Community projects combining llama.cpp, Whisper/faster-whisper, Kokoro or similar TTS, and LiveKit for fully local voice agents.



- **[voice-agents-from-scratch & educational pipelines](https://github.com/pguso/voice-agents-from-scratch)**  

  Hands-on open-source tutorials and libraries for building end-to-end streaming voice agents with explicit latency control.



- **[rrweb-style or custom full-duplex agents](https://github.com/)**  

  Research and production open-source full-duplex dialogue agents with continuous turn-taking behavior.



- **[Vocode and related orchestration libraries](https://github.com/)**  

  Open-source frameworks for composing conversational voice agents with telephony and streaming support.



### Additional Strong Open-Source Options

- **Whisper / faster-whisper / Voxtral / Canary** and other open STT models.

- **Kokoro, XTTS, Chatterbox, Coqui** and similar open TTS engines.

- **Silero VAD** and open turn-detection / end-of-turn models.

- Self-hosted WebRTC stacks (LiveKit open-source server, mediasoup, etc.).

- Integration of open LLMs (via Ollama, vLLM, llama.cpp) into real-time voice loops.

- Telephony bridges (SIP, Twilio-compatible open components) for phone connectivity.



**Frameworks for building custom systems**: Start with **LiveKit Agents** or **Pipecat** for the real-time media and orchestration layer, plug in open or commercial STT/TTS (Whisper + Kokoro for fully local, or Deepgram/Cartesia/ElevenLabs for quality), drive conversation with any LLM, and optionally layer a visual builder such as **Dograh**. Use WebRTC for web clients and SIP/telephony providers for phone numbers. Focus on streaming, barge-in, and sub-second perceived latency.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Voice AI systems process biometric and conversational data. Self-hosted open-source stacks require careful attention to privacy, consent, recording laws, and security of audio streams and transcripts.

- Latency, voice quality, and reliability depend heavily on model choice, network conditions, and infrastructure; always benchmark for your specific use case and region.



---

**Made for AI engineers, product teams, and organizations building real-time voice experiences.**

Let's make conversational voice AI more open, controllable, and self-hostable.
