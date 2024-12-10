🎥 Movie Recommender System

A content-based movie recommendation app built with Streamlit and powered by TMDb API for fetching movie posters.

🚀 Features

Recommends 5 movies based on user-selected titles.
Displays movie posters dynamically using TMDb API.
Interactive and simple user interface.

🛠️ Technologies

Python, Streamlit, TMDb API, Machine Learning, Pickle

🌟 How to Run

Clone this repository:

bash
Copy code
git clone https://github.com/your-username/movie-recommender-system.git  
cd movie-recommender-system 

Install dependencies:

bash
Copy code
pip install -r requirements.txt  
Run the app:

bash
Copy code
streamlit run app.py  
Open http://localhost:8501 in your browser.

🔑 API Key Setup

Replace YOUR_API_KEY in the fetch_poster function with your TMDb API key from TMDb.

📂 Folder Structure

model/movie_list.pkl: Movie metadata
model/similarity.pkl: Similarity matrix
app.py: Main application
