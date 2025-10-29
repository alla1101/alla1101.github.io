# Academic Website for GitHub Pages

This is a Jekyll-based academic website designed for GitHub Pages. It provides a professional platform for sharing academic work, documents, posts, and information.

## Features

- **Homepage**: Welcome page with site overview
- **Bio**: Biography and background information
- **CV**: Academic curriculum vitae
- **Papers & Lectures**: Publications and teaching experience
- **Posts**: Blog functionality for academic updates
- **Documents**: Section for sharing downloadable documents

## Site Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML layouts
│   └── default.html     # Main layout template
├── _posts/              # Blog posts (YYYY-MM-DD-title.md format)
├── assets/              # CSS and other assets
│   └── css/
│       └── style.css    # Custom styling
├── documents/           # Shared documents folder
├── index.md            # Homepage
├── bio.md              # Biography page
├── cv.md               # CV page
├── papers.md           # Papers and lectures page
├── posts.md            # Posts listing page
└── documents.md        # Documents page
```

## Getting Started

### 1. Update Configuration

Edit `_config.yml` to customize:
- Site title and description
- Your contact information
- Navigation links
- Other site settings

### 2. Customize Pages

Update the following pages with your information:
- `bio.md` - Add your biography
- `cv.md` - Add your curriculum vitae
- `papers.md` - Add your publications and teaching experience
- `index.md` - Customize the homepage

### 3. Add Posts

Create new posts in the `_posts/` directory:
- Filename format: `YYYY-MM-DD-post-title.md`
- Include front matter with layout, title, date, and categories
- Example post: `2024-01-15-welcome.md`

### 4. Share Documents

1. Upload files to the `documents/` folder
2. Update `documents.md` with links to your files
3. Use the format shown in the documents page

### 5. Deploy to GitHub Pages

The site will automatically build and deploy when you push to the repository:
1. Commit and push your changes
2. GitHub Pages will build the site automatically
3. Visit `https://yourusername.github.io` to see your site

## Customization

### Styling

Edit `assets/css/style.css` to customize colors, fonts, and layout.

### Layout

Edit `_layouts/default.html` to modify the site structure and navigation.

### Adding New Pages

1. Create a new `.md` file in the root directory
2. Add front matter with `layout: default` and `title: Your Page Title`
3. Add a link to your new page in `_config.yml` under `navigation`

## Local Development

To test the site locally before deploying:

1. Install Jekyll (if not already installed):
   ```bash
   gem install bundler jekyll
   ```

2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000` in your browser

## Tips

- Use Markdown for all content pages
- Upload PDFs and documents to the `documents/` folder
- Keep post filenames in the correct date format
- Test locally before pushing to GitHub
- Check GitHub Pages settings to ensure the site is enabled

## Support

For issues or questions:
- Check Jekyll documentation: https://jekyllrb.com/docs/
- Check GitHub Pages documentation: https://docs.github.com/pages

## License

This website template is provided as-is. Feel free to customize it for your needs.

