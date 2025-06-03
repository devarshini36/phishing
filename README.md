# 🔐 PHISHALERT: Real-Time Detection and Analysis of Malicious URLs

A machine learning-powered web application to detect phishing websites in real time, using advanced feature extraction and a Gradient Boosting classifier.

## 🚀 Features

- Real-time phishing URL detection
- Extracts 30+ features from submitted URLs
- User-friendly web interface built with Flask
- Trained using Gradient Boosting Classifier
- Python-based backend with support for model updates

## 📁 Project Structure

Final_Project/
├── app.py # Main Flask application
├── feature.py # Feature extraction logic
├── phishing.csv # Dataset (if available)
├── pickle/
│ └── model.pkl # Trained ML model (serialized)
├── templates/
│ └── index.html # HTML frontend
├── static/
│ └── styles.css # (Optional) Custom styles
├── venv/ # Python virtual environment (optional)
└── README.md # Project documentation


## 🛠️ Tech Stack

- **Python 3**
- **Flask**
- **scikit-learn**
- **pandas, numpy**
- **BeautifulSoup, requests**
- **whois, dateutil**

## 🧠 Model Details

- **Algorithm**: Gradient Boosting Classifier
- **Input**: 30 handcrafted features extracted from the URL and its metadata
- **Output**: Probability score of phishing risk

## 💻 How to Run


```bash
git clone https://github.com/devarshini36/phishalert.git
cd phishalert
python -m venv venv
venv\Scripts\activate   # On Windows
pip install -r requirements.txt
pip install flask scikit-learn pandas numpy beautifulsoup4 python-whois python-dateutil requests
python app.py



