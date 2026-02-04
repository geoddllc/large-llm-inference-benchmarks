# mistral-nemo — Deploypad Geodd — Nvidia RTX 6000 Blackwell

Model: mistralai/mistral-nemo  
Hardware: Nvidia RTX 6000 Blackwell  
Inference Stack: Deploypad Geodd  
Date: 2026-02

This document reports inference performance metrics for the
mistralai/mistral-nemo model on Nvidia RTX 6000 Blackwell using the Deploypad Geodd inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 0.89 s
- **Mean Tokens Per Second (TPS):** 66.66
- **Mean Latency Per Token:** 0.0150 s
- **Mean Total Time:** 7.83 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 5.8374 | 7.8296 | 10.9735 | 12.1962 |
| **TTFT (s)** | 0.7377 | 0.8881 | 1.0311 | 1.0321 |
| **Latency/Token (s)** | 0.0137 | 0.0150 | 0.0163 | 0.0166 |
| **Tokens/Second** | 61.3285 | 66.6627 | 72.9941 | 74.5381 |

## Observations

- Low TTFT (Mean 0.89s) indicates good responsiveness.
- Consistent TPS around 66.

## Notes

- Hardware specified as "RTX PR0 6000 Blackwell".

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
