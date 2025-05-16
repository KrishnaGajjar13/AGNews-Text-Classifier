# AG News Classification with BERT

This project demonstrates fine-tuning BERT for news topic classification on the AG News dataset. It covers the full pipeline: data preprocessing, model training, evaluation, ONNX export, and inference.

## Features

- Fine-tune BERT (`bert-base-uncased`) for text classification
- Evaluate performance with accuracy and confusion matrix
- Export the trained model to ONNX for efficient inference
- Example ONNX inference pipeline

## Dataset

- **AG News**: A large-scale dataset for news categorization with four classes: World, Sports, Business, Sci/Tech.

## Getting Started

### 1. Clone the Repository

```bash
git clone [https://github.com/yourusername/bert-agnews.git](https://github.com/KrishnaGajjar13/AGNews-Text-Classifier.git)
cd bert-agnews
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

Or, for ONNX export:

```bash
pip install optimum[exporters] onnxruntime
```

### 3. Download the Fine-Tuned Model

[Download the fine-tuned model here.]([#](https://www.kaggle.com/models/krishnagajjar1311/bert-news-text-classifier)) <!-- Insert your model download link here -->

### 4. Training

You can run the notebook `bert-agnews.ipynb` to train and evaluate the model.

### 5. Export to ONNX

The notebook includes steps to export the model to ONNX format using Optimum.

### 6. Inference

Perform inference on new texts using the exported ONNX model, as shown in the notebook.

## Project Structure

```
AGNEWS/
├── bert-agnews.ipynb      # Main notebook with all steps
├── README.md              # Project documentation
├── requirements.txt       # Python dependencies
├── model.onnx             # (Optional) Exported ONNX model
└── results/               # Training outputs and checkpoints
```

## Citation

If you use this project, please cite the original [AG News dataset](https://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html) and [BERT paper](https://arxiv.org/abs/1810.04805).

---

**Author:** [Your Name]  
**License:** MIT

