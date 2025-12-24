# Cover Letter AI Assistant (Deep Learning Project)

An end-to-end **NLP application** that helps users write, complete, and analyze cover letters using Transformer-based models. The system combines **BERT fine-tuned classifiers** with a **Qwen causal language model** and exposes the functionality through an **interactive CLI**.

---

## Features
- **Intent Detection**: Fine-tuned BERT model classifies user intent (write, complete, analyze, exit)
- **Cover Letter Generation**: Qwen2.5 causal language model generates personalized cover letters
- **Sentence Auto-Completion**: Continues partial cover letter drafts in a professional tone
- **Cover Letter Analysis**: BERT-based sentence classification (name, skills, education, objective, other)
- **GPU Support**: CUDA-enabled training and inference when available

---

## Tech Stack
- **PyTorch**
- **Hugging Face Transformers & Datasets**
- **BERT (Sequence Classification)**
- **Qwen2.5 (Causal Language Modeling)**
- **Pandas**
- **scikit-learn**
- **CUDA / GPU Acceleration**

---

## How to Run
1. Open `cover_letter_generator.ipynb` in Google Colab or Jupyter
2. Run cells top-to-bottom to install dependencies and train/load models
3. Start the interactive assistant:
   ```python
   interactive_cli()
