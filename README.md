# Eco Eats — Online Store (Portfolio Demo)

Summary
- A simple static demo site for an organic meals restaurant.
- Built with HTML and CSS (Sass). Ready for local preview or deployment as a static site.

Features
- Responsive layout using Bootstrap.
- Light/dark theme with user choice persisted in localStorage.
- Source Sass file available for editing and compilation to CSS.

Important files
- `index.html`
- `styles.scss`
- `styles.css`
- Images folder: `img/`

Local preview
- VS Code: install the Live Server extension and open `index.html`.
- Python (quick): run in project root:
  `python -m http.server 8000`
  Then open `http://localhost:8000`.
- Node (alternative): if you have `http-server`:
  `npx http-server . -p 8080`

Development (Sass)
- To edit SCSS and automatically generate CSS:
  1. Install Sass: `npm install -g sass`
  2. Run watcher: `sass --watch styles.scss:styles.css`

Contributing
- Fork the repository, create a branch, make changes, and open a pull request.
- Keep changes small and document them in commits.

License
- Add a preferred license (for example, MIT). I can add an MIT `LICENSE` template if you want.

Contact
- For questions or requests, open an issue in the repository.
