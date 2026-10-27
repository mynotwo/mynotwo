# Hi, I'm Audrey

I publish as **Yu Mao**. I'm a Research Scientist at **ByteDance** in San Jose,
and received my Ph.D. in Computer Science from **City University of Hong Kong**.

I work on compression and inference systems, with a particular interest in
when saving bytes actually helps a system run better. I also study reproducible
inference, model capability and agent reliability.

[Homepage](https://mynotwo.github.io/) ·
[Publications](https://mynotwo.github.io/publications/) ·
[Google Scholar](https://scholar.google.com/citations?user=Iw3bTCAAAAAJ&hl=en) ·
[LinkedIn](https://www.linkedin.com/in/yu-m-475219138)

## Research projects

| Project | Question | Start with |
|---|---|---|
| [KVBytePack](https://github.com/mynotwo/kvbytepack) | When do smaller KV records pay for their codec cost? | [Public records, CPU cost and memory measurements](https://github.com/mynotwo/kvbytepack/blob/main/docs/cpu-decode.md) |
| [BitExact LLM](https://github.com/mynotwo/bitexact-llm) | What stays identical when inference execution changes? | [Weight-free arithmetic checks and scoped device reports](https://github.com/mynotwo/bitexact-llm/blob/main/docs/REPRODUCING.md) |
| [AIBrix Hybrid KV Cache](https://github.com/mynotwo/aibrix-hybrid-kvcache) | What state must a hybrid prefix cache preserve? | [CPU storage/trace example](https://github.com/mynotwo/aibrix-hybrid-kvcache/blob/main/python/aibrix_kvcache/tools/CPU_QUICKSTART.md) · [RFC](https://github.com/vllm-project/aibrix/issues/3220) |
| [Random-Reward RL Probe](https://github.com/mynotwo/rl-random-prob) | What can training reach without correctness feedback? | [Paper result CSVs and GPU-free figure reproduction](https://github.com/mynotwo/rl-random-prob#explore-the-published-results-no-gpu) |

These projects expose their tradeoffs and evidence: byte-preserving codecs,
explicit inference-identity contracts, independently testable storage behavior,
and reported training outcomes. The hybrid integration's model equivalence is
still unresolved; BitExact's current CPU checks do not certify every device.

Earlier compression work includes [TRACE](https://github.com/mynotwo/A-Fast-Transformer-based-General-Purpose-LosslessCompressor)
(WWW 2022), with follow-ups at
[ACM MM 2022](https://github.com/mynotwo/compressor_via_simple_and_scalable_parameterization)
and [DAC 2023](https://github.com/mynotwo/Faster-and-Stronger-Lossless-Compression-with-Optimized-Autoregressive-Framework).

## Everyday tools

I'm also building [Hushword](https://github.com/mynotwo/hushword): speak in the
app you're using, then return to writing. It combines local Whisper with Apple
Speech and offers an optional Agent rewrite after dictation.

[Build and try it on an Apple Silicon Mac](https://github.com/mynotwo/hushword#build-and-install-from-source) ·
[Where audio and text are processed](https://github.com/mynotwo/hushword#processing-and-privacy)

## 📝 Selected publications

- **AgentPProf: Semantic Profiler for AI Agents** · AgenticOS @ SOSP 2026 · 🏆 *Best Paper Award*
- **Probe with Participation Trophies: Random-Reward RL as a Probe of LLM Capability** · Preprint 2026
- **WISE: A Framework for Gigapixel Whole-Slide-Image Lossless Compression** · CVPR 2025
- **PMR: Fast Application Response via Parallel Memory Reclaim on Mobile Devices** · USENIX ATC 2025
- **When Compression Meets Model Compression** · EMNLP Findings 2024
- **Faster and Stronger Lossless Compression with Optimized Autoregressive Framework** · DAC 2023
- **TRACE: A Fast Transformer-based General-purpose Lossless Compressor** · WWW 2022

Full list on my [homepage](https://mynotwo.github.io/publications/) and [Google Scholar](https://scholar.google.com/citations?user=Iw3bTCAAAAAJ&hl=en).

## 🛠️ Tools I use

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/Triton-224b8d?style=flat-square" alt="Triton">
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA">
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" alt="vLLM">
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
<img src="https://img.shields.io/badge/eBPF-FF6600?style=flat-square" alt="eBPF">
</p>
