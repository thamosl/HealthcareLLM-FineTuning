# 🏥 Healthcare LLM Fine-Tuning using BERT

A Natural Language Processing (NLP) project that fine-tunes a **BERT (Bidirectional Encoder Representations from Transformers)** model for **healthcare sentiment classification** using the Hugging Face Transformers library.

The project demonstrates the complete machine learning workflow, including data preprocessing, text tokenization, dataset preparation, model training, evaluation, and saving the fine-tuned model for future inference.

---

## 📌 Project Overview

Healthcare organizations receive thousands of patient reviews and feedback messages. Manually analyzing these reviews is time-consuming and inefficient.

This project automates the process by fine-tuning a pre-trained **BERT** model to classify healthcare-related text into sentiment categories.

---

## ✨ Features

* Data cleaning and preprocessing
* Text tokenization using Hugging Face Tokenizer
* Dataset splitting (Training, Validation, Testing)
* Fine-tuning a pre-trained BERT model
* Model evaluation using Accuracy and F1 Score
* Save the trained model for deployment
* End-to-end NLP workflow in a Jupyter Notebook

---

## 🛠️ Technologies Used

* Python
* Pandas
* Regular Expressions (Regex)
* Scikit-learn
* Hugging Face Transformers
* Hugging Face Datasets
* PyTorch
* Jupyter Notebook

---

## 📂 Project Structure

```
HealthcareLLM-FineTuning/
│
├── HealthcareLLM-FineTuning.ipynb
├── fine-tuned-bert/
│   ├── config.json
│   ├── tokenizer files
│   ├── model weights
│   └── ...
├── requirements.txt
└── README.md
```

---

## ⚙️ Workflow

1. Load healthcare text dataset
2. Clean and preprocess text
3. Tokenize using BERT tokenizer
4. Split data into training, validation, and test sets
5. Convert data into Hugging Face Dataset format
6. Load pre-trained BERT model
7. Fine-tune the model
8. Evaluate model performance
9. Save the trained model

---

## 📊 Evaluation Metrics

The model is evaluated using:

* Accuracy
* F1 Score

These metrics provide a balanced evaluation of classification performance.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/thamosl/HealthcareLLM-FineTuning.git
```

Navigate to the project directory:

```bash
cd HealthcareLLM-FineTuning
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the notebook:

```bash
jupyter notebook HealthcareLLM-FineTuning.ipynb
```

Run the notebook cells sequentially to:

* Prepare the dataset
* Train the BERT model
* Evaluate performance
* Save the fine-tuned model

---

## 📈 Future Improvements

* Train on larger healthcare datasets
* Support multi-class sentiment classification
* Hyperparameter tuning
* Deploy using Flask or FastAPI
* Build a web interface using Streamlit
* Integrate with electronic health record (EHR) systems

---

## 🤝 Contributions

Contributions, feature requests, and suggestions are welcome. Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Thamotharan**

B.Tech – Artificial Intelligence & Data Science

Interested in Machine Learning, NLP, Data Analytics, and Generative AI.
