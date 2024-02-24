### 4. 進階 RAG

現實應用程式可能需要複雜的管道，包括 SQL 或圖形資料庫，以及自動選擇相關工具和 API。這些先進技術可以改進基準解決方案並提供附加功能。

* **查詢建構**: 儲存在傳統數據庫中的結構化數據需要特定的查詢語言，如SQL、Cypher、元數據等。我們可以直接將用戶指令翻譯成查詢，通過查詢建構來存取數據。
    * [LangChain - Query Construction查詢建構](https://blog.langchain.dev/query-construction/): 關於不同類型查詢建構的博客文章.
    * [LangChain - SQL](https://python.langchain.com/docs/use_cases/qa_structured/sql): 教程，介紹如何利用LLMs與SQL數據庫互動，包括Text-to-SQL和可選的SQL代理。
* **代理與工具**: 代理透過自動選擇最相關的工具來增強LLMs的回答能力。這些工具可以像使用Google或Wikipedia那麼簡單，或者像Python解釋器或Jira這樣複雜。
    * [Pinecone - LLM agents(代理)](https://www.pinecone.io/learn/series/langchain/langchain-agents/): 介紹不同類型的代理和工具。
    * [LLM Powered Autonomous Agents(代理)](https://lilianweng.github.io/posts/2023-06-23-agent/) by Lilian Weng: 關於LLM代理的更理論性文章。
* **後處理**: 處理輸入到LLM的最後一步。它通過重新排序、[RAG融合](https://github.com/Raudaschl/rag-fusion)和分類來增強檢索文檔的相關性和多樣性。
    * [LangChain - OpenAI's RAG](https://blog.langchain.dev/applying-openai-rag/): 概述OpenAI使用的RAG策略，包括後處理。



