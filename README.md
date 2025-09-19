# 🚢 Titanic Survival Prediction (Machine Learning Project)

## 📌 Overview
This project predicts passenger survival on the Titanic using **Machine Learning**.  
It includes:
- A **Jupyter Notebook** (`titanic_notebook.ipynb`) with explanations, preprocessing, model training & evaluation.
- A **script version** (`script.py`) for quick execution.
- Cleaned structure to make it **GitHub-ready**.

The dataset used is the **Titanic dataset from Kaggle**.

---

## 📂 Project Structure
```
task1_titanic/
│── data/                  # place titanic.csv here
│── titanic_notebook.ipynb # main notebook with code + outputs
│── script.py              # run the pipeline directly
│── requirements.txt       # required dependencies
│── README.md              # project documentation
```

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/task1_titanic.git
cd task1_titanic
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run Notebook (Recommended)
1. Open `titanic_notebook.ipynb` in **Jupyter** or **Google Colab**.
2. Upload the Titanic dataset (`titanic.csv`) to the `data/` folder.
3. Run all cells to see preprocessing, training, and evaluation.

### Run Script
```bash
cd task1_titanic
python script.py
```

---

## 📊 Models & Results
- Logistic Regression
- Random Forest
- XGBoost

**Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

📈 Best-performing model: **Random Forest (~82% accuracy)** on validation data.

---

## 🎥 Demo
You can check the notebook run-through by executing on **Google Colab** or locally and recording the outputs.

---

## 📚 Dataset
Dataset available at [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

---

## 🤝 Contributing
Feel free to fork this repo, raise issues, and submit pull requests.

---

## 📜 License
This project is licensed under the MIT License.
