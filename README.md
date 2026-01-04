# Fine-Tuning a Transformer Model for Text Classification

## Overview
This project demonstrates fine-tuning a pretrained transformer-based language model for supervised text classification. It highlights practical use of transfer learning, training optimization, and evaluation workflows using modern NLP libraries.

The task is binary sentiment classification using the IMDB movie reviews dataset, a standard benchmark in NLP research.

---

## Model and Dataset
- **Model:** DistilBERT (`distilbert-base-uncased`)
- **Dataset:** IMDB Movie Reviews
- **Task:** Binary sentiment classification (positive / negative)

DistilBERT is chosen for its balance between performance and computational efficiency.

---

## Training Pipeline
1. **Tokenization**
   - Text data is tokenized with padding and truncation using the model tokenizer.

2. **Fine-Tuning**
   - The pretrained model is fine-tuned using the Hugging Face Trainer API.

3. **Evaluation**
   - Model performance is evaluated using accuracy on a validation dataset.

Training is performed on Google Colab with GPU acceleration.

---

## Technologies Used
- Python  
- PyTorch  
- Hugging Face Transformers  
- Hugging Face Datasets  
- Evaluate library  
- Google Colab (GPU)

---

## How to Run
1. Open `.ipynb` in Google Colab  
2. Enable GPU support  
3. Run all cells sequentially  
4. Test the model with custom text inputs  

---

## Key Learning Outcomes
- Practical transformer fine-tuning  
- Transfer learning for NLP tasks  
- Model evaluation and experimentation  
- Efficient training using cloud GPUs  

---

## Future Extensions
- Multi-class sentiment classification  
- Additional metrics (F1-score, precision, recall)  
- Domain-specific fine-tuning  
- Model comparison and ablation studies  
