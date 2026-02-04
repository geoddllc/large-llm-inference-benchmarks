# mistral-small-24b-instruct-2501 — VLLM Vanilla — Nvidia RTX 6000

Model: mistralai/mistral-small-24b-instruct-2501  
Hardware: Nvidia RTX 6000  
Inference Stack: VLLM Vanilla  
Date: 2026-02

This document reports inference performance metrics for the
mistralai/mistral-small-24b-instruct-2501 model on Nvidia RTX 6000 using the VLLM Vanilla inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 2.21 s
- **Mean Tokens Per Second (TPS):** 31.50
- **Mean Latency Per Token:** 0.0321 s
- **Mean Total Time:** 12.28 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 7.8487 | 12.2823 | 13.6694 | 13.7220 |
| **TTFT (s)** | 1.0188 | 2.2103 | 3.7982 | 4.0816 |
| **Latency/Token (s)** | 0.0273 | 0.0321 | 0.0438 | 0.0474 |
| **Tokens/Second** | 22.8512 | 31.4983 | 36.5786 | 36.6338 |

## Observations

- Higher TTFT (Mean 2.21s) compared to Mistral Nemo on the same hardware.
- TPS is similar to Mistral Nemo (~31.5).

## Notes

- Hardware specified as "RTX Pro 6000".

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
