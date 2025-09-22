# Images Directory

This directory contains all images for the Spices & Suitcases website.

## Structure

### `/authors/`
- Author profile photos
- Recommended size: 300x300px, square format
- Files needed:
  - `him.jpg` - The Chef's profile photo
  - `her.jpg` - The Organizer's profile photo
  - `couple.jpg` - Joint photo for posts authored by both

### `/posts/`
- Featured images for blog posts
- Recommended size: 1200x600px (2:1 aspect ratio)
- Current post images needed:
  - `bangkok-street-food.jpg` - Street food scene from Bangkok
  - `budget-spreadsheet.jpg` - Organized budget/planning image
  - `organized-kitchen.jpg` - Clean, organized small kitchen
  - `travel-books.jpg` - Stack of travel-related books

### `/general/`
- General site images
- Hero images, backgrounds, etc.
- Files that might be useful:
  - `about-hero.jpg` - Image for about page
  - `site-logo.png` - Site logo if needed

## Image Guidelines

- **Quality**: High resolution, well-lit, crisp images
- **Style**: Warm, inviting, authentic (not overly polished)
- **Format**: JPG for photos, PNG for graphics with transparency
- **Optimization**: Compress images for web use
- **Alt Text**: Always include descriptive alt text in posts

## Placeholder Images

Until you add your own photos, you can use placeholder services like:
- Unsplash (https://unsplash.com) for high-quality stock photos
- Picsum (https://picsum.photos) for placeholder images
- Your own photos from travels and cooking adventures

## Adding Images

1. Add images to the appropriate subdirectory
2. Reference them in posts using: `{{ '/assets/images/path/filename.jpg' | relative_url }}`
3. Always include alt text for accessibility
4. Consider adding captions for context
