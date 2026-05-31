# 🔥 Viral Clip Finder

A modern, responsive web application to discover high-performing viral clips from TikTok, YouTube, and Instagram before they explode.

## Features ✨

- **Smart Search** - Search by clip title, keyword, or creator name
- **Platform Filtering** - Filter clips by TikTok, YouTube, or Instagram
- **Viral Scoring** - See viral scores with visual progress bars
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Real-time Search** - Press Enter or click Search button
- **No Results Message** - Helpful feedback when no clips match
- **Enhanced UX** - Smooth animations, hover effects, and visual feedback

## Improvements Made 🚀

✅ Added 9 sample clips for better showcase  
✅ Added creator names and posting dates  
✅ Implemented viral score progress bars  
✅ Better search with Enter key support  
✅ Reset button to clear filters  
✅ Result count display  
✅ Platform-specific badge colors  
✅ No results message  
✅ Accessibility improvements (alt text, ARIA labels)  
✅ Mobile-optimized interface  
✅ Better visual hierarchy and styling  

## Live Website 🌐

Your site is live at:
```
https://liamhodgson84-hash.github.io/viral-clip-finder/
```

## How to Use

1. **Search**: Type a keyword, niche, or creator name
2. **Filter**: Select a platform from the dropdown
3. **Press Enter** or click the **Search** button
4. **Reset**: Click Reset to clear all filters and see all clips

## Customization

### Add Your Own Clips

Edit the `clips` array in `index.html`:

```javascript
{
  title:"Your Clip Title",
  platform:"TikTok", // or YouTube, Instagram
  views:"1.2M",
  likes:"150K",
  score:92,
  creator:"@your_handle",
  date:"1 day ago",
  thumb:"https://your-image-url.jpg"
}
```

### Connect to a Real API

Replace the `clips` array with an API call:

```javascript
fetch('https://your-api.com/clips')
  .then(res => res.json())
  .then(data => render(data));
```

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Gradients)
- Vanilla JavaScript (No dependencies!)
- Responsive Design (Mobile-first)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

MIT License - Feel free to use this for your projects!

---

**Made with ❤️ for viral content creators**