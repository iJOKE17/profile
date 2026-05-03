# Personal Portfolio — Arthorn Kittinukul

A static personal portfolio website for a Fullstack Developer. Built with plain HTML, CSS, and JavaScript (pre-compiled via webpack).

## Pages

| File | Description |
|---|---|
| `index.html` | Home / hero landing |
| `works.html` | Work list |
| `work.html` | Work detail |
| `about.html` | About me |
| `contact.html` | Contact form |

## Folder Structure

```
profile/
├── assets/
│   └── images/          # All image assets
├── index.html
├── works.html
├── work.html
├── about.html
├── contact.html
├── main.3f6952e4.css     # Compiled CSS
├── main.70a66962.js      # Compiled JS bundle
└── main.70a66962.map     # Source map
```

## Run

No build step required. Just serve the files with any static file server.

**Using Python:**
```bash
python3 -m http.server 8080
```

**Using Node.js (`npx`):**
```bash
npx serve .
```

Then open `http://localhost:8080` in your browser.
