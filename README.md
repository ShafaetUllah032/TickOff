# TickOff
# ⚡ FastAPI To-Do Application Backend

A robust, fully containerized RESTful API backend for a To-Do application built with Python and FastAPI. It implements clean architecture with separate routers, database models, and authentication services.

## 🌟 Key Features
* **JWT Authentication:** Secure user signup, login, and token-based protection (`auth.py`).
* **Admin Controls:** Special administrative routes for managing system data (`admin.py`).
* **Task CRUD:** Full functional endpoints to Create, Read, Update, and Delete todo items (`todos.py`).
* **Relational Database:** SQLite integration using SQLAlchemy ORM (`database.py`, `models.py`).

## 🛠️ Tech Stack
* **Framework:** FastAPI
* **Database:** SQLite (SQLAlchemy ORM)
* **Language:** Python 3.10+

## ⚙️ Getting Started

### Prerequisites
* Python 3.10 or higher installed on your system.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd TO_DO_APP
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install the required packages:**
   *(Note: Make sure to generate your requirements file using `pip freeze > requirements.txt`)*
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the FastAPI development server:**
   ```bash
   uvicorn main:app --reload
   ```

## 🔍 API Documentation & Testing
Once the server is running locally, you can view the automatically generated interactive API docs at:
* **Swagger UI:** [http://127.0.0](http://127.0.0)
* **ReDoc:** [http://127.0.0](http://127.0.0)
