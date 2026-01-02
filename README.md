# Ayush's credle

A small browser-based physics/graphics demo built with JavaScript. The project contains a simple interactive sketch of Newton's cradle that runs in the browser.

## Files

- `index.html` — Entry point for the demo; loads the sketch and required scripts.
- `sketch.js` — Main sketch and application logic (renders and updates the scene).
- `bob.js` — Component implementing the bob (pendulum ball) behavior.
- `rope.js` — Component implementing rope constraints between objects.
- `roof.js` — Component representing the fixed anchor/roof for ropes.
- `README.md` — This file.

## Run locally

1. Open `index.html` directly in a modern browser (double-click the file).
2. Or run a simple local server and open the page:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Development

- Edit the JavaScript files in your editor and reload the browser to see changes.
- This sketch uses various p5.js libraries and matter.js to make development easy

## Contributing

Feel free to open issues or submit pull requests to improve the demo, add features, or fix bugs.

## License

MIT License

## Contact

For questions or collaboration, open an issue in the repository.

