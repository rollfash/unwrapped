# Unwrapped

Your top Spotify artists, songs and genres of the year, with the music playing, without waiting for December.

Live at https://rollfash.github.io/unwrapped/ (served from the `gh-pages` branch).

One static page (`index.html`), no server and no build step.

- **Login**: Spotify authorization code + PKCE in the browser. The Client ID is the `CLIENT_ID` constant near the top of the script; its Spotify app must list this site's address as a Redirect URI.
- **Who can use it**: the Spotify app is in development mode, so only accounts added under User Management in the Spotify developer dashboard can connect. The demo works for anyone.
- **Song clips**: 30-second previews from Deezer (matched by ISRC, then by search) with Apple's music search as a fallback. Deezer answers as JSONP, which runs in a sandboxed iframe.
- **Demo**: this week's Deezer chart.
