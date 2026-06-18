# POS Tagging Project - ENCS5342

## 📊 Results
- **Accuracy**: 96.69%
- **Macro F1**: 88.15%
- **Micro F1**: 96.69%

## 🛠️ Techniques Used
- BiLSTM with Dropout (0.5)
- Gradient Clipping
- Early Stopping (patience=3)
- Learning Rate Scheduling (ReduceLROnPlateau)
- L2 Regularization (weight_decay=1e-5)

## 📁 Files
- `POS_Tagging_Project.ipynb`: Main Jupyter Notebook with all code and results
- `en-universal-train.conll`: Training dataset
- `en-universal-dev.conll`: Development dataset

## 🚀 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open the notebook: `jupyter notebook POS_Tagging_Project.ipynb`
3. Run all cells

## 👥 Team
- **Aseel Rabee** - 1210627
- **Fatima Zahran** - 1212141
- **Shahd Hammad** - 1212011