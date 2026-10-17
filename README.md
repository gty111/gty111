
- PH.D. student at Sun Yat-sen university

- AI Infra, MLSys, Simulaters, GPU architecture

- [Visit my personal web](https://gty111.github.io/info)

## News

- [2026/01/13] [\[LMSYS blog\]](https://lmsys.org/blog/2026-01-12-epd/) EPD Disaggregation: Elastic Encoder Scaling for Vision-Language Models in SGLang
- [2025/06/27] [\[arXiv\]](https://arxiv.org/abs/2504.14775) [\[Code\]](https://github.com/gty111/gLLM) gLLM is accepted by SC'25. Congratulations!
- [2025/05/28] [\[arXiv\]](https://arxiv.org/abs/2505.21889) [\[Code\]](https://github.com/gty111/EFIM) EFIM is accepted by Euro-Par'25 
- [2025/04/27] [\[arXiv\]](https://arxiv.org/abs/2504.14775) [\[Code\]](https://github.com/gty111/gLLM) We have released gLLM, an efficient pipeline parallelism inference engine for LLM.

# Merged PRs by Project

## vLLM

32 merged PRs

- [\[Model\] Add Clef-Flash support](https://github.com/vllm-project/vllm/pull/61308)
- [\[Bugfix\]\[KVConnector\]\[NIXL\] Fix TP handshake test after per-region FA desc flags](https://github.com/vllm-project/vllm/pull/60157)
- [\[Bugfix\]\[Model\] Fix Qwen3-Omni interleaved M-RoPE boundary positions](https://github.com/vllm-project/vllm/pull/59842)
- [\[Bugfix\]\[Attention\] Restrict FlashInfer sparse MLA FULL graphs to decode](https://github.com/vllm-project/vllm/pull/59751)
- [\[Bugfix\]\[EPD\] Skip sampling for encoder-only async steps](https://github.com/vllm-project/vllm/pull/58490)

<details>
<summary>Show 27 more PRs</summary>

- [\[Bugfix\] Disable prefix caching for encoder-only before model config hooks](https://github.com/vllm-project/vllm/pull/58287)
- [\[Bugfix\]\[EC Connector\] Size transfers by measured encoder output widths](https://github.com/vllm-project/vllm/pull/57904)
- [\[EPD\] Support metadata-only audio inputs](https://github.com/vllm-project/vllm/pull/57887)
- [\[Perf\]\[EPD\] Batch image requests per encoder](https://github.com/vllm-project/vllm/pull/57095)
- [\[Performance\]\[EPD\] Reduce Python proxy serialization overhead](https://github.com/vllm-project/vllm/pull/56657)
- [\[Bugfix\]\[EPD\] Preserve explicit multimodal UUIDs with caches disabled](https://github.com/vllm-project/vllm/pull/56432)
- [\[EC\] Automatically enable embedding inputs on EC/KV consumers](https://github.com/vllm-project/vllm/pull/56379)
- [\[Frontend\]\[EPD\] Use JSON arrays for multimodal metadata](https://github.com/vllm-project/vllm/pull/56090)
- [\[Bugfix\]\[EC Connector\] Fail the request, not the engine, when a remote encoding cannot arrive](https://github.com/vllm-project/vllm/pull/55290)
- [\[Feature\]\[EPD\] Support dynamic EPD (EC-connector) proxy](https://github.com/vllm-project/vllm/pull/54176)
- [\[Config\]\[EC\] Normalize producer-only encoder config](https://github.com/vllm-project/vllm/pull/53656)
- [\[Refactor\]\[Model Runner V2\]\[Multimodal\] Move the encoder-only path out of the shared runner](https://github.com/vllm-project/vllm/pull/53176)
- [\[Bugfix\]\[V1\]\[Multimodal\] Ignore stale same-step encoder cache evictions](https://github.com/vllm-project/vllm/pull/52482)
- [\[Perf\] Avoid repeated multimodal prompt update scans](https://github.com/vllm-project/vllm/pull/51774)
- [\[Bugfix\]\[EPD\]\[Model Runner V2\] Skip gather mm embeddings for encoder only instance](https://github.com/vllm-project/vllm/pull/51222)
- [\[EPD\] Remove duplicate image preprocessing in EPD and enable preprocess on GPU](https://github.com/vllm-project/vllm/pull/50390)
- [\[Bugfix\]\[EC Connector\] Don't stop an encoder-instance request before its images are encoded](https://github.com/vllm-project/vllm/pull/50275)
- [[Model] Support Unlimited OCR](https://github.com/vllm-project/vllm/pull/46564)
- [[Bugfix][Multimodal] Fix Qwen3-Omni use_audio_in_video with mixed image/video inputs](https://github.com/vllm-project/vllm/pull/46213)
- [Fix the order of _free_encoder_inputs](https://github.com/vllm-project/vllm/pull/38907)
- [Remove unused EVS functions in qwen3_vl.py](https://github.com/vllm-project/vllm/pull/37183)
- [Support online use_audio_in_video](https://github.com/vllm-project/vllm/pull/36319)
- [[Bugfix] Fix benchmark_moe.py](https://github.com/vllm-project/vllm/pull/19016)
- [[Benchmark] Refactor sample_requests in benchmark_throughput](https://github.com/vllm-project/vllm/pull/3613)
- [[Bugfix] fix automatic prefix args and add log info](https://github.com/vllm-project/vllm/pull/3608)
- [[Minor Fix] Fix comments in benchmark_serving](https://github.com/vllm-project/vllm/pull/3252)
- [[Minor Fix] Remove unused code in benchmark_prefix_caching.py](https://github.com/vllm-project/vllm/pull/3171)

</details>

## SGLang

6 merged PRs

- [Support PP for zmq_to_scheduler](https://github.com/sgl-project/sglang/pull/15312)
- [Add EPD disaggregation doc](https://github.com/sgl-project/sglang/pull/15224)
- [feat: support EPD disaggregation](https://github.com/sgl-project/sglang/pull/12263)
- [[VLM] Support PP for Qwen2.5-VL](https://github.com/sgl-project/sglang/pull/13075)
- [Add PP support for dots_vlm](https://github.com/sgl-project/sglang/pull/12763)

<details>
<summary>Show 1 more PR</summary>

- [Fix port number overflow](https://github.com/sgl-project/sglang/pull/2826)

</details>

## xDiT

2 merged PRs

- [Enable warm up for VAE](https://github.com/xdit-project/xDiT/pull/300)
- [Fix parallel vae](https://github.com/xdit-project/xDiT/pull/281)

## DistVAE

1 merged PR

- [Fix batch dimension](https://github.com/xdit-project/DistVAE/pull/3)

## TVM

2 merged PRs

- [[Doc] Fix minor error in "Expressions in Relay"](https://github.com/apache/tvm/pull/16346)
- [[Doc] Fix minor error in doc (Add an operator to Relay)](https://github.com/apache/tvm/pull/16282)
