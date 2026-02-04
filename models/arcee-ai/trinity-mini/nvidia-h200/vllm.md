# trinity-mini — VLLM — Nvidia H200

Model: arcee-ai/trinity-mini  
Hardware: Nvidia H200  
Inference Stack: VLLM  
Date: 2026-02

This document reports inference performance metrics for the
arcee-ai/trinity-mini model on Nvidia H200 using the VLLM inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 0.71 s
- **Mean Tokens Per Second (TPS):** 78.00
- **Mean Latency Per Token:** 0.0128 s
- **Mean Total Time:** 17.17 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 14.0301 | 17.1711 | 21.5182 | 21.9916 |
| **TTFT (s)** | 0.6136 | 0.7055 | 0.8444 | 0.8525 |
| **Latency/Token (s)** | 0.0114 | 0.0128 | 0.0136 | 0.0136 |
| **Tokens/Second** | 73.7567 | 77.9996 | 87.9719 | 90.6320 |

## Observations

- Extremely low and consistent TTFT (Mean 0.71s, P99 0.85s), indicating excellent responsiveness.
- Consistent TPS with low variance.

## Notes

- This benchmark was run on Nvidia H200 hardware using VLLM.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
