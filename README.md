🎥 Movie Recommender System
A content-based movie recommendation system that suggests movies similar to the one selected by the user. The application fetches movie details and posters using The Movie Database (TMDb) API and is built using Streamlit for the user interface.

🚀 Features
Provides recommendations for movies based on user-selected titles.
Displays movie posters fetched dynamically using TMDb API.
Simple and interactive user interface using Streamlit.
🛠️ Technologies Used
Python
Streamlit
Machine Learning (Content-Based Filtering)
TMDb API
Pickle (for saving pre-trained models and data)
📂 Folder Structure
bash
Copy code
📦 Movie-Recommender-System  
├── model  
│   ├── movie_list.pkl          # Pickle file containing movie metadata  
│   ├── similarity.pkl          # Pickle file with similarity matrix  
├── app.py                      # Main Python script for the Streamlit app  
├── README.md                   # Documentation  
🧩 Prerequisites
Before running the project, ensure you have the following installed:

Python 3.7+
Streamlit
Requests
Install the required Python packages using:

bash
Copy code
pip install -r requirements.txt
🌟 How It Works
Movie Selection:
The user selects a movie from the dropdown menu.

Recommendation:
The app computes movie similarities using a pre-trained model and recommends the top 5 similar movies.

Poster Display:
The TMDb API fetches and displays the posters of the recommended movies.

🛠️ How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open your browser and navigate to http://localhost:8501.

🔑 API Key Setup
Replace YOUR_API_KEY in the fetch_poster function with your TMDb API key.
Obtain your TMDb API key from TMDb.

Recommendations with Posters

🛡️ License
This project is licensed under the MIT License - see the LICENSE file for details.

🙌 Acknowledgments
The Movie Database (TMDb) for the API.
Streamlit for providing a simple framework for creating web apps.
