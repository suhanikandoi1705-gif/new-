# 🎉 25th Anniversary Celebration Website

A beautiful, interactive, and fully responsive website to celebrate 25 years of marriage with automated Bollywood music, cherished memories, and personalized content.

## 📋 Features

✨ **Complete Interactive Experience**
- Elegant hero section with animated anniversary badge
- Smooth scroll navigation
- Music player with toggle control
- Responsive design for all devices
- Beautiful animations and transitions

🎵 **Automatic Bollywood Music**
- Auto-plays when page opens
- Music toggle button in navigation
- Loop functionality

📸 **Memory Gallery**
- 6-image grid layout
- Hover overlays with descriptions
- Fully responsive gallery

📅 **Timeline Section**
- Your journey together visualization
- 4 milestones showcasing your love story
- Interactive timeline with hover effects

💝 **Special Wishes Section**
- 6 reasons to celebrate your love
- Floating icons with animations
- Beautiful card layout

🎯 **Interactive Quiz**
- Fun questions about the couple
- Customizable quiz items
- Interactive button responses

✉️ **Messages & Contact**
- Contact form for guest wishes
- Contact information display
- Message submission handling

🎨 **Design Features**
- Professional color scheme (Red & Gold)
- Smooth animations throughout
- Parallax scrolling effects
- Falling heart particles on mouse movement
- Modern gradient backgrounds

## 📁 File Structure

```
anniversary-website/
├── index.html       (Main HTML file)
├── styles.css       (All styling)
├── script.js        (Interactivity)
├── music/           (Add your music here)
│   └── bollywood-music.mp3
├── images/          (Add your photos here)
│   ├── memory-1.jpg
│   ├── memory-2.jpg
│   ├── memory-3.jpg
│   ├── memory-4.jpg
│   ├── memory-5.jpg
│   └── memory-6.jpg
└── README.md        (This file)
```

## 🚀 Quick Start

### 1. Clone or Download
```bash
git clone https://github.com/suhanikandoi1705-gif/new-.git
cd new-
```

### 2. Add Your Music
- Create a folder named `music/`
- Add your Bollywood song: `bollywood-music.mp3`
- Free music sources:
  - Pixabay (pixabay.com/music)
  - YouTube Audio Library
  - Bensound (bensound.com)
  - Free Music Archive (freemusicarchive.org)

### 3. Add Your Photos
- Create a folder named `images/`
- Add 6 photos (JPG or PNG):
  - `memory-1.jpg` - Wedding photo
  - `memory-2.jpg` - Happy moment
  - `memory-3.jpg` - Family photo
  - `memory-4.jpg` - Travel/adventure
  - `memory-5.jpg` - Celebration
  - `memory-6.jpg` - Recent photo

### 4. Customize Content
Open `index.html` and update:
- Parent names in the logo/title
- Timeline dates and events
- Quiz questions (search for "First Date Destination")
- Contact information in the footer
- Wedding year and dates

Open `script.js` and update:
- Parent names in console logs (optional)
- Quiz logic if needed

### 5. Open the Website
```bash
# Option 1: Double-click index.html
# Option 2: Open in browser
open index.html

# Option 3: Use Live Server (VS Code)
# Install Live Server extension, right-click index.html → "Open with Live Server"
```

## 🎵 Recommended Bollywood Songs for 25th Anniversary

- "Raataan Lambiyan" - Shershaah
- "Tum Hi Ho" - Aashiqui 2
- "Tera Chehra" - Saaya
- "Mere Haath Mein" - Fanaa
- "Janam Janam" - Dilwale
- "Humein Tumse Pyaar Kitna" - Pakeezah

## 🌐 Deployment Options

### Option 1: GitHub Pages (FREE & EASY)
```bash
# In GitHub Settings:
# 1. Go to Settings → Pages
# 2. Set source to "main" branch
# 3. Your site will be live at:
# https://suhanikandoi1705-gif.github.io/new-/
```

### Option 2: Netlify (FREE)
1. Go to netlify.com
2. Drag and drop your project folder
3. Your site is live instantly!

