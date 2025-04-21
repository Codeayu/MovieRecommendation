
# 🎬 AI-Powered Movie Recommendation Engine

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/Codeayu/MovieRecommendation?style=social)](https://github.com/Codeayu/MovieRecommendation)

> ⚡ Stop wasting time deciding what to watch.  
> Let our AI recommend your next favorite movie — in seconds. No user history required.

---

🔗 **[Live Demo](https://movierecommender01.streamlit.app/)**  
📽️ **[Watch the 30-second Demo](https://github.com/Codeayu/MovieRecommendation/tree/main/photos)**

<p align="center">
  <img src="https://github.com/Codeayu/MovieRecommendation/blob/main/photos/1d6dde0cda644f0a89d30547fa44410a.jpg?raw=true" alt="Demo GIF" width="100%" />
</p>
<p align="center">
  <img src="https://github.com/Codeayu/MovieRecommendation/blob/main/photos/275de601ea244f8aa2d3f91b18f5367e.jpg?raw=true" alt="Demo GIF" width="100%" />
</p>
---

## ✨ Features That Make It Shine

- 🔍 **Better than Netflix**: Finds hidden gems, not just what's trending  
- ⚡ **Blazing Fast**: Recommendations in under 2 seconds  
- 🔒 **Privacy First**: No tracking or user data storage  
- 📦 **Offline Capable**: Built-in fallback ensures results even without live API

---

## 🛠️ Tech Stack

| 🧩 Component              | 🚀 Tech Used                       | 📝 Why We Used It                            |
|---------------------------|-------------------------------------|-----------------------------------------------|
| Recommendation Engine     | `Scikit-learn`, `Cosine Similarity` | Powerful similarity detection without ratings |
| Frontend UI               | `Streamlit`                         | Lightweight, beautiful, and super fast        |
| Data & Metadata           | `Pandas`, `TMDB API`                | Live movie details and posters                |
| Persistence & Caching     | `Pickle`, Custom Cache System       | Remembers user preferences, avoids API spam   |

---

## ⚙️ 1-Minute Setup

bash
# 1. Clone this repo
git clone https://github.com/Codeayu/MovieRecommendation.git

# 2. Move into the folder
cd MovieRecommendation

# 3. Run the app
streamlit run app.py


> 💡 **Pro Tip:** Add your TMDB API key in a `.env` file for real-time posters and details.  
> Or use the built-in fallback for offline results!

---

## 🤖 How It Works (in Plain English)

1. Type in a movie you like (e.g., `"Inception"`)  
2. Our model analyzes 50+ features — storyline, genre, keywords, etc.  
3. It finds **5 similar movies** you’ve likely never heard of  
4. You get instant recommendations with posters & ratings from TMDB  

---

## 🤝 Contribute & Collaborate

Want to improve this project? We’d love that!

bash
# Fork → Code → PR → Ship 🚀


🔧 Good first issues:  
- Add a collaborative filtering option  
- Enhance the UI with animation or dark/light toggle  
- Add Hindi/Marathi movie support for regional reach  

---

## 📜 License

This project is licensed under the **MIT License**.  
Use it for your startup, personal projects, or commercial tools!

---

## 🙌 Special Thanks

- 🎞️ [TMDB](https://www.themoviedb.org/) for the movie data  
- ⚙️ [Streamlit](https://streamlit.io/) for the interface  
- 🧠 You, for reading this far and starring ⭐ the project!

---

## 💬 Let’s Connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush%20Chainani-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ayushchainani/)

---

> 👇 **Loved it? Star the repo. Have questions? Open an issue. Want more AI magic? Let’s connect on LinkedIn!**
