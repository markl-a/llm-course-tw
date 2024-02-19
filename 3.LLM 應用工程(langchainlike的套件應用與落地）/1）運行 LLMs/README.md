3. 👷 **LLM 應用工程** 專注在創建 LLM 驅動的應用以及部署.


| 名稱 | 敘述 | 文章 | 連結 |
|---------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Decoding Strategies in Large Language Models | 從波束搜尋(beam search)到核採樣(nucleus sampling)的文本生成指南| [Article](https://mlabonne.github.io/blog/posts/2022-06-07-Decoding_strategies.html) | <a href="https://colab.research.google.com/drive/19CJlOS5lI29g-B3dziNn93Enez1yiHk2?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |
| Visualizing GPT-2's Loss Landscape | 基於權重擾動的損失景觀三維圖(3D plot of the loss landscape based on weight perturbations.)| [Tweet](https://twitter.com/maximelabonne/status/1667618081844219904) | <a href="https://colab.research.google.com/drive/1Fu1jikJzFxnSPzR_V2JJyDVWWJNXssaL?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |
| Improve ChatGPT with Knowledge Graphs | 用知識圖譜增強 ChatGPT 的答案 | [Article](https://mlabonne.github.io/blog/posts/Article_Improve_ChatGPT_with_Knowledge_Graphs.html) | <a href="https://colab.research.google.com/drive/1mwhOSw9Y9bgEaIFKT4CLi0n18pXRM4cj?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |
| Merge LLMs with mergekit | 輕鬆創建您自己的模型，無需 GPU！| [Article](https://towardsdatascience.com/merge-large-language-models-with-mergekit-2118fb392b54) | <a href="https://colab.research.google.com/drive/1_JS7JKJAQozD48-LhYdegcuuZ2ddgXfr?usp=sharing"><img src="../img/colab.svg" alt="Open In Colab"></a> |


## 👷 LLM 應用工程

本課程的這一部分重點是學習如何建立可在生產中使用的由 LLM 支援的應用程序，重點主要在增強模型和部署它們。

![](../img/roadmap_engineer.png)


### 1. 運行 LLMs


由於硬體要求高，運行大型語言模型可能會有困難。根據您的使用案例，您也可能只想通過API（如GPT-4）簡單地使用模型，或者在本地運行它。無論哪種情況，額外的提示和指導技術都可以改善或限制您的應用程序的輸出。

* **LLM APIs**: APIs是部署LLMs的便捷方式。這個領域分別有私有LLMs ([OpenAI](https://platform.openai.com/), [Google](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/overview), [Anthropic](https://docs.anthropic.com/claude/reference/getting-started-with-the-api), [Cohere](https://docs.cohere.com/docs), 等.) 和開源LLMs ([OpenRouter](https://openrouter.ai/), [Hugging Face](https://huggingface.co/inference-api), [Together AI](https://www.together.ai/), 等.).
* **開源 LLMs**: [Hugging Face Hub](https://huggingface.co/models) 是尋找LLMs的好地方。 您可以直接在 [Hugging Face Spaces](https://huggingface.co/spaces)中運行一些模型， 或者下載並在像 [LM Studio](https://lmstudio.ai/) 這樣的應用程序中本地運行以及通過CLI使用 [llama.cpp](https://github.com/ggerganov/llama.cpp) 或 [Ollama](https://ollama.ai/)。
* **提示工程 Prompt engineering**: 常見技術包括零提示詞、少量提示詞、思維鏈與ReAct。它們在更大的模型上工作得更好，但也可以適應較小的模型。
* **結構化輸出 Structuring outputs**: 許多任務需要結構化的輸出，如嚴格的模板或JSON格式。像 [LMQL](https://lmql.ai/), [Outlines](https://github.com/outlines-dev/outlines), [Guidance](https://github.com/guidance-ai/guidance), 等庫可以用來指導生成並遵循給定的結構。

📚 **參考資料**:
* [Run an LLM locally with LM Studio](https://www.kdnuggets.com/run-an-llm-locally-with-lm-studio) by Nisha Arya: 關於如何使用LM Studio的簡短指南。
* [Prompt engineering guide](https://www.promptingguide.ai/) by DAIR.AI: 帶有示例的提示技術的詳盡列表。
* [Outlines - Quickstart](https://outlines-dev.github.io/outlines/quickstart/): Outlines啟用的指導生成技術的列表。
* [LMQL - Overview](https://lmql.ai/docs/language/overview.html): 對LMQL語言的介紹。
---
### 2. 建立向量儲存

創建向量儲存是建立檢索增強生成（Retrieval Augmented Generation，簡稱RAG）流程的第一步。文件被加載、拆分，並使用相關的片段來產生向量表示（嵌入），這些向量表示將被存儲以便在推理過程中使用。

* **文檔導入 Ingesting documents**: 文檔加載器是方便的包裝器，可以處理多種格式： PDF, JSON, HTML, Markdown, 等。 它們還可以直接從一些數據庫和API（GitHub, Reddit, Google Drive, 等）檢索數據。
* **文檔拆分 Splitting documents**: 文本拆分器將文檔拆分成較小的、語義上有意義的片段。通常最好不要在n個字符後拆分文本，而是按照標題或遞迴地拆分，並附帶一些額外的元數據。
* **嵌入模型 Embedding models**: 嵌入模型將文本轉換為向量表示。這允許對語言進行更深入、更細膩的理解，這對於進行語義搜索至關重要。
* **向量數據庫 Vector databases**: 向量數據庫（如 [Chroma](https://www.trychroma.com/), [Pinecone](https://www.pinecone.io/), [Milvus](https://milvus.io/), [FAISS](https://faiss.ai/), [Annoy](https://github.com/spotify/annoy), 等）專為儲存嵌入向量而設計。它們支援基於向量相似性有效檢索與查詢最相似的數據。

📚 ** 參考資料**:
* [LangChain - Text splitters](https://python.langchain.com/docs/modules/data_connection/document_transformers/): LangChain實現的不同文本拆分器列表。
* [Sentence Transformers library](https://www.sbert.net/): 流行的嵌入模型庫。
* [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard): 嵌入模型的排行榜。
* [The Top 5 Vector Databases](https://www.datacamp.com/blog/the-top-5-vector-databases) by Moez Ali: 最佳和最流行的向量數據庫比較。

---
### 3. Retrieval Augmented Generation 檢索增強生成

借助 RAG，LLMs 可以從資料庫中檢索上下文文檔，以提高答案的準確性。RAG 是一種無需任何微調即可增強模型知識的流行方法。

* **Orchestrators 協作器**: Orchestrators 協作器 (如 [LangChain](https://python.langchain.com/docs/get_started/introduction), [LlamaIndex](https://docs.llamaindex.ai/en/stable/), [FastRAG](https://github.com/IntelLabs/fastRAG), 等）是流行的框架，用於將您的 LLM 與工具、資料庫、記憶體等連接起來並增強他們的能力。
* **Retrievers 檢索器**: 使用者指令未針對檢索進行最佳化。可以應用不同的技術（例如，多查詢檢索器、 [HyDE](https://arxiv.org/abs/2212.10496), 等）來重新表述/擴展它們並提高效能。
* **記憶**: 為了記住先前的說明和答案，LLM 和 ChatGPT 等聊天機器人會將此歷史記錄添加到其上下文視窗中。此緩衝區可以透過匯總（例如，使用較小的 LLM）、向量儲存 + RAG 等來改進。
* **評估**: 我們需要評估文件檢索（上下文精確度和召回率）和生成階段（可信度和答案相關性）。可以使用 [Ragas](https://github.com/explodinggradients/ragas/tree/main) 和 [DeepEval](https://github.com/confident-ai/deepeval)工具進行簡化。

📚 **參考資料**:
* [Llamaindex - High-level concepts](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html): 建造 RAG 管道時需要了解的主要概念。
* [Pinecone - Retrieval Augmentation](https://www.pinecone.io/learn/series/langchain/langchain-retrieval-augmentation/): 檢索增強流程概述。
* [LangChain - Q&A with RAG](https://python.langchain.com/docs/use_cases/question_answering/quickstart): 建立典型 RAG 管道的逐步教學。
* [LangChain - Memory types](https://python.langchain.com/docs/modules/memory/types/): 不同類型記憶體及其相關用途的清單。
* [RAG pipeline - Metrics](https://docs.ragas.io/en/stable/concepts/metrics/index.html): 用於評估 RAG 管道的主要指標的概述。
---
### 4. 進階 RAG

現實應用程式可能需要複雜的管道，包括 SQL 或圖形資料庫，以及自動選擇相關工具和 API。這些先進技術可以改進基準解決方案並提供附加功能。

* **查詢建構**: 儲存在傳統數據庫中的結構化數據需要特定的查詢語言，如SQL、Cypher、元數據等。我們可以直接將用戶指令翻譯成查詢，通過查詢建構來存取數據。
* **代理與工具**: 代理透過自動選擇最相關的工具來增強LLMs的回答能力。這些工具可以像使用Google或Wikipedia那麼簡單，或者像Python解釋器或Jira這樣複雜。
* **後處理**: 處理輸入到LLM的最後一步。它通過重新排序、[RAG融合](https://github.com/Raudaschl/rag-fusion)和分類來增強檢索文檔的相關性和多樣性。

📚 **參考資料**:
* [LangChain - Query Construction查詢建構](https://blog.langchain.dev/query-construction/): 關於不同類型查詢建構的博客文章.
* [LangChain - SQL](https://python.langchain.com/docs/use_cases/qa_structured/sql): 教程，介紹如何利用LLMs與SQL數據庫互動，包括Text-to-SQL和可選的SQL代理。
* [Pinecone - LLM agents(代理)](https://www.pinecone.io/learn/series/langchain/langchain-agents/): 介紹不同類型的代理和工具。
* [LLM Powered Autonomous Agents(代理)](https://lilianweng.github.io/posts/2023-06-23-agent/) by Lilian Weng: 關於LLM代理的更理論性文章。
* [LangChain - OpenAI's RAG](https://blog.langchain.dev/applying-openai-rag/): 概述OpenAI使用的RAG策略，包括後處理。

---
### 5. Inference optimization 推理優化

文本生成是一個成本高昂的過程，需要昂貴的硬體設備。除了量化之外，還有各種技術被提出以最大化吞吐量並降低推論成本。

* **Flash Attention 閃存注意力**: 優化注意力機制，將其複雜性從二次方變成線性以加快訓練和推論速度。
* **Key-value cache 鍵值快取**: 請多了解鍵值快取以及多查詢注意力（[Multi-Query Attention](https://arxiv.org/abs/1911.02150) (MQA)）和(分組查詢注意力[Grouped-Query Attention](https://arxiv.org/abs/2305.13245) (GQA)）帶來的改進。
* **Speculative decoding 投機解碼**: 使用小型模型產生草稿，然後由更大的模型審核，以加快文本生成速度。

📚 **參考資料**:
* [GPU Inference](https://huggingface.co/docs/transformers/main/en/perf_infer_gpu_one) by Hugging Face: 解釋如何在GPU上優化推論.
* [LLM Inference](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices) by Databricks: 實際運作中優化LLM推論的最佳實踐。
* [Optimizing LLMs for Speed and Memory](https://huggingface.co/docs/transformers/main/en/llm_tutorial_optimization) by Hugging Face: 解釋三種主要的速度和記憶體優化技術，即量化、閃存注意力和架構創新。
* [Assisted Generation](https://huggingface.co/blog/assisted-generation) by Hugging Face: HF版本的投機解碼，這是一篇有趣的博客文章，介紹了它的工作原理及其實現代碼。

---
### 6. Deploying LLMs 部署大型語言模型

在大規模部署大型語言模型（LLMs）是一項工程壯舉，可能需要多個GPU集群。在其他情景下，演示和本地應用可以更簡單的實現運作。

* **Local deployment 本地部署**: 隱私是開源LLMs相對於私有LLMs的一個重要優勢。 本地LLM服務器 ([LM Studio](https://lmstudio.ai/), [Ollama](https://ollama.ai/), [oobabooga](https://github.com/oobabooga/text-generation-webui), [kobold.cpp](https://github.com/LostRuins/koboldcpp), 等）利用這一優勢為本地應用提供動力。 
* **Demo deployment 演示部署**:像 [Gradio](https://www.gradio.app/) 和 [Streamlit](https://docs.streamlit.io/) 這樣的框架有助於原型應用的開發和演示的分享。您也可以輕鬆地在線上部署，例如使用 [Hugging Face Spaces](https://huggingface.co/spaces)。 
* **Server deployment 服務器部署**: 大規模部署LLMs需要雲端 (詳見 [SkyPilot](https://skypilot.readthedocs.io/en/latest/)) 或內部部署的基礎設施，並經常利用優化的文本生成框架，如 [TGI](https://github.com/huggingface/text-generation-inference), [vLLM](https://github.com/vllm-project/vllm/tree/main)等。
* **Edge deployment 邊緣(中低算力)部署**: 在受限環境中，高性能框架如 [MLC LLM](https://github.com/mlc-ai/mlc-llm) 和 [mnn-llm](https://github.com/wangzhaode/mnn-llm/blob/master/README_en.md) 可以在網頁瀏覽器、Android和iOS中部署LLM。

📚 **參考資料**:
* [Streamlit - Build a basic LLM app](https://docs.streamlit.io/knowledge-base/tutorials/build-conversational-apps): 使用Streamlit創建類似ChatGPT的基礎應用的教學。
* [HF LLM Inference Container](https://huggingface.co/blog/sagemaker-huggingface-llm): D使用Hugging Face的推論容器在Amazon SageMaker上部署LLMs。
* [Philschmid blog](https://www.philschmid.de/) by Philipp Schmid: 關於使用Amazon SageMaker部署LLM的高質量文章集。
* [Optimizing latence 優化延遲](https://hamel.dev/notes/llm/inference/03_inference.html) by Hamel Husain:比較TGI、vLLM、CTranslate2和mlc在吞吐量和延遲方面的性能。

---
### 7. Securing LLMs 

除了與軟體相關的傳統安全問題外，由於訓練和提示的方式，大型語言模型（LLMs）還有特定的弱點。

* **Prompt hacking 提示詞攻擊**: 與提示工程相關的技術略有不同，提示詞注入（使用額外指令以劫持模型的答案）、數據/提示洩漏（檢索其原始數據/提示）和越獄（製作提示詞以繞過安全特性）都算在此範圍內。
* **Backdoors 後門**:  攻擊向量可以針對訓練數據本身，通過污染訓練數據（例如，使用錯誤信息）或創建後門（觸發器在推論期間秘密的改變模型行為）。
* **Defensive measures 防禦措施**: 保護您的LLM應用程序的最佳方式是對這些漏洞進行測試 (e.g., 例如，使用紅隊測試和像[garak](https://github.com/leondz/garak/)這樣的檢查 ) 並在實際的環境中觀察它們（使用像[langfuse](https://github.com/langfuse/langfuse)這樣的框架）。

📚 **References**:
* [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) by HEGO Wiki: LLM應用程序中10個最嚴重的漏洞清單。
* [Prompt Injection Primer](https://github.com/jthack/PIPE) by Joseph Thacker: 專門針對工程師的提示注入短指南。
* [LLM Security](https://llmsecurity.net/) by [@llm_sec](https://twitter.com/llm_sec): 與LLM安全相關的廣泛資源列表。
* [Red teaming LLMs](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming) by Microsoft: 關於如何執行LLM紅隊測試的指南。
