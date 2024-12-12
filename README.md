🎥 Movie Recommender System

A simple content-based movie recommendation app built with Streamlit, powered by TMDb API for fetching movie posters.

🚀 Features

Recommends 5 movies based on the selected title.
Displays dynamic movie posters.
Interactive user interface.

🛠️ Technologies

Python
Streamlit
TMDb API
Machine Learning

🌟 How to Run

Clone the repository:

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

🔑 Setup TMDb API Key
Replace YOUR_API_KEY in the fetch_poster function with your TMDb API key.

📂 Folder Structure
model/movie_list.pkl: Movie metadata.
model/similarity.pkl: Similarity matrix.
app.py: Main application script.
📸 Screenshots
![Screenshot 2024-12-12 153405](https://github.com/user-attachments/assets/1cd6caf6-64b2-4b49-b51f-0059cec0ac0f)

Recommendations

✨ Example Output
Input: Select a movie from the dropdown.
Output: Recommended movies with posters.
