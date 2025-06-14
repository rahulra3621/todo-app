# 📝 MyTodo App

A simple and responsive Todo web application built with **Flask**, **Bootstrap 5**, and **SQLite**.  
It allows users to create, update, and delete tasks, with a built-in dark mode toggle and clean UI.

---

## 🚀 Features

- ✅ Add, edit, and delete todo items  
- ✅ Track creation timestamps  
- ✅ Responsive UI with Bootstrap 5  
- ✅ Dark/Light mode toggle (saved in localStorage)  
- ✅ Clean URL structure using Flask routing  
- ✅ Persistent storage using SQLite


---

## 🛠️ Tech Stack

- **Backend**: Python 3, Flask  
- **Frontend**: HTML, Jinja2, Bootstrap 5  
- **Database**: SQLite with SQLAlchemy ORM  

---

## 📁 Project Structure

```
mytodo/
│
├── static/                  # Optional static files
│
├── templates/              # HTML Templates
│   ├── base.html
│   ├── index.html
│   ├── update.html
│   └── about.html
│
├── app.py                  # Main Flask app
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 🧑‍💻 Getting Started

### 🔧 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/mytodo.git
cd mytodo
```

2. **Create and activate a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the app**
```bash
python app.py
```

Visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📌 Routes

| Route       | Description          |
|-------------|----------------------|
| `/`         | Home page (todo list)|
| `/about`    | About page           |
| `/update/<sno>` | Edit a todo       |
| `/delete/<sno>` | Delete a todo     |

---

## 🤝 Contributions

Feel free to fork the repo and submit a pull request with improvements!  
Suggestions and issues are also welcome.

---

## 📃 License

MIT License © 2025 [Rahul Rajput](https://github.com/rahulra3621)
