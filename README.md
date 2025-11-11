# Breast Cancer Detection using Deep Learning

A machine learning system for breast cancer detection using EfficientNetB0 and transfer learning on mammography images.

##  Results
- **Accuracy**: 56.4%
- **Dataset**: 2,864 medical images (CBIS-DDSM)
- **Model**: EfficientNetB0 with transfer learning
- **Key Finding**: Identified class imbalance causing model bias (59% benign vs 41% malignant)

##  Quick Start (Google Colab)
1. Upload `HealthAi.ipynb` to [Google Colab](https://colab.research.google.com/)
2. **Kaggle API Setup Required**:
   - Get your Kaggle API key from https://www.kaggle.com/settings
   - Upload `kaggle.json` when prompted in the notebook
3. Run all cells sequentially
4. The notebook will automatically install dependencies and download the dataset

