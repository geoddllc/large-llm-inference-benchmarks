# llama-3-3-70b — VLLM Vanilla — Nvidia H200

Model: meta-llama/llama-3-3-70b  
Hardware: Nvidia H200  
Inference Stack: VLLM Vanilla  
Date: 2026-02

This document reports inference performance metrics for the
meta-llama/llama-3-3-70b model on Nvidia H200 using the VLLM Vanilla inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 0.81 s
- **Mean Tokens Per Second (TPS):** 44.58
- **Mean Latency Per Token:** 0.0224 s
- **Mean Total Time:** 13.36 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 7.8813 | 13.3645 | 17.3840 | 17.7711 |
| **TTFT (s)** | 0.6873 | 0.8112 | 1.1534 | 1.3509 |
| **Latency/Token (s)** | 0.0218 | 0.0224 | 0.0233 | 0.0234 |
| **Tokens/Second** | 42.8861 | 44.5817 | 45.9618 | 46.1789 |

## Observations

- Significantly lower TPS (~44.6) compared to Deploypad Geodd (~90) on the same hardware, despite using fp8 precision.
- TTFT is slightly higher (0.81s vs 0.71s).

## Notes

- Precision: fp8.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
