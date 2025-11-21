# 📊 CSV Summary Generator Web Application (Flask + Python)

A lightweight web application that allows users to upload a CSV file and automatically generates a complete summary of the dataset.

## 🚀 Features
- Upload CSV from browser
- Automatic decoding
- HTML summary report
- Downloadable CSV summary
- Numeric, categorical, and correlation reports

## 🛠 Technologies Used
- Python 3.x
- HTML
- CSS
- Flask
- pandas
- numpy
- matplotlib

## 📁 Project Structure
```
csv_app/
│── csv_flask.py
│── README.md
│── doc ai project.docx
│── ppt ai project.pptx
│── source code.txt 
```

## 📂 Recommended GitHub Repository Structure
```
csv-summary-app/
│
├─ backend/
│  ├─ src/
│  │  └─ csv_flask.py
│  ├─ venv/                # Do NOT upload to GitHub
│  └─ requirements.txt
│
├─ docs/
│  ├─ Submission_Document.docx
│  └─ CSV_Project_Submission_PPT.pptx
│
├─ screenshots/
│  ├─ home.png
│  └─ summary.png
│
└─ README.md
```

---

## ▶️ Running the Project (FINAL WORKING COMMANDS)

### 1️⃣ Go to project folder
```powershell
cd "C:\Users\saket\OneDrive\Desktop\csv_app"
```

### 2️⃣ Create virtual environment
```powershell
python -m venv venv
```

### 3️⃣ Activate environment
```powershell
.env\Scripts\Activate.ps1
```

### 4️⃣ Install dependencies
```powershell
pip install --upgrade pip
pip install flask pandas numpy matplotlib
```

### 5️⃣ Run application
```powershell
python csv_flask.py
```

### 6️⃣ Open in browser
```
http://127.0.0.1:5000/
```

---

## 📡 Upload via cURL (Optional)
```bash
curl -o summary.csv -F "file=@yourfile.csv" "http://127.0.0.1:5000/upload?format=csv"
```

---

## 🤝 Contributing
Open issues and submit PRs to enhance the project.

## 📜 License
This project is intended for educational use.
