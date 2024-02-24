
### 3. Retrieval Augmented Generation 檢索增強生成

借助 RAG，LLMs 可以從資料庫中檢索上下文文檔，以提高答案的準確性。RAG 是一種無需任何微調即可增強模型知識的流行方法。

* **Orchestrators 協作器**: Orchestrators 協作器 (如 [LangChain](https://python.langchain.com/docs/get_started/introduction), [LlamaIndex](https://docs.llamaindex.ai/en/stable/), [FastRAG](https://github.com/IntelLabs/fastRAG), 等）是流行的框架，用於將您的 LLM 與工具、資料庫、記憶體等連接起來並增強他們的能力。
    * [Llamaindex - High-level concepts](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html): 建造 RAG 管道時需要了解的主要概念。
    * [Building and Evaluating Advanced RAG Applications](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/): Deeplearning AI 跟 Llamaindex共同推出的短課程。
    * [Pinecone - Retrieval Augmentation](https://www.pinecone.io/learn/series/langchain/langchain-retrieval-augmentation/): 檢索增強流程概述。
* **Retrievers 檢索器**: 使用者指令未針對檢索進行最佳化。可以應用不同的技術（例如，多查詢檢索器、 [HyDE](https://arxiv.org/abs/2212.10496), 等）來重新表述/擴展它們並提高效能。
    * [LangChain - Q&A with RAG](https://python.langchain.com/docs/use_cases/question_answering/quickstart): 建立典型 RAG 管道的逐步教學。
* **記憶**: 為了記住先前的說明和答案，LLM 和 ChatGPT 等聊天機器人會將此歷史記錄添加到其上下文視窗中。此緩衝區可以透過匯總（例如，使用較小的 LLM）、向量儲存 + RAG 等來改進。
    * [LangChain - Memory types](https://python.langchain.com/docs/modules/memory/types/): 不同類型記憶體及其相關用途的清單。
* **評估**: 我們需要評估文件檢索（上下文精確度和召回率）和生成階段（可信度和答案相關性）。可以使用 [Ragas](https://github.com/explodinggradients/ragas/tree/main) 和 [DeepEval](https://github.com/confident-ai/deepeval)工具進行簡化。
    * [RAG pipeline - Metrics](https://docs.ragas.io/en/stable/concepts/metrics/index.html): 用於評估 RAG 管道的主要指標的概述。