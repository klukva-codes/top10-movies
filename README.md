# 🎬 My Top 10 Movies (Flask App)

A stylish and interactive movie ranking app built with Flask and SQLAlchemy.  
Users can add movies, edit ratings and reviews, and delete entries — all from a beautifully animated interface.

---

## 🚀 Features

- Add movies by title (API fetch or manual input)
- Display your favorite movies with ranking, posters, ratings, and reviews
- Edit rating and review inline
- Delete movies
- Responsive animated UI with card flipping effect

---

## 🛠️ Tech Stack

- **Backend:** Flask, SQLAlchemy, Flask-WTF
- **Frontend:** Bootstrap, custom CSS animations
- **Database:** SQLite
- **APIs Used:** [OMDb API](https://www.omdbapi.com/) or TMDb (if implemented)

---

## ▶️ How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Launch the app:

```bash
python main.py
```

3. Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser

---

## 📂 Project Structure

```
top10_movies/
├── main.py
├── movies.db
├── requirements.txt
├── static/
│   └── css/
│       └── styles.css
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── add.html
│   ├── edit.html
│   └── select.html
└── README.md
```


