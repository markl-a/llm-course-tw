
### 6. Deploying LLMs 部署大型語言模型

在大規模部署大型語言模型（LLMs）是一項工程壯舉，可能需要多個GPU集群。在其他情景下，演示和本地應用可以更簡單的實現運作。

* **Local deployment 本地部署**: 隱私是開源LLMs相對於私有LLMs的一個重要優勢。 本地LLM服務器 ([LM Studio](https://lmstudio.ai/), [Ollama](https://ollama.ai/), [oobabooga](https://github.com/oobabooga/text-generation-webui), [kobold.cpp](https://github.com/LostRuins/koboldcpp), 等）利用這一優勢為本地應用提供動力。     
* **Demo deployment 演示部署**:像 [Gradio](https://www.gradio.app/) 和 [Streamlit](https://docs.streamlit.io/) 這樣的框架有助於原型應用的開發和演示的分享。您也可以輕鬆地在線上部署，例如使用 [Hugging Face Spaces](https://huggingface.co/spaces)。 
    * [Streamlit - Build a basic LLM app](https://docs.streamlit.io/knowledge-base/tutorials/build-conversational-apps): 使用Streamlit創建類似ChatGPT的基礎應用的教學。
* **Server deployment 服務器部署**: 大規模部署LLMs需要雲端 (詳見 [SkyPilot](https://skypilot.readthedocs.io/en/latest/)) 或內部部署的基礎設施，並經常利用優化的文本生成框架，如 [TGI](https://github.com/huggingface/text-generation-inference), [vLLM](https://github.com/vllm-project/vllm/tree/main)等。
    * [HF LLM Inference Container](https://huggingface.co/blog/sagemaker-huggingface-llm): D使用Hugging Face的推論容器在Amazon SageMaker上部署LLMs。
* **Edge deployment 邊緣(中低算力)部署**: 在受限環境中，高性能框架如 [MLC LLM](https://github.com/mlc-ai/mlc-llm) 和 [mnn-llm](https://github.com/wangzhaode/mnn-llm/blob/master/README_en.md) 可以在網頁瀏覽器、Android和iOS中部署LLM。
    * [Philschmid blog](https://www.philschmid.de/) by Philipp Schmid: 關於使用Amazon SageMaker部署LLM的高質量文章集。
    * [Optimizing latence 優化延遲](https://hamel.dev/notes/llm/inference/03_inference.html) by Hamel Husain:比較TGI、vLLM、CTranslate2和mlc在吞吐量和延遲方面的性能。

