# Asset Classification in Houdini Using Machine Learning

This project demonstrates how Machine Learning can be integrated into Houdini pipelines to automate 3D asset classification.  
By training a Logistic Regression model on geometric features, we classify simple 3D assets (spheres vs. torus) to showcase the potential of ML-driven asset management in production.

---

## Process Overview

### Dataset Creation
Generated simple geometric assets (sphere and torus) inside Houdini.

### Feature Engineering
Extracted basic geometric features as training data.

### Model Training
Trained a Logistic Regression model using scikit-learn on the extracted features.

### Model Evaluation
Evaluated performance on a validation set to measure classification accuracy.

---
## Houdini Python Code for Model Inference:
![image](https://github.com/user-attachments/assets/62fe295e-82fa-4c43-be4c-99cca6447870)


---

- **Houdini** — for 3D asset generation and feature extraction.
- **Python** + **scikit-learn** — for machine learning model development.

