<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=26&amp;duration=3500&amp;pause=900&amp;color=224B8D&amp;center=true&amp;vCenter=true&amp;width=640&amp;lines=Hi%2C+I%27m+Audrey+%F0%9F%91%8B%3BCompression+%2B+Inference+Systems%3BModel+Capability+%2B+Agent+Reliability" alt="Hi, I’m Audrey — compression, inference systems and agent reliability" />
</h1>

I publish as **Yu Mao**. I'm a Research Scientist at **ByteDance** working on
efficient and reliable AI systems, with a focus on compression, LLM inference,
and reproducibility. I received my Ph.D. in Computer Science from
**City University of Hong Kong** and am based in San Jose.

[Homepage](https://mynotwo.github.io/) ·
[Publications](https://mynotwo.github.io/publications/) ·
[Google Scholar](https://scholar.google.com/citations?user=Iw3bTCAAAAAJ&hl=en) ·
[LinkedIn](https://www.linkedin.com/in/yu-m-475219138)

## Research projects

| Project | Status | Question | Start with |
|---|---|---|---|
| [KVBytePack](https://github.com/mynotwo/kvbytepack) | Reproducible artifact | When do smaller KV records pay for their codec cost? | [Public records, CPU cost and memory measurements](https://github.com/mynotwo/kvbytepack/blob/main/docs/cpu-decode.md) |
| [BitExact LLM](https://github.com/mynotwo/bitexact-llm) | Research prototype | What stays identical when inference execution changes? | [Weight-free arithmetic checks and scoped device reports](https://github.com/mynotwo/bitexact-llm/blob/main/docs/REPRODUCING.md) |
| [AIBrix Hybrid KV Cache](https://github.com/mynotwo/aibrix-hybrid-kvcache) | Experimental | What state must a hybrid prefix cache preserve? | [CPU storage/trace example](https://github.com/mynotwo/aibrix-hybrid-kvcache/blob/main/python/aibrix_kvcache/tools/CPU_QUICKSTART.md) · [RFC](https://github.com/vllm-project/aibrix/issues/3220) |
| [Random-Reward RL Probe](https://github.com/mynotwo/rl-random-prob) | Paper artifact | What can training reach without correctness feedback? | [Paper result CSVs and GPU-free figure reproduction](https://github.com/mynotwo/rl-random-prob#explore-the-published-results-no-gpu) |

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

- [**AgentPProf: Semantic Profiler for AI Agents**](https://os-for-agent.github.io/papers/AgenticOS_SOSP_2026_paper_27.pdf) · AgenticOS @ SOSP 2026 · 🏆 *Best Paper Award*
- [**Probe with Participation Trophies: Random-Reward RL as a Probe of LLM Capability**](https://github.com/mynotwo/rl-random-prob) · Preprint 2026
- [**WISE: A Framework for Gigapixel Whole-Slide-Image Lossless Compression**](https://mynotwo.github.io/assets/pdfs/wise.pdf) · CVPR 2025
- [**PMR: Fast Application Response via Parallel Memory Reclaim on Mobile Devices**](https://mynotwo.github.io/assets/pdfs/pmr.pdf) · USENIX ATC 2025
- [**When Compression Meets Model Compression**](https://mynotwo.github.io/assets/pdfs/compression-meets.pdf) · EMNLP Findings 2024
- [**Faster and Stronger Lossless Compression with Optimized Autoregressive Framework**](https://github.com/mynotwo/Faster-and-Stronger-Lossless-Compression-with-Optimized-Autoregressive-Framework) · DAC 2023
- [**TRACE: A Fast Transformer-based General-purpose Lossless Compressor**](https://github.com/mynotwo/A-Fast-Transformer-based-General-Purpose-LosslessCompressor) · WWW 2022

Full list on my [homepage](https://mynotwo.github.io/publications/) and [Google Scholar](https://scholar.google.com/citations?user=Iw3bTCAAAAAJ&hl=en).

## 🛠️ Tools I use

Python · PyTorch · Triton · CUDA · vLLM · Go · eBPF

<p>
  <img src="https://komarev.com/ghpvc/?username=mynotwo&amp;style=flat&amp;color=lightgrey&amp;label=Profile+views" alt="Approximate profile views, counted from image requests" />
</p>
