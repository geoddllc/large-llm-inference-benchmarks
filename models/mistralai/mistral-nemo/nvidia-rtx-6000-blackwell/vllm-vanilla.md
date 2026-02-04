# mistral-nemo — VLLM Vanilla — Nvidia RTX 6000

Model: mistralai/mistral-nemo  
Hardware: Nvidia RTX 6000  
Inference Stack: VLLM Vanilla  
Date: 2026-02

This document reports inference performance metrics for the
mistralai/mistral-nemo model on Nvidia RTX 6000 using the VLLM Vanilla inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 0.87 s
- **Mean Tokens Per Second (TPS):** 32.94
- **Mean Latency Per Token:** 0.0305 s
- **Mean Total Time:** 12.71 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 8.1446 | 12.7104 | 20.7792 | 22.0766 |
| **TTFT (s)** | 0.6399 | 0.8664 | 0.9872 | 0.9872 |
| **Latency/Token (s)** | 0.0273 | 0.0305 | 0.0379 | 0.0401 |
| **Tokens/Second** | 26.3967 | 32.9402 | 36.5849 | 37.3722 |

## Observations

- Lower TPS (~33) compared to Deploypad Geodd on similar hardware (~66 TPS on RTX 6000 Blackwell).
- TTFT is comparable (~0.87s).

## Notes

- Hardware specified as "RTX Pro 6000".

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
