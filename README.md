# ⚡ Quick-Note Application

A lightweight single-page web application that allows users to create, view, edit, and delete notes in real time. Built with FastAPI, SQLite, and Vanilla JavaScript with Tailwind CSS.

---

## 🚀 Features

* **Create & Read Notes**: Instantly save notes with highlighted titles and view saved entries dynamically.
* **In-Place Editing**: Edit existing notes directly in the form without creating duplicate records.
* **Delete Functionality**: Remove unwanted notes with a single click.
* **Responsive UI**: Styled with Tailwind CSS and Lucide Icons following a clean 2-column layout.
* **REST API & SQLite**: Fully backed by FastAPI and SQLite (SQLAlchemy ORM).

---

## 🛠️ Tech Stack

* **Backend**: Python, FastAPI, Uvicorn
* **Database**: SQLite (SQLAlchemy ORM)
* **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS (CDN), Lucide Icons

---

## 📁 Project Structure

```text
quick-note-app/
├── main.py          # FastAPI backend & database logic
├── static/
│   └── index.html   # Single-page frontend app
├── .gitignore       # Excludes cache and DB files
└── README.md        # Project documentation
