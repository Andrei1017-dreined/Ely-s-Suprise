# 💕 Love Letter Website

A beautiful, romantic static website to express your love and showcase special memories together. Perfect for GitHub Pages hosting!

## ✨ Features

- **Animated Hero Section** - Eye-catching title with romantic gradient background
- **Floating Hearts** - Animated heart emojis floating in the background
- **Love Letter Section** - Express your feelings with styled text
- **Reasons Cards** - Highlight things you love about your partner
- **Photo Gallery** - Showcase your favorite pictures with captions and messages
- **Lightbox** - Click photos to view them in fullscreen
- **Sparkle Effects** - Interactive sparkles on click
- **Fully Responsive** - Looks great on desktop, tablet, and mobile
- **GitHub Pages Ready** - 100% static, no backend required

## 🚀 Getting Started

### Adding Your Photos

1. Place your photos in the `images/` folder
2. Name them `photo1.jpg`, `photo2.jpg`, etc. (or update the paths in `index.html`)
3. Supported formats: JPG, PNG, WebP, GIF

### Customizing Content

Edit `index.html` to personalize:

1. **Title & Subtitle** - Change the main heading in the hero section
2. **Love Letter** - Write your personal message in the letter section
3. **Reasons** - Update the "Things I Adore About You" cards
4. **Photo Captions** - Add captions for each photo in `.photo-caption`
5. **Photo Messages** - Add personal messages in `.photo-message`
6. **Final Message** - Customize the ending declaration

### Customizing Colors

Edit `styles.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: #e91e63;      /* Main pink color */
    --secondary-color: #ff6b9d;    /* Secondary pink */
    --accent-color: #f8bbd9;       /* Light accent */
    --dark-color: #2c1810;         /* Text color */
    --light-color: #fff5f8;        /* Background */
}
```

## 📁 Project Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styles and animations
├── script.js       # Interactive features
├── images/         # Your photos go here
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── ...
└── README.md       # This file
```

## 🌐 Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - love letter website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to repository **Settings** → **Pages**
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## 💡 Tips

- Use high-quality photos for best results
- Keep photo file sizes reasonable (under 2MB each) for faster loading
- Test on mobile devices before sharing
- Consider using WebP format for smaller file sizes

## 🎨 Customization Ideas

- Change the Google Fonts in `index.html`
- Add more photo gallery items by copying the gallery-item template
- Add a music player (use an iframe from Spotify/YouTube)
- Change the color scheme to match your partner's favorite colors
- Add more sections with your story timeline

## 💖 Made with Love

This website template was created with love. Feel free to customize it and make it your own!

---

*For my love - Every moment with you is a blessing* 💕
