# Project Title
- Million Songs Data – Music Recommendation Engine
![music](https://github.com/user-attachments/assets/e1234d3f-74a0-4371-a3ae-36285074d197)
# Objective
- To develop a music recommendation system that suggests songs to users based on their listening history and preferences, leveraging the Million Songs Dataset.
# Why We Use This Project
- Music platforms like Spotify, Apple Music, and YouTube Music aim to enhance user engagement by recommending personalized tracks. This project demonstrates how recommendation engines can be built using real-- --world music listening behavior data, helping businesses improve retention and user satisfaction.
# Step-by-Step Approach
- Data Collection
- Load triplets_file.csv containing user_id, song_id, and listen counts.
- Load metadata_file.csv containing song details like title, artist_name, release, and year.
- Data Cleaning
- Handle missing values in metadata (e.g., missing year or title).
- Remove duplicates in song metadata.
# Exploratory Data Analysis (EDA)
- Understand user listening patterns (most active users).
- Identify the most popular songs and artists.
- Visualize distribution of listens per song and per user.
# Feature Selection
- From metadata: song_id, title, artist_name (for content-based filtering).
- From triplets: user_id, song_id, and listen count (for collaborative filtering).
# Feature Engineering
- Create a unique song feature combining title and artist_name.
- Aggregate play counts for popularity-based recommendations.
- Normalize listen counts for weighting in similarity scores.
# Model Training
- Popularity-based Recommender: Rank songs by total listen count.
- Collaborative Filtering: Suggest songs based on similar user preferences.
- Content-based Filtering: Use song metadata to recommend similar songs.
# Model Testing
- Test recommendations for a sample user ID.
- Evaluate using metrics like Precision@K, Recall@K, or qualitative inspection.
# Output
<img width="698" height="148" alt="Screenshot 2025-08-14 090710" src="https://github.com/user-attachments/assets/c1cfebe4-072a-4b09-b3d3-7d1c0ef67820" />
