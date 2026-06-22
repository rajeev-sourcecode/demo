# Demo Portfolio Website

A simple, responsive portfolio website hosted on GitHub Pages.

## Features

- 📱 Fully responsive design (mobile, tablet, desktop)
- 🎨 Modern gradient styling
- 📄 Multiple sections (Home, About, Projects, Contact)
- ⚡ Fast loading and lightweight
- 🔗 Easy to customize and extend

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `README.md` - Documentation

## How to Host on GitHub Pages

1. **Settings**: Go to your repository **Settings** → **Pages**
2. **Source**: Select `Deploy from a branch`
3. **Branch**: Choose `main` branch and `/root` folder
4. **Save**: Click Save
5. **Access**: Your site will be available at `https://rajeev-sourcecode.github.io/demo/`

## Local Development

To view the website locally:
1. Clone the repository
2. Open `index.html` in your web browser
3. Or use a local server: `python -m http.server 8000`

## Customization

### Update Your Information
- Edit the contact email in the Contact section
- Update project descriptions in the Projects section
- Modify the navigation links as needed

### Change Colors
Edit the gradient colors in `styles.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Add More Projects
Add new project cards in the projects grid section of `index.html`:
```html
<div class="project-card">
    <h3>Your Project</h3>
    <p>Your project description</p>
</div>
```

## License

Feel free to use this template for your personal portfolio.

---

**Status**: ✅ Ready to deploy on GitHub Pages