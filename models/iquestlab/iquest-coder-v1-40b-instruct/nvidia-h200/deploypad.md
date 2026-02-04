# IQuest-Coder-V1-40B-Instruct — Deploypad — Nvidia H200

Model: IQuestLab/IQuest-Coder-V1-40B-Instruct  
Hardware: Nvidia H200  
Inference Stack: Deploypad  
Status: Preliminary / Compatibility Verified  
Date: 2026-02

## Performance Summary

- **Target Tokens Per Second (TPS):** 50 - 80
- **Optimization Status:** Compatibility verified; performance optimization active.

## Observations

- Deploypad compatibility has been developed specifically to address the performance bottlenecks observed in standard inference stacks for the IQuest-Coder-V1-40B-Instruct model.
- Preliminary testing indicates a significant performance increase, moving from the 5-8 TPS range (observed in VLLM) to a target range of 50-80 TPS on a single Nvidia H200.

## Notes

- Full benchmark reports with detailed TTFT and latency metrics will be added once final point-in-time measurements are completed.
