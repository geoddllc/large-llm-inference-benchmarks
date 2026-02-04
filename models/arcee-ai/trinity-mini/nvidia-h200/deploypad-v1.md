# trinity-mini — Deploypad v1 — Nvidia H200

Model: arcee-ai/trinity-mini  
Hardware: Nvidia H200  
Inference Stack: Deploypad v1  
Date: 2026-02

This document reports inference performance metrics for the
arcee-ai/trinity-mini model on Nvidia H200 using the Deploypad v1 inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 16.67 s
- **Mean Tokens Per Second (TPS):** 61.04
- **Mean Latency Per Token:** 0.0212 s
- **Mean Total Time:** 29.29 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 10.3902 | 29.2859 | 48.1467 | 48.4794 |
| **TTFT (s)** | 0.5142 | 16.6687 | 37.8945 | 38.2475 |
| **Latency/Token (s)** | 0.0089 | 0.0212 | 0.0452 | 0.0502 |
| **Tokens/Second** | 22.1024 | 61.0414 | 112.7113 | 113.8795 |

## Observations

- Initial version shows high variability in TTFT, with a P99 of over 38 seconds.
- Mean TPS is approximately 61 tokens/second.

## Notes

- This benchmark was run on Nvidia H200 hardware.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
