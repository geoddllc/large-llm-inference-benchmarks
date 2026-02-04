# Time to First Token (TTFT) Methodology

## Definition
Time to First Token (TTFT) measures the latency between the arrival of a request and the generation of the first output token. It encompasses:
1.  Request network latency (if applicable).
2.  Request queueing time.
3.  Prompt processing (prefill) time.

## Importance
TTFT is the primary indicator of responsiveness for interactive applications (e.g., chatbots). High TTFT can lead to a perceived "laggy" user experience, even if the subsequent generation speed (TPS) is high.

## Measurement
In this repository, TTFT is measured from the client side unless otherwise noted. This includes network overhead for API-based benchmarks.
