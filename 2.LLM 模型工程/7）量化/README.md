
### 7. 量化

量化是將模型的權重（和啟動值）轉換成更低精度表示的過程。例如，原本使用16位元儲存的權重可以轉換成4位元表示。這種技術愈來愈重要，用來減少與大型語言模型（LLMs）相關的計算與記憶體成本。

* **簡介**: 
    * [量化簡介](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html): 量化概述，absmax與零點量化，以及使用 LLM.int8()在程式碼上。
    * [目前针对大模型进行量化的方法有哪些？](https://www.zhihu.com/question/627484732)
    * [大语言模型量化相关技术](https://zhuanlan.zhihu.com/p/664054739)

* **基礎技術**: 瞭解不同的精確度層級（FP32、FP16、INT8等）以及如何使用absmax與零點技術(zero-point techniques)進行簡單的量化。
* **GGUF和llama.cpp**: 最初設計用於在CPU上運行，[llama.cpp](https://github.com/ggerganov/llama.cpp) 和GGUF格式已成為在消費級硬體上運行LLMs的最受歡迎的工具。
    * [使用llama.cpp量化Llama模型](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html): 關於如何使用llama.cpp和GGUF格式量化Llama 2模型的教學。
* **GPTQ和EXL2**: [GPTQ](https://arxiv.org/abs/2210.17323) ，特別是 [EXL2](https://github.com/turboderp/exllamav2) ，提供了較快的速度，但只能在GPU上運行。模型量化也需要很長時間。
    * [使用GPTQ進行4位元LLM量化](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html):關於如何使用GPTQ演算法和AutoGPTQ量化LLM的教學。
    * [ExLlamaV2: 運行LLMs的最快程式庫](https://mlabonne.github.io/blog/posts/ExLlamaV2_The_Fastest_Library_to_Run%C2%A0LLMs.html): 指南；關於如何使用EXL2格式量化Mistral模型，並使用ExLlamaV2程式庫運行。
* **AWQ**: 這種新格式比GPTQ更準確（困惑度更低），但使用的顯存更多，速度也不一定更快。
    * [了解啟動感知權重量化](https://medium.com/friendliai/understanding-activation-aware-weight-quantization-awq-boosting-inference-serving-efficiency-in-10bb0faf63a8) by FriendliAI: AWQ技術及其優勢的概述。

📚 **參考文獻**:
    * [LLM Note Day 14 - 量化 Quantization](https://ithelp.ithome.com.tw/articles/10330372) :筆記式版本的量化介紹。



