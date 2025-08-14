

---

# 🚀 Step 2: Source Code Repository with Setup Instructions ⏳

## 💼 Resume Generator App

A **Streamlit web app** that generates professional **ATS-friendly resumes** in **DOCX** and **PDF** formats using **OpenRouter API** and Python libraries.

---

## 🛠 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Moraka1952/resume-generator-app.git
cd resume-generator-app
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up API Keys

* Replace your **OpenRouter API key** in `app.py` with your own:

```python
API_KEY = "your_openrouter_api_key_here"
```

> ⚠️ **Important:** Never share your API key publicly.

### 5️⃣ Run the App Locally

```bash
streamlit run app.py
```

* The app will open in your default browser automatically.

---

## 🎯 How to Use the App

1. Fill in **personal details** in the sidebar.
2. Add **work experience**, **education**, **skills**, and **target job description**.
3. Click **Generate Resume**.
4. Download your resume as **DOCX**,**HTML** or **PDF**.

---

## 💡 Notes

* Ensure you have a stable **internet connection** for API requests.
* Tested on **Python 3.11** and **Streamlit 1.48.0**.
* For best results, enter **complete and accurate details** in the sidebar fields.

