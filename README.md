<!-- NOTE: the Voice-Agent repo currently lives under the justkuldeep account. Update its links below if you move/fork it to DamnKuldeep. -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Kuldeep&fontSize=76&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Agentic%20AI%20%C2%B7%20Voice%20Agents%20%C2%B7%20RAG%20%C2%B7%20LLM%20Inference&descSize=20&descAlignY=58" alt="Kuldeep" width="100%" />

<a href="https://github.com/DamnKuldeep">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=2800&pause=900&color=8B5CF6&center=true&vCenter=true&width=900&height=50&lines=Agentic+AI+%26+GenAI+Engineer;Voice+Agents+%C2%B7+Multi-Agent+Systems;RAG+%26+Inference+Engineering;LLM+Products+That+Actually+Ship" alt="Typing SVG" />
</a>

<br/>

![Focus](https://img.shields.io/badge/Focus-Production%20AI%20Systems-8B5CF6?style=for-the-badge)
![Mode](https://img.shields.io/badge/Mode-Multi--Agent%20%2B%20RAG-10B981?style=for-the-badge)
![Voice](https://img.shields.io/badge/Voice-STT%20%E2%86%92%20LLM%20%E2%86%92%20TTS-F59E0B?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-LLMs%20%2F%20Vision%20%2F%20Video-EC4899?style=for-the-badge)

<img src="https://komarev.com/ghpvc/?username=DamnKuldeep&label=Profile%20views&color=8B5CF6&style=flat" alt="Profile views" />

</div>

---

### 👋 About

I build **multi-agent systems**, **voice agents**, **RAG pipelines**, and **LLM-powered products** that go from idea to something actually running — not just a notebook. Lately I care about **measured** engineering: load-tested inference, honest evals, and keeping every wrong prediction on the record.

<table>
<tr>
<td width="50%" valign="top">

**🔭 Working on**
- Real-time **voice agents** (local STT → LLM → neural TTS)
- Serving LLMs on **constrained hardware**
- Agent ensembles that *don't* trust a single model
- Fully unattended generative media pipelines

</td>
<td width="50%" valign="top">

**⚡ What I build**
- Multi-agent workflows with tools, memory & reasoning
- Retrieval + reranking for grounded, cited answers
- Inference gateways with admission control & observability
- Image / video / voice generation pipelines

</td>
</tr>
</table>

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🎙️ [Voice-Agent](https://github.com/justkuldeep/Voice-Agent)
**A complete AI voice call pipeline, built step by step.**
Local **Whisper** speech-to-text → **Gemini** for conversation → **ElevenLabs** for voice, with real-time audio playback. Modular design with documentation and troubleshooting guides.

`Whisper` `Gemini` `ElevenLabs` `Python` `Real-time audio`

</td>
<td width="50%" valign="top">

#### ⚡ [qwen2.5-1.5b-awq-vllm-rtx3050-4gb](https://github.com/DamnKuldeep/qwen2.5-1.5b-awq-vllm-rtx3050-4gb)
**20 concurrent chat users from one 4 GiB laptop GPU.**
**97%** of messages get a first token within **1.5 s** (retries included). Cache-aware admission control, a head-of-line fix, 10 predictive alerts, a 14-case failure matrix, and 24 predictions kept on record.

`vLLM` `AWQ + Marlin` `FastAPI` `Prometheus` `Grafana`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⚖️ [KnowYourRightsAI](https://github.com/DamnKuldeep/KnowYourRightsAI)
**Indian-law answers in English, Hindi & Hinglish — every claim traced to an Act and section.**
**38,890** chunks across **1,020** Acts, **98%** recall@5, calibrated to decline rather than hallucinate. Reads government portals for procedure questions.

`FastAPI` `LanceDB` `bge-m3 + BM25` `Cross-encoder rerank` `NVIDIA NIM`

</td>
<td width="50%" valign="top">

#### 🎬 [ContentFactory](https://github.com/DamnKuldeep/ContentFactory)
**One story idea → a finished 1080×1920 vertical video, fully unattended.**
Script, narration with per-character timing, 30+ consistent scene images, music built from the voice's energy, and the cut. **88 videos** in one batch on 3 machines, ~25 min each.

`Llama 3.3 70B` `FLUX.2` `Fish Speech` `WhisperX` `FFmpeg`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 🎞️ [ltxv-13b-distilled-free-gpu-pipeline](https://github.com/DamnKuldeep/ltxv-13b-distilled-free-gpu-pipeline)
**A 13B text/image-to-video model on free Kaggle T4 GPUs.**
NF4 quantization shrinks ~26 GB of weights to ~8.5 GB, dual-GPU memory splitting, 22 hot-swappable LoRA styles, and LLM prompt enhancement.

`LTX-Video` `NF4` `PEFT / LoRA` `Gradio` `Kaggle`

</td>
</tr>
</table>

#### 🎙️ How the voice agent works

```mermaid
flowchart LR
    A[🎤 Mic] --> B[Whisper<br/>local STT]
    B --> C[Gemini<br/>conversation]
    C --> D[ElevenLabs<br/>TTS]
    D --> E[🔊 Real-time<br/>playback]
```

---

### 🧠 Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![NVIDIA](https://img.shields.io/badge/NVIDIA%20NIM-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=for-the-badge&logo=gradio&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

![vLLM](https://img.shields.io/badge/Inference-vLLM%20%2F%20AWQ-0EA5E9?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-LanceDB%20%2B%20BM25-22C55E?style=for-the-badge)
![Voice](https://img.shields.io/badge/Voice-Whisper%20%2F%20ElevenLabs%20%2F%20Fish-F59E0B?style=for-the-badge)
![Gen](https://img.shields.io/badge/GenAI-FLUX.2%20%2F%20LTX--Video-A855F7?style=for-the-badge)

</div>

---

### 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=DamnKuldeep&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DamnKuldeep&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=DamnKuldeep&theme=tokyonight&hide_border=true" alt="Streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=DamnKuldeep&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" width="100%" />

</div>

---

### 🔥 Currently exploring

> Building AI experiences that are not just interesting, but **useful, deployable, and engineered for scale.**

`Voice agents` · `Agentic execution systems` · `Grounded retrieval & memory` · `Performance-first inference` · `LLM-native products`

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-DamnKuldeep-181717?style=for-the-badge&logo=github)](https://github.com/DamnKuldeep)
[![Kaggle](https://img.shields.io/badge/Kaggle-damnyadav-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/damnyadav)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" width="100%" alt="" />

</div>
