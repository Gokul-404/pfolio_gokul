# Gokul Murali portfolio

Static site: `index.html`, `robot.png`, `favicon.svg`. No build step.

## Run Locally
Since this is a static site with no build dependencies, you can run it using any of the following:

- **Browser**: Double-click [index.html](file:///c:/Users/gokul/OneDrive/Desktop/gokul-portfolio/index.html) to open directly in your browser.
- **Python**:
  ```bash
  python -m http.server 3000
  ```
  Then open `http://localhost:3000`.
- **Node / npx**:
  ```bash
  npx serve .
  ```

## Push to GitHub
```bash
git add .
git commit -m "Update portfolio"
git push
```

## Deploy on Vercel
Import the repo. Framework preset: Other. No build command, output directory left empty (root).
