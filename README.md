# Exploratory Data Analysis of an Artist's Discography on Spotify

The goal of this project is to explore different features of the music by King Gizzard and the Lizard Wizard (KGLW). I chose this musical group due to their expansive (217 songs) discography and eclectic mix of instruments and genres. Breaking these down 

## Data Preparation
* I used the Spotipy library to access the Spotify API and gather my data, which essentially collected all the information I wanted from I playlist I created on Spotify with all of KGLW's songs. The function can also be used for other playlists, and was used twice in this project.
* I cleaned the data by converting all the type's from 'object' to the type they correspond with.
## Data Visualization
I used plotly, Seaborn, matplotlib, and pandas to guide my answering of the following questions:
* **Popularity**
    * What are the qualities that seem to contribute to a tracks popularity?
        * Certain audio features?
        * The key of a track?
    * How do these compare to Billboard's Top 100 Songs?
* **Audio Features**
    * Which of the audio features that Spotify defines describes KGLW the best?
    * Are these similar to Billboard's Top 100?
* **Album Features**
    * Which of KGLW's albums is most danceable? Most energetic? Loudest? Happiest?

Visuals and analysis can be found in the file!

