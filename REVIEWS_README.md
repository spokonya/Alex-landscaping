# Reviews Management Guide

## Quick Start
1. Open `reviews-admin.html` in your browser
2. Add, edit, or delete reviews using the simple form
3. Copy the generated HTML code
4. Paste it into `index.html` to replace the existing reviews section

## How to Add/Edit Reviews

### Method 1: Admin Interface (Recommended)
1. Open `reviews-admin.html` in your web browser
2. Fill out the form for each review:
   - **Customer Name**: Full name (e.g., "Sarah Johnson")
   - **Star Rating**: Choose 1-5 stars
   - **Review Text**: The testimonial content
3. Click "Add Review" to add it to the list
4. Click "Generate HTML" to get the code
5. Copy the generated code and replace the reviews section in `index.html`

### Method 2: Direct HTML Editing
1. Open `index.html` in a text editor
2. Find the section with `<!-- Manual Reviews Carousel -->`
3. Each review is wrapped in a `<div class="review-card">` block
4. Edit the content inside each block:
   - **Stars**: Change `★★★★★` to your desired rating (use ★ for filled, ☆ for empty)
   - **Review Text**: Update the text between the quotes
   - **Author**: Change the name after the dash

## Star Rating Guide
- 5 stars: `★★★★★`
- 4 stars: `★★★★☆`
- 3 stars: `★★★☆☆`
- 2 stars: `★★☆☆☆`
- 1 star: `★☆☆☆☆`

## Adding More Reviews
1. Copy an entire `<div class="review-card">` block
2. Paste it before the closing `</div>` of the reviews container
3. Update the content (stars, text, author)
4. Add a corresponding dot in the navigation: `<span class="dot" onclick="currentReview(X)"></span>`
5. Update the JavaScript `totalReviews` count if needed

## Removing Reviews
1. Delete the entire `<div class="review-card">` block
2. Remove the corresponding dot from the navigation
3. Update the JavaScript `totalReviews` count

## Best Practices
- Keep reviews concise (2-3 sentences)
- Use real customer names when possible
- Include specific details about your service
- Mix different types of work (landscaping, hardscaping, treescape)
- Update reviews regularly to keep content fresh

## Troubleshooting
- **Carousel not working**: Check that all review cards have the same structure
- **Navigation dots not matching**: Ensure you have the same number of dots as review cards
- **Styling issues**: Make sure the CSS classes match exactly

## File Structure
- `index.html` - Main website with reviews section
- `reviews-admin.html` - Admin interface for managing reviews
- `styles.css` - Contains all the carousel styling
- `REVIEWS_README.md` - This guide









