<div align="center">
  <h1>🗣️ 大語言模型課程心得</h1>
  <p align="center">
    🐦 <a href="https://twitter.com/maximelabonne">Follow me on X</a> • 
    🤗 <a href="https://huggingface.co/mlabonne">Hugging Face</a> • 
    💻 <a href="https://mlabonne.github.io/blog">Blog</a> • 
    📙 <a href="https://github.com/PacktPublishing/Hands-On-Graph-Neural-Networks-Using-Python">Hands-on GNN</a> • 
    🗣️ <a href="https://chat.openai.com/g/g-yviLuLqvI-llm-course">Interactive GPT</a>
  </p>
</div>
<br/>

此 LLM 課程心得分成三個部分:

1. 🧩 **LLM 基礎** 涵蓋了數學,Python 和神經網路等基礎知識.
2. 🧑‍🔬 **LLM 模型工程** 專注在使用最新的技巧,技術搭建現階段個人可實現最好的LLMs.
3. 👷 **LLM 應用工程** 專注在創建 LLM 驅動的應用以及部署.

## 📝 Notebooks

與大型語言模型相關的筆記本和文章清單。

### Tools

| 名稱 | 敘述 | 連結 |
|----------|-------------|----------|
| 🧐 [LLM AutoEval](https://github.com/mlabonne/llm-autoeval) | 使用 RunPod 自動評估您的LLMs | <a href="https://colab.research.google.com/drive/1Igs3WZuXAIv9X0vwqiE90QlEPys8e8Oa?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| 🥱 LazyMergekit | 使用 mergekit 一鍵輕鬆合併模型. | <a href="https://colab.research.google.com/drive/1obulZ1ROXHjYLn6PPZJwRR6GzgQogxxb?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| ⚡ AutoGGUF | 一鍵量化 GGUF 格式的 LLM. | <a href="https://colab.research.google.com/drive/1P646NEg33BZy4BfLDNpTz0V0lwIU3CHu?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| 🌳 Model Family Tree | 可視化合併模型的樹狀結構圖. | <a href="https://colab.research.google.com/drive/1s2eQlolcI1VGgDhqWIANfkfKvcKrMyNr?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |

### Fine-tuning (微調)

| 名稱 | 敘述 | 文章 | 連結 |
|---------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Fine-tune Llama 2 in Google Colab | 微調您的第一個 Llama 2 模型的逐步指南。 | [Article](https://mlabonne.github.io/blog/posts/Fine_Tune_Your_Own_Llama_2_Model_in_a_Colab_Notebook.html) | <a href="https://colab.research.google.com/drive/1PEQyJO1-f6j0S_XJ8DV50NkpzasXkrzd?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| Fine-tune LLMs with Axolotl | 最先進微調工具的端到端指南。| [Article](https://mlabonne.github.io/blog/posts/A_Beginners_Guide_to_LLM_Finetuning.html) | <a href="https://colab.research.google.com/drive/1Xu0BrCB7IShwSWKVcfAfhehwjDrDMH5m?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| Fine-tune Mistral-7b with DPO | 使用 DPO 提升監督微調模型的性能 | [Article](https://medium.com/towards-data-science/fine-tune-a-mistral-7b-model-with-direct-preference-optimization-708042745aac) | <a href="https://colab.research.google.com/drive/15iFBr1xWgztXvhrj5I9fBv20c7CFOPBE?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |

### Quantization(量化)

| 名稱 | 敘述 | 文章 | 連結 |
|---------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. Introduction to Quantization | 使用 8 位元量化的大型語言模型最佳化。 | [Article](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html) | <a href="https://colab.research.google.com/drive/1DPr4mUQ92Cc-xf4GgAaB6dFcFnWIvqYi?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| 2. 4-bit Quantization using GPTQ | 量化您自己的開源 LLM 以在消費性硬體上運行它們。 | [Article](https://mlabonne.github.io/blog/4bit_quantization/) | <a href="https://colab.research.google.com/drive/1lSvVDaRgqQp_mWK_jC9gydz6_-y6Aq4A?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| 3. Quantization with GGUF and llama.cpp | 使用 llama.cpp 量化 Llama 2 模型並將 GGUF 版本上傳到 HF Hub。 | [Article](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html) | <a href="https://colab.research.google.com/drive/1pL8k7m04mgE5jo2NrjGi8atB0j_37aDD?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| 4. ExLlamaV2: The Fastest Library to Run LLMs | 量化並執行 EXL2 模型並將其上傳至 HF Hub。| [Article](https://mlabonne.github.io/blog/posts/ExLlamaV2_The_Fastest_Library_to_Run%C2%A0LLMs.html) | <a href="https://colab.research.google.com/drive/1yrq4XBlxiA0fALtMoT2dwiACVc77PHou?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |

### 其他

| 名稱 | 敘述 | 文章 | 連結 |
|---------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Decoding Strategies in Large Language Models | 從波束搜尋(beam search)到核採樣(nucleus sampling)的文本生成指南| [Article](https://mlabonne.github.io/blog/posts/2022-06-07-Decoding_strategies.html) | <a href="https://colab.research.google.com/drive/19CJlOS5lI29g-B3dziNn93Enez1yiHk2?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| Visualizing GPT-2's Loss Landscape | 基於權重擾動的損失景觀三維圖(3D plot of the loss landscape based on weight perturbations.)| [Tweet](https://twitter.com/maximelabonne/status/1667618081844219904) | <a href="https://colab.research.google.com/drive/1Fu1jikJzFxnSPzR_V2JJyDVWWJNXssaL?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| Improve ChatGPT with Knowledge Graphs | 用知識圖譜增強 ChatGPT 的答案 | [Article](https://mlabonne.github.io/blog/posts/Article_Improve_ChatGPT_with_Knowledge_Graphs.html) | <a href="https://colab.research.google.com/drive/1mwhOSw9Y9bgEaIFKT4CLi0n18pXRM4cj?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |
| Merge LLMs with mergekit | 輕鬆創建您自己的模型，無需 GPU！| [Article](https://towardsdatascience.com/merge-large-language-models-with-mergekit-2118fb392b54) | <a href="https://colab.research.google.com/drive/1_JS7JKJAQozD48-LhYdegcuuZ2ddgXfr?usp=sharing"><img src="img/colab.svg" alt="Open In Colab"></a> |


## 🧩 LLM 基礎

![](img/roadmap_fundamentals.png)

### 1. 機器學習數學

在掌握機器學習之前，了解支撐了這些演算法的基本數學概念非常重要。

- **線性代數**: 這對於理解許多演算法至關重要，尤其是深度學習中使用的演算法。關鍵概念包括向量、矩陣、行列式、特徵值和特徵向量、向量空間和線性變換。
- **微積分**: 許多機器學習演算法涉及連續函數的最佳化，這需要了解導數、積分、極限和級數。另外多變量微積分和梯度的概念也很重要。
- **機率和統計**: 這些對於理解模型如何從數據中學習並做出預測至關重要。 關鍵概念包括機率論、隨機變數、機率分佈、期望、變異數、協方差、相關性、假設檢定、信賴區間、最大似然估計和貝葉斯推理。

📚 資源:

- [3Blue1Brown - 線性代數的本質](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab): 此系列的影片介紹幾何相關的概念
- [StatQuest with Josh Starmer - 統計基礎知識](https://www.youtube.com/watch?v=qBigTkBLU6g&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9): 為許多統計概念提供簡單明了的解釋。
- [Aerin女士的AP統計直觀理解](https://automata88.medium.com/list/cacc224d5e7d): 提供每個機率分佈背後的Medium文章清單。
- [沉浸式線性代數](https://immersivemath.com/ila/learnmore.html): 線性代數的另一種圖像化詮釋.
- [Khan Academy - 線性代數](https://www.khanacademy.org/math/linear-algebra): 非常適合初學者，因為它以非常直觀的方式解釋了概念。
- [Khan Academy - 微積分](https://www.khanacademy.org/math/calculus-1): 一門涵蓋微積分所有基礎知識的互動課程。
- [Khan Academy - 機率與統計](https://www.khanacademy.org/math/statistics-probability): 以易於理解的格式提供材料。
---

### 2. 用於機器學習的Python

Python 是一種強大而靈活的程式語言，由於其可讀性、一致性和強大的資料科學庫生態系統，特別適合機器學習。


- **Python基礎**: Python程式設計需要很好地理解基本語法、資料類型、錯誤處理和物件導向程式設計。
- **資料科學函式庫**: 包括熟悉用於數值運算的 NumPy、用於資料操作和分析的 Pandas、用於資料視覺化的 Matplotlib 和 Seaborn。
- **資料預處理**: 這涉及特徵縮放和標準化、處理缺失資料、異常值檢測、分類資料編碼以及將資料拆分為訓練集、驗證集和測試集。
- **機器學習函式庫**: 熟練使用 Scikit-learn（一個提供多種監督和非監督學習演算法的函式庫）至關重要。了解如何實現線性迴歸、邏輯迴歸、決策樹、隨機森林、k 最近鄰 (K-NN) 和 K 均值聚類等演算法非常重要。PCA 和 t-SNE 等降維技術也有助於視覺化高維度資料。

📚 資源：

- [Real Python](https://realpython.com/): 綜合資源，包含初學者和進階 Python 概念的文章和教學。

- [freeCodeCamp - 學習 Python](https://www.youtube.com/watch?v=rfscVS0vtbw): 長影片，完整介紹了 Python 中的所有核心概念。
- [Python 資料科學手冊](https://jakevdp.github.io/PythonDataScienceHandbook/): 免費的數位書籍，是學習 pandas、NumPy、Matplotlib 和 Seaborn 的絕佳資源。
- [freeCodeCamp - 適合所有人的機器學習](https://youtu.be/i_LwzRVP7bg): 為初學者介紹不同的機器學習演算法。
- [Udacity - 機器學習簡介](https://www.udacity.com/course/intro-to-machine-learning--ud120): 免費課程，涵蓋 PCA 和其他幾個機器學習概念。

---

### 3. 神經網絡

神經網路是許多機器學習模型的基本組成部分，特別是在深度學習領域。為了有效地利用它們，全面了解它們的設計和機制至關重要。

- **基礎知識**: 這包括理解神經網路的結構，例如層、權重、偏差和激活函數（sigmoid、tanh、ReLU 等）
- **訓練與最佳化**: 熟悉反向傳播和不同類型的損失函數，例如均方誤差 (MSE) 和交叉熵。了解各種最佳化演算法，例如梯度下降、隨機梯度下降、RMSprop 和 Adam。
- **過度擬合**: 了解過度擬合的概念（模型在訓練資料上表現良好，但在未見過的資料上表現不佳）並學習各種正則化技術（dropout、L1/L2 正則化、提前停止、資料增強）來防止過度擬合。
- **實作多層感知器 (MLP)**: 使用 PyTorch 建構 MLP，也稱為全連接網路。
  
📚 資源:

- [3Blue1Brown - 什麼是神經網路？](https://www.youtube.com/watch?v=aircAruvnKk): 該影片直觀地解釋了神經網路及其內部運作原理。
- [freeCodeCamp - 深度學習速成課程](https://www.youtube.com/watch?v=VyWAvY2CF9c): 此影片簡潔地介紹了深度學習中所有最重要的概念。
- [Fast.ai - 實用深度學習](https://course.fast.ai/): 為具有程式設計經驗、想要了解深度學習的人設計的免費課程。
- [Patrick Loeber - PyTorch 教學](https://www.youtube.com/playlist?list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4): 為初學者學習 PyTorch 的系列影片。

---

### 4. 自然語言處理(NLP)

NLP 是人工智慧的一個令人著迷的分支，它彌合了人類語言和機器理解之間的差距。從簡單的文字處理到理解語言的細微差別，NLP 在翻譯、情緒分析、聊天機器人等許多應用中發揮著至關重要的作用。

- **文字預處理**: 學習各種文字預處理步驟，例如分詞（將文字分割成單字或句子）、詞幹擷取（將單字還原為其詞根形式）、詞形還原（與詞幹擷取類似，但考慮上下文）、停用詞刪除等。
- **特徵提取技術**: 熟悉將文字資料轉換為機器學習演算法可以理解的格式的技術。主要方法包括詞袋 (BoW)、詞頻-逆文檔頻率 (TF-IDF) 和 n-gram。
- **詞嵌入**: 詞嵌入是一種詞表示形式，允許具有相似意義的詞具有相似的表示形式。主要方法包括 Word2Vec、GloVe 和 FastText。
- **遞歸神經網路 (RNN)**: 了解 RNN 的工作原理，RNN 是一種設計用於處理序列資料的神經網路。探索 LSTM 和 GRU，這兩種能夠學習長期依賴關係的 RNN 變體。
📚 Resources:

- [RealPython - NLP with spaCy in Python](https://realpython.com/natural-language-processing-spacy-python/): 有關 Python 中用於 NLP 任務的 spaCy 函式庫的詳細指南。
- [Kaggle - NLP Guide](https://www.kaggle.com/learn-guide/natural-language-processing):一些 notebooks 和資源，用於 Python 中 NLP 的實踐解釋。 
- [Jay Alammar - The Illustration Word2Vec](https://jalammar.github.io/illustrated-word2vec/):了解著名 Word2Vec 架構的一個好材料。
- [Jake Tae - PyTorch RNN from Scratch](https://jaketae.github.io/study/pytorch-rnn/): 在 PyTorch 中實用且簡單地實作 RNN、LSTM 和 GRU 模型。
- [colah's blog - Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/): 一篇更理論性的 LSTM 網路文章。

## 🧑‍🔬 LLM 模型工程

本課程的這一部分重點在於學習如何使用最新技術來建立最好的 LLMs。

![](img/roadmap_scientist.png)

### 1. The LLM 架構

雖然不需要深入了解 Transformer 架構，但深入了解其輸入（tokens 令牌）和輸出（logits）非常重要。普通的注意力機制是另一個需要掌握的關鍵組成部分，稍後會介紹它的改進版本。

* **高階視圖 High-level view**: 重新審視編碼器-解碼器 Transformer 架構，更具體地說，是僅解碼器的 GPT 架構，該架構在每個最近的 LLM 中基本都有使用。
* **標記化 Tokenization**: 了解如何將原始文字資料轉換為模型可以理解的格式，這涉及將文字拆分為標記（通常是單字或子單字）。
* **注意力機制**: 掌握注意力機制背後的理論，包括自註意力和縮放點積注意力，這使得模型在產生輸出時能夠專注於輸入的不同部分。
* **文字生成**: 了解模型產生輸出序列的不同方式。常見的策略包括貪婪解碼(greedy decoding)、波束搜尋(beam searc)、top-k 採樣(top-k sampling)和核採樣(nucleus sampling)。

📚 **參考資料**:
- [Transformer 插圖](https://jalammar.github.io/illustrated-transformer/) by Jay Alammar: Transformer 模型的直觀解釋。
- [GPT-2圖解](https://jalammar.github.io/illustrated-gpt2/) by Jay Alammar: 此文比上一篇文章想對更重要些，它專注於和 Llama 非常相似的 GPT 架構。
- [LLM Visualization](https://bbycroft.net/llm) by Brendan Bycroft: 以 3D 視覺化方式呈現 LLM 內部發生的情況。
* [nanoGPT](https://www.youtube.com/watch?v=kCc8FmEb1nY) by Andrej Karpathy:一段 2 小時長的 YouTube 影片，用於從頭開始重新實現 GPT（以程式設計師的視角）。
* [Attention? Attention!](https://lilianweng.github.io/posts/2018-06-24-attention/) by Lilian Weng: 以更正式的方式介紹注意力的必要性。
* [Decoding Strategies in LLMs](https://mlabonne.github.io/blog/posts/2023-06-07-Decoding_strategies.html): 提供對生成文本的不同解碼策略的圖像化介紹以及程式碼。

---
### 2. 構建一個範例(或指令)資料集 instruction dataset

雖然從維基百科和其他網站找到原始資料很容易，但在很多的環境中收集成對的指示,範例和答案卻很困難。與傳統機器學習一樣，資料集的品質將直接影響模型的品質，這就是為什麼它可能是微調過程中最重要的組成部分。

* **[類似 Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)-的資料集**: 使用 OpenAI API (GPT) 從頭開始產生合成資料。您可以指定種子和系統提示來建立多樣化的資料集。
* **進階技巧**: 了解如何使用[Evol-Instruct](https://arxiv.org/abs/2304.12244)改進現有資料集，如何產生和[Orca](https://arxiv.org/abs/2306.02707) 和 [phi-1](https://arxiv.org/abs/2306.11644) 論文中類似的高品質合成資料.
* **資料過濾**: 涉及正規表示式、刪除近似重複項、關注具有大量標記的答案等的傳統技巧.
* **提示詞模板**: 目前還沒有真正的標準方法來格式來標準化說明範本和答案，這就是為什麼了解不同的聊天範本很重要, 像是 [ChatML](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/chatgpt?tabs=python&pivots=programming-language-chat-ml), [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html) 等.

📚 **參考資料**:
* [Preparing a Dataset for Instruction tuning](https://wandb.ai/capecape/alpaca_ft/reports/How-to-Fine-Tune-an-LLM-Part-1-Preparing-a-Dataset-for-Instruction-Tuning--Vmlldzo1NTcxNzE2) by Thomas Capelle: Alpaca 和 Alpaca-GPT4 資料集的探索以及如何標準化資料.
* [Generating a Clinical Instruction Dataset](https://medium.com/mlearning-ai/generating-a-clinical-instruction-dataset-in-portuguese-with-langchain-and-gpt-4-6ee9abfa41ae) by Solano Todeschini: 有關如何使用 GPT-4 建立綜合指導資料集的教學. 
* [GPT 3.5 for news classification](https://medium.com/@kshitiz.sahay26/how-i-created-an-instruction-dataset-using-gpt-3-5-to-fine-tune-llama-2-for-news-classification-ed02fe41c81f) by Kshitiz Sahay: 使用 GPT 3.5 建立範例資料集來微調 Llama 2 的新聞分類.
* [Dataset creation for fine-tuning LLM](https://colab.research.google.com/drive/1GH8PW9-zAe4cXEZyOIE-T9uHXblIldAg?usp=sharing): 包含一些過濾資料集和上傳結果技術的 Notebook .
* [Chat Template](https://huggingface.co/blog/chat-templates) by Matthew Carrigan: 關於提示模板的 Hugging Face 頁面

---
### 3. 預訓練模型

預訓練是一個非常漫長且成本高昂的過程，這就是為什麼這不是本課程的重點。但是對預訓練期間發生的情況有一定程度的了解是很好的。

* **資料處理流程**: 預訓練需要龐大的資料集 (例如： [Llama 2](https://arxiv.org/abs/2307.09288) 使用 2 兆個tokens進行訓練) ，需要將這些資料集過濾、標記化並與預先定義的詞彙進行整理。
* **因果語言建模(Causal language modeling)**: 了解因果語言建模和掩碼語言建模(causal and masked language modeling)之間的區別,以及本例中使用的損失函數。更多高效率的預訓練知識可前往 [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) 或[gpt-neox](https://github.com/EleutherAI/gpt-neox)了解。 
* **縮放的規律**: [縮放的規律](https://arxiv.org/pdf/2001.08361.pdf) 根據模型大小、資料集大小和用於訓練的計算量描述預期的模型性能。
* **高效能運算**: 這有點超出了本文的範圍，但如果您打算從頭開始創建自己的LLMs(大語言模型)（硬體、分散式工作負載等），那麼更多有關 HPC 的知識是對你而言是必要的。
  
📚 **參考資料**:
* [LLMDataHub](https://github.com/Zjh-819/LLMDataHub) by Junhao Zhao: 用於預訓練、微調和 RLHF 的精選資料集清單。
* [Training a causal language model from scratch](https://huggingface.co/learn/nlp-course/chapter7/6?fw=pt) by Hugging Face: 使用 Transformers 庫從頭開始預先訓練 GPT-2 模型。
* [TinyLlama](https://github.com/jzhang38/TinyLlama) by Zhang et al.: 可在此項目很好地了解 Llama 模型是如何從頭開始訓練的。
* [Causal language modeling](https://huggingface.co/docs/transformers/tasks/language_modeling) by Hugging Face: 解釋因果語言建模和屏蔽語言建模之間的差異以及如何快速微調 DistilGPT-2 模型。
* [Chinchilla's wild implications](https://www.lesswrong.com/posts/6Fpvch8RR29qLEWNH/chinchilla-s-wild-implications) by nostalgebraist: 討論縮放定律並解釋它們對大語言模型的意義。
* [BLOOM](https://bigscience.notion.site/BLOOM-BigScience-176B-Model-ad073ca07cdf479398d5f95d88e218c4) by BigScience: 描述如何建立 BLOOM 模型的 Notion 頁面，其中包含大量有關工程部分和遇到問題的有用資訊。
* [OPT-175 Logbook](https://github.com/facebookresearch/metaseq/blob/main/projects/OPT/chronicles/OPT175B_Logbook.pdf) by Meta: 研究日誌顯示出了什麼錯的以及什麼是正確的。如果您計劃預先訓練非常大的語言模型（在本例中為 175B 參數），則非常有用。
* [LLM 360](https://www.llm360.ai/): 開源大於言模型框架，包含訓練和資料準備代碼、資料、指標和模型。

---
### 4. 監督微調 (Supervised Fine-Tuning)

預訓練模型僅針對下一個標記(next-token)預測任務進行訓練，這就是為什麼它們不是有用的助手。SFT 允許您調整它們以回應指令。此外，它允許您根據任何資料（私人資料、GPT-4 無法看到的資料等）微調您的模型並使用它，而無需支付 OpenAI 等 API 的費用。

* **全微調**: 全微調是指訓練模型中的所有參數(就是模型訓練)。這不是一種有效的技術，但它會產生稍微好一點的結果.
* [**LoRA**](https://arxiv.org/abs/2106.09685): 一種基於低階適配器(low-rank adapters)的高效參數微調技術（PEFT）。我們不訓練所有參數，而是只訓練這些適配器(adapters)。
* [**QLoRA**](https://arxiv.org/abs/2305.14314): 另一個基於 LoRA 的 PEFT，它還將模型的權重量化為 4 bits，並引入分頁優化器來管理記憶體峰值。將其與[Unsloth](https://github.com/unslothai/unsloth)結合使用，可以在免費的 Colab 筆記本上運行。
* **[Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl)**: 一種用戶友好且功能強大的微調工具，用於許多最先進的開源模型。
* [**DeepSpeed**](https://www.deepspeed.ai/): 針對多 GPU 和多節點設定的 LLM 的高效預訓練和微調（在 Axolotl 中實現）。

📚 **參考資料**:
* [The Novice's LLM Training Guide](https://rentry.org/llm-training) by Alpin: 概述微調 LLM 時要考慮的主要概念和參數.
* [LoRA insights](https://lightning.ai/pages/community/lora-insights/) by Sebastian Raschka: 有關 LoRA 以及如何選擇最佳參數的實用見解.
* [Fine-Tune Your Own Llama 2 Model](https://mlabonne.github.io/blog/posts/Fine_Tune_Your_Own_Llama_2_Model_in_a_Colab_Notebook.html): 有關如何使用 Hugging Face 庫微調 Llama 2 模型的實作教學.
* [Padding Large Language Models](https://towardsdatascience.com/padding-large-language-models-examples-with-llama-2-199fb10df8ff) by Benjamin Marie: 為因果LLMs(causal LLMs)填充訓練範例的最佳實踐 
* [A Beginner's Guide to LLM Fine-Tuning](https://mlabonne.github.io/blog/posts/A_Beginners_Guide_to_LLM_Finetuning.html): 有關如何使用 Axolotl 微調 CodeLlama 模型的教學.

---
### 5. Reinforcement Learning from Human Feedback RLHF (根據人類回饋進行強化學習)

經過監督微調後，RLHF 是用來使 LLM 的答案與人類期望保持一致的一個步驟。這個想法是從人類（或人工）回饋中學習偏好，這可用於減少偏見、審查模型或使它們以更有用的方式行事。它比 SFT 更複雜，並且通常被視為可選項之一。


* **偏好資料集**: 這些資料集通常包含具有某種排名的多個答案，這使得它們比指令資料集更難產生.
* [**近端策略最佳化**](https://arxiv.org/abs/1707.06347): 此演算法利用獎勵模型來預測給定文字是否被人類排名較高。然後使用該預測來最佳化 SFT 模型，並根據 KL 散度進行獎懲。
* **[直接偏好優化](https://arxiv.org/abs/2305.18290)**: DPO 透過將其重新定義為分類問題來簡化流程。它使用參考模型而不是獎勵模型（無需訓練），並且只需要一個超參數，使其更加穩定和高效。

📚 **參考資料**:
* [An Introduction to Training LLMs using RLHF](https://wandb.ai/ayush-thakur/Intro-RLAIF/reports/An-Introduction-to-Training-LLMs-Using-Reinforcement-Learning-From-Human-Feedback-RLHF---VmlldzozMzYyNjcy) by Ayush Thakur: 這解釋了為什麼 RLHF 對於減少大語言模型的偏見和提高績效是可取的。
* [Illustration RLHF](https://huggingface.co/blog/rlhf) by Hugging Face: RLHF 簡介，包括獎勵模型訓練和強化學習微調.
* [StackLLaMA](https://huggingface.co/blog/stackllama) by Hugging Face: 使用 Transformer 函式庫有效地將 LLaMA 模型與 RLHF 對齊的教學.
* [LLM Training: RLHF and Its Alternatives](https://substack.com/profile/27393275-sebastian-raschka-phd) by Sebastian Rashcka: RLHF 流程和 RLAIF 等替代方案的概述.
* [Fine-tune Mistral-7b with DPO](https://huggingface.co/blog/dpo-trl):使用 DPO 微調 Mistral-7b 模型並重現[NeuralHermes-2.5](https://huggingface.co/mlabonne/NeuralHermes-2.5-Mistral-7B) 的教學.

---
### 6. 評估 Evaluation

評估大型語言模型(LLMs)是流程中一個被低估的部分，因為評估這一個過程耗時且相對可靠性較低。你的下游任務應該指明你想要評估的內容，但記得古德哈特定律(Goodhart's law)提到的：“當一個衡量指標變成了目標，它就不再是一個好的衡量指標。”

* **傳統指標 Traditional metrics**: 像困惑度(perplexity)和BLEU分數這樣的指標不再像以前那樣受歡迎，因為在大多數情況下它們是有缺陷的。但了解它們以及它們適用的情境仍然很重要。
* **通用基準 General benchmarks**: 基於語言模型評估工具箱 [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)，Open LLM排行榜 [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) 是用於通用大型語言模型（如ChatGPT）的主要基準。還有其他受歡迎的基準，如[BigBench](https://github.com/google/BIG-bench), [MT-Bench](https://arxiv.org/abs/2306.05685)等。
* **任務特定基準 Task-specific benchmarks**: 如摘要、翻譯和問答等任務有專門的基準、指標甚至子領域（醫療、金融等），例如用於生物醫學問答 [PubMedQA](https://pubmedqa.github.io/)。
* **人類評估 Human evaluation**: 最可靠的評估是用戶的接受度或由人類所做的比較。如果你想知道一個模型表現得如何，最簡單但最確定的方式就是自己使用它。

📚 **參考文獻**:
* [固定長度輸入(有最大輸入限制)模型的困惑度](https://huggingface.co/docs/transformers/perplexity) by Hugging Face: 困惑度(perplexity)的概述，並使用 Transformer 庫實現了它的程式碼。
* [BLEU 使用風險](https://towardsdatascience.com/evaluating-text-output-in-nlp-bleu-at-your-own-risk-e8609665a213) by Rachael Tatman: BLEU 分數及其許多問題的概述，並提供了示例。
* [大型語言模型評估調查](https://arxiv.org/abs/2307.03109) by Chang et al.: 關於評估什麼、在哪裡評估以及如何評估的綜合性論文。
* [聊天機器人排行榜](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard) by lmsys: 基於人類比較的通用大型語言模型的Elo評分。

---
### 7. 量化

量化是將模型的權重（和啟動值）轉換成更低精度表示的過程。例如，原本使用16位元儲存的權重可以轉換成4位元表示。這種技術愈來愈重要，用來減少與大型語言模型（LLMs）相關的計算與記憶體成本。

* **基礎技術**: 瞭解不同的精確度層級（FP32、FP16、INT8等）以及如何使用absmax與零點技術(zero-point techniques)進行簡單的量化。
* **GGUF和llama.cpp**: 最初設計用於在CPU上運行，[llama.cpp](https://github.com/ggerganov/llama.cpp) 和GGUF格式已成為在消費級硬體上運行LLMs的最受歡迎的工具。
* **GPTQ和EXL2**: [GPTQ](https://arxiv.org/abs/2210.17323) ，特別是 [EXL2](https://github.com/turboderp/exllamav2) ，提供了較快的速度，但只能在GPU上運行。模型量化也需要很長時間。
* **AWQ**: 這種新格式比GPTQ更準確（困惑度更低），但使用的顯存更多，速度也不一定更快。

📚 **參考文獻**:
* [量化簡介](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html): 量化概述，absmax與零點量化，以及使用 LLM.int8()在程式碼上。
* [使用llama.cpp量化Llama模型](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html): 關於如何使用llama.cpp和GGUF格式量化Llama 2模型的教學。
* [使用GPTQ進行4位元LLM量化](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html):關於如何使用GPTQ演算法和AutoGPTQ量化LLM的教學。
* [ExLlamaV2: 運行LLMs的最快程式庫](https://mlabonne.github.io/blog/posts/ExLlamaV2_The_Fastest_Library_to_Run%C2%A0LLMs.html): 指南；關於如何使用EXL2格式量化Mistral模型，並使用ExLlamaV2程式庫運行。
* [了解啟動感知權重量化](https://medium.com/friendliai/understanding-activation-aware-weight-quantization-awq-boosting-inference-serving-efficiency-in-10bb0faf63a8) by FriendliAI: AWQ技術及其優勢的概述。

---
### 8. 新趨勢

* **位置嵌入 Positional embeddings**: 了解大型語言模型（LLMs）如何編碼位置，特別是像 [RoPE](https://arxiv.org/abs/2104.09864) 這樣的相對位置編碼方案。實現 [YaRN](https://arxiv.org/abs/2309.00071) (通過溫度因子乘以注意力矩陣) or [ALiBi](https://arxiv.org/abs/2108.12409) (基於token距離的注意力獎懲) 來擴展上下文長度。
* **模型融合 Model merging**: 將訓練好的模型合併已成為一種流行的方式，用於創建表現優異的模型，無需任何微調。流行的 [mergekit](https://github.com/cg123/mergekit) 庫實現了最受歡迎的融合方法，如e SLERP, [DARE](https://arxiv.org/abs/2311.03099), 和 [TIES](https://arxiv.org/abs/2311.03099)。模型融合通常指的是將多個已訓練的模型合併成一個單一模型的過程。這不僅僅是平均或投票決定輸出，而是在模型的權重和結構層面上進行合併。這個過程不需要再次訓練，可以通過數學操作（如球面線性內插（SLERP）或其他融合技術）將不同模型的知識整合起來。模型融合用於創建一個表現更佳、更強大的模型，通常是將多個模型在特定任務上的優勢結合起來。
* **專家混合 Mixture of Experts**: [Mixtral](https://arxiv.org/abs/2401.04088) 因其卓越的性能而重新使MoE架構流行起來。 與此同時，OSS社區出現了一種frankenMoE，通過融合像 [Phixtral](https://huggingface.co/mlabonne/phixtral-2x2_8)這樣的模型，這是一個更經濟且性能良好的選項。MoE是一種結構，它包含多個子模型或“專家”，每個專家專門處理不同的任務或數據子集。在MoE架構中，一個“gate”或調度器決定對於給定的輸入，哪個專家被使用。這是一種稀疏啟動方法，可以大幅提升模型的容量和效率，因為不是所有的專家都會對每個輸入進行響應。
* **多模態模型 Multimodal models**: 這些模型（ [CLIP](https://openai.com/research/clip), [Stable Diffusion](https://stability.ai/stable-image), 或 [LLaVA](https://llava-vl.github.io/)) 處理多種類型的輸入（文本、圖像、音頻等）與統一的嵌入空間，從而解鎖了強大的應用，如文本到圖像。

📚 **參考文獻**:
* [Extending the RoPE](https://blog.eleuther.ai/yarn/) by EleutherAI: 總結不同位置編碼技術的文章.
* [Understanding YaRN](https://medium.com/@rcrajatchawla/understanding-yarn-extending-context-window-of-llms-3f21e3522465) by Rajat Chawla: 對YaRN的介紹.
* [Merge LLMs with mergekit](https://mlabonne.github.io/blog/posts/2024-01-08_Merge_LLMs_with_mergekit.html): 關於使用mergekit進行模型融合的教程.
* [Mixture of Experts Explained](https://huggingface.co/blog/moe) by Hugging Face: 關於MoE及其工作方式的詳盡指南.
* [Large Multimodal Models](https://huyenchip.com/2023/10/10/multimodal.html) by Chip Huyen: 對多模態系統及其近期發展歷史的概述.

## 👷 LLM 應用工程

本課程的這一部分重點是學習如何建立可在生產中使用的由 LLM 支援的應用程序，重點主要在增強模型和部署它們。

![](img/roadmap_engineer.png)


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
### 5. Inference optimization

Text generation is a costly process that requires expensive hardware. In addition to quantization, various techniques have been proposed to maximize throughput and reduce inference costs.

* **Flash Attention**: Optimization of the attention mechanism to transform its complexity from quadratic to linear, speeding up both training and inference.
* **Key-value cache**: Understand the key-value cache and the improvements introduced in [Multi-Query Attention](https://arxiv.org/abs/1911.02150) (MQA) and [Grouped-Query Attention](https://arxiv.org/abs/2305.13245) (GQA).
* **Speculative decoding**: Use a small model to produce drafts that are then reviewed by a larger model to speed up text generation.

📚 **References**:
* [GPU Inference](https://huggingface.co/docs/transformers/main/en/perf_infer_gpu_one) by Hugging Face: Explain how to optimize inference on GPUs.
* [LLM Inference](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices) by Databricks: Best practices for how to optimize LLM inference in production.
* [Optimizing LLMs for Speed and Memory](https://huggingface.co/docs/transformers/main/en/llm_tutorial_optimization) by Hugging Face: Explain three main techniques to optimize speed and memory, namely quantization, Flash Attention, and architectural innovations.
* [Assisted Generation](https://huggingface.co/blog/assisted-generation) by Hugging Face: HF's version of speculative decoding, it's an interesting blog post about how it works with code to implement it.

---
### 6. Deploying LLMs

Deploying LLMs at scale is an engineering feat that can require multiple clusters of GPUs. In other scenarios, demos and local apps can be achieved with a much lower complexity. 

* **Local deployment**: Privacy is an important advantage that open-source LLMs have over private ones. Local LLM servers ([LM Studio](https://lmstudio.ai/), [Ollama](https://ollama.ai/), [oobabooga](https://github.com/oobabooga/text-generation-webui), [kobold.cpp](https://github.com/LostRuins/koboldcpp), etc.) capitalize on this advantage to power local apps. 
* **Demo deployment**: Frameworks like [Gradio](https://www.gradio.app/) and [Streamlit](https://docs.streamlit.io/) are helpful to prototype applications and share demos. You can also easily host them online, for example using [Hugging Face Spaces](https://huggingface.co/spaces).
* **Server deployment**: Deploy LLMs at scale requires cloud (see also [SkyPilot](https://skypilot.readthedocs.io/en/latest/)) or on-prem infrastructure and often leverage optimized text generation frameworks like [TGI](https://github.com/huggingface/text-generation-inference), [vLLM](https://github.com/vllm-project/vllm/tree/main), etc.
* **Edge deployment**: In constrained environments, high-performance frameworks like [MLC LLM](https://github.com/mlc-ai/mlc-llm) and [mnn-llm](https://github.com/wangzhaode/mnn-llm/blob/master/README_en.md) can deploy LLM in web browsers, Android, and iOS.

📚 **References**:
* [Streamlit - Build a basic LLM app](https://docs.streamlit.io/knowledge-base/tutorials/build-conversational-apps): Tutorial to make a basic ChatGPT-like app using Streamlit.
* [HF LLM Inference Container](https://huggingface.co/blog/sagemaker-huggingface-llm): Deploy LLMs on Amazon SageMaker using Hugging Face's inference container.
* [Philschmid blog](https://www.philschmid.de/) by Philipp Schmid: Collection of high-quality articles about LLM deployment using Amazon SageMaker.
* [Optimizing latence](https://hamel.dev/notes/llm/inference/03_inference.html) by Hamel Husain: Comparison of TGI, vLLM, CTranslate2, and mlc in terms of throughput and latency.

---
### 7. Securing LLMs

In addition to traditional security problems associated with software, LLMs have unique weaknesses due to the way they are trained and prompted.

* **Prompt hacking**: Different techniques related to prompt engineering, including prompt injection (additional instruction to hijack the model's answer), data/prompt leaking (retrieve its original data/prompt), and jailbreaking (craft prompts to bypass safety features).
* **Backdoors**: Attack vectors can target the training data itself, by poisoning the training data (e.g., with false information) or creating backdoors (secret triggers to change the model's behavior during inference).
* **Defensive measures**: The best way to protect your LLM applications is to test them against these vulnerabilities (e.g., using red teaming and checks like [garak](https://github.com/leondz/garak/)) and observe them in production (with a framework like [langfuse](https://github.com/langfuse/langfuse)).

📚 **References**:
* [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) by HEGO Wiki: List of the 10 most critic vulnerabilities seen in LLM applications.
* [Prompt Injection Primer](https://github.com/jthack/PIPE) by Joseph Thacker: Short guide dedicated to prompt injection for engineers.
* [LLM Security](https://llmsecurity.net/) by [@llm_sec](https://twitter.com/llm_sec): Extensive list of resources related to LLM security.
* [Red teaming LLMs](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming) by Microsoft: Guide on how to perform red teaming with LLMs.
---
## Acknowledgements

This roadmap was inspired by the excellent [DevOps Roadmap](https://github.com/milanm/DevOps-Roadmap) from Milan Milanović and Romano Roth.

Special thanks to:

* Thomas Thelen for motivating me to create a roadmap
* André Frade for his input and review of the first draft
* Dino Dunn for providing resources about LLM security

*Disclaimer: I am not affiliated with any sources listed here.*

---
<p align="center">
  <a href="https://star-history.com/#mlabonne/llm-course&Date">
    <img src="https://api.star-history.com/svg?repos=mlabonne/llm-course&type=Date" alt="Star History Chart">
  </a>
</p>
