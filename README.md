# 🏥 Patient Management API (FastAPI)

A simple RESTful API built with **FastAPI** to manage patient records including BMI and health status. It supports creating, reading, updating, deleting, and sorting patient data.

---

## 🚀 Features

- Add a new patient with automatic BMI calculation.
- View all or individual patient records.
- Edit or delete existing patients.
- Sort patients by height, weight, or BMI.
- JSON-based lightweight data storage.

---

## 📁 Project Structure
├── main.py # FastAPI application code
├── patients.json # Local JSON storage for patient data
├── requirements.txt # Python dependencies
├── Dockerfile # For containerized deployment
└── README.md # Project documentation

---

## 🧪 Example Patient Record

```json
{
  "id": "P001",
  "name": "Ananya Verma",
  "city": "Guwahati",
  "age": 28,
  "gender": "female",
  "height": 1.65,
  "weight": 90.0,
  "bmi": 33.06,
  "verdict": "Obese"
}
