# Personal Website

A simple, elegant, and lightweight personal website built with HTML, CSS, and JavaScript.

## Features

- Clean, minimalist design
- Responsive layout
- Tab-based navigation (Home, Publications, Writing)
- Lightweight and fast loading
- Easy to maintain and customize

## File Structure

```
athki/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## How to Test View the Website

### Option 1: Open directly in browser
1. Simply double-click on `index.html` to open it in your default web browser
2. The website will load locally and you can test all functionality

### Option 2: Use a local server (recommended)
1. Open your terminal/command prompt
2. Navigate to the project directory: `cd /path/to/athki`
3. Start a simple HTTP server:

**Using Python 3:**
```bash
python3 -m http.server 8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Using Node.js (if you have it installed):**
```bash
npx serve .
```

4. Open your browser and go to `http://localhost:8000`

### Option 3: Using VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Customization

### Adding Your Content

1. **Home Page**: Edit the content in `index.html` within the `#home` section:
   - Replace `[Your Name]` with your actual name
   - Update the profession/description
   - Add your mission/purpose
   - Replace the placeholder interests with your actual interests

2. **Profile Image**: Replace the image placeholder:
   - Add your image file to the project directory
   - Replace the `<div class="image-placeholder">` with:
   ```html
   <img src="your-image.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover;">
   ```

3. **Publications**: Update the publications section with your actual publications

4. **Writing**: Add your articles and writing samples

### Styling Customization

- Edit `styles.css` to change colors, fonts, spacing, etc.
- The design uses a clean, minimalist approach with subtle animations
- All colors are defined as CSS variables for easy customization

## Deployment

### GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch" and choose your main branch
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Drag and drop your project folder to [netlify.com](https://netlify.com)
2. Your site will be deployed instantly with a unique URL

### Vercel (Free)
1. Connect your GitHub repository to [vercel.com](https://vercel.com)
2. Vercel will automatically deploy your site

## Browser Compatibility

This website works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Performance

The website is optimized for speed:
- Minimal JavaScript
- Optimized CSS
- No external dependencies
- Fast loading times

## License

This project is open source and available under the MIT License. 