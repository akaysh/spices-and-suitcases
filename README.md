# Spices & Suitcases

A beautiful Jekyll-based publishing platform for a couple's adventures in travel, food, and life. Built for GitHub Pages with a modern, responsive design.

## About

We're a couple who couldn't be more different—he's a gourmet chef, she's all about street food; he's a thrill-seeker, she's a homebody. But together, we're on a mission to prove that opposites not only attract, they also cook and travel pretty darn well. Follow us as we wander the world one meal at a time (and probably argue over the spice level while we're at it)!

## Features

- **Beautiful, responsive design** with cute, modern UI
- **Category-based content** for travel, cooking, organizing, planning, finance, and reading
- **Dual author system** supporting individual and collaborative posts
- **Automatic GitHub Pages deployment** via GitHub Actions
- **SEO optimized** with Jekyll SEO plugin
- **Social sharing** built into posts
- **Mobile-friendly** navigation and layout
- **Fast loading** with optimized CSS and JavaScript

## Quick Start

### 1. Repository Setup
1. Fork or clone this repository
2. Update `_config.yml` with your information:
   ```yaml
   title: "Your Site Title"
   url: "https://yourusername.github.io"
   social:
     instagram: "your_instagram"
     twitter: "your_twitter"
     email: "your_email@example.com"
   ```

### 2. GitHub Pages Setup
1. Go to your repository settings
2. Navigate to "Pages" section
3. Set source to "GitHub Actions"
4. The site will automatically deploy when you push to main branch

### 3. Content Setup
1. Add your author photos to `assets/images/authors/`
2. Update author information in `_authors/` directory
3. Add your own posts to `_posts/` directory
4. Replace sample content with your own

### 4. Customization
- Edit `_config.yml` for site settings
- Modify `assets/css/main.css` for styling changes
- Update social links in `_config.yml`
- Add your own images to `assets/images/`

## Content Structure

### Posts
- Located in `_posts/` directory
- Use filename format: `YYYY-MM-DD-title.md`
- Include front matter with categories, tags, author, etc.
- Support for featured images and read time estimates

### Categories
- Six main categories: travel, cooking, organizing, planning, finance, reading
- Category pages in `categories/` directory
- Automatic post filtering and display

### Authors
- Author profiles in `_authors/` directory
- Support for individual author pages and bios
- Flexible authoring (individual authors or "both")

## File Structure

```
spices-and-suitcases/
├── _config.yml              # Site configuration
├── _layouts/                # Page layouts
│   ├── default.html         # Base layout
│   ├── post.html           # Blog post layout
│   ├── page.html           # Static page layout
│   └── category.html       # Category page layout
├── _posts/                 # Blog posts
├── _authors/               # Author profiles
├── assets/
│   ├── css/main.css        # Main stylesheet
│   ├── js/main.js          # JavaScript functionality
│   └── images/             # Site images
├── categories/             # Category pages
├── .github/workflows/      # GitHub Actions
├── about.md               # About page
├── contact.md             # Contact page
├── blog.html              # All posts page
└── index.html             # Homepage
```

## Customization Guide

### Colors and Styling
Edit the CSS variables in `assets/css/main.css`:
```css
:root {
  --primary-color: #ff6b6b;    /* Main accent color */
  --secondary-color: #4ecdc4;   /* Secondary accent */
  --accent-color: #ffe66d;      /* Highlight color */
  /* ... more variables ... */
}
```

### Adding New Categories
1. Add category to `_config.yml` categories list
2. Create new page in `categories/` directory
3. Posts will automatically appear when tagged with the category

### Social Media Integration
Update the social section in `_config.yml`:
```yaml
social:
  instagram: "your_handle"
  twitter: "your_handle"
  pinterest: "your_handle"
  email: "your_email@example.com"
```

## Development

### Local Development
```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Build for production
bundle exec jekyll build
```

### Requirements
- Ruby 3.1+
- Jekyll 4.3+
- Bundler

## Deployment

The site automatically deploys to GitHub Pages via GitHub Actions when you push to the main branch. No additional setup required!

## Contributing

This is a personal blog template, but feel free to:
- Fork for your own use
- Submit bug reports
- Suggest improvements
- Share your own customizations

## License

This project is open source and available under the MIT License.

## Support

Having issues? Check out:
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll SEO Plugin](https://github.com/jekyll/jekyll-seo-tag)

---

**Happy blogging!** 🌶️✈️
