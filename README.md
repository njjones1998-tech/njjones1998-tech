# Nathaniel Jones

**Founder & CEO, Scriptores Helm LLC — AI Systems | Python | Linux**

I build and operate private AI infrastructure: a dual-Xeon + GPU inference lab running large language models 24/7, and the products and agent systems built on top of it. Self-taught across software and hardware. I publish measured results — including the failures.

## What I've shipped

- **[Conviction Market](https://conviction-market-nate.nj1223.chatgpt.site)** — Deployed prediction-market and gaming platform (TypeScript, D1/SQLite, Cloudflare Workers): prediction markets, blackjack, roulette, parlay betting with bankroll management, atomic D1 transaction batches, anonymous sessions, and an owner-only admin dashboard with telemetry.
- **[forge-inference-lab](https://github.com/njjones1998-tech/forge-inference-lab)** — The lab notebook: NUMA pinning law (+43–76%), MTP speculative decoding (+45–55%), custom CUDA/PTX kernels for Pascal GPUs, honest scoreboard of wins AND failures.
- **[scribe-streaming-bridge](https://github.com/njjones1998-tech/scribe-streaming-bridge)** — Python Telegram bridge streaming a local LLM's answers live, with per-chat history, allowlisted access, and real code execution.
- **[llama-cpp-engine-recipes](https://github.com/njjones1998-tech/llama-cpp-engine-recipes)** — Production launch configs: GPU+CPU expert offload at 262K context, 284B pure-CPU serving, cross-vendor distributed inference (CUDA + ROCm).
- **[self-taught-academy](https://github.com/njjones1998-tech/self-taught-academy)** — Self-teaching platform: 15-module curriculum, deterministic pytest verifier, Leitner scheduling, timed exams.
- **Service Desk product suite** — Job & Payment Tracker (Excel), Service Quote Calculator (Excel), Client Intake & Job Checklist Pack (Word/PDF, A4+Letter). Business tools built for distribution. *(repo incoming)*

## The hardware it all runs on

2× Xeon Silver 4216 · 562 GB RAM · Tesla P100 16 GB · 13.5 TB — serving MoE models up to 744B parameters and GPU-offloaded workloads at 262K context, tuned at the NUMA/thread/kernel level. Upgrading to multiple NVIDIA V100s next.

## Contact

info@scriptoreshelm.com · [LinkedIn](https://www.linkedin.com/in/nathaniel-jones-381208433) · [Portfolio](https://njjones1998-tech.github.io/nathaniel-jones-site/)
