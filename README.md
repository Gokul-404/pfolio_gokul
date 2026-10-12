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

## Live Site
- **Production URL**: [https://gokul-portfolio-lac.vercel.app](https://gokul-portfolio-lac.vercel.app)

## Deploy on Vercel
The repository is linked to Vercel. Pushing to `main` automatically triggers deployments, or deploy manually using:
```bash
vercel --prod
```
