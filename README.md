
---

# 👨‍💼 Mentor Sync — Office Employee Management System

**Mentor Sync** is a Django-based web application designed to efficiently manage office employees. It offers features to **view**, **add**, **remove**, and **filter** employees through a clean, responsive, and user-friendly interface powered by **Bootstrap**.

---

## 🔧 Features

* **🔍 View Employees** – See all employees in a structured table with key details.
  
* **➕ Add Employee** – Add new staff using a Bootstrap-powered input form.
 
* **❌ Remove Employee** – Remove an employee via a dropdown selector.
 
* **🔎 Filter Employees** – Search by name, department, or role with a simple form.

---

## 📁 Project Structure

```
Office-Sync/
├── manage.py
├── db.sqlite3
├── README.md
├── venv/
├── offc_emp_proj/          # Django project settings
│   ├── settings.py
│   └── urls.py
└── emp_app/                # Core app
    ├── models.py
    ├── views.py
    ├── urls.py
    └── templates/
        ├── index.html
        ├── add.html
        ├── view.html
        ├── remove.html
        └── filter.html
```

---

## 💻 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, Bootstrap
* **Database:** SQLite3

---

## 🛠️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Office-Sync.git
   cd Office-Sync
   ```

2. **Create and Activate Virtual Environment**

   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install Dependencies**

   ```bash
   pip install django
   ```

4. **Apply Migrations**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the Development Server**

   ```bash
   python manage.py runserver
   ```

6. **Open in Browser**

   ```
   http://127.0.0.1:8000/
   ```

---

## 🙌 Contributions

Pull requests are welcome! If you'd like to enhance the UI, add more filters, or extend functionality feel free to fork the repository and contribute.

---

