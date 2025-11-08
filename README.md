# Grits & Eggs Podcast Website

A modern, user-friendly replacement for Linktree that serves as a central hub for all podcast content, merchandise, and community engagement.

## 🎯 Features

- **Clean, Modern Design**: Professional look that reflects the brand's identity
- **Responsive Layout**: Perfect viewing experience on all devices (mobile, tablet, desktop)
- **All CTAs Equally Prominent**: Balanced design giving equal weight to:
  - Patreon subscriptions
  - Podcast listening
  - Merchandise sales
  - Direct support
- **Fast Loading**: Optimized performance with smooth animations
- **Accessible**: WCAG compliant with keyboard navigation support
- **SEO Optimized**: Proper meta tags and semantic HTML

## 📁 File Structure

```
deante/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md           # Documentation
```

## 🚀 Getting Started

### Quick Start
1. Open `index.html` in any modern web browser
2. That's it! No build process needed.

### Deployment Options

#### Option 1: GitHub Pages (Free)
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/deante`

#### Option 2: Netlify (Free)
1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Get instant live URL
3. Optional: Connect custom domain

#### Option 3: Vercel (Free)
1. Push to GitHub
2. Import project in Vercel dashboard
3. Automatic deployments on every commit

#### Option 4: Custom Hosting
Upload all files to your web hosting via FTP/cPanel

## 🎨 Customization

### Updating Content

**Change Links:**
Edit the `href` attributes in `index.html`:
```html
<a href="YOUR_NEW_URL" target="_blank">
```

**Update Text:**
Modify any text directly in `index.html`

**Add New Episodes:**
Duplicate a content card and update the link and title

### Changing Colors

Open `styles.css` and modify the color variables:
```css
:root {
    --primary-color: #f7eb73;     /* Yellow accent */
    --secondary-color: #000000;   /* Black */
    --accent-color: #ff6b6b;      /* Red accent */
}
```

### Adding Images

Replace the video placeholder:
```html
<div class="featured-image">
    <img src="your-image.jpg" alt="Episode thumbnail">
</div>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px

## 🔧 Browser Support

- Chrome (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Edge (last 2 versions)

## 📊 Analytics Integration

To add Google Analytics:

1. Add before `</head>` in index.html:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

2. Replace `GA_MEASUREMENT_ID` with your tracking ID

## 🎯 Current Links Included

1. **Latest Episode** (YouTube)
2. **Patreon** ($8/month membership)
3. **Podcast Platforms** (Apple, Spotify)
4. **Merchandise Store**
5. **Cash App Support**
6. **Recent Content** (4 videos)
7. **Social Media** (Instagram, TikTok, YouTube)
8. **Email Contact**

## 💡 Future Enhancements

Consider adding:
- Email newsletter signup form
- RSS feed integration
- Episode search functionality
- Dark mode toggle
- Audio player for latest episode
- Event calendar for live shows
- Guest showcase section

## 🐛 Troubleshooting

**Links not working?**
- Check that URLs start with `http://` or `https://`
- Verify all links open in new tabs (`target="_blank"`)

**Styling looks off?**
- Clear browser cache (Cmd/Ctrl + Shift + R)
- Check that `styles.css` is in the same folder

**Animations not smooth?**
- Disable if user has reduced motion preferences enabled
- Check browser support for CSS animations

## 📝 Maintenance

### Regular Updates
- Update featured episode weekly
- Add new content to Recent Content section
- Check all links monthly
- Update copyright year annually

### Performance Checks
- Run Lighthouse audit monthly
- Optimize any images added
- Monitor page load times

## 📞 Support

For questions or issues:
- Email: Deante@deantekyle.com
- Review this README
- Check browser console for errors (F12)

## 📄 License

This website is proprietary to Grits & Eggs Podcast.

---

Built with ❤️ for Deanté Kyle | Last Updated: 2024
