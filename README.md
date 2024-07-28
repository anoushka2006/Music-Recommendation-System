# Music-Recommendation-System
Music Recommendation System that uses sophisticated algorithms to suggest songs based on user preferences, and song popularity to give song recommendations and predict hits in the genre based on the similarity of certain musical features. By using content-based filtering, the system examines song characteristics like genre, tempo and more (listed below), the system provides personalized recommendations. Advanced machine learning techniques enhance the accuracy of these suggestions, predicting hits within specific genres by analyzing historical patterns. This approach not only enhances user experience and music discovery but also provides valuable market insights for artists and labels, ensuring that the recommendations remain relevant and engaging.

<h2> Sections </h2>

### Hit Predicition
The algorithm predicts hits based on the similarity of songs to previous hits.

### Recommending songs based on Top Hits in a Genre
The algorithm recommends songs based on the top hits in a selected genre.

### Recommending songs based on content and user selection
The algorithm recommends songs based on user-selected songs in the database.

---

### Musical Features in the dataset:
1. index - Location of song in data
2. Artist - Creator of song
3. Track - Name of the song
4. Year - Song's release
5. danceability - Strength and regularity of the beat
6. energy - How fast and noisy the song sounds
7. key - Tonality, what central set of notes the song is based on
8. loudness - Average volume of the song, measured in decibels
9. mode - Major or minor
10. speechiness - How much spoken words are in a track
11. acousticness - Likelihood that the song uses acoustic instruments
12. instrumentalness - Detects whether a track contains no vocals
13. liveness - Detects whether the track was performed live
14. valence - How cheerful the song sounds
15. tempo - Speed of audio in beats per minute
16. Label - Whether a song is a hit or not
17. url - Link to the song on Spotify

NOTE: This data has been retrieved from a Spotify API from 2015.


<h2> Getting started </h2>
This program has been written and developed in Google Colab. 
![Google Colab File]("https://colab.research.google.com/drive/1-vvmK2xOUnXCVCFMyKVvP9KfIBNc3vNm?usp=sharing")

To run the recommendation system, the last section ```Streamlit``` needs to be run. 
A temporary link will be generated that will allow the user full access to the algorithm with a user-friendly interface.
Click on "Visit site" tp use the recommendation system.

The UI has been developed using Streamlit, and hosted using NGROK as it is only a prototype.


## Webpage
![Webpage]("images/index.png")

## Example of the User-Based Recommendation in use
![Content-Based Recommendation]("images/content-filtering.png")

<h3><span style="color: red">Note: </span>Predicted Top Hits and Content-Based Recommendation may take a LONG time to run</h3>
