# trinity-mini — OpenRouter — Nvidia B200

Model: arcee-ai/trinity-mini  
Hardware: Nvidia B200  
Inference Stack: OpenRouter  
Date: 2026-01

This document reports inference performance metrics for the
arcee-ai/trinity-mini model on Nvidia B200 using the OpenRouter inference stack.

## Metrics Summary

- **Mean Time to First Token (TTFT):** 5.41 s
- **Mean Tokens Per Second (TPS):** 117.09
- **Mean Latency Per Token:** 0.0092 s
- **Mean Total Time:** 9.14 s

## Detailed Statistics

| Metric | Min | Mean | Max | P99 |
| :--- | :--- | :--- | :--- | :--- |
| **Time Taken (s)** | 6.5521 | 9.1421 | 19.3534 | 21.8181 |
| **TTFT (s)** | 3.4662 | 5.4128 | 14.3568 | 16.7630 |
| **Latency/Token (s)** | 0.0066 | 0.0092 | 0.0194 | 0.0218 |
| **Tokens/Second** | 51.6705 | 117.0912 | 152.6238 | 152.9999 |

## Observations

- The Time to First Token (TTFT) shows significant variance, with a P99 of 16.76s compared to a mean of 5.41s, suggesting potential queueing or network variability on the public endpoint.
- Throughput (TPS) is high, averaging ~117 tokens per second.

## Notes

- These results were collected from the OpenRouter API. Network latency contributes to the reported TTFT.

## Related Documents

- [Model Summary](../README.md)
- [Methodology: Metrics](../../../../methodology/metrics.md)
- [Methodology: TTFT](../../../../methodology/ttft.md)
