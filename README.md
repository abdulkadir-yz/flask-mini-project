# Flask Mini Project — User Registration App

A simple web application built with **Flask** and **PostgreSQL (Neon)**.  
Users can register with a username and email, and view all registered users.

---

## Tech Stack

- **Python 3.13**
- **Flask** — Web framework
- **SQLAlchemy** — ORM (Object Relational Mapper)
- **PostgreSQL** — Database (hosted on [Neon](https://neon.tech))
- **Jinja2** — HTML templating
- **python-dotenv** — Environment variable management

---

## Features

- Register a new user (username + email)
- List all registered users
- Duplicate email validation
- PostgreSQL integration via SQLAlchemy ORM

---

## Project Structure

```
flask_mini_project/
├── app.py              # Main application — routes and logic
├── models.py           # Database models (SQLAlchemy)
├── templates/
│   ├── base.html       # Base template
│   ├── index.html      # Registration form
│   └── users.html      # User list
├── .env.example        # Example environment variables
├── .gitignore
└── requirements.txt
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/flask-mini-project.git
cd flask-mini-project
```

### 2. Create and activate virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

Create a `.env` file in the root directory:

```
DATABASE_URL=your_neon_postgresql_connection_string
```

> Get your connection string from [neon.tech](https://neon.tech)

### 5. Run the application

```bash
python app.py
```

Open your browser at `http://127.0.0.1:5000`

---

## What I Learned

- How Flask handles HTTP requests and responses
- Connecting a Python web app to a cloud PostgreSQL database
- ORM concepts with SQLAlchemy (models, sessions, queries)
- Template inheritance with Jinja2
- Separating secrets from code using environment variables

---

## Author

**Abdulkadir Yılmaz**  
Backend Developer in training | .NET & Python  
[LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
