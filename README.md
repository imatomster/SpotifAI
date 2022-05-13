# SpotifAI
🎵 PlayList Curator Machine Learning Model

> Often times, music can run dry after repeated listens. Thankfully, with SpotifAI, we can make you a playlist we KNOW you will like. What are you waiting for? Tell us some of your favorite songs!

More information can be found in this `README.md`

- [YouTube Demo](https://www.youtube.com/watch?v=YjfuihfVOMY)

# Current Status
Still a Work In Progress!
Start Date: 1/25/22

# Description
## 🔨 How I built it
- Python
- NumPy
- Pandas
- Scikit-learn
- Dash
- Spotify API

## ⚙️ What I did
- Constructed an app with a Dash interface that allows users to input at least 5 favorite songs & in turn create custom target playlists catered for the user 
- Extracted user input searches from the Spotify API into a Pandas DataFrame that contains song traits to be spliced, filtered, and fed to ML models 
- Trained models with sklearn to execute algorithms that learn what songs the user likes based on the danceability, acousticness, energy, etc of the songs
