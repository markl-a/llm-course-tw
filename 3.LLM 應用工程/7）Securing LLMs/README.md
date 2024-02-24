### 7. Securing LLMs 

除了與軟體相關的傳統安全問題外，由於訓練和提示的方式，大型語言模型（LLMs）還有特定的弱點。

* **Prompt hacking 提示詞攻擊**: 與提示工程相關的技術略有不同，提示詞注入（使用額外指令以劫持模型的答案）、數據/提示洩漏（檢索其原始數據/提示）和越獄（製作提示詞以繞過安全特性）都算在此範圍內。
    * [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) by HEGO Wiki: LLM應用程序中10個最嚴重的漏洞清單。
    * [Prompt Injection Primer](https://github.com/jthack/PIPE) by Joseph Thacker: 專門針對工程師的提示注入短指南。
* **Backdoors 後門**:  攻擊向量可以針對訓練數據本身，通過污染訓練數據（例如，使用錯誤信息）或創建後門（觸發器在推論期間秘密的改變模型行為）。
* **Defensive measures 防禦措施**: 保護您的LLM應用程序的最佳方式是對這些漏洞進行測試 (e.g., 例如，使用紅隊測試和像[garak](https://github.com/leondz/garak/)這樣的檢查 ) 並在實際的環境中觀察它們（使用像[langfuse](https://github.com/langfuse/langfuse)這樣的框架）。

📚 **References**:
* [LLM Security](https://llmsecurity.net/) by [@llm_sec](https://twitter.com/llm_sec): 與LLM安全相關的廣泛資源列表。
* [Red teaming LLMs](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming) by Microsoft: 關於如何執行LLM紅隊測試的指南。
