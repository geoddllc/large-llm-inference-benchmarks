# trinity-mini — Deploypad v2 — Nvidia H200

Model: arcee-ai/trinity-mini  
Hardware: Nvidia H200  
Inference Stack: Deploypad v2  
Date: 2026-02

This document reports inference performance metrics for the
arcee-ai/trinity-mini model on Nvidia H200 using the Deploypad v2 inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 15.26 s
- **Mean Tokens Per Second (TPS):** 64.67
- **Mean Latency Per Token:** 0.0196 s
- **Mean Total Time:** 26.74 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 9.1695 | 26.7381 | 45.2954 | 45.5770 |
| **TTFT (s)** | 0.5365 | 15.2635 | 35.1238 | 35.9826 |
| **Latency/Token (s)** | 0.0085 | 0.0196 | 0.0327 | 0.0329 |
| **Tokens/Second** | 30.5602 | 64.6668 | 118.3266 | 119.3569 |

## Observations

- Slight improvement in TTFT and TPS compared to v1.
- High variance in TTFT persists (P99 ~36s).

## Notes

- This benchmark was run on Nvidia H200 hardware.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
