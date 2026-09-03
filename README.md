# 📚 Library Management Application

A web-based **Library Management Application** built with **Python and Django**. The application provides a simple and efficient way to manage students, books, and book-issue transactions within a library.

The system is designed to help librarians keep track of library resources and monitor which books have been issued to students.

## ✨ Features

The application provides the following core functionality:

* 👨‍🎓 **Student Management** – Add and manage student information.
* 📚 **Book Management** – Add and manage books available in the library.
* 📖 **Book Issuing** – Issue books to specific students.
* 🔄 **Multiple Transactions** – Allow multiple books to be issued to the same student.
* 🗂️ **Organized Records** – Keep student, book, and transaction information organized in one system.

## 🛠️ Tech Stack

* **Python** – Programming language
* **Django** – Web development framework
* **HTML/CSS** – Frontend structure and styling
* **SQLite** – Database for storing application data

## 🚀 Getting Started

Follow the steps below to set up the project locally.

### Prerequisites

Make sure you have the following installed:

* **Python 3**
* **pip**
* **Git**

### 📥 Clone the Repository

Open your terminal and clone the repository:

```bash
git clone https://github.com/owizy/library-management-application.git
```

Navigate into the project directory:

```bash
cd library-management-application
```

## 🐍 Set Up a Virtual Environment

Create a Python virtual environment:

```bash
python3 -m venv venv
```

Activate the virtual environment.

### Linux / macOS

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

## 📦 Install Dependencies

Install Django using pip:

```bash
pip install django
```

If the project includes a `requirements.txt` file, you can install all dependencies with:

```bash
pip install -r requirements.txt
```

## 🗄️ Set Up the Database

Create the required database migrations:

```bash
python manage.py makemigrations
```

Apply the migrations:

```bash
python manage.py migrate
```

## ▶️ Run the Application

Start the Django development server:

```bash
python manage.py runserver
```

The application will be available at:

```text
http://127.0.0.1:8000/
```

Open the address in your web browser to access the application.

## 📂 Project Structure

```text
library-management-application/
│
├── manage.py
├── venv/
├── templates/
├── static/
├── app/
├── db.sqlite3
└── README.md
```

> The exact project structure may vary depending on the Django application configuration.

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve the project:

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes:

```bash
git commit -m "Add your feature"
```

5. Push your branch:

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

## 📄 License

This project is available under the **MIT License**.
