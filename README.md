# Billboard to Spotify Playlist Creator

This script allows you to create a Spotify playlist based on the Billboard Hot 100 chart for a specific date. It scrapes song information from the Billboard website and uses the Spotify API to create and populate a playlist with those songs.

## Features

- Scrapes the Billboard Hot 100 chart for a user-specified date.
- Authenticates with the Spotify API.
- Searches for the songs on Spotify and retrieves their URIs.
- Creates a new private playlist in your Spotify account.
- Adds the retrieved songs to the newly created playlist.

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `spotipy` library
