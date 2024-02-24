
### 6. 評估 Evaluation

評估大型語言模型(LLMs)是流程中一個被低估的部分，因為評估這一個過程耗時且相對可靠性較低。你的下游任務應該指明你想要評估的內容，但記得古德哈特定律(Goodhart's law)提到的：“當一個衡量指標變成了目標，它就不再是一個好的衡量指標。”
* 簡介與入門：
    * [Evaluating and Debugging Generative AI Models Using Weights and Biases](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai//): Deeplearning AI 的短課程，適合快速入門。
    * [LLM Evaluation 如何评估一个大模型？](https://zhuanlan.zhihu.com/p/644373658): 別人的心得，可以參考下。

* **傳統指標 Traditional metrics**: 像困惑度(perplexity)和BLEU分數這樣的指標不再像以前那樣受歡迎，因為在大多數情況下它們是有缺陷的。但了解它們以及它們適用的情境仍然很重要。
    * [固定長度輸入(有最大輸入限制)模型的困惑度](https://huggingface.co/docs/transformers/perplexity) by Hugging Face: 困惑度(perplexity)的概述，並使用 Transformer 庫實現了它的程式碼。
    * [BLEU 使用風險](https://towardsdatascience.com/evaluating-text-output-in-nlp-bleu-at-your-own-risk-e8609665a213) by Rachael Tatman: BLEU 分數及其許多問題的概述，並提供了示例。
* **通用基準 General benchmarks**: 基於語言模型評估工具箱 [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)，Open LLM排行榜 [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) 是用於通用大型語言模型（如ChatGPT）的主要基準。還有其他受歡迎的基準，如[BigBench](https://github.com/google/BIG-bench), [MT-Bench](https://arxiv.org/abs/2306.05685)等。
    * [大型語言模型評估調查](https://arxiv.org/abs/2307.03109) by Chang et al.: 關於評估什麼、在哪裡評估以及如何評估的綜合性論文。
* **任務特定基準 Task-specific benchmarks**: 如摘要、翻譯和問答等任務有專門的基準、指標甚至子領域（醫療、金融等），例如用於生物醫學問答 [PubMedQA](https://pubmedqa.github.io/)。
* **人類評估 Human evaluation**: 最可靠的評估是用戶的接受度或由人類所做的比較。如果你想知道一個模型表現得如何，最簡單但最確定的方式就是自己使用它。

📚 **參考文獻**:
* [聊天機器人排行榜](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard) by lmsys: 基於人類比較的通用大型語言模型的Elo評分。
