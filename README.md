# 🎬 Movie Recommender System

A **content-based Movie Recommender System** that suggests movies similar to a user-selected title using **machine learning techniques**. The project includes an **interactive Streamlit web application** and integrates the **TMDB API** to display movie posters and enhance user experience.

---

## 🚀 Features

* Content-based movie recommendations
* Uses **cosine similarity** for finding similar movies
* Interactive and user-friendly **Streamlit UI**
* Real-time movie posters fetched using **TMDB API**
* Fast and efficient model loading using **Pickle**

---

## 🛠️ Technologies Used

* **Python**
* **Pandas, NumPy**
* **Scikit-learn**
* **Streamlit**
* **TMDB API** (for fetching movie posters and metadata)
* **Pickle** (for saving and loading trained models)

---

## 📂 Project Structure

```
├── app.py                 # Streamlit application
├── notebook.ipynb         # Data preprocessing & model development
└── README.md              # Project documentation

```
---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**

```bash
streamlit run app.py
```

---

## 🧠 How It Works

* Movie metadata is preprocessed and converted into numerical vectors
* **Cosine similarity** is calculated between movies
* The trained similarity model and movie data are stored using **Pickle**
* Based on the selected movie, the system recommends the most similar movies
* **TMDB API** is used to fetch and display movie posters and additional details in real time
* Based on the selected movie, the system recommends the most similar movies

---

## 📌 Future Enhancements

* Add collaborative filtering
* Improve UI/UX design
* Deploy the app on cloud platforms

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 👤 Author

**Preet Solanki**

---

⭐ If you like this project, don’t forget to give it a star!
