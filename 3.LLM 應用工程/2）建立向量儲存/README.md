### 2. 建立向量儲存

創建向量儲存是建立檢索增強生成（Retrieval Augmented Generation，簡稱RAG）流程的第一步。文件被加載、拆分，並使用相關的片段來產生向量表示（嵌入），這些向量表示將被存儲以便在推理過程中使用。

* **文檔導入 Ingesting documents**: 文檔加載器是方便的包裝器，可以處理多種格式： PDF, JSON, HTML, Markdown, 等。 它們還可以直接從一些數據庫和API（GitHub, Reddit, Google Drive, 等）檢索數據。 
* **文檔拆分 Splitting documents**: 文本拆分器將文檔拆分成較小的、語義上有意義的片段。通常最好不要在n個字符後拆分文本，而是按照標題或遞迴地拆分，並附帶一些額外的元數據。
    * [LangChain - Text splitters](https://python.langchain.com/docs/modules/data_connection/document_transformers/): LangChain實現的不同文本拆分器列表。
    * [LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) :  Deeplearning AI的短課程，使用的是LangChain的技術棧跟雲端，有興趣或需要的可以嘗試看看。  
* **嵌入模型 Embedding models**: 嵌入模型將文本轉換為向量表示。這允許對語言進行更深入、更細膩的理解，這對於進行語義搜索至關重要。
    * [Understanding and Applying Text Embeddings](https://www.deeplearning.ai/short-courses/google-cloud-vertex-ai/): 使用google家的產品了解詞向量。
    * [Sentence Transformers library](https://www.sbert.net/): 流行的嵌入模型庫。
    * [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard): 嵌入模型的排行榜。
* **向量數據庫 Vector databases**: 向量數據庫（如 [Chroma](https://www.trychroma.com/), [Pinecone](https://www.pinecone.io/), [Milvus](https://milvus.io/), [FAISS](https://faiss.ai/), [Annoy](https://github.com/spotify/annoy), 等）專為儲存嵌入向量而設計。它們支援基於向量相似性有效檢索與查詢最相似的數據。
    * [The Top 5 Vector Databases](https://www.datacamp.com/blog/the-top-5-vector-databases) by Moez Ali: 最佳和最流行的向量數據庫比較。
    * [Vector Databases: from Embeddings to Applications](https://www.deeplearning.ai/short-courses/vector-databases-embeddings-applications/) :  Deeplearning AI的短課程，使用的是Weaviate的技術棧跟雲端，有興趣或需要的可以嘗試看看。
    * [Building Applications with Vector Databases](https://www.deeplearning.ai/short-courses/vector-databases-embeddings-applications/) :  Deeplearning AI的短課程，使用的是pinecone的技術棧跟雲端，有興趣或需要的可以嘗試看看。



