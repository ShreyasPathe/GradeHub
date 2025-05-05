# 📊 GradeHub

GradeHub is a powerful yet user-friendly result management tool built using **Python** and **Streamlit**. Designed as part of our 5th semester mini project, it aims to simplify the result processing tasks for teachers while allowing students to easily view their individual academic performance.

## 🎯 Project Objective

To eliminate the need for performing complex Excel operations by enabling teachers to upload CSV files and execute multiple result-related operations with a single click. The application also offers seamless data export capabilities and provides students with a dedicated interface to view their results.

---

## 🚀 Features

### For Teachers:
- 🔼 Upload CSV file containing student results.
- ⚙️ Perform one-click data analysis like:
  - Identifying top performers.
  - Filtering pass/fail students.
  - Calculating average scores.
- 💾 Export processed data to:
  - CSV format
  - JSON format

### For Students:
- 🔍 View your individual result securely after it’s published by the teacher.
- 🎯 Access only relevant subject-wise marks and final status (Pass/Fail).

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (Pandas for data handling)
- **Data Format**: CSV (Input), CSV/JSON (Output)

---

## 🧪 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/gradehub.git
   cd gradehub
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the App

bash
Copy
Edit
streamlit run app.py
Usage

Teacher: Upload CSV → Perform analysis → Export data.

Student: Enter credentials (or name/ID) → View results.

📁 Project Structure
bash
Copy
Edit
gradehub/
│
├── app.py              # Main Streamlit application
├── teacher_module.py   # Handles CSV processing and data export
├── student_module.py   # Displays student results
├── requirements.txt    # Python dependencies
└── sample_data.csv     # Sample input file
📌 Future Scope
Authentication and login system for added security.

Graphical result analysis (e.g., bar charts, pie charts).

Database integration for storing results permanently.

Email notifications for students.

👨‍💻 Developed By
Shreyas Pathe

Soham Pashte

Akash Keni

📃 License
This project is part of an academic assignment and is intended for educational purposes only.
