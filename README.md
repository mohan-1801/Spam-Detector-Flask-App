#  Spam Detector - Flask Web App

- A modern, dark-themed **Spam Detection** web app built using **Flask**, **Naive Bayes**, and **Scikit-learn**.  
It classifies input messages as either **Spam** or **Not Spam** using a trained machine learning model.

---

## 🚀 Features

- ⚙️ Built with Python & Flask
- 🎨 Stylish dark theme with animated UI
- 🧠 Trained spam classification model using Naive Bayes
- 🔍 Real-time prediction from user input
- 💾 Secure and lightweight



---

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/mohan-1801/spam-detector-flask-app.git
cd spam-detector-flask-app
```
### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows

```
### 3. Install dependencies

```bash
pip install flask scikit-learn
```
### 4. Add your trained model files
   #### - Place your model.pkl and vectorizer.pkl in the project root directory.(These files are not included in the repo because they are ignored by .gitignore)

### 5. Run the application
```bash
python app.py
```
### 🧠 How It Works
- The model is trained on SMS messages using Naive Bayes.
- Input is vectorized using a TfidfVectorizer or similar.
- Model predicts:

   - 1 → Spam

  - 0 → Not Spam

- Output is shown instantly on the web interface.

 ### 📦 Dependencies
- Flask
- Scikit-learn
- HTML & CSS


