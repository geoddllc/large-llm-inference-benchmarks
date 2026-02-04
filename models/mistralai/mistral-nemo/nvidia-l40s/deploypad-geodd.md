# mistral-nemo — Deploypad Geodd — Nvidia L40s

Model: mistralai/mistral-nemo  
Hardware: Nvidia L40s  
Inference Stack: Deploypad Geodd  
Date: 2026-02

This document reports inference performance metrics for the
mistralai/mistral-nemo model on Nvidia L40s using the Deploypad Geodd inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 1.23 s
- **Mean Tokens Per Second (TPS):** 36.11
- **Mean Latency Per Token:** 0.0278 s
- **Mean Total Time:** 10.57 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 6.9984 | 10.5659 | 13.8595 | 13.9359 |
| **TTFT (s)** | 1.1932 | 1.2265 | 1.2611 | 1.2614 |
| **Latency/Token (s)** | 0.0252 | 0.0278 | 0.0337 | 0.0351 |
| **Tokens/Second** | 29.7137 | 36.1109 | 39.6329 | 40.0022 |

## Observations

- Slower performance compared to RTX 6000 Blackwell and H100.
- TTFT is slightly higher at ~1.23s.

## Notes

- None.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
