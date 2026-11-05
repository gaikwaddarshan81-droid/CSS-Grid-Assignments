# CSS Grid Layout Assignments

A set of five self-contained exercises demonstrating CSS Grid from fixed tracks to responsive implicit grids. Each assignment is a standalone HTML page with its own stylesheet; the homepage links to every exercise.

## Technologies

- HTML5 for semantic page structure and accessible content
- CSS3 for Grid layouts, responsive breakpoints, transitions, and visual styling
- Google Fonts and Unsplash-hosted photography for visual assets
- No JavaScript or build tools required

## Run the project

Open `index.html` in a browser, then choose an assignment. The pages work as static files; an optional local server can also be used from this folder, for example:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
CSS-Grid-Assignments/
├── index.html
├── style.css
├── README.md
├── assignment-1/
│   ├── index.html
│   └── style.css
├── assignment-2/
│   ├── index.html
│   └── style.css
├── assignment-3/
│   ├── index.html
│   └── style.css
├── assignment-4/
│   ├── index.html
│   └── style.css
└── assignment-5/
    ├── index.html
    └── style.css
```

## Assignments

1. **Basic Grid:** Nine distinct 100 × 100 px cells arranged in three fixed columns and rows with a 10 px gap.
2. **Blog Page:** Editorial layout using named grid areas, flexible fractional sizing, article imagery, and a responsive sidebar.
3. **Responsive Gallery:** Twelve images in an `auto-fit` / `minmax(150px, 1fr)` grid, with consistent crops and hover treatment.
4. **Dashboard:** Named grid areas, responsive navigation, metric summaries, a CSS bar chart, and recent team activity.
5. **Implicit Card Grid:** Six image-led destination cards arranged using `auto-fill` and `minmax()`.

Photography is loaded from Unsplash and web fonts from Google Fonts, so those assets require an internet connection. The layouts and page content themselves are local and static.