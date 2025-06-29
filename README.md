![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-D00000?style=for-the-badge&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge&logo=plotly&logoColor=white)

# 🌾 Pollen Grain Classification using Deep Learning & AI

A deep learning project for accurate and lightweight classification of pollen grain images.

---

## 📊 Dataset

- **Source:** [Kaggle: Pollen Grain Image Classification](https://www.kaggle.com/datasets/andrewmvd/pollen-grain-image-classification)
- Contains labeled images of various pollen species.

---

## 🧠 Structure 

POLLEN_GRAIN/
├── data/                             # Dataset files (CSV, images, etc.)
│
├── flask/
│   ├── static/                       # CSS, JS, and frontend assets
│   ├── templates/                    # HTML templates
│   │   ├── index.html                # Homepage for image upload
│   │   ├── prediction.html           # Page showing prediction results
│   │   └── logout.html               # Logout/session end page
│   └── .ipynb_checkpoints/           # Jupyter auto-saves (can be ignored)
│
├── uploads/                          # Uploaded images for prediction
│
├── app.py                            # Flask server entry point
├── model.h5                          # Trained CNN model (Keras format)
├── cnn.hdf5                          # Older/alternative model checkpoint
├── pollen_grain_classification.ipynb # Jupyter notebook for training/testing
└── requirements.txt                  # Required Python packages

             
---

## 🔍 Objective

- Identify and classify pollen grain types using deep learning.
- Build a deployable, efficient model.
- Visualize predictions and evaluate performance (accuracy, confusion matrix).

---

## 📈 Results

- **Accuracy:** ~90%
- **Confusion Matrix:** See [`notebooks/pollen-grain.ipynb`](notebooks/pollen-grain.ipynb)
- Real-time prediction via Flask web UI.

---

## 🧪 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV / PIL
- Scikit-learn
- Pandas, NumPy
- Flask

---

## 📜 License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

---

**Thanks to SmartBridge for this deep learning project on ai !**



