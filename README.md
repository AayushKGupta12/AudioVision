# AI in Music Track Popularity Predictions

## Project Description
This project will analyze and predict the **popularity of music tracks** based on varied audio features. It aims at applying **machine learning techniques** in finding patterns that influence the success of music, so that artists, producers, and streaming platforms can leverage such advancements in optimization strategies.

## Objectives
1. **Develop a Prediction Model**: Design an ML model that predicts how popular a song is in terms of its track audio features.
2. **Select Most Relevant Features**: Determine which of the audio features - **danceability**, **energy, and tempo**-best determines the popularity of a song.
3. **Enlighten Recommendations**: This can be used to enhance music recommendation systems and assist artists and producers in creating better tracks that actually become hits.
Dataset
The dataset includes music tracks available on the platform of **Spotify**, consisting of:
- Attributes: **danceability**, **energy**, **valence**, **tempo**, **acousticness**, and many more.
- Metadata: **track name**, **artist**, **release year**, **streams**, and ranking in popular playlists and charts.

## Used Libraries
- **Python**: Primary programming language.
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For performing numerical computations.
- **Matplotlib & Seaborn**: For data visualization
- **Scikit-learn**: Used for machine learning, including K-means clustering and regression.

## Running the Project
1. Clone the repository:
   ```bash
git clone <repository-link>
   ```
2. Installing required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Running the Jupyter notebook:
   Open the `AI_in_Music.ipynb` in Jupyter Notebook and run the cells to execute analysis and model training.
END.
2. **EDA**: Distribution of key audio features, such as **danceability**, **valence**, and **energy**, to see what the value is for the distribution of those audio features, their implications regarding track popularity, and mutual correlation of these features.
3. **Feature Selection**: Key features selected for the analysis of modeling are **danceability**, **energy**, **acousticness**, and **instrumentalness**.
4. **Machine Learning Model**: K-Means clustering is used to group tracks based on the audio features. Predictive models that estimate the popularity of a track given these audio features are then developed.

## In Key Features
- **Danceability**: How well a song could be danced to with regard to rhythm, tempo, and beat.
- **Energy**: Intensity and activity level of a track.
- **Valence**: Musical positivity in terms of the track.
- **Acousticness**: How acoustically a track sounds.
- **Instrumentalness**: Probability of a given track being instrumental, that is, no vocals are used in it.
- **Liveness**: The probability of a track having been recorded before an audience.
* **Track Popularity Prediction**: The system accepts the feature data of tracks and predicts the popularity of the track.
Clustering : It classifies the combined audio features to obtain more deeper insights related to the trends present within popular music.

## Visualization
* **Feature Distribution Graphs**: Pie charts or bar charts that describe the critical audio features of popular tracks.
* **Clustering**: Scatter plot representing the track grouping based on **danceability**, **valence**, and **energy** using K-means clustering.
Elbow Method The method is used to find the optimum number of clusters for the K-Means algorithm.

Future Enhancements
Deep Learning Models Techniques such as neural networks may be used to improve prediction accuracy.
Collaborative Filtering: User-based recommendation could be added to make it more personalized.

Conclusion
This project is an insight into popular tracks of music, offering which audio features are most predictive of success on streams. In doing so, it identifies some key patterns that can help artists, producers, and streaming platforms make data-driven decisions to improve their strategies.

## Acknowledgments
- **Spotify**: This project used audio features and track metadata accessed via Spotify.
- **Scikit-learn**: For providing the machine learning tools used in this project.
