🎬 Movie Recommendation System

This project is a content-based movie recommendation system built using Python and machine learning techniques. It suggests movies to users based on similarities in movie metadata such as genres, cast, crew, and storyline.

🚀 Features
- Recommend top similar movies for a given movie.
- Uses cosine similarity for recommendation.
- Fetches movie posters dynamically using TMDb API.
- Interactive Streamlit web application for easy use.

🛠️ Tech Stack

- Python (Data processing and backend)
- Libraries: pandas, numpy, scikit-learn, pickle, requests
- Web App: Streamlit
- API: The Movie Database (TMDb) API

📂 Project Structure

Movie_Recommendation_System/
│── Movie_Recommendation_system.ipynb   # Jupyter notebook (model building + processing)
│── app.py                              # Streamlit web application
│── movies.pkl                          # Pickle file storing movie data
│── similarity.pkl                      # Pickle file storing similarity matrix
│── README.md                           # Project documentation


⚙️ Installation & Setup

1.Clone this repository:

git clone https://github.com/your-username/Movie_Recommendation_System.git
cd Movie_Recommendation_System

2.Install required dependencies:
pip install -r requirements.txt

3.Run the Streamlit app:
streamlit run app.py

🎥 Usage
- Enter/select a movie in the app.
- Get top 5 recommended movies with posters.
- Explore visually appealing recommendations.

📊 Workflow
1.Data Preprocessing
   - Clean and merge datasets.
   - Extract features like genre, keywords, cast, crew.
   - Convert text to vectors using CountVectorizer.

2.Similarity Calculation
   - Use cosine similarity to measure closeness between movies.

3.Deployment
   - Save processed data (movies.pkl) and similarity matrix (similarity.pkl) for fast recommendations.
   - Build an interactive UI with Streamlit.

🔑 API Key
To fetch posters from TMDb:
   - Create an account on TMDb
   - Generate an API key.
   - Replace the API key inside app.py.

📌 Example
If you search for Inception, recommendations may include:
   - Interstellar
   - The Dark Knight
   - Shutter Island
   - The Prestige
   - Memento

📜 License

This project is licensed under the MIT License.
