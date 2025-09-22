# Setup Instructions

Follow these steps to get your Spices & Suitcases blog up and running!

## Step 1: Customize Your Site

### Update Site Configuration
Edit `_config.yml` and update these key fields:

```yaml
title: "Your Blog Title"
subtitle: "Your Blog Subtitle"
description: "Your blog description"
url: "https://yourusername.github.io"

social:
  instagram: "your_instagram_handle"
  twitter: "your_twitter_handle"
  pinterest: "your_pinterest_handle"
  email: "your_email@example.com"
```

### Update Author Information
Edit the files in `_authors/` directory:
- `_authors/him.md` - Update with his information
- `_authors/her.md` - Update with her information

### Add Your Photos
Add photos to `assets/images/authors/`:
- `him.jpg` - His profile photo (300x300px recommended)
- `her.jpg` - Her profile photo (300x300px recommended)
- `couple.jpg` - Photo of both for joint posts

## Step 2: Create Your Content

### Replace Sample Posts
The `_posts/` directory contains sample posts. Replace them with your own:
1. Delete or modify the existing sample posts
2. Create new posts using the format: `YYYY-MM-DD-title.md`
3. Use this front matter template:

```yaml
---
layout: post
title: "Your Post Title"
date: 2024-MM-DD
categories: [travel, cooking, organizing, planning, finance, reading]
tags: [tag1, tag2, tag3]
author: him # or "her" or "both"
read_time: 5 # estimated reading time in minutes
featured_image: "/assets/images/posts/your-image.jpg"
excerpt: "Brief description of your post"
---

Your post content here...
```

### Update Pages
- Edit `about.md` with your story
- Update `contact.md` with your contact information
- Customize any other pages as needed

## Step 3: Add Images

### Post Images
Add featured images for your posts to `assets/images/posts/`
- Recommended size: 1200x600px (2:1 aspect ratio)
- Use descriptive filenames
- Optimize for web (compress file sizes)

### General Images
- Add any other images to appropriate subdirectories in `assets/images/`
- Update image paths in your content

## Step 4: Test Locally (Optional)

If you want to test locally before publishing:

```bash
# Install Ruby dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve

# Visit http://localhost:4000 to view your site
```

## Step 5: Deploy to GitHub Pages

### Enable GitHub Pages
1. Go to your repository settings on GitHub
2. Navigate to "Pages" section
3. Set source to "GitHub Actions"
4. The GitHub Actions workflow is already configured

### Push Your Changes
```bash
git add .
git commit -m "Initial site setup"
git push origin main
```

Your site will automatically build and deploy! It will be available at `https://yourusername.github.io/repository-name`

## Step 6: Customize Further

### Colors and Styling
Edit CSS variables in `assets/css/main.css` to match your brand:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --accent-color: #your-color;
}
```

### Add Analytics (Optional)
Add Google Analytics by including your tracking ID in `_config.yml`:

```yaml
google_analytics: "YOUR-GA-TRACKING-ID"
```

### Social Media Integration
Update social links throughout the site by modifying the `social` section in `_config.yml`

## Troubleshooting

### Site Not Building?
- Check the "Actions" tab in your GitHub repository for build errors
- Ensure all required fields in `_config.yml` are filled out
- Make sure image paths are correct

### Images Not Showing?
- Check that image files exist in the correct directories
- Verify image paths in your posts start with `/assets/images/`
- Ensure images are properly optimized (not too large)

### Styling Issues?
- Clear your browser cache
- Check that CSS file paths are correct
- Verify any custom CSS is valid

## Next Steps

Once your site is running:
1. Start writing your first posts
2. Share your site on social media
3. Consider setting up a custom domain
4. Add more features as needed

## Need Help?

- Check the main README.md for detailed documentation
- Review Jekyll documentation at jekyllrb.com
- Look at the sample posts for formatting examples

**Happy blogging!** 🎉
