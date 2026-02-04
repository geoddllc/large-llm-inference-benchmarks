# trinity-mini — Deploypad v3 — Nvidia H200

Model: arcee-ai/trinity-mini  
Hardware: Nvidia H200  
Inference Stack: Deploypad v3  
Date: 2026-02

This document reports inference performance metrics for the
arcee-ai/trinity-mini model on Nvidia H200 using the Deploypad v3 inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 5.93 s
- **Mean Tokens Per Second (TPS):** 75.70
- **Mean Latency Per Token:** 0.0143 s
- **Mean Total Time:** 19.58 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 11.8540 | 19.5799 | 29.3542 | 30.1038 |
| **TTFT (s)** | 0.5960 | 5.9271 | 14.6245 | 14.6980 |
| **Latency/Token (s)** | 0.0105 | 0.0143 | 0.0233 | 0.0244 |
| **Tokens/Second** | 42.9576 | 75.6994 | 94.8351 | 95.5051 |

## Observations

- Significant reduction in TTFT compared to v2 (Mean 15.26s -> 5.93s).
- TPS has improved to ~75.7.

## Notes

- This benchmark was run on Nvidia H200 hardware.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
