# QA Self-Learning Chatbot in Python

This repository contains a **self-learning chatbot** built using **Python** and **Natural Language Processing (NLP)** techniques. It can answer frequently asked questions (FAQs) using **TF-IDF vectorization**, **cosine similarity**, and **efficient search mechanisms** such as `faiss`.

## 🚀 Features
- **Natural Language Processing (NLP):** Uses `nltk`, `spacy`, and `textblob` for tokenization, lemmatization, and stopword removal.
- **TF-IDF & Cosine Similarity:** Converts text into numerical vectors and finds the most relevant response.
- **Self-Learning Ability:** Updates its knowledge base by learning from user interactions.
- **Database Storage:** Uses SQLite to store and retrieve FAQs efficiently.
- **Fast Search with FAISS:** Implements **Facebook AI Similarity Search (faiss)** for efficient query matching.

## 📌 Use Cases
1. **Customer Support Automation:** Instantly answers frequently asked questions, reducing human workload.
2. **Educational Assistant:** Acts as a tutor by providing quick answers to student queries.
3. **Knowledge Base Chatbot:** Retrieves precise information from a structured FAQ database.

## 📥 Installation

1. **Clone the repository:**
```sh
git clone https://github.com/Abdus-Sami01/QA-self-learning-chatbot-in-python.git
cd QA-self-learning-chatbot-in-python
```

2. **Install dependencies:**
```sh
pip install -r requirements.txt
```

3. **Download necessary NLP resources:**
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

4. **If using `spacy`, download the language model:**
```sh
python -m spacy download en_core_web_sm
```

## 🛠️ Usage
Open and run the `chatbot.ipynb` Jupyter Notebook:

1. Start Jupyter Notebook:
```sh
jupyter notebook
```
2. Open `chatbot.ipynb` and execute the cells to interact with the chatbot.

## 📚 How It Works

1. **User Input:** The chatbot takes an input query from the user.
2. **Preprocessing:** The input is tokenized, lemmatized, and stopwords are removed.
3. **Vectorization:** The text is transformed using **TF-IDF**.
4. **Similarity Search:** It computes the **cosine similarity** between the user query and stored FAQs.
5. **Database Interaction:** Retrieves the best-matching response from an **SQLite database**.
6. **Learning Module:** The chatbot updates its FAQ database when it encounters a new question.

## 🛠 Dependencies
- `nltk`
- `spacy`
- `numpy`
- `scikit-learn`
- `sqlite3`
- `faiss-cpu`
- `textblob`

## 🤝 Contribution
Feel free to contribute to this project by improving the chatbot’s capabilities or adding new features!

## 📜 License
This project is open-source and available under the **MIT License**.

📌 **Repository Link:** [GitHub](https://github.com/Abdus-Sami01/QA-self-learning-chatbot-in-python)

---
🔹 **Author:** [Abdus Sami](https://github.com/Abdus-Sami01)



## Dependencies
The dependencies are listed in `requirements.txt`.
