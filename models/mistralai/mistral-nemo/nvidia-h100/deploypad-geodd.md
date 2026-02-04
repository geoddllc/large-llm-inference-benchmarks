# mistral-nemo — Deploypad Geodd — Nvidia H100

Model: mistralai/mistral-nemo  
Hardware: Nvidia H100  
Inference Stack: Deploypad Geodd  
Date: 2026-02

This document reports inference performance metrics for the
mistralai/mistral-nemo model on Nvidia H100 using the Deploypad Geodd inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 0.77 s
- **Mean Tokens Per Second (TPS):** 86.21
- **Mean Latency Per Token:** 0.0116 s
- **Mean Total Time:** 6.35 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 4.3084 | 6.3467 | 9.3767 | 9.7582 |
| **TTFT (s)** | 0.5561 | 0.7652 | 0.8860 | 0.8862 |
| **Latency/Token (s)** | 0.0109 | 0.0116 | 0.0123 | 0.0124 |
| **Tokens/Second** | 81.0250 | 86.2059 | 91.4123 | 91.9514 |

## Observations

- Excellent performance with high TPS (~86) and low TTFT (~0.77s).
- Best performing hardware for this model/stack combination among those tested.

## Notes

- None.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
