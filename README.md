# 🐦 TweetFlow

TweetFlow is a simple yet powerful Django web application that allows users to create, manage, and delete tweets. It supports user registration, authentication, and media uploads for tweet images.

## 🚀 Features

- 📝 User Registration & Login
- 🐤 Create, Edit, and Delete Tweets
- 🖼️ Upload Images with Tweets
- 🔒 Secure User Authentication
- 📁 Media & Static Files Handling
- 🎨 Responsive UI with HTML templates

## 📂 Project Structure

```

TweetFlow/
├── manage.py
├── db.sqlite3
├── TweetFlow/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── TwitDesk/
├── models.py
├── views.py
├── urls.py
├── templates/
└── migrations/

````

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (Django Templates)
- **Database**: SQLite (default)
- **Authentication**: Django Auth

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/BitGladiator/TweetFlow.git
   cd TweetFlow


2. **Create and activate a virtual environment**

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the development server**

   ```bash
   python manage.py runserver
   ```

6. **Visit**
   Open [http://localhost:8000](http://localhost:8000) in your browser.

## 🧪 Running Tests

```bash
python manage.py test
```

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

Made with 💻 by [@BitGladiator](https://github.com/BitGladiator)
