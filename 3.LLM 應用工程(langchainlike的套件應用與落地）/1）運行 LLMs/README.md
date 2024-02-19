3. 👷 **LLM 應用工程** 專注在創建 LLM 驅動的應用以及部署.


| 名稱 | 敘述 | 文章 | 連結 |
|---------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Decoding Strategies in Large Language Models | 從波束搜尋(beam search)到核採樣(nucleus sampling)的文本生成指南| [Article](https://mlabonne.github.io/blog/posts/2022-06-07-Decoding_strategies.html) | <a href="https://colab.research.google.com/drive/19CJlOS5lI29g-B3dziNn93Enez1yiHk2?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |
| Visualizing GPT-2's Loss Landscape | 基於權重擾動的損失景觀三維圖(3D plot of the loss landscape based on weight perturbations.)| [Tweet](https://twitter.com/maximelabonne/status/1667618081844219904) | <a href="https://colab.research.google.com/drive/1Fu1jikJzFxnSPzR_V2JJyDVWWJNXssaL?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |
| Improve ChatGPT with Knowledge Graphs | 用知識圖譜增強 ChatGPT 的答案 | [Article](https://mlabonne.github.io/blog/posts/Article_Improve_ChatGPT_with_Knowledge_Graphs.html) | <a href="https://colab.research.google.com/drive/1mwhOSw9Y9bgEaIFKT4CLi0n18pXRM4cj?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |
| Merge LLMs with mergekit | 輕鬆創建您自己的模型，無需 GPU！| [Article](https://towardsdatascience.com/merge-large-language-models-with-mergekit-2118fb392b54) | <a href="https://colab.research.google.com/drive/1_JS7JKJAQozD48-LhYdegcuuZ2ddgXfr?usp=sharing"><img src="../../img/colab.svg" alt="Open In Colab"></a> |


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
