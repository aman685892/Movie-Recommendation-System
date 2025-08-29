 🎬 Movie Recommendation System

 Overview
A content-based recommendation system that suggests similar movies 
based on their description, genres, keywords, and cast.

 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Cosine Similarity

 How It Works
1. Load dataset (TMDB 5000 movies).
2. Process text data (overview, genres, cast).
3. Convert text to vectors using CountVectorizer.
4. Calculate similarity between movies using Cosine Similarity.
5. Recommend top 5 similar movies.

 Example Output
Input: `Avatar`  
Output:  
- Beowulf  
- Apollo 18  
- Tears of the Sun  
- The American  
- Aliens vs Predator: Requiem  

 Future Improvements
- Add deep learning model (using embeddings).
- Create a simple web app using Streamlit.

---
👨‍💻 Made by [Aman Gupta](https://github.com/aman685892)
