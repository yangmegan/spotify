### spotify wrapped (without the wonky AI)

#### 📌 features
- uses spotify API to fetch most frequently played songs
- generates playlist with your top 50 songs from the past 1-2 years
- visualizes how niche your taste in music is based on spotify popularity scores
- supports chinese, japanese, and korean characters

#### 👩🏻‍💻 tech stack
- python
- spotipy (spotify API)
- pandas (data processing)
- matplotlib (data vis)

#### ✨ setup
1️⃣ clone this repository

`git clone https://github.com/yangmegan/spotify.git
cd spotify`

2️⃣ install the dependencies

`pip install spotipy pandas matplotlib`

3️⃣ get spotify API credentials
-create a new app using your spotify developer dashboard

-note your client ID and client secret

-set the redirect URI to: http://localhost:8888/callback (since I used google colab, I set mine to https://google.com)

`SPOTIFY_CLIENT_ID="your_client_id"
SPOTIFY_CLIENT_SECRET="your_client_secret"
SPOTIFY_REDIRECT_URI="http://localhost:8888/callback"`

4️⃣ run !

`python main.py`

#### 💫 follow the prompts to access your spotify data, then the playlist will auto-publish to your spotify profile
