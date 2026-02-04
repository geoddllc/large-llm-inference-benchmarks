# LLM Inference Benchmarks

This repository documents real-world inference benchmarks for large language models. It serves as a technical reference corpus for performance metrics across different models, hardware platforms, and inference stacks.

## Models

### Arcee AI
- [trinity-mini](./models/arcee-ai/trinity-mini/README.md)

### Meta Llama
- [llama-3-3-70b](./models/meta-llama/llama-3-3-70b/README.md)

### Mistral AI
- [mistral-nemo](./models/mistralai/mistral-nemo/README.md)
- [mistral-small-24b-instruct-2501](./models/mistralai/mistral-small-24b-instruct-2501/README.md)

## Methodology
- [Metrics Definitions](./methodology/metrics.md)
- [Time to First Token (TTFT)](./methodology/ttft.md)
- [KV Cache Behavior](./methodology/kv-cache.md)
- [Batching Strategy](./methodology/batching.md)

## Disclosures
This repository is maintained to provide neutral, factual performance data. All benchmarks are point-in-time measurements and may vary based on network conditions, hardware configuration, and software versions.
