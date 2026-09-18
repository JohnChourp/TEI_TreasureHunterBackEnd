# Treasure Hunter

Treasure Hunter is a platform to create treasure hunt games.

## Configuration

- **MongoDB:** set `MONGODB_URI` to your connection string. Without it the app
  uses a local `mongodb://localhost:27017/TreasureHunter`.
- **Google Maps:** replace `YOUR_GOOGLE_MAPS_API_KEY` in
  `src/main/resources/templates/addMarker.html` and `updateMarker.html` with your
  own key, restricted to your domain in the Google Cloud console.

Never commit a real key or a connection string with a password: this repository
is public, and a value stays readable in git history after it is removed.
