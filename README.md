# 🎬 Movie Recommender System

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)


A content-based movie recommendation system built using **Python**, **Machine Learning**, and **Streamlit**. This application recommends movies similar to the one selected by the user and displays their posters using the TMDB API.

---

## 📌 Features

- 🎥 Content-based movie recommendations
- 🧠 Cosine similarity-based recommendation engine
- 🖼️ Movie posters fetched dynamically from TMDB API
- ⚡ Interactive web interface built with Streamlit
- 📚 Simple and user-friendly UI

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- TMDB API

---

## 🎯 Skills Demonstrated

- Content-Based Recommendation Systems
- Cosine Similarity
- Feature Engineering
- Data Preprocessing
- API Integration
- Deployment
- Python Development
  
---
## 📚 Dataset

The project uses the TMDB 5000 Movies Dataset for generating movie recommendations.

---
## 📂 Project Structure

```
movie-recommender-system/
│
├── app.py
├── movie_dict.pkl
├── movies.pkl
├── similarity.pkl
├── requirements.txt
├── setup.sh
├── Procfile
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Ama-an-nu/movie-recommender-system.git
```

Navigate to the project directory

```bash
cd movie-recommender-system
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment

### macOS/Linux

```bash
source .venv/bin/activate
```

### Windows

```bash
.venv\Scripts\activate
```

Install the dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 🔑 TMDB API

This project uses **The Movie Database (TMDB) API** to fetch movie posters.

Get your API key from:

https://www.themoviedb.org/settings/api

Replace your API key inside:

```python
fetch_poster(movie_id)
```

---

## 📊 How It Works

1. User selects a movie.
2. The application finds the movie index.
3. Cosine similarity scores are calculated.
4. Top 5 similar movies are selected.
5. Movie posters are fetched using the TMDB API.
6. Recommendations are displayed on the Streamlit interface.

---

## 📸 Screenshots


---

## 📈 Future Improvements

- User authentication
- Hybrid recommendation system
- Genre and language filters
- Movie trailers
- Ratings and reviews
- Search suggestions
- Deploy using Docker

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is intended for educational and portfolio purposes.

---

## 👨‍💻 Author

**Amaan Danishi**

GitHub: https://github.com/Ama-an-nu

LinkedIn: https://www.linkedin.com/in/amaan-danishi-6a94a4372/

---

⭐ If you found this project useful, don't forget to **Star** the repository!
