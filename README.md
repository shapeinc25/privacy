# Privacy Policy for GitHub Pages

A simple page to host your privacy policy on GitHub Pages.

## How to Use

### 1. Insert Your Policy Text

Open the `index.html` file and find the comment:
```html
<!-- 
═══════════════════════════════════════════════════════════
INSERT YOUR PRIVACY POLICY TEXT BELOW
═══════════════════════════════════════════════════════════
-->
```

Replace the content inside `<div id="policy-content">` with your actual privacy policy text.

You can use HTML tags for formatting:
- `<p>` - paragraphs
- `<h2>` - section headings
- `<ul>` and `<li>` - lists
- `<strong>` - bold text
- `<em>` - italic text

### 2. Upload to GitHub

1. Create a new repository on GitHub (e.g., `privacy-policy`)

2. Upload files to the repository:
   ```bash
   git init
   git add index.html
   git commit -m "Add privacy policy page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to Settings in your repository
   - Find "Pages" in the left menu
   - Under "Source", select "Deploy from a branch"
   - Choose branch `main` and folder `/ (root)`
   - Click "Save"

4. Your page will be available at:
   `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

## Customization

- **Update Date**: Automatically set to current date. To change it, find `<span id="date"></span>` in the HTML
- **Title**: Change the text in `<h1>Privacy Policy</h1>`
- **Styles**: All styles are in the `<style>` tag in `<head>` - you can customize colors, fonts, and spacing

## File Structure

```
policy_shape/
├── index.html      # Main page (edit this file)
└── README.md       # This instruction file
```
