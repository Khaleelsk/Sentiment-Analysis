<h1 align="center">🎯 Sentiment Analysis with Logistic Regression</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" alt="Python Version" />
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression-green" alt="Model" />
  <img src="https://img.shields.io/badge/Deployment-Streamlit-orange?logo=streamlit" alt="Deployment" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" alt="Status" />
</p>

---

<h2>📌 Overview</h2>

<p>
This project is focused on analyzing the sentiment of user-generated text using <strong>Logistic Regression</strong>. Given a review or a comment, the model predicts whether it is <span style="color:green"><b>Positive</b></span>, <span style="color:red"><b>Negative</b></span>, or <span style="color:orange"><b>Neutral</b></span>.
</p>

---

<h2>🧠 Features</h2>

<ul>
  <li>🔤 Text Preprocessing (cleaning, stopword removal, stemming)</li>
  <li>🔍 TF-IDF Vectorization</li>
  <li>🧮 Logistic Regression Classifier</li>
  <li>📈 Evaluation using Accuracy, Precision, Recall, F1-Score</li>
  <li>🧑‍💻 Real-time prediction through <b>Streamlit UI</b></li>
</ul>

---

<h2>🛠️ Tech Stack</h2>

<table>
  <tr>
    <td><b>Language</b></td>
    <td>Python</td>
  </tr>
  <tr>
    <td><b>Libraries</b></td>
    <td>pandas, scikit-learn, nltk, streamlit</td>
  </tr>
  <tr>
    <td><b>Model</b></td>
    <td>Logistic Regression</td>
  </tr>
  <tr>
    <td><b>Deployment</b></td>
    <td>Streamlit</td>
  </tr>
</table>

---

<h2>📂 Folder Structure</h2>

<pre>
Sentiment-Analysis/
├── data/                   # Dataset files
├── notebooks/              # Jupyter Notebooks
├── sentiment_model.pkl     # Trained Model
├── vectorizer.pkl          # TF-IDF Vectorizer
├── app.py                  # Streamlit App
├── requirements.txt        # Dependencies
└── README.md               # Project Info
</pre>

---

<h2>⚙️ How to Run</h2>

```bash
# Clone the repo
git clone https://github.com/yourusername/Sentiment-Analysis.git
cd Sentiment-Analysis

# Install dependencies
pip install -r requirements.txt

# Launch the app
streamlit run App.py
```

<h2>🌐 Deployment</h2> 
<p> This project is deployed using <b>Streamlit</b>. You can try it live (https://my-sentiment-analysis.streamlit.app/). </p>
<h2>🚀 Future Enhancements</h2> <ul> <li>🤖 Use of advanced models like BERT, LSTM</li> <li>🌐 Multi-language support</li> <li>💬 Add sentiment confidence score</li> <li>🧱 Enhanced user interface with charts and feedback loop</li> </ul>
<h2>📬 Contact</h2> <p> <b>Khaleel Shaik</b><br> 📧 khaleelsk631@gmail.com <br> 🌐 <a href="https://github.com/Khaleelsk" target="_blank">GitHub Profile</a> </p>
<h3 align="center">✨ Made with ❤️ by Khaleel ✨</h3>
