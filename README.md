# Skin_Cancer_Detection
This repository contains code, data, and final figures for a skin cancer classification project using convolutional neural networks (CNNs) and dermatoscopic image analysis.

**Developers:** Lily Ellis, Ava Ferrentino, Lily Saada, and Olivia Matlaga

Inspired by research and applications of deep learning in medical imaging, this project explores automated skin cancer detection using TensorFlow/Keras.

---
We used the [Skin Cancer - 9 Classes (ISIC) dataset](https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic) from Kaggle.
Before running the notebook, upload your `kaggle.json` API key file when prompted (you can generate this from your Kaggle account settings).
You do **not** need to manually download the dataset.  
Before running the notebook, simply upload your `kaggle.json` API key file when prompted.  
*You can generate this from your Kaggle account settings under “API” > Create New Token.*

The FinalSkinClassification.ipynb is our final version.

---
**Figures:**

All figures in this notebook were generated using Python and matplotlib, primarily for data exploration and model interpretability. The following types of visualizations are included:

- Sample Images by Class: One representative image from each of the 9 skin cancer classes was plotted by unbatching the training dataset and selecting a single image per class.

- Clean vs Adversarial Comparisons: For each class, both the original (clean) and adversarially perturbed images were loaded from disk and displayed side-by-side to visualize the effects of adversarial attacks.

- Bar Charts: Class distributions and accuracy metrics for the two models on clean and adversarial data were visualized using matplotlib.pyplot to better understand dataset imbalances and model behavior.

These plots support reproducibility and visual diagnostics during model development.

---

**References:**

Harsoor, S. (2023). Skin Cancer Detection [Code notebook]. Kaggle. https://www.kaggle.com/code/sharanharsoor/skin-cancer-detection

nodoubttome. (2019). Skin Cancer9 Classes ISIC [Data set]. Kaggle. https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic

OpenAI. (2025, May 4). ChatGPT response to coding questions [Large language model]. https://chat.openai.com/
