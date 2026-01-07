# Roee Bloch - Portfolio

A professional portfolio website showcasing my projects, skills, and experience.

🔗 **Live Site:** [roeeblo.github.io](https://roeeblo.github.io)

## Deployment to GitHub Pages

### Option 1: Using the `roeeblo.github.io` Repository (Recommended)

1. Create a new repository named exactly `roeeblo.github.io`

2. Clone the repository:
   ```bash
   git clone https://github.com/roeeblo/roeeblo.github.io.git
   cd roeeblo.github.io
   ```

3. Copy all portfolio files to the repository:
   - `index.html`
   - `styles.css`
   - `script.js`

4. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio deployment"
   git push origin main
   ```

5. Your site will be live at `https://roeeblo.github.io` within a few minutes!

### Option 2: Using Any Repository with GitHub Pages

1. Push the portfolio files to any repository

2. Go to repository **Settings** → **Pages**

3. Under "Source", select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`

4. Click **Save**

5. Your site will be available at `https://roeeblo.github.io/repository-name`

## Local Development

Open `index.html` in your browser to preview the site locally.

For live reload during development, you can use any local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve
```

## Customization

- **Colors:** Edit CSS variables in `styles.css` under `:root`
- **Content:** Update text and links in `index.html`
- **Projects:** Add/remove project cards in the projects section

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript (Intersection Observer, Smooth Scroll)
- Google Fonts (Syne, Space Mono)

