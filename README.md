# 📸 Photo Gallery

Welcome to the photo gallery for AresHydra & Friends!

## 🚀 Your Site is Live!

**Visit your site here:** https://AresHydra.github.io

## 📝 How to Add Your Photos

### Easy Way: Use Image URLs from the Web

1. Find a photo online or upload to a free service like:
   - **Imgur** (imgur.com) - upload → copy image URL
   - **Google Photos** - right-click image → "Copy image address"
   - **Discord** - upload to a server → copy link

2. Edit `index.html` and replace placeholder URLs:
   ```html
   <img src="https://your-image-url-here.jpg" alt="Description">
   ```

3. Change the caption `<p>` text to describe your photo

4. Commit and push - it updates automatically!

### Example:
```html
<div class="photo-card">
    <img src="https://imgur.com/abc123.jpg" alt="Summer vibes">
    <p>Beach day 2024</p>
</div>
```

## 🎨 Customize Your Site

**Change colors:** Edit `style.css` line 8
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

**Change title:** Edit `index.html` 
```html
<h1>📸 Your Title Here</h1>
<p>Your subtitle</p>
```

## 💡 Quick Tips

- Add as many photos as you want - just copy and paste `<div class="photo-card">...</div>` blocks
- Keep image URLs working (some free sites delete old images)
- Use consistent image sizes for best look
- Test on your phone too!

## 🔗 Share Your Site

Send friends this link: **https://AresHydra.github.io**

Enjoy! 📸✨
