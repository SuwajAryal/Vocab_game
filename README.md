# GRE Scholar

A lo-fi flashcard game for making GRE vocabulary practice a little more fun. Pick a word group, flip a card to check its meaning, and rate how well you knew it. The app tracks your streak and saves progress in the current browser.

## Play locally

From the project folder, start a local web server with Python 3.

```sh
python -m http.server 8000
```

Open `http://localhost:8000` in your browser. Use the card controls to move through the group, or swipe on a touch screen. The app uses plain HTML, CSS, and JavaScript, with a service worker for offline caching.
