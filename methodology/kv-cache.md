# KV Cache Behavior

## Overview
Key-Value (KV) caching is an optimization technique used during LLM inference to avoid recomputing attention scores for tokens that have already been processed.

## Impact on Performance
- **Memory Usage**: The KV cache grows linearly with the sequence length (context window) and batch size. High memory usage can limit the maximum batch size or context length.
- **Throughput**: Effective KV caching significantly improves Tokens Per Second (TPS) by reducing computational overhead during the decoding phase.

## Scaling Limits
As context length increases, the KV cache can become a bottleneck, potentially requiring techniques like PagedAttention or quantization to maintain performance on limited hardware memory.