### Option 3: Vercel (FREE)
1. Go to vercel.com
2. Import your GitHub repository
3. Deploy automatically!

## 🎨 Customization Guide

### Change Colors
Edit `:root` variables in `styles.css`:
```css
:root {
    --primary-color: #d4336f;     /* Main red */
    --secondary-color: #ffd700;    /* Gold */
    --dark-color: #1a1a1a;
    --light-color: #f5f5f5;
    --accent-color: #c41e3a;
}
```

### Modify Text
All text is in `index.html`:
- Hero title: Line 87
- Timeline content: Lines 120-150
- Wish cards: Lines 197-235
- Footer text: Line 343

### Add More Photos
Add more images to gallery:
```html
<div class="gallery-item" style="background-image: url('images/memory-7.jpg')">
    <div class="gallery-overlay">
        <p>Your Caption</p>
    </div>
</div>
```

### Add More Wishes
Copy and paste a wish-card div:
```html
<div class="wish-card">
    <div class="wish-icon">
        <i class="fas fa-star"></i>
    </div>
    <h3>Your Title</h3>
    <p>Your description</p>
</div>
```

## 📱 Browser Support

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- IE 11: ⚠️ Limited support

## ⚡ Features Explained

### Animated Badge
The golden circle with "25" spins continuously using CSS animation. It's a 3D perspective effect.

### Music Autoplay
JavaScript attempts to autoplay music on load. If blocked by browser, the button still works on click.

### Falling Hearts
Hover your mouse around the page to see hearts fall. This is a fun Easter egg!

### Scroll Animations
Photos, cards, and timeline items fade in as you scroll. Done with Intersection Observer API.

### Active Navigation
The navigation links highlight in gold when their section is visible.

## 🛠️ Troubleshooting

### Music Not Playing?
1. Check file path: `music/bollywood-music.mp3`
2. Ensure file format is `.mp3`
3. Try a different browser
4. Modern browsers may require user interaction first

### Photos Not Showing?
1. Check folder path: `images/`
2. Check file names: `memory-1.jpg`, etc.
3. Ensure images are in JPG or PNG format
4. Try absolute URLs if relative paths fail

### Website Not Responsive?
1. Clear browser cache (Ctrl+Shift+Del)
2. Check viewport meta tag in HTML
3. Test in different screen sizes

### Form Not Submitting?
Currently the form shows an alert. To send emails, you'll need a backend service:
- Formspree (formspree.io) - FREE
- EmailJS (emailjs.com) - FREE tier available

## 📧 Form Integration (Optional)

To add email functionality, use Formspree:

1. Go to formspree.io
2. Create account and new form
3. Replace form action:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## 🎓 Learning Resources

- HTML Basics: developer.mozilla.org
- CSS Animations: web.dev/animations
- JavaScript Events: javascript.info

## 💡 Pro Tips

1. **Mobile Optimization**: Test on phone before sharing
2. **Image Size**: Compress images for faster loading
3. **Music Quality**: Use 128kbps MP3 for optimal size/quality ratio
4. **Backup**: Keep copies of your photos and music files
5. **Share Link**: Use short URL services for easy sharing

## 🎁 Ideas to Extend

- Add a comments section
- Video message from family
- Photo slideshow with transitions
- Love quotes carousel
- Guest book functionality
- Countdown timer for future events
- Social media integration

## 📄 License

This project is free to use and modify for personal use.

## 🎉 Enjoy!

This website is a celebration of 25 wonderful years. Customize it with your stories, music, and photos. Share it with family and friends!

---

**Created with ❤️ for your Silver Jubilee**

For support or questions, feel free to reach out!

---

## Quick Customization Checklist

- [ ] Added Bollywood music to `music/` folder
- [ ] Added 6 photos to `images/` folder
- [ ] Updated parent names in index.html
- [ ] Updated wedding year and dates
- [ ] Updated contact information
- [ ] Customized quiz questions
- [ ] Changed colors to match preference (optional)
- [ ] Deployed to GitHub Pages / Netlify / Vercel
- [ ] Tested on mobile devices
- [ ] Shared with family and friends

Congratulations on 25 years! 🎊🎉💕
