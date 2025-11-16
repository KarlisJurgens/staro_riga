# Staro Rīga Rating Tool

A simple web-based rating tool for Staro Rīga light festival installations.

## How to Share with Others

Once you upload to GitHub, share this link (replace with your info):
```
https://raw.githack.com/YOUR-USERNAME/YOUR-REPO-NAME/main/rating.html
```

## Quick Setup on GitHub

1. **Create a new repository** on GitHub
   - Go to [github.com/new](https://github.com/new)
   - Name it (e.g., `staro-riga-rating`)
   - Make it **Public**
   - Click "Create repository"

2. **Upload files**:
   - Click "uploading an existing file"
   - Drag and drop these files:
     - `rating.html`
     - `staroriga_filtered.json`
   - Click "Commit changes"

3. **Get the sharing link**:
   - Go to your uploaded `rating.html` file
   - Click "Raw" button
   - Copy the URL
   - Replace `raw.githubusercontent.com` with `raw.githack.com`

   **Example:**
   - Raw URL: `https://raw.githubusercontent.com/username/repo/main/rating.html`
   - Share URL: `https://raw.githack.com/username/repo/main/rating.html`

4. **Share the link** - anyone can click it and start rating immediately!

## How to Use

1. Open the link in your browser
2. Rate each installation by clicking on a star (1-7)
3. Click "Skip" to skip an installation (it won't be included in results)
4. After rating all items, you'll see the results sorted by rating
5. Click "Copy to Clipboard" to copy all ratings

## Features

- 7-star rating system
- Skip functionality for items you don't want to rate
- Progress tracker
- Final results sorted by rating (highest first)
- One-click copy to clipboard
- Dark theme for better focus
- Works completely in the browser (no server needed)

## Local Testing

To test locally before uploading to GitHub:
1. Download both `rating.html` and `staroriga_filtered.json`
2. Put them in the same folder
3. Open `rating.html` in your web browser

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Responsive design
- Works on mobile and desktop
- Automatically detects GitHub Pages and loads JSON accordingly
