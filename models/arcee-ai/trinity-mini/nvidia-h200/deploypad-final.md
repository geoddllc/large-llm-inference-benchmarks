# trinity-mini — Deploypad Final — Nvidia H200

Model: arcee-ai/trinity-mini  
Hardware: Nvidia H200  
Inference Stack: Deploypad Final  
Date: 2026-02

This document reports inference performance metrics for the
arcee-ai/trinity-mini model on Nvidia H200 using the Deploypad Final inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 2.93 s
- **Mean Tokens Per Second (TPS):** 114.51
- **Mean Latency Per Token:** 0.0105 s
- **Mean Total Time:** 15.45 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 9.3865 | 15.4469 | 24.3530 | 24.9137 |
| **TTFT (s)** | 0.5370 | 1.0538 | 0.7581 | 1.1681 |
| **Latency/Token (s)** | 0.0088 | 0.0105 | 0.0173 | 0.0173 |
| **Tokens/Second** | 57.8701 | 114.5079 | 134.1837 | 134.8033 |

## Observations

- Best performance among Deploypad versions.
- Mean TTFT reduced to 2.93s.
- Mean TPS increased to ~114.5, comparable to OpenRouter B200 performance.

## Notes

- This benchmark was run on Nvidia H200 hardware.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
