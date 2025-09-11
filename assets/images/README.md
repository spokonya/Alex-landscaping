# Image Organization for Alex Landscaping Website

This folder contains all images organized by page and purpose for easy management.

## Folder Structure

### `/home/` - Homepage Images
- **`hero/`** - Main hero section image (large landscape shot)
- **`features/`** - Three feature section images (expert design, sustainable builds, ongoing care)

### `/work/` - Portfolio/Work Page Images  
- **`portfolio/`** - Organized portfolio images by category (Landscape Design, Hardscaping, Maintenance, Before/After)

### `/about/` - About Page Images
- **`portrait/`** - Alex's professional portrait/headshot

## Image Guidelines

### Recommended Formats
- **Web-optimized JPG** for photos (quality 80-85%)
- **PNG** for logos and graphics with transparency
- **WebP** for modern browsers (with JPG fallback)

### Recommended Sizes
- **Hero images**: 1200x800px minimum
- **Feature images**: 600x600px (square)
- **Portfolio images**: 600x600px (square) - all portfolio images use consistent sizing
- **Portrait**: 600x800px

### File Naming Convention
Use descriptive names with hyphens and category prefixes:
- `hero-landscape.jpg`
- `feature-expert-design.jpg`
- `portfolio-design-1.jpg` (Landscape Design Projects)
- `portfolio-hardscape-1.jpg` (Hardscaping & Patios)
- `portfolio-maintenance-1.jpg` (Lawn Care & Maintenance)
- `portfolio-before-after-1.jpg` (Before & After Projects)
- `portrait-alex.jpg`

## How to Add Images

### For Portfolio Images (Work Page)
1. **Choose your categories** from the four portfolio sections
2. **Upload images** to `assets/images/work/portfolio/` folder
3. **Use the naming convention** with category prefixes (design-, hardscape-, maintenance-, before-after-)
4. **Optimize images** for web (compress to reduce file size)
5. **Images will automatically appear** in organized sections on the work page

### For Other Pages
1. **Upload your image** to the appropriate folder
2. **Rename it** using the naming convention above
3. **Optimize it** for web (compress to reduce file size)
4. **Update the HTML** to reference the new image

The HTML files are already set up to use these image paths - just replace the placeholder elements with `<img>` tags pointing to your uploaded images.

## Portfolio Organization Benefits
- **Automatic categorization** - Images are organized by service type
- **Professional presentation** - Each category has its own section
- **Easy management** - Add images to any category as needed
- **Flexible content** - Showcase your best work in each service area
- **Client-focused** - Visitors can easily find examples of specific services
