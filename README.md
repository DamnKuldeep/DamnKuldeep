# Kuldeep

Agentic AI & GenAI engineer -- I build multi-agent systems, RAG pipelines, and LLM-orchestrated products that go from idea to something actually running in production, not just a notebook. Lately: inference engineering, measured rather than assumed.

### Selected work

**[qwen2.5-1.5b-awq-vllm-rtx3050-4gb](https://github.com/DamnKuldeep/qwen2.5-1.5b-awq-vllm-rtx3050-4gb)** -- Serves an LLM to ~22 concurrent chat users from a single 4 GiB laptop GPU. Measured the hardware's real ceiling (6 requests in flight), built a gateway that refuses to exceed it, and recorded 24 wrong predictions instead of hiding them. p95 TTFT held at 778 ms while offered load rose 6x; 14-case failure matrix, every case measured.
`vLLM` `AWQ + Marlin` `FastAPI` `admission control` `Prometheus/Grafana` `load testing`

**[KnowYourRightsAI](https://github.com/DamnKuldeep/KnowYourRightsAI)** -- Answers Indian-law questions in plain English/Hindi/Hinglish, every claim traced to a specific Act & section. 38,890 chunks across 1,020 Acts, 98% recall@5, tuned to decline rather than hallucinate.
`FastAPI` `LanceDB (bge-m3 + BM25)` `cross-encoder reranking` `NVIDIA NIM`

**[ContentFactory](https://github.com/DamnKuldeep/ContentFactory)** -- Turns a story idea into a finished vertical video: script, narration, 30+ consistent scene images, matched music, and cut, fully unattended across a distributed, multi-machine job queue. ~25 min/video, 88 videos in one batch run.
`Llama 3.3 70B` `FLUX.2` `Fish Speech` `WhisperX` `FFmpeg`

**[StealTheDealAI](https://github.com/DamnKuldeep/StealTheDealAI)** -- 9-agent system that scans live Amazon India listings for genuinely underpriced products; 3 independent pricing models cross-check each other with outlier rejection before a deal is flagged.
`RAG + fine-tuned LLM + local NN ensemble` `ChromaDB` `crawl4ai/Playwright` `Modal`

**[ltxv-13b-distilled-free-gpu-pipeline](https://github.com/DamnKuldeep/ltxv-13b-distilled-free-gpu-pipeline)** -- Runs a 13B text/image-to-video model on free Kaggle T4 GPUs by NF4-quantizing it from 26GB to 8.5GB and splitting work across two GPUs. 22 LoRA style adapters, 30+ second generations.
`LTX-Video` `NF4 quantization` `PEFT/LoRA` `Gradio`

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-multi--agent%20systems-6E56CF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-hybrid%20retrieval%20%2B%20reranking-2E7D32?style=flat-square)
![Inference](https://img.shields.io/badge/Inference-vLLM%20%2B%20AWQ%2C%20measured-0B5FFF?style=flat-square)
