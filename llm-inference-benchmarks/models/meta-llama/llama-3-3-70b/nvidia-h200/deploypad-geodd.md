# llama-3-3-70b — Deploypad Geodd — Nvidia H200

Model: meta-llama/llama-3-3-70b  
Hardware: Nvidia H200  
Inference Stack: Deploypad Geodd  
Date: 2026-02

This document reports inference performance metrics for the
meta-llama/llama-3-3-70b model on Nvidia H200 using the Deploypad Geodd inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 0.71 s
- **Mean Tokens Per Second (TPS):** 89.95
- **Mean Latency Per Token:** 0.0112 s
- **Mean Total Time:** 6.49 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 4.2908 | 6.4883 | 7.9544 | 7.9696 |
| **TTFT (s)** | 0.5646 | 0.7134 | 0.8417 | 0.8422 |
| **Latency/Token (s)** | 0.0097 | 0.0112 | 0.0122 | 0.0122 |
| **Tokens/Second** | 82.3038 | 89.9459 | 103.1892 | 104.673 |

## Observations

- Very high throughput (~90 TPS) for a 70B model, likely due to H200 hardware and fp16 precision.
- Low TTFT (~0.71s).

## Notes

- Precision: fp16.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
