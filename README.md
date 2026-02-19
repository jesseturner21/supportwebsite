# Support Website

A simple, professional support contact page. Direct people to reach out for help.

## Features

- Clean, modern design
- Responsive (works on mobile and desktop)
- One-click email contact
- Fast and lightweight

## Deploying to GitHub Pages

### Option 1: Using the `landing` repository (Recommended)

1. **Create a GitHub repository** named `landing` (or use an existing one)
2. **Push this code** to the repository:
   ```bash
   git add .
   git commit -m "Add support website"
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub
   - Scroll to "Pages" section
   - Select `main` branch as the source
   - Save

4. Your site will be live at: `https://yourusername.github.io/landing/`

### Option 2: Using a custom domain

If you want it at `https://yourusername.github.io/` directly:

1. Create a repository named `yourusername.github.io`
2. Push this code to that repository
3. Your site will be live at `https://yourusername.github.io/`

### Option 3: Using a custom domain

If you have a custom domain:

1. Add a `CNAME` file to the root with your domain name
2. Point your domain's DNS to GitHub Pages
3. Enable GitHub Pages in repository settings

## Customization

- **Email Address**: Change `jesse.turner2021@gmail.com` in the HTML
- **Colors**: Modify the `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);` in the CSS
- **Text**: Edit the heading, paragraphs, or add additional sections

## Local Testing

Open `index.html` in your browser to preview locally before deploying.
