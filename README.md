🎬 Movie Recommendation System

📌 Overview

This is a content-based Movie Recommendation System built using Python, Pandas, and Scikit-learn. It recommends similar movies based on genres, keywords, cast, and crew using Natural Language Processing (NLP) and Cosine Similarity.

✨ Features

✅ Processes movie dataset from TMDB 5000 Movies and TMDB 5000 Credits.
✅ Extracts relevant information such as genres, keywords, cast, and directors.
✅ Uses text preprocessing (stemming, stopword removal, and vectorization) to create feature vectors.
✅ Computes Cosine Similarity between movies to find similar ones.
✅ Provides movie recommendations based on user input.

🛠 Technologies Used

📌 Python (Programming Language)📌 Pandas (Data Manipulation)📌 NumPy (Numerical Computing)📌 NLTK (Natural Language Processing)📌 Scikit-learn (Machine Learning - CountVectorizer, Cosine Similarity)

🚀 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/movie-recommendation.git
cd movie-recommendation

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Download Dataset

Ensure tmdb_5000_movies.csv and tmdb_5000_credits.csv are placed in the project directory.

4️⃣ Run the Script

python movie_recommendation.py

🎥 How to Use

1️⃣ Run the script and enter a movie name.2️⃣ The system will suggest 5 similar movies.

📌 Example Output

🎬 Movies similar to 'The Dark Knight Rises':
1. The Dark Knight
2. Batman Begins
3. Man of Steel
4. Inception
5. Iron Man

📂 Project Structure

📂 movie-recommendation/
│── 📂 data/
│   ├── 📄 tmdb_5000_movies.csv
│   ├── 📄 tmdb_5000_credits.csv
│── 📂 src/
│   ├── 📜 movie_recommendation.py
│── 📄 README.md
│── 📄 requirements.txt

🌍 Deployment

You can deploy this project on GitHub using the following commands:

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/movie-recommendation.git
git push -u origin main

📜 License

This project is open-source and free to use.

👨‍💻 Author: Your Name

