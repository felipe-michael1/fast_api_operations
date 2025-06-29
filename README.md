# 📊 fast_api_operations

A lightweight and efficient API built with **FastAPI** for performing basic mathematical operations. This project provides a simple and fast way to access common arithmetic functions via HTTP endpoints.

## 🚀 Features

- 🧮 Addition, subtraction, multiplication, and division
- ⚡ High performance powered by FastAPI
- ✅ Input validation and error handling with Pydantic
- 🔄 JSON-based requests and responses

## 📌 Example Endpoints

- `POST /add` → `{"a": 5, "b": 3}` → `{"result": 8}`
- `POST /subtract` → `{"a": 10, "b": 4}` → `{"result": 6}`
- `POST /multiply` → `{"a": 2, "b": 3}` → `{"result": 6}`
- `POST /divide` → `{"a": 10, "b": 2}` → `{"result": 5}`

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fast_api_operations.git
cd fast_api_operations
```

### 2.Create a virtual environment (optional but recommended)

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
uvicorn main:app --reload
```

