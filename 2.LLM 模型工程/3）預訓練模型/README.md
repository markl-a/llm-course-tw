### 3. 預訓練模型

預訓練是一個非常漫長且成本高昂的過程，這就是為什麼這不是本課程的重點。但是對預訓練期間發生的情況有一定程度的了解是很好的。簡單來說，了解可以，實現沒四千萬別做，目前已知花最少錢訓練的是[10萬美元](https://www.ithome.com.tw/news/158779)。

* 目前號稱完全開源的預訓練模型：
    * 1.[olmo](https://allenai.org/olmo):[號稱真正開源！AI2釋出OLMo語言模型和所有相關資料](https://www.ithome.com.tw/news/161199)
        * [史上首个100%开源大模型重磅登场，破纪录公开代码/权重/数据集/训练全过程，AMD都能训](https://36kr.com/p/2632336993616134)
    * 2.[LLM 360](https://www.llm360.ai/): 開源大語言模型框架，包含訓練和資料準備代碼、資料、指標和模型。
    * 3.[全球首個完全開源的大語言模型Dolly，性能堪比 GPT3.5！](https://github.com/databrickslabs/dolly)

* **資料處理流程**: 預訓練需要龐大的資料集 (例如： [Llama 2](https://arxiv.org/abs/2307.09288) 使用 2 兆個tokens進行訓練) ，需要將這些資料集過濾、標記化並與預先定義的詞彙進行整理。
    * [LLMDataHub](https://github.com/Zjh-819/LLMDataHub) by Junhao Zhao: 用於預訓練、微調和 RLHF 的精選資料集清單。
    * [Training a causal language model from scratch](https://huggingface.co/learn/nlp-course/chapter7/6?fw=pt) by Hugging Face: 使用 Transformers 庫從頭開始預先訓練 GPT-2 模型。
    * [TinyLlama](https://github.com/jzhang38/TinyLlama) by Zhang et al.: 可在此項目很好地了解 Llama 模型是如何從頭開始訓練的。
    * [使用pytorch，用搭积木的方式实现完整的Transformer模型](https://zhuanlan.zhihu.com/p/682451065) 
    
* **因果語言建模(Causal language modeling)**: 了解因果語言建模和掩碼語言建模(causal and masked language modeling)之間的區別,以及本例中使用的損失函數。更多高效率的預訓練知識可前往 [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) 或[gpt-neox](https://github.com/EleutherAI/gpt-neox)了解。
    * [Causal language modeling](https://huggingface.co/docs/transformers/tasks/language_modeling) by Hugging Face: 解釋因果語言建模和屏蔽語言建模之間的差異以及如何快速微調 DistilGPT-2 模型。
* **縮放的規律**: [縮放的規律](https://arxiv.org/pdf/2001.08361.pdf) 根據模型大小、資料集大小和用於訓練的計算量描述預期的模型性能。
    * [Chinchilla's wild implications](https://www.lesswrong.com/posts/6Fpvch8RR29qLEWNH/chinchilla-s-wild-implications) by nostalgebraist: 討論縮放定律並解釋它們對大語言模型的意義。
* **高效能運算**: 這有點超出了本文的範圍，但如果您打算從頭開始創建自己的LLMs(大語言模型)（硬體、分散式工作負載等），那麼更多有關 HPC 的知識是對你而言是必要的。
  
📚 **參考資料**:
* [BLOOM](https://bigscience.notion.site/BLOOM-BigScience-176B-Model-ad073ca07cdf479398d5f95d88e218c4) by BigScience: 描述如何建立 BLOOM 模型的 Notion 頁面，其中包含大量有關工程部分和遇到問題的有用資訊。
* [OPT-175 Logbook](https://github.com/facebookresearch/metaseq/blob/main/projects/OPT/chronicles/OPT175B_Logbook.pdf) by Meta: 研究日誌顯示出了什麼錯的以及什麼是正確的。如果您計劃預先訓練非常大的語言模型（在本例中為 175B 參數），則非常有用。

---
