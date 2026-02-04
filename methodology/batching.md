# Batching Strategy

## Overview
Batching involves processing multiple requests simultaneously to maximize GPU utilization.

## Trade-offs
- **Throughput vs. Latency**: Increasing batch size generally increases overall system throughput (requests per second) but may increase individual request latency (TTFT and Latency Per Token) due to resource contention and scheduling overhead.
- **Memory Constraints**: Larger batches require more memory for KV caches and intermediate activations.

## Methodology
Benchmarks in this repository may specify the batch size used. If not specified, "dynamic batching" (where the inference server manages batch sizes automatically) is assumed.
