# Student Performance & Attendance Management System

A Python-based CLI application to manage student records, track attendance, record marks, generate reports, and predict students at academic risk using Logistic Regression.

---

## Features
- Add and view student records
- Mark daily attendance (Present/Absent)
- Record marks for multiple tests/exams
- Generate attendance reports with pie charts
- View marks summary per student
- Predict students at academic risk using Machine Learning

---

## Tech Stack
- Python
- Pandas
- Scikit-learn (Logistic Regression)
- Matplotlib
- CSV (data storage)

---

## Project Structure
├── main.py          # Entry point, main menu

├── student.py       # Add/view students

├── attendance.py    # Mark and show attendance

├── marks.py         # Add marks/test scores

├── report.py        # Attendance & marks reports with graphs

├── predictor.py     # ML-based risk prediction

├── students.csv     # Student data

├── attendance.csv   # Attendance records

├── marks.csv        # Marks records

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/saumyaambar/your-repo-name
cd your-repo-name
```

2. Install dependencies:
```bash
pip install pandas scikit-learn matplotlib
```

3. Run the application:
```bash
python main.py
```

---

## How It Works
1. Add students with name and roll number
2. Mark attendance date-wise (P/A)
3. Add marks for each test
4. View attendance % with pie chart visualization
5. Predict which students are at risk based on:
   - Attendance below 75%
   - Average marks below 40

---

## ML Model
- **Algorithm:** Logistic Regression (Scikit-learn)
- **Features:** Attendance percentage, Average marks
- **Output:** Safe / At Risk classification per student

---

## Objective
To help teachers monitor student performance and identify at-risk students early using data-driven predictions.
