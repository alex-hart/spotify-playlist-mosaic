# Spotify Playlist Mosaic

Simple collage generator for your spotify playlist using the album art from the tracks.

### Steps for local development work

1. Create a Spotify Developer account on https://developer.spotify.com/dashboard/login and create a new app, call it Playlist Mosaic generator or similar
2. Once you've created the app, go to `Edit Settings` and add two redirect URIs: `http://localhost:8888` and `http://localhost:8888/callback`
3. Replace `client_id` and `client_secret` at the top of `app.js` with the values given to you in the Spotify Developer console.
4. Replace `redirect_uri` on `line 8` in `app.js `with `http://localhost:8888`
5. Open your console of your choice, `cd` to wherever you cloned this repo, and then run `node app.js`
6. Open your browser of choice, and then go to `localhost:8888`
 
Done! Now you can develop this locally -- remember that any changes to app.js you need to restart the node app for changes to occur.
