# Kuldeep

Agentic AI & GenAI engineer -- I build multi-agent systems, RAG pipelines, and LLM-orchestrated products that go from idea to something actually running in production, not just a notebook.

### Currently

Building a story-to-video pipeline (multi-stage agentic generation: script, visuals, voice, music, cut) and going deeper on retrieval quality and multi-agent verification patterns.

### Selected work

**[KnowYourRightsAI](https://github.com/DamnKuldeep/KnowYourRightsAI)** -- Answers Indian-law questions in plain English/Hindi/Hinglish, every claim traced to a specific Act & section. 38,890 chunks across 1,020 Acts, 98% recall@5, tuned to decline rather than hallucinate.
`FastAPI` `LanceDB (bge-m3 + BM25)` `cross-encoder reranking` `NVIDIA NIM`

**[StealTheDealAI](https://github.com/DamnKuldeep/StealTheDealAI)** -- 9-agent system that scans live Amazon India listings for genuinely underpriced products; 3 independent pricing models cross-check each other with outlier rejection before a deal is flagged.
`RAG + fine-tuned LLM + local NN ensemble` `ChromaDB` `crawl4ai/Playwright` `Modal`

**[ContentFactory](https://github.com/DamnKuldeep/ContentFactory)** -- Turns a story idea into a finished vertical video: script, narration, 30+ consistent scene images, matched music, and cut, fully unattended across a distributed, multi-machine job queue. ~25 min/video, 88 videos in one batch run.
`Llama 3.3 70B` `FLUX.2` `Fish Speech` `WhisperX` `FFmpeg`

**[ltxv-13b-distilled-free-gpu-pipeline](https://github.com/DamnKuldeep/ltxv-13b-distilled-free-gpu-pipeline)** -- Runs a 13B text/image-to-video model on free Kaggle T4 GPUs by NF4-quantizing it from 26GB to 8.5GB and splitting work across two GPUs. 22 LoRA style adapters, 30+ second generations.
`LTX-Video` `NF4 quantization` `PEFT/LoRA` `Gradio`

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-multi--agent%20systems-6E56CF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-hybrid%20retrieval%20%2B%20reranking-2E7D32?style=flat-square)
