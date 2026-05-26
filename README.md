# Portfolio Template

A modern, responsive portfolio template ready for GitHub Pages deployment.

## Features

- **Responsive Design** - Works on all devices and screen sizes
- **Modern UI** - Clean, professional design with gradient accents
- **Smooth Navigation** - Sticky navbar with smooth scrolling
- **Multiple Sections** - Home, About, Projects, Skills, and Contact
- **Animations** - Subtle fade-in animations on scroll
- **SEO Friendly** - Optimized for search engines

## File Structure

```
.
├── index.html              # Main portfolio page
├── _config.yml            # Jekyll configuration
├── README.md              # This file
├── assets/
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   └── js/
│       └── script.js      # JavaScript interactivity
```

## Getting Started

### 1. Clone/Copy to Your Repository

```bash
# Clone this template
git clone https://github.com/yourusername/your-portfolio.git
cd your-portfolio
```

### 2. Update GitHub Pages Settings

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Source", select the **main** branch (or your default branch)
4. Select the folder to **/ (root)**
5. Click **Save**

### 3. View Your Portfolio

Your portfolio will be live at:
- If repository is named `yourusername.github.io`: `https://yourusername.github.io`
- Otherwise: `https://yourusername.github.io/repository-name`

## Customization

### Basic Information
Edit `index.html` and replace:
- `Your Name` - Your actual name
- `your.email@example.com` - Your email address
- Social media links in the Contact section

### Colors
Edit the CSS variables in `assets/css/style.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f5576c;
    /* ... other colors ... */
}
```

### Projects
Update the project cards in the Projects section:
1. Change project titles, descriptions, and technologies
2. Update project links to point to your projects
3. Modify gradient colors in `style="background: linear-gradient(...)"`

### Skills
Edit the skill categories and items in the Skills section to match your expertise.

### Jekyll Configuration
Update `_config.yml`:
- `title` - Your portfolio title
- `description` - Short description
- `url` - Your GitHub Pages URL
- `author` - Your name

## Deployment

### First Time Setup

```bash
# Initialize git (if not already done)
git init
git add .
git commit -m "Initial portfolio template"

# Add remote and push
git remote add origin https://github.com/yourusername/your-portfolio.git
git branch -M main
git push -u origin main
```

### After Making Changes

```bash
git add .
git commit -m "Update portfolio content"
git push
```

Your changes will be live within a few minutes!

## Testing Locally (Optional)

To test before pushing to GitHub:

1. **Install Ruby and Jekyll**
   ```bash
   # On Windows, use Ruby installer from https://rubyinstaller.org/
   # Or use WSL with Linux package manager
   ```

2. **Install Jekyll**
   ```bash
   gem install bundler jekyll
   ```

3. **Run locally**
   ```bash
   jekyll serve
   ```
   Visit `http://localhost:4000` in your browser

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Personalization

1. **Add a Profile Picture** - Add an image to the About section
2. **Include Project Links** - Link to live projects or GitHub repos
3. **Update Social Links** - Add your actual social media profiles
4. **Customize Colors** - Choose a color scheme that matches your brand
5. **Add More Sections** - Create additional sections as needed

## License

This template is free to use and modify for your personal portfolio.

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Jekyll Documentation: https://jekyllrb.com/docs/
- Check the comments in HTML files for detailed structure

---

**Happy coding! 🚀**
