# Wine Quality Prediction App

A machine learning web app that predicts red wine quality (binary classification) using Streamlit.

![App Screenshot](https://github.com/Bhaathii/wine-quality-app/blob/main/notebooks/ss.png?raw=true)  


## 📁 Dataset Source
- **Dataset**: [Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) from Kaggle
- **Task**: Binary classification (Quality: 0=Average, 1=Excellent)
- **Features**: 11 physicochemical properties (fixed acidity, pH, alcohol content, etc.)

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Bhathii/wine_quality_app.git
   cd wine_quality_app

2. **Create and activate conda environment**:
   ```bash
   conda create -n wine_quality python=3.9
   conda activate wine_quality

3. **Install dependencies:**:
   ```bash
   pip install -r requirements.txt

🚀 How to Run Locally
1. **Train the model (optional)**:

Run notebooks/model_training.ipynb in Jupyter

This generates model.joblib in the root folder

2. **Launch the Streamlit app**:
   ```bash
   streamlit run app.py

The app will open automatically in your browser at http://localhost:8501

**🌟 Features**
Data Exploration: Filter and visualize the dataset

Interactive Visualizations: 3 types of plots (histograms, scatter plots, heatmap)

Quality Prediction: Real-time predictions with probability scores

Model Performance: Accuracy metrics and confusion matrix

**Project Structure**
```wine_quality_app/
├── app.py                # Streamlit application
├── model.joblib          # Trained model
├── requirements.txt      # Dependencies
├── data/
│   └── winequality-red.csv  # Dataset
└── notebooks/
    └── model_training.ipynb # Training code
```





















