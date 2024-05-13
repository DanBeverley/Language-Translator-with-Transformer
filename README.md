### Language Translator with Transformer
# Overview
This project is a language translator powered by a transformer model, designed to accurately translate text between multiple languages. Leveraging the advancements in natural language processing (NLP), particularly transformer architectures . Using a Sequence-to-Sequence (Seq2Seq) model with a Transformer architecture. The model is trained on the Multi30k dataset, which consists of parallel sentences in English, German, and French. The goal is to translate sentences from one language to another using the power of deep learning and natural language processing.

---

### Features
- **Transformer Architecture**: Utilizes the state-of-the-art Transformer architecture, which has shown remarkable performance in sequence-to-sequence tasks.

  ![image](https://github.com/DanBeverley/Language-Translator-with-Transformer/assets/161696810/7acc6ff2-686e-48bb-8400-832895dca375)

  
- **Seq2Seq Learning**: Implements the Seq2Seq learning paradigm, which consists of an encoder-decoder architecture for translating sequences of variable lengths.

  ![image](https://github.com/DanBeverley/Language-Translator-with-Transformer/assets/161696810/80279fbb-775a-4af1-ba07-05cdae1794e0)

- **Greedy Decoding**: Utilizes greedy decoding strategy for generating translations, selecting the most probable word at each step without considering future context. 
- **Multi30k Dataset**: Trained and evaluated on the Multi30k dataset, a widely used benchmark for machine translation tasks.

### Dependencies
- Python 3.x
- PyTorch
- NumPy
- tqdm


### Acknowledgements
- This project builds upon the excellent work done by the PyTorch and Hugging Face communities.
- The Multi30k dataset is provided by the creators of the WMT 2016 Multimodal Translation Shared Task.


---
