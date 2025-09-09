# Phishing Email Detector

A beginner-friendly machine learning project to detect phishing emails. This project uses a publicly available dataset to build a classifier that can identify whether an email is phishing or legitimate.

---

## 📁 Dataset

This project uses the [Email Phishing Dataset](https://www.kaggle.com/datasets/ethancratchley/email-phishing-dataset) from Kaggle.

**Directory structure:**
- `data/raw/` – Original dataset (download from Kaggle)
- `data/processed/` – Preprocessed data ready for ML

---

## ⚙️ Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/hatixntsoa/phishing.email.detector.git
cd phishing.email.detector
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download the Kaggle dataset and place it in `data/raw/`.

4. Open notebooks to explore, preprocess, train, and evaluate models.

---

## 🧪 Usage

* Explore the dataset in `01_data_exploration.ipynb`.
* Train and evaluate models in `02_model_training.ipynb`.
* Use `src/predict.py` to make predictions on new emails.

---

## 📌 Notes

* This project is for **educational purposes only**.
* Ensure that preprocessing in `src/` matches the model’s input format.

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
