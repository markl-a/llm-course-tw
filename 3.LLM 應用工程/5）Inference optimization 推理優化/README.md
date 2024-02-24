### 5. Inference optimization 推理優化

文本生成是一個成本高昂的過程，需要昂貴的硬體設備。除了量化之外，還有各種技術被提出以最大化吞吐量並降低推論成本。

* **主要內容**: 
    * [GPU Inference](https://huggingface.co/docs/transformers/main/en/perf_infer_gpu_one) by Hugging Face: 解釋如何在GPU上優化推論.
    * [LLM Inference](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices) by Databricks: 實際運作中優化LLM推論的最佳實踐。
* **Flash Attention 閃存注意力**: 優化注意力機制，將其複雜性從二次方變成線性以加快訓練和推論速度。
    * [Optimizing LLMs for Speed and Memory](https://huggingface.co/docs/transformers/main/en/llm_tutorial_optimization) by Hugging Face: 解釋三種主要的速度和記憶體優化技術，即量化、閃存注意力和架構創新。
* **Key-value cache 鍵值快取**: 請多了解鍵值快取以及多查詢注意力（[Multi-Query Attention](https://arxiv.org/abs/1911.02150) (MQA)）和(分組查詢注意力[Grouped-Query Attention](https://arxiv.org/abs/2305.13245) (GQA)）帶來的改進。
* **Speculative decoding 投機解碼**: 使用小型模型產生草稿，然後由更大的模型審核，以加快文本生成速度。
    * [Assisted Generation](https://huggingface.co/blog/assisted-generation) by Hugging Face: HF版本的投機解碼，這是一篇有趣的博客文章，介紹了它的工作原理及其實現代碼。
