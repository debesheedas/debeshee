# Debeshee Das | AI Security & Privacy Researcher

A beautiful, fast-loading personal website built with lots of vibe coding.

## 🚀 Live Website

Visit the live website at: [https://debesheedas.github.io/debeshee](https://debesheedas.github.io/debeshee)

## 📁 Project Structure

```
debeshee/
├── index.html              # Main HTML file
├── styles.css              # CSS with Material Design styling
├── script.js               # JavaScript functionality
├── publications.json       # Publications data (easily editable)
├── _config.yml            # GitHub Pages configuration
├── Debeshee Das - Researcher.pdf  # CV/Resume PDF
└── README.md              # This file
```

## 🛠️ Setup & Deployment

### GitHub Pages Deployment

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Custom Domain (Optional)**:
   - Add a `CNAME` file with your custom domain
   - Configure DNS settings with your domain provider

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/debesheedas/debeshee.git
   cd debeshee
   ```

2. **Serve locally**:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have it)
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**: Navigate to `http://localhost:8000`

## 📝 Updating Publications

To add or update publications, edit the `publications.json` file:

```json
{
  "title": "Your Paper Title",
  "authors": ["D. Das", "Co-Author"],
  "venue": "Conference Name",
  "year": 2024,
  "location": "City, Country",
  "pages": "1-10",
  "doi": "10.1000/example",
  "links": {
    "pdf": "https://example.com/paper.pdf",
    "arxiv": "https://arxiv.org/abs/2024.xxxxx",
    "github": "https://github.com/username/repo"
  },
  "thumbnail": "article",
  "abstract": "Brief description of the paper..."
}
```

### Supported Link Types
- `pdf`: Direct link to PDF
- `arxiv`: ArXiv preprint link
- `github`: GitHub repository
- `conference`: Conference website
- `acm`: ACM Digital Library
- `ieee`: IEEE Xplore
- `springer`: Springer Link

### Thumbnail Icons
- `article`: General research paper
- `code`: Software/tool papers
- `security`: Security-related work
- `book`: Book chapters/surveys

## 🎨 Customization

### Colors
The color palette is defined in CSS custom properties in `styles.css`. Update the `:root` section to change colors:

```css
:root {
  --color-primary: #059AA0;        /* Dark cyan */
  --color-primary-variant: #7FC3B7; /* Tiffany Blue */
  --color-secondary: #FFCAD4;       /* Pink */
  /* ... */
}
```

### Content
- **Bio**: Update the about section in `index.html`
- **Links**: Update social media links in the hero section
- **CV**: Replace `Debeshee Das - Researcher.pdf` with your CV
- **Contact**: Update email in `_config.yml`

## 🔧 Technical Details

### Performance Optimizations
- **Minimal Dependencies**: Only Google Fonts and Material Icons
- **Optimized CSS**: Custom properties for consistent theming
- **Lazy Loading**: Images load only when needed
- **Efficient JavaScript**: Modern ES6+ with minimal DOM manipulation

### Browser Support
- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Accessibility Features
- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- High contrast mode support
- Reduced motion respect

## 📊 Analytics & SEO

The website includes:
- Meta tags for social media sharing
- Structured data for search engines
- Sitemap generation via Jekyll
- SEO-optimized URLs and content

To add Google Analytics:
1. Get your GA4 tracking ID
2. Add the tracking code to `index.html` before `</head>`

## 🤝 Contributing

This is a personal website template. Feel free to:
- Fork for your own use
- Submit issues for bugs
- Suggest improvements via pull requests

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Material Design**: Google's Material Design system
- **Color Palette**: Custom teal/cyan theme
- **Icons**: Google Material Icons
- **Fonts**: Google Fonts (Roboto family)


