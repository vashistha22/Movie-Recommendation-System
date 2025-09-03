# 🎬 Movie Recommendation System  

An academic project implementing **Content-Based** and **Collaborative Filtering** techniques for Movie Recommendation using **Streamlit**.  

---

## 📖 Project Overview  
This project demonstrates the practical application of recommender systems in **information retrieval and personalization**.  
We designed a movie recommendation engine that suggests movies based on:  

1. **Content-Based Filtering** → Uses movie metadata (like genre, description, cast).  
2. **Collaborative Filtering** → Uses user-movie interaction data to find patterns and similarities.  

---

## 📂 Dataset  
- **Movie Metadata Dataset** (from TMDB or MovieLens)  
- Contains features like:  
  - Movie Title  
  - Genres  
  - Overview/Description  
  - Cast & Crew  
  - Ratings  

---

## 🛠️ Approach  

### 1. Content-Based Filtering  
- Used **TF-IDF Vectorization** on movie overviews.  
- Calculated **cosine similarity** between movies.  
- Recommended top-N movies most similar to the selected one.  

### 2. Collaborative Filtering  
- Implemented **Matrix Factorization (SVD)** using Surprise library.  
- Predicted user preferences for unseen movies.  
- Recommended movies based on predicted ratings.  

---

## 📊 Results  
- **Content-Based**: Provides recommendations closely related in theme/genre.  
- **Collaborative Filtering**: Learns user preference patterns, providing personalized suggestions.  

---

## 📁 Repository Contents  
- `app.py` → Streamlit web app code  
- `requirements.txt` → List of dependencies  
- `README.md` → Project documentation  

---

## ▶️ Running the Project Locally  

1. Clone this repository:  
   git clone https://github.com/vashistha22/Movie-Recommender-System.git
   cd Movie-Recommender-System
2. Install dependencies:
   pip install -r requirements.txt
3. Run the Streamlit app:
   streamlit run app.py

## 👨‍🎓 Author
Vashistha Pankaj

📧 Email: vashistha22@iitk.ac.in

🔗 LinkedIn: (https://www.linkedin.com/in/vashistha021/)
  
