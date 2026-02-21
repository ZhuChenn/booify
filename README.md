# babyboo

A premium, Spotify-inspired music player website with a luxurious dark theme and stunning UI.

## Features

- **Premium Dark Theme** - Sleek dark interface with subtle gradients and glass morphism effects
- **Responsive Design** - Looks great on desktop, tablet, and mobile
- **Smooth Animations** - Beautiful hover effects, transitions, and soundwave indicators
- **Full Player Controls** - Play/pause, previous/next, shuffle, repeat, progress bar, volume
- **Keyboard Shortcuts** - Space to play/pause, arrows for seeking, and more

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play/Pause |
| `←` | Seek backward 5 seconds |
| `→` | Seek forward 5 seconds |
| `Shift + ←` | Previous track |
| `Shift + →` | Next track |
| `↑` | Volume up |
| `↓` | Volume down |
| `M` | Mute/Unmute |

## Customizing Songs

Edit the `tracks` array in `app.js` to add your own songs:

```javascript
const tracks = [
    {
        id: 1,
        title: "Your Song Title",
        artist: "Artist Name",
        album: "Album Name",
        cover: "https://your-image-url.com/cover.jpg",
        duration: "3:20",
        dateAdded: "2 weeks ago"
    },
    // Add more tracks...
];
```

## Running Locally

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then open http://localhost:8000 in your browser.

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## License

MIT
