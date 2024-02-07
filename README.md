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
### 5. Reinforcement Learning from Human Feedback RLHF (根據人類回饋進行強化學習
)
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

Evaluating LLMs is an undervalued part of the pipeline, which is time-consuming and moderately reliable. Your downstream task should dictate what you want to evaluate, but always remember Goodhart's law: "When a measure becomes a target, it ceases to be a good measure."

* **Traditional metrics**: Metrics like perplexity and BLEU score are not as popular as they were because they're flawed in most contexts. It is still important to understand them and when they can be applied.
* **General benchmarks**: Based on the [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness), the [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) is the main benchmark for general-purpose LLMs (like ChatGPT). There are other popular benchmarks like [BigBench](https://github.com/google/BIG-bench), [MT-Bench](https://arxiv.org/abs/2306.05685), etc.
* **Task-specific benchmarks**: Tasks like summarization, translation, and question answering have dedicated benchmarks, metrics, and even subdomains (medical, financial, etc.), such as [PubMedQA](https://pubmedqa.github.io/) for biomedical question answering.
* **Human evaluation**: The most reliable evaluation is the acceptance rate by users or comparisons made by humans. If you want to know if a model performs well, the simplest but surest way is to use it yourself.

📚 **References**:
* [Perplexity of fixed-length models](https://huggingface.co/docs/transformers/perplexity) by Hugging Face: Overview of perplexity with code to implement it with the transformers library.
* [BLEU at your own risk](https://towardsdatascience.com/evaluating-text-output-in-nlp-bleu-at-your-own-risk-e8609665a213) by Rachael Tatman: Overview of the BLEU score and its many issues with examples.
* [A Survey on Evaluation of LLMs](https://arxiv.org/abs/2307.03109) by Chang et al.: Comprehensive paper about what to evaluate, where to evaluate, and how to evaluate.
* [Chatbot Arena Leaderboard](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard) by lmsys: Elo rating of general-purpose LLMs, based on comparisons made by humans.

---
### 7. Quantization

Quantization is the process of converting the weights (and activations) of a model using a lower precision. For example, weights stored using 16 bits can be converted into a 4-bit representation. This technique has become increasingly important to reduce the computational and memory costs associated with LLMs.

* **Base techniques**: Learn the different levels of precision (FP32, FP16, INT8, etc.) and how to perform naïve quantization with absmax and zero-point techniques.
* **GGUF and llama.cpp**: Originally designed to run on CPUs, [llama.cpp](https://github.com/ggerganov/llama.cpp) and the GGUF format have become the most popular tools to run LLMs on consumer-grade hardware.
* **GPTQ and EXL2**: [GPTQ](https://arxiv.org/abs/2210.17323) and, more specifically, the [EXL2](https://github.com/turboderp/exllamav2) format offer an incredible speed but can only run on GPUs. Models also take a long time to be quantized.
* **AWQ**: This new format is more accurate than GPTQ (lower perplexity) but uses a lot more VRAM and is not necessarily faster.

📚 **References**:
* [Introduction to quantization](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html): Overview of quantization, absmax and zero-point quantization, and LLM.int8() with code.
* [Quantize Llama models with llama.cpp](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html): Tutorial on how to quantize a Llama 2 model using llama.cpp and the GGUF format.
* [4-bit LLM Quantization with GPTQ](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html): Tutorial on how to quantize an LLM using the GPTQ algorithm with AutoGPTQ.
* [ExLlamaV2: The Fastest Library to Run LLMs](https://mlabonne.github.io/blog/posts/ExLlamaV2_The_Fastest_Library_to_Run%C2%A0LLMs.html): Guide on how to quantize a Mistral model using the EXL2 format and run it with the ExLlamaV2 library.
* [Understanding Activation-Aware Weight Quantization](https://medium.com/friendliai/understanding-activation-aware-weight-quantization-awq-boosting-inference-serving-efficiency-in-10bb0faf63a8) by FriendliAI: Overview of the AWQ technique and its benefits.

---
### 8. New Trends

* **Positional embeddings**: Learn how LLMs encode positions, especially relative positional encoding schemes like [RoPE](https://arxiv.org/abs/2104.09864). Implement [YaRN](https://arxiv.org/abs/2309.00071) (multiplies the attention matrix by a temperature factor) or [ALiBi](https://arxiv.org/abs/2108.12409) (attention penalty based on token distance) to extend the context length.
* **Model merging**: Merging trained models has become a popular way of creating peformant models without any fine-tuning. The popular [mergekit](https://github.com/cg123/mergekit) library implements the most popular merging methods, like SLERP, [DARE](https://arxiv.org/abs/2311.03099), and [TIES](https://arxiv.org/abs/2311.03099).
* **Mixture of Experts**: [Mixtral](https://arxiv.org/abs/2401.04088) re-popularized the MoE architecture thanks to its excellent performance. In parallel, a type of frankenMoE emerged in the OSS community by merging models like [Phixtral](https://huggingface.co/mlabonne/phixtral-2x2_8), which is a cheaper and performant option.
* **Multimodal models**: These models (like [CLIP](https://openai.com/research/clip), [Stable Diffusion](https://stability.ai/stable-image), or [LLaVA](https://llava-vl.github.io/)) process multiple types of inputs (text, images, audio, etc.) with a unified embedding space, which unlocks powerful applications like text-to-image.

📚 **References**:
* [Extending the RoPE](https://blog.eleuther.ai/yarn/) by EleutherAI: Article that summarizes the different position-encoding techniques.
* [Understanding YaRN](https://medium.com/@rcrajatchawla/understanding-yarn-extending-context-window-of-llms-3f21e3522465) by Rajat Chawla: Introduction to YaRN.
* [Merge LLMs with mergekit](https://mlabonne.github.io/blog/posts/2024-01-08_Merge_LLMs_with_mergekit.html): Tutorial about model merging using mergekit.
* [Mixture of Experts Explained](https://huggingface.co/blog/moe) by Hugging Face: Exhaustive guide about MoEs and how they work.
* [Large Multimodal Models](https://huyenchip.com/2023/10/10/multimodal.html) by Chip Huyen: Overview of multimodal systems and the recent history of this field.

## 👷 The LLM Engineer

This section of the course focuses on learning how to build LLM-powered applications that can be used in production, with a focus on augmenting models and deploying them.

![](img/roadmap_engineer.png)


### 1. Running LLMs

Running LLMs can be difficult due to high hardware requirements. Depending on your use case, you might want to simply consume a model through an API (like GPT-4) or run it locally. In any case, additional prompting and guidance techniques can improve and constrain the output for your applications.

* **LLM APIs**: APIs are a convenient way to deploy LLMs. This space is divided between private LLMs ([OpenAI](https://platform.openai.com/), [Google](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/overview), [Anthropic](https://docs.anthropic.com/claude/reference/getting-started-with-the-api), [Cohere](https://docs.cohere.com/docs), etc.) and open-source LLMs ([OpenRouter](https://openrouter.ai/), [Hugging Face](https://huggingface.co/inference-api), [Together AI](https://www.together.ai/), etc.).
* **Open-source LLMs**: The [Hugging Face Hub](https://huggingface.co/models) is a great place to find LLMs. You can directly run some of them in [Hugging Face Spaces](https://huggingface.co/spaces), or download and run them locally in apps like [LM Studio](https://lmstudio.ai/) or through the CLI with [llama.cpp](https://github.com/ggerganov/llama.cpp) or [Ollama](https://ollama.ai/).
* **Prompt engineering**: Common techniques include zero-shot prompting, few-shot prompting, chain of thought, and ReAct. They work better with bigger models, but can be adapted to smaller ones.
* **Structuring outputs**: Many tasks require a structured output, like a strict template or a JSON format. Libraries like [LMQL](https://lmql.ai/), [Outlines](https://github.com/outlines-dev/outlines), [Guidance](https://github.com/guidance-ai/guidance), etc. can be used to guide the generation and respect a given structure.

📚 **References**:
* [Run an LLM locally with LM Studio](https://www.kdnuggets.com/run-an-llm-locally-with-lm-studio) by Nisha Arya: Short guide on how to use LM Studio.
* [Prompt engineering guide](https://www.promptingguide.ai/) by DAIR.AI: Exhaustive list of prompt techniques with examples
* [Outlines - Quickstart](https://outlines-dev.github.io/outlines/quickstart/): List of guided generation techniques enabled by Outlines. 
* [LMQL - Overview](https://lmql.ai/docs/language/overview.html): Introduction to the LMQL language.

---
### 2. Building a Vector Storage

Creating a vector storage is the first step to build a Retrieval Augmented Generation (RAG) pipeline. Documents are loaded, split, and relevant chunks are used to produce vector representations (embeddings) that are stored for future use during inference.

* **Ingesting documents**: Document loaders are convenient wrappers that can handle many formats: PDF, JSON, HTML, Markdown, etc. They can also directly retrieve data from some databases and APIs (GitHub, Reddit, Google Drive, etc.).
* **Splitting documents**: Text splitters break down documents into smaller, semantically meaningful chunks. Instead of splitting text after *n* characters, it's often better to split by header or recursively, with some additional metadata.
* **Embedding models**: Embedding models convert text into vector representations. It allows for a deeper and more nuanced understanding of language, which is essential to perform semantic search.
* **Vector databases**: Vector databases (like [Chroma](https://www.trychroma.com/), [Pinecone](https://www.pinecone.io/), [Milvus](https://milvus.io/), [FAISS](https://faiss.ai/), [Annoy](https://github.com/spotify/annoy), etc.) are designed to store embedding vectors. They enable efficient retrieval of data that is 'most similar' to a query based on vector similarity.

📚 **References**:
* [LangChain - Text splitters](https://python.langchain.com/docs/modules/data_connection/document_transformers/): List of different text splitters implemented in LangChain.
* [Sentence Transformers library](https://www.sbert.net/): Popular library for embedding models.
* [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard): Leaderboard for embedding models.
* [The Top 5 Vector Databases](https://www.datacamp.com/blog/the-top-5-vector-databases) by Moez Ali: A comparison of the best and most popular vector databases.

---
### 3. Retrieval Augmented Generation

With RAG, LLMs retrieves contextual documents from a database to improve the accuracy of their answers. RAG is a popular way of augmenting the model's knowledge without any fine-tuning.

* **Orchestrators**: Orchestrators (like [LangChain](https://python.langchain.com/docs/get_started/introduction), [LlamaIndex](https://docs.llamaindex.ai/en/stable/), [FastRAG](https://github.com/IntelLabs/fastRAG), etc.) are popular frameworks to connect your LLMs with tools, databases, memories, etc. and augment their abilities.
* **Retrievers**: User instructions are not optimized for retrieval. Different techniques (e.g., multi-query retriever, [HyDE](https://arxiv.org/abs/2212.10496), etc.) can be applied to rephrase/expand them and improve performance.
* **Memory**: To remember previous instructions and answers, LLMs and chatbots like ChatGPT add this history to their context window. This buffer can be improved with summarization (e.g., using a smaller LLM), a vector store + RAG, etc.
* **Evaluation**: We need to evaluate both the document retrieval (context precision and recall) and generation stages (faithfulness and answer relevancy). It can be simplified with tools [Ragas](https://github.com/explodinggradients/ragas/tree/main) and [DeepEval](https://github.com/confident-ai/deepeval).

📚 **References**:
* [Llamaindex - High-level concepts](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html): Main concepts to know when building RAG pipelines.
* [Pinecone - Retrieval Augmentation](https://www.pinecone.io/learn/series/langchain/langchain-retrieval-augmentation/): Overview of the retrieval augmentation process. 
* [LangChain - Q&A with RAG](https://python.langchain.com/docs/use_cases/question_answering/quickstart): Step-by-step tutorial to build a typical RAG pipeline.
* [LangChain - Memory types](https://python.langchain.com/docs/modules/memory/types/): List of different types of memories with relevant usage.
* [RAG pipeline - Metrics](https://docs.ragas.io/en/stable/concepts/metrics/index.html): Overview of the main metrics used to evaluate RAG pipelines.

---
### 4. Advanced RAG

Real-life applications can require complex pipelines, including SQL or graph databases, as well as automatically selecting relevant tools and APIs. These advanced techniques can improve a baseline solution and provide additional features.

* **Query construction**: Structured data stored in traditional databases requires a specific query language like SQL, Cypher, metadata, etc. We can directly translate the user instruction into a query to access the data with query construction.
* **Agents and tools**: Agents augment LLMs by automatically selecting the most relevant tools to provide an answer. These tools can be as simple as using Google or Wikipedia, or more complex like a Python interpreter or Jira. 
* **Post-processing**: Final step that processes the inputs that are fed to the LLM. It enhances the relevance and diversity of documents retrieved with re-ranking, [RAG-fusion](https://github.com/Raudaschl/rag-fusion), and classification.

📚 **References**:
* [LangChain - Query Construction](https://blog.langchain.dev/query-construction/): Blog post about different types of query construction.
* [LangChain - SQL](https://python.langchain.com/docs/use_cases/qa_structured/sql): Tutorial on how to interact with SQL databases with LLMs, involving Text-to-SQL and an optional SQL agent.
* [Pinecone - LLM agents](https://www.pinecone.io/learn/series/langchain/langchain-agents/): Introduction to agents and tools with different types.
* [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) by Lilian Weng: More theoretical article about LLM agents.
* [LangChain - OpenAI's RAG](https://blog.langchain.dev/applying-openai-rag/): Overview of the RAG strategies employed by OpenAI, including post-processing.

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
