# Unwrapped

Your top Spotify artists, songs and genres of the year, without waiting for December.

One static page (`index.html`), no server. It logs in to Spotify in the browser (authorization code + PKCE) and reads your top items. Song clips are 30-second previews looked up in Apple's public music search.

Setup: create an app in the Spotify developer dashboard (needs Premium), add this site's address as the Redirect URI, and paste the app's Client ID into the page.
