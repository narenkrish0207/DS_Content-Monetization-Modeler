# DS_Content-Monetization-Modeler


# YouTube Ad Revenue Predictor

A Streamlit-based web application that estimates YouTube ad revenue using video performance metrics. This tool enables content creators and analysts to quickly forecast potential earnings and understand key factors affecting monetization.

---

## 🚀 Features

### Input key video metrics

* Views
* Likes
* Comments
* Watch Time (minutes)
* Video Length (minutes)
* Subscribers

### Select categorical attributes

* **Category:** Entertainment, Education, Gaming, Music, Technology
* **Device:** Mobile, Desktop, Tablet
* **Country:** US, India, UK, Canada, Other

### Additional Capabilities

* Predicts estimated ad revenue in **USD** using a **Linear Regression model**
* Clean YouTube-themed UI with styled buttons and gradient prediction cards
* Provides suggestions to improve engagement and monetization

---

## 📊 Tech Stack

* Python 3.11
* Streamlit – interactive web UI
* Pandas – data processing
* Joblib – load the trained ML model
* Scikit-learn – Linear Regression for prediction

---

## 🛠 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/venkatgvm/Youtube-ad-revenue-prediction.git
cd Content-Monetization-Modeler
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app

```bash
streamlit run streamlit1.py
```

Use the sidebar to input video metrics and view the predicted ad revenue instantly.

---

## 💡 Tips to Increase Ad Revenue

* Improve watch time and audience retention
* Target regions with higher CPM (e.g., US, UK)
* Encourage likes, comments, and shares to boost algorithm reach

---

## 📂 Project Structure

```bash
Content-Monetization-Modeler/
│
├── streamlit1.py           # Main Streamlit application
├── Linear Regression.pkl   # Pre-trained Linear Regression model
├── requirements.txt        # Dependencies list
└── README.md               # Project documentation
```

---

