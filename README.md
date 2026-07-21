<!-- <div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=LucaTamSapienza&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=LucaTamSapienza&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div> -->

```yaml
apiVersion: human/v1
kind: Engineer

metadata:
  name: Luca Tam
  location: Rome, Italy  # 🇮🇹
  role: AI Engineer
  labels:
    - open-source-enthusiast
    - llm-plumber          # RAG pipelines, retrieval, evaluation
    - hpc-user             # if it fits on one GPU, it's a warm-up
    - sapienza-engineer
  annotations:
    motto: "if it's not open source, I'm only mildly interested"

contact:
  email: luca.tam04@gmail.com
  github: LucaTamSapienza
  linkedin: luca-tam
  discord: Famezz

education:
  - degree: MSc — Engineering in Computer Science & Artificial Intelligence
    university: Sapienza University of Rome
    status: in_progress
    expected: 2027
  - degree: BSc — Computer Engineering
    university: Sapienza University of Rome
    grade: 110/110 with honors
    status: completed  # ✅

work:
  - company: Martes AI
    role: AI Engineer
    since: 2025-06
    shipping:
      - production LLM newsletter platform for a financial research firm
      - AI content generation platform (multi-stage LLM planning pipeline)
      - self-learning clinical RAG system grounded in scientific evidence (PubM
      - ERP platform with a read-only LLM data agent

  - company: Babelscape
    role: NLP Engineer Intern
    period: 2025-10 -> 2026-07
    focus: >
      Retrieval stack of Minerva Web, the RAG system behind Italy's largest
      open-source LLM: query routing, query reformulation, safety
      classification, and evaluation.
    infrastructure: >
      Trained and evaluated models on Leonardo, CINECA's pre-exascale
      supercomputer: SLURM-scheduled multi-GPU jobs, fine-tuning of
      encoders and LLMs, large-scale dataset processing for SFT.
    # also shrank a 397B teacher into a 307M student once. it behaved.

  - program: Google Summer of Code 2024
    org: OpenVINO Toolkit
    built: >
      PyTorch adapter POC for OpenVINO's Python API
      (import torch_adapter as torch), covering pre/post-processing
      and inference on PyTorch Hub models.

open_source:
  why: >
    Most of what I know, I learned by reading other people's code.
    Contributing is just paying the rent.
  contributed_to:
    - repo: openvinotoolkit/openvino
      what: >
        Merged PRs to the Python API (slice & negative indexing for
        Shape/PartialShape, opset name appending) and the
        PyTorch/TensorFlow frontends (new ops: aminmax, dot, expm1;
        complex-tensor support for Size, AddN, Round).
  my_projects:
    - repo: LucaTamSapienza/glance
      what: >
        Token-efficient Markdown memory layer for LLM agents: budget-aware
        retrieval, per-query token receipts, CLI + MCP server,
        and a terminal reader/editor written in C.
    - repo: prollyyes/faqbuddy
      what: >
        AI chatbot answering university FAQs: RAG + text-to-SQL,
        Next.js + FastAPI + PostgreSQL. Live at faqbuddy.net.
  watching_and_loving:
    - vllm-project/vllm
    - huggingface/transformers
    - ggml-org/llama.cpp
    - karpathy/nanoGPT
    - openvinotoolkit/openvino
    - CGAL/cgal

stack:
  languages: [Python, TypeScript, C, C++, Java, SQL]
  ai_ml: [PyTorch, HuggingFace, vLLM, ONNX, OpenVINO, scikit-learn, RAG & LLM ]
  hpc: [Leonardo @ CINECA, SLURM, distributed multi-GPU training]
  web_cloud: [Next.js, Node.js, FastAPI, PostgreSQL, Docker, Git]
  spoken: {italian: native, english: C1}

runtime:
  currently_learning: [LLM evaluation, retrieval systems, scaling training on H
  hobbies: [gym, IoT]
  livenessProbe:
    exec:
      command: ["gym", "--daily"]
    failureThreshold: 1

status:
  open_to:
    - open source collaboration
    - interesting AI/ML problems
    - talking about retrieval, evaluation, or why your RAG hallucinates
  response_time: fast
```
