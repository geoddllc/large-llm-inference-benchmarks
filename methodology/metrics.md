# Inference Metrics Definitions

This document defines the standard metrics used in this repository to measure Large Language Model (LLM) inference performance.

## Time to First Token (TTFT)
The duration from the moment a request is sent to the moment the first token of the response is received. This metric is critical for perceived latency in interactive applications.

## Tokens Per Second (TPS)
The rate at which the model generates tokens after the first token has been produced. This is also referred to as "decode speed" or "generation throughput".
- **Formula**: `(Total Tokens - 1) / (Total Time - TTFT)`

## Latency Per Token
The average time it takes to generate a single token during the decoding phase. This is the inverse of TPS.
- **Formula**: `1 / TPS`

## Total Time Taken
The total duration from request submission to the receipt of the final token.

## Statistical Measures
- **Min**: The best recorded performance in the sample set.
- **Mean**: The arithmetic average of the sample set.
- **Max**: The worst recorded performance in the sample set.
- **P99**: The 99th percentile value, indicating the performance experienced by 99% of requests (useful for understanding tail latency).
