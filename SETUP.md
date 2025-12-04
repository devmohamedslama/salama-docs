# 🚀 GitHub Pages Setup Guide

## Enabling GitHub Pages

1. **Go to Repository Settings**
   - Navigate to: `https://github.com/devmohamedslama/salama-docs/settings`
   - Click on "Pages" in the left sidebar

2. **Configure Pages**
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select `main` (or `gh-pages` if using the workflow)
   - **Folder**: Select `/ (root)`
   - Click "Save"

3. **Access Your Site**
   - Your site will be available at: `https://devmohamedslama.github.io/salama-docs/`
   - It may take a few minutes to deploy initially

## Adding New Content

### Quick Method (GitHub Web Interface):
1. Navigate to the `docs/` folder in your repository
2. Click "Create new file" or "Upload files"
3. Add your `.md` files in the appropriate subfolder:
   - `docs/strategy/` - Business and marketing content
   - `docs/research/` - Technical research and concepts  
   - `docs/personal/` - Ideas and experiments
4. Update `_sidebar.md` to add navigation links
5. Commit the changes

### Local Development:
1. Clone the repository locally
2. Add your `.md` files to the `docs/` directory
3. Test locally: `python3 -m http.server 3000`
4. View at: `http://localhost:3000`
5. Commit and push changes

## Site Features

### 🔍 Search
- Press `Ctrl+/` or use the search box
- Searches across all documentation

### 🎨 Professional Theme
- Custom gradient sidebar
- Professional color scheme
- Responsive design

### 📱 Mobile Friendly
- Optimized for mobile viewing
- Touch-friendly navigation

### 🔧 Enhanced Features
- Copy code buttons
- Image zoom functionality
- Page navigation (Previous/Next)
- Syntax highlighting for code blocks

## Customization

### Changing Colors
Edit the CSS variables in `index.html`:
```css
:root {
  --theme-color: #2c3e50;        /* Main theme color */
  --theme-color-secondary: #3498db; /* Secondary color */
  --accent-color: #e74c3c;        /* Accent color */
}
```

### Adding New Sections
1. Create a new folder in `docs/`
2. Add your `.md` files
3. Update `_sidebar.md` with navigation links

### Custom Domain (Optional)
1. Add a `CNAME` file with your domain
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings