# Visual Assets for Certes Institute Website

This directory contains images and visual assets for the website.

## Current Image Requirements

### Team Photos
The following team member photos are referenced in the website:

- **pip-foweraker.jpg** - Pip Foweraker (Executive Director)
  - Referenced in: `team.html`, `board.html`
  - Recommended size: 800x800px (square)
  - Format: JPG or PNG

- **charlie-renner.jpg** - Charlie Renner (Consulting Expert)
  - Referenced in: `team.html`
  - Recommended size: 800x800px (square)
  - Format: JPG or PNG

### Board Member Photos
The following board candidate photos are referenced:

- **placeholder-person.jpg** - Generic placeholder for candidate directors
  - Referenced in: `board.html` (Tushar Paradkar, James Gauci, Amy Goss)
  - Currently using CSS fallback (colored background)
  - Recommended size: 800x800px (square)
  - Format: JPG or PNG

## Image Guidelines

### Profile Photos
- **Dimensions**: 800x800px minimum (square aspect ratio)
- **Format**: JPG (preferred for photos) or PNG
- **File size**: Under 500KB per image
- **Naming**: Use lowercase with hyphens (e.g., `pip-foweraker.jpg`)

### General Images
- Optimize all images before uploading (use tools like TinyPNG, ImageOptim, or similar)
- Use descriptive filenames
- Consider providing 2x versions for retina displays if needed

## Fallback Behavior

The website is designed to handle missing images gracefully:
- Team/board member cards will display with a colored background if the image fails to load
- This is implemented via the `onerror` attribute in the HTML

## Adding New Images

1. Add the image file to this directory
2. Ensure the filename matches the reference in the HTML
3. Test the website locally to verify the image displays correctly
4. Commit and push to deploy

## Future Assets

Consider adding:
- Favicon (certes-favicon.ico or .png)
- Open Graph image for social media sharing (og-image.jpg, 1200x630px)
- Any research visualizations, charts, or infographics
