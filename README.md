
## 📰 Fake News Detection App

This is a **Streamlit-based web application** that detects whether the input news is **Real** or **Fake** using a trained **Logistic Regression model** and **TF-IDF vectorizer**.

---

## 🚀 Features

- 🧠 Pre-trained ML model using `LogisticRegression`
- ✍️ Custom preprocessing pipeline (removes noise, punctuation, numbers, stopwords)
- 📊 TF-IDF Vectorization for feature extraction
- ✅ Real-time predictions using Streamlit UI
- 💬 Instant feedback on whether input news is **Real** or **Fake**
- ⚠️ Handles edge cases like empty or invalid input

---

## 📁 Project Structure
```
├── app.py                 # Streamlit app
├── vector.pkl             # Pickle file for TF-IDF vectorizer
├── model.pkl              # Pickle file for trained ML model
├── README.md              # This file

````

---

## 🛠️ Requirements

Install the required packages using pip:

```bash
pip install streamlit scikit-learn nltk
````

Also, download NLTK stopwords:

```python
import nltk
nltk.download('stopwords')
```

---

## ▶️ How to Run the App

1. Navigate to the project directory:

```bash
cd "C:\Users\G.S.V.Mohan Kadari\Desktop\Brain O Vision\Project\Programing_Files"
```

2. Run the Streamlit app:

```bash
streamlit run app.py
```

---

## 🧪 Example Usage

* Enter a news headline or paragraph in the text box.
* Click the **Predict** button.
* The app will display one of the following:

  * ✅ "It's Real News"
  * ⚠️ "It's a Fake News"
  * ⚠️ "Please enter proper text" (for empty or invalid inputs)

---

## 📌 Notes

* The model expects valid English text input.
* Avoid using only special characters or numbers.
* The model is trained on a labeled fake/real news dataset (e.g., FakeNewsNet, Kaggle dataset).

## 👨‍💻 Author

**Kadari Giri Surya Venkata Mohan**
Student at Brain-O-Vision AI Program
📧 [gsvmohankadari@gmail.com](mailto:gsvmohankadari@gmail.com)

---

## 📃 License

This project is for educational purposes only.
```

