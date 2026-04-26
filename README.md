# KVForge-CUDA-Optimized-KV-Cache-Manager-for-vLLM
This repo can benchmark latency, throughput, and memory usage under different prompt lengths and concurrency levels. This is strong because vLLM relies heavily on PagedAttention and KV-cache reuse, and both vLLM and TensorRT-LLM document KV cache as a central inference bottleneck.
