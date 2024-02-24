
### 8. 新趨勢

* **位置嵌入 Positional embeddings**: 了解大型語言模型（LLMs）如何編碼位置，特別是像 [RoPE](https://arxiv.org/abs/2104.09864) 這樣的相對位置編碼方案。實現 [YaRN](https://arxiv.org/abs/2309.00071) (通過溫度因子乘以注意力矩陣) or [ALiBi](https://arxiv.org/abs/2108.12409) (基於token距離的注意力獎懲) 來擴展上下文長度。
    * [Extending the RoPE](https://blog.eleuther.ai/yarn/) by EleutherAI: 總結不同位置編碼技術的文章.
    * [Understanding YaRN](https://medium.com/@rcrajatchawla/understanding-yarn-extending-context-window-of-llms-3f21e3522465) by Rajat Chawla: 對YaRN的介紹.
* **模型融合 Model merging**: 將訓練好的模型合併已成為一種流行的方式，用於創建表現優異的模型，無需任何微調。流行的 [mergekit](https://github.com/cg123/mergekit) 庫實現了最受歡迎的融合方法，如e SLERP, [DARE](https://arxiv.org/abs/2311.03099), 和 [TIES](https://arxiv.org/abs/2311.03099)。模型融合通常指的是將多個已訓練的模型合併成一個單一模型的過程。這不僅僅是平均或投票決定輸出，而是在模型的權重和結構層面上進行合併。這個過程不需要再次訓練，可以通過數學操作（如球面線性內插（SLERP）或其他融合技術）將不同模型的知識整合起來。模型融合用於創建一個表現更佳、更強大的模型，通常是將多個模型在特定任務上的優勢結合起來。
    * [Merge LLMs with mergekit](https://mlabonne.github.io/blog/posts/2024-01-08_Merge_LLMs_with_mergekit.html): 關於使用mergekit進行模型融合的教程.
* **專家混合 Mixture of Experts**: [Mixtral](https://arxiv.org/abs/2401.04088) 因其卓越的性能而重新使MoE架構流行起來。 與此同時，OSS社區出現了一種frankenMoE，通過融合像 [Phixtral](https://huggingface.co/mlabonne/phixtral-2x2_8)這樣的模型，這是一個更經濟且性能良好的選項。MoE是一種結構，它包含多個子模型或“專家”，每個專家專門處理不同的任務或數據子集。在MoE架構中，一個“gate”或調度器決定對於給定的輸入，哪個專家被使用。這是一種稀疏啟動方法，可以大幅提升模型的容量和效率，因為不是所有的專家都會對每個輸入進行響應。
    * [Mixture of Experts Explained](https://huggingface.co/blog/moe) by Hugging Face: 關於MoE及其工作方式的詳盡指南.
* **多模態模型 Multimodal models**: 這些模型（ [CLIP](https://openai.com/research/clip), [Stable Diffusion](https://stability.ai/stable-image), 或 [LLaVA](https://llava-vl.github.io/)) 處理多種類型的輸入（文本、圖像、音頻等）與統一的嵌入空間，從而解鎖了強大的應用，如文本到圖像。
    * [Large Multimodal Models](https://huyenchip.com/2023/10/10/multimodal.html) by Chip Huyen: 對多模態系統及其近期發展歷史的概述.
    * [sora可能架構的解析](https://blog.csdn.net/v_JULY_v/article/details/136143475?spm=1000.2115.3001.5927)

📚 **參考文獻**:
 * [模型融合、混合专家、更小的LLM，几篇论文看懂2024年LLM发展方向](https://www.jiqizhixin.com/articles/2024-02-22)：可以參考下，寫得算全面的。
* [Ten Noteworthy AI Research Papers of 2023](https://magazine.sebastianraschka.com/p/10-ai-research-papers-2023?utm_source=profile&utm_medium=reader2): 這篇文章回顧了2023年十篇值得注意的AI研究論文。涵蓋了從大規模訓練運行的洞察、開放基礎和微調聊天模型到量化LLM的高效微調等多個方面。作者強調了這些研究在透明度、方法創新和特定領域應用方面的重要性，並期待未來的研究能夠帶來更多類似的高質量論文。這篇跟上一篇是同一個作者。


