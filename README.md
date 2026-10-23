<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3500&pause=900&color=224B8D&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Yu+(Audrey)+Mao+%F0%9F%91%8B;Inference+systems+%C2%B7+Compression+%C2%B7+Agent+reliability;Same+prompt%2C+same+bits%2C+any+hardware" alt="Hi, I'm Yu (Audrey) Mao" />

Research Scientist at **ByteDance** (San Jose) · Ph.D. in CS, **City University of Hong Kong**

<a href="https://mynotwo.github.io/"><img src="https://img.shields.io/badge/Homepage-mynotwo.github.io-224b8d?style=flat-square&logo=githubpages&logoColor=white" alt="Homepage"></a>
<a href="https://scholar.google.com/citations?user=Iw3bTCAAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-Yu_Mao-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
<a href="https://www.linkedin.com/in/yu-m-475219138"><img src="https://img.shields.io/badge/LinkedIn-Yu_Mao-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

</div>

---

I work on **AI infrastructure and LLM inference**: how inference state is represented, compressed and moved through serving systems, how to make model outputs reproducible down to the bit, and how reliably agents use the capabilities their models have.

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [BitExact LLM](https://github.com/mynotwo/bitexact-llm)
Bit-reproducible Llama inference in integer arithmetic. The same prompt and seed give the same logits, bit for bit, on H800, H100, x86 CPU and Apple M4 Pro, across batch sizes, with or without KV cache. Runs the original bf16 weights exactly, and ships as a vLLM plugin.

`Python` `Triton` `vLLM` `CUDA`

</td>
<td width="50%" valign="top">

### [AIBrix Hybrid KV Cache](https://github.com/mynotwo/aibrix-hybrid-kvcache)
Prefix-cache offloading for hybrid models on AIBrix: variable-length KV records, a bounded MEMORY backend and compression profiling.

[RFC](https://github.com/vllm-project/aibrix/issues/3220) · [Draft PR](https://github.com/vllm-project/aibrix/pull/3221) · [Preview](https://github.com/mynotwo/aibrix-hybrid-kvcache/releases/tag/hybrid-v0.1.1-experimental)

`Go` `KV cache` `LLM serving`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [TRACE](https://github.com/mynotwo/A-Fast-Transformer-based-General-Purpose-LosslessCompressor)
A fast Transformer-based general-purpose lossless compressor (WWW 2022), with follow-ups at [ACM MM 2022](https://github.com/mynotwo/compressor_via_simple_and_scalable_parameterization) and [DAC 2023](https://github.com/mynotwo/Faster-and-Stronger-Lossless-Compression-with-Optimized-Autoregressive-Framework).

`PyTorch` `Lossless compression`

</td>
<td width="50%" valign="top">

### [Random-Reward RL Probe](https://github.com/mynotwo/rl-random-prob)
Code for *Probe with Participation Trophies*: random-reward RL as a probe of what an LLM can already do. [arXiv 2610.01066](https://arxiv.org/abs/2610.01066)

`RLVR` `LLM capability`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [kvzip](https://github.com/mynotwo/kvzip)
Lossless compression of LLM KV cache and activations with a byte-plane layout and general-purpose codecs.

`Python` `KV cache`

</td>
<td width="50%" valign="top">

### [HushWord](https://github.com/mynotwo/hushword)
Local-first macOS menu-bar dictation.

`Swift` `macOS`

</td>
</tr>
</table>

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
