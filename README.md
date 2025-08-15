# 🩺 Medical Image Classification

This project is a deep learning-based medical image classifier designed to identify multiple disease categories from X-ray or medical imaging data. It uses a fine-tuned model with transfer learning to achieve high accuracy while keeping the model lightweight and efficient.

## Dataset

The dataset consists of labeled medical images for multi-class classification.  
Each image belongs to one of the disease categories or the healthy class.  
The dataset is split into training, validation, and testing sets for fair performance evaluation.

## How to Use

1. Clone this repository.
2. Place the dataset in the appropriate `train/`, `val/`, and `test/` folders.
3. Open the `medical_classification_code.ipynb` notebook in Google Colab or Jupyter and run the cells.

## Requirements

- Python 3.x  
- PyTorch  
- torchvision  
- scikit-learn  
- NumPy  
- Pandas  
- Matplotlib  

Install dependencies:

```bash
pip install torch torchvision scikit-learn numpy pandas matplotlib
```

## Results

| Metric    | Value    |
|-----------|----------|
| Accuracy  | 97.54%   |
| Precision | 96.60%   |
| Recall    | 97.50%   |
| F1-score  | 97.54%   |

### If you need the trained model weights (medical_classification.pth), feel free to email me at:
📧 k.prabhav2005@gmail.com
