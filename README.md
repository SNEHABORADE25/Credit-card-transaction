Credit Card Transaction Analysis

Output 1:

<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/6a41d304-7653-48ee-8f69-2f4ebd3bae3d" />

Output 2:

<img width="1916" height="1015" alt="image" src="https://github.com/user-attachments/assets/1a5a50d1-ecad-4aa2-8041-23fb9a161517" />

Output 3:

<img width="1903" height="1017" alt="image" src="https://github.com/user-attachments/assets/211af2f9-89b0-4bba-b08a-474ca7c85bb5" />

Output 4:

<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/89da3a96-bec8-4508-8d49-c77ea0c12f26" />

Output 5:

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/93f7a2dd-1103-423a-8cce-55c82c7b7fe1" />

Overview

This project demonstrates how to use MLflow for tracking, managing, and visualizing Machine Learning experiments.
With MLflow, you can easily log parameters, metrics, artifacts, and models, enabling reproducibility and efficient model comparison.

https://mlflow.org/img/hero.png

🚀 Features

📊 Experiment Tracking – Log metrics, parameters, and artifacts.

📂 Model Registry – Save and manage different versions of models.

🔄 Reproducibility – Ensure experiments can be repeated with the same results.

📈 Visualization – Interactive UI to compare model performance.

🔌 Integration – Works with scikit-learn, TensorFlow, PyTorch, and custom ML code.

🛠️ Tech Stack

Language: Python

ML Library: scikit-learn / TensorFlow / PyTorch (as per your use)

Tracking Tool: MLflow

Data Handling: Pandas, NumPy

📦 Installation
# Clone the repository
git clone https://github.com/yourusername/your-repo.git
cd your-repo

# Install dependencies
pip install -r requirements.txt

▶️ Usage
# Run MLflow UI
mlflow ui


Then, open http://127.0.0.1:5000 in your browser to view experiment logs.

📂 Folder Structure
project/
│── data/           # Dataset
│── notebooks/      # Jupyter notebooks
│── src/            # Source code for training
│── mlruns/         # MLflow experiment logs
│── requirements.txt
│── README.md

📊 Example MLflow Output

After training, MLflow logs:

Parameters: learning rate, batch size, etc.

Metrics: accuracy, precision, recall, etc.

Artifacts: model files, plots, confusion matrices.
