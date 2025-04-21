# Evaluating Large Language Models for Automated Code Comment Generation
This project explores how different Large Language Models (LLMs) like CodeT5, StarCoder, PolyCoder, and Llama 3.2 perform in generating or refining code comments. It focuses on zero-shot and one-shot prompting without fine-tuning, using real-world datasets.
I tested these models on the CodeSearchNet (Python) and CoNaLa datasets using prompts like 'Explain the following code:' to measure how well they can generate useful, accurate, and human-like comments out-of-the-box.
Datasets Used:
- CodeSearchNet (Python subset)
- CoNaLa (Python)
Models Tested:
- CodeT5
- StarCoder
- PolyCoder
- Llama 3.2 (Zero-shot and One-shot)
Evaluation Metrics:
- BLEU-2
- ROUGE-1, ROUGE-2, ROUGE-L
- METEOR
- Cosine Similarity (semantic alignment)
Key Findings:
- Code-specific models (like StarCoder) performed better in lexical similarity.
- Llama 3.2 improved significantly with one-shot prompting.
- Cosine similarity and METEOR revealed semantic strength even in models with lower lexical scores.
- One-shot prompts help general models mimic code-specific patterns.
