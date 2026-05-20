🎬 Movie Success Predictor ML
📌 Overview
This project uses a Decision Tree Classifier to predict a movie's success category (Blockbuster, Hit, Average, Flop, or Disaster) based on features like budget, genre, director, and real-world audience sentiment from 32 million ratings.

📊 Data Sources
This project merges three major cinematic datasets:

TMDB 5000 Movies: Core metadata and revenue data.

IMDB Metadata: Additional director and cast details.

MovieLens 32M Dataset: Used for high-granularity audience scoring.

Download Link: MovieLens 32M Dataset

🛠️ How to Set Up (The "Big Data" Steps)
Because the MovieLens dataset is over 1GB, it is not included in this repository. Follow these steps to run the project:

Download the Data: Go to the GroupLens website and download the ml-32m.zip file.

Extract the Files: You only need ratings.csv and links.csv from the zip folder.

Open Google Colab: Upload the .ipynb file from this repo to your Colab environment.

Upload CSVs:

Click the Files icon on the left sidebar in Colab.

Upload tmdb_movies_data.csv, movie_metadata.csv, ratings.csv, and links.csv.

Note: Be patient while uploading ratings.csv; it’s a heavy file.

Run All Cells: The code uses chunking logic to process the 32 million ratings without crashing the Colab RAM.

🚀 Usage
Scroll to the bottom of the notebook to find the Interactive Predictor Tab. Use the dropdown menus to select:

Budget & Runtime

Genre & Release Month

Lead Actor & Director

Expected Rating

The model will instantly predict the success category and give you a reality check on your movie idea.

📈 Visualizations
The project generates:

Feature Importance: See what actually drives movie success.

Correlation Heatmap: Relationships between budget, popularity, and ratings.

Decision Tree Map: A visual flow of how the AI makes its "Hit" or "Flop" decisions.

👨‍💻 Author
Gururaj DS,Hemanth A B,Lingaraj GSB,Kruthik Gowda GR


