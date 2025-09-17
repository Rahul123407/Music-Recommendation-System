# Music-Recommendation-System
A Music Recommendation System built with machine learning techniques using the tcc_ceds_music.csv dataset. The system analyzes music metadata and user interaction data to suggest songs that match user preferences.
📊 Dataset

This project uses the TCC CEDS Music Dataset. Due to GitHub file size limits, the dataset is not stored in the repository.

👉 Download the dataset here

Once downloaded, place it in the root project folder and rename it to:

tcc_ceds_music.csv

📂 Project Files

Music_recommendation_system.ipynb → Jupyter Notebook containing the full implementation

requirements.txt → List of Python dependencies

README.md → Project documentation

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/YOUR-USERNAME/music-recommendation-system.git
cd music-recommendation-system


Download the dataset from Google Drive

and save it as tcc_ceds_music.csv inside the project folder.

Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook Music_recommendation_system.ipynb

🚀 Features

Data Preprocessing: Cleaning, handling missing values, feature selection

Recommendation Models: Content-based filtering and collaborative filtering

Evaluation: Measured performance using standard recommendation metrics

Visualization: Insights into user preferences and music patterns

📈 Results

Explored correlations between listening behavior and music preferences

Built recommendation models capable of generating personalized suggestions

Delivered a pipeline from raw data → model training → evaluation → recommendations

🛠️ Tech Stack

Python

Pandas / NumPy → Data manipulation

Scikit-learn → Machine learning models

Matplotlib / Seaborn → Visualization

Jupyter Notebook → Development and experimentation

📌 Future Work

Implement Neural Collaborative Filtering (NCF) or deep learning–based recommenders

Deploy as a web application with Flask/Streamlit

Build a frontend interface for interactive music suggestions
