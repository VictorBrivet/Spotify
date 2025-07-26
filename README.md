**Spotify Listening Analysis Data Science Project**

This project explores a user's listening behavior on Spotify through data science techniques. By using the Spotify Web API, it retrieves personal listening data and analyzes it through statistics, visualizations, and machine learning models. The result is a detailed view of your musical habits, preferences, and routines.

**Overview**
The goal is to build a complete analytical dashboard that covers everything from track popularity to genre diversity. It highlights when and how you listen to music, identifies patterns in your behavior, and even attempts to predict what you might listen to next. Along the way, it uses a mix of traditional data analysis, network modeling, and predictive algorithms to reveal insights about your listening history.

**What the project does**
You can explore your top tracks and artists across different periods (short, medium, and long term), understand how long your favorite tracks are, and how popular they tend to be. The project also tracks how your listening varies by hour and day of the week, and how frequently you repeat songs or return to the same artists.

It builds transition graphs showing how you move from one artist or genre to another, and maps the geographic origins of your favorite artists using MusicBrainz. Finally, it trains a decision tree model that tries to predict your next artist based on the time and context of your previous listens.

**Technologies**
The project is written in Python and uses a range of libraries including:

**Spotipy to connect to the Spotify API**

Pandas, NumPy, and collections for data manipulation

Matplotlib, Seaborn, and Plotly for visualizations

NetworkX for graph analysis

Scikit-learn for building a predictive model

Pycountry and the MusicBrainz API to retrieve artist origin data

**Getting started**
To run this project, you need to set up access to the Spotify API.

Start by creating a .env file and enter your Spotify client credentials. You’ll need to register your app at Spotify Developer Dashboard to get your client ID, secret, and redirect URI.

Once your environment is set up, install the required Python packages and run the script or notebook. The data will be fetched directly from your Spotify account through OAuth authentication.

