# NZB RSS Feeds Web App

A modern, static web app for browsing NZB RSS feeds and TMDB trending content, with a beautiful responsive UI.

## Features

- Browse trending movies, shows, and trailers from TMDB
- Browse custom NZB RSS feeds (movies and TV)
- Responsive design for desktop and mobile
- Animated navigation bar with sliding highlight
- Modal popups with trailers, cast, and details
- Easy to customize for your own feeds

## Setup

1. **Clone or download this repository.**
2. **Open `index.html` in a text editor.**
3. **Insert your TMDB API key and your custom RSS feed URLs** in the marked sections:
   - Replace `TMDB_API_KEY` with your TMDB API key.
   - Replace each feed URL with your own RSS feed URLs and SABnzbd server details.
4. **Open `index.html` in your browser.**

No build step or server is required—this is a static HTML/JS app.

## Usage

- Click the navigation tabs to switch between feeds.
- Click a movie or show for more details and a trailer.
- On mobile, use the dropdown navigation.

## Screenshots

Add screenshots here if desired.

## Contributing

Pull requests and suggestions are welcome! Please open an issue or PR.

## License

MIT

## SABnzbd Integration

This app can display your SABnzbd download queue and history in a dedicated tab. To enable this feature:

1. Open `index.html` in a text editor.
2. Locate the configuration section at the top of the file:
   - Set `SABNZBD_URL` to the base URL of your SABnzbd server (e.g., `http://192.168.1.20:8080`).
   - Set `SABNZBD_API_KEY` to your SABnzbd API key (found in SABnzbd under Config > General > API Key).
3. Save the file and open it in your browser.

**Note:**
- For SABnzbd integration to work, your browser must be able to access the SABnzbd server directly (usually on the same local network).
- If you encounter CORS errors, you may need to use a browser extension or proxy to allow cross-origin requests.
- The Downloads tab will show your current queue and recent history, including status and progress bars. 