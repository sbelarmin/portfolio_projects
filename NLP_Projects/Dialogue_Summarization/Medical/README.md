# Medical Dialogue Summarization with DistilBART

## Objective
The goal of this exercise is to train a **DistilBART** model to effectively summarize doctor-patient dialogues into the **SOAP note** framework. This approach aims to leverage advanced summarization techniques to streamline and structure medical notes.

## Why DistilBART?
- **Lightweight and Efficient**: DistilBART is a distilled version of BART, offering faster training and inference while maintaining strong performance.
- **Pretrained on Summarization**: The model has been pretrained on the **CNN/Daily Mail corpus**, which focuses on summarization tasks, making it well-suited for this project.
- **Architecture**: DistilBART exemplifies the power of BART's **encoder-decoder architecture**, designed specifically for sequence-to-sequence tasks like summarization.

## Future Enhancements
To further evaluate the performance of BART's architecture:
- Additional models will be incorporated for comparison, including:
  - **Encoder-only Models**: E.g., BERT, DistilBERT
  - **Decoder-only Models**: E.g., GPT, DistilGPT
- These models will be benchmarked against the DistilBART baseline to analyze their strengths and limitations in the context of medical dialogue summarization.

---

This framework ensures a comprehensive evaluation of various architectures, paving the way for improving medical note automation.
