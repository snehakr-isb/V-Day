# Valentine's Day Interactive Website 💕

A sweet, nostalgic Y2K-themed Valentine's Day website with interactive pages and animations.

## Features

- **6 Interactive Pages** with smooth transitions
- **Y2K Nostalgic Design** with pastel colors and retro aesthetic
- **Special Logic**: Name conversion (Nileesh → Bobo display)
- **Form Validations** on every page
- **Fun Interactions**: Disabled "No" button with tooltip, floating hearts, confetti
- **Mobile Responsive** design
- **Embedded CSS & JavaScript** for easy deployment

## Setup Instructions

### 1. Add Your Images

Place these two images in the same directory as `index.html`:

1. **proposal-image.jpg** - Your beach photo (for Page 5 - Valentine's proposal)
2. **final-image.jpg** - Photo of both of you on laptop (for Page 6 - final reveal)

### 2. Open the Website

Simply open `index.html` in any web browser:
- Double-click the file
- Or right-click → Open with → Your browser
- Or drag and drop into browser window

### 3. Deploy Online (Optional)

To share this online, you can use any of these free hosting services:

**GitHub Pages:**
```bash
# Push to GitHub
git add .
git commit -m "Add Valentine's Day website"
git push

# Enable GitHub Pages in repository settings
# Your site will be live at: https://yourusername.github.io/V-Day
```

**Netlify:**
- Drag and drop the folder to [netlify.com/drop](https://app.netlify.com/drop)
- Get instant live URL

**Vercel:**
- Import repository to [vercel.com](https://vercel.com)
- Automatic deployment

## Page Flow

1. **Welcome/Login** - Enter name and select "Sneha" as mommy
2. **Dating Anniversary** - Answer how long you've been dating (6 years, 34 days)
3. **Love Question 1** - Do you love Dobo? (Both options are "Yes")
4. **Love Question 2** - Does Dobo love you? (Both options are "Yes")
5. **Valentine's Proposal** - Will you be Dobo's Valentine? (Only "Yes" works, "No" is disabled)
6. **Final Reveal** - Restaurant info, Google Maps link, and celebration message

## Special Features

- **Name Conversion**: When "Nileesh" is entered, it displays as "Bobo" on all subsequent pages
- **Disabled No Button**: On the proposal page, the "No" button is greyed out with a tooltip
- **Animations**: Floating hearts, confetti, bouncing text, and smooth transitions
- **Restaurant Integration**: Direct link to Nasi & Mee on Google Maps
- **Local Storage**: Saves the name for consistency across pages

## Customization

To customize colors, fonts, or text, open `index.html` and modify:
- **Colors**: Search for color codes (e.g., `#FF69B4`, `#FFB6C1`)
- **Fonts**: Google Fonts are used (Bubblegum Sans, Fredoka, Quicksand)
- **Text**: Find text in HTML sections and update as needed
- **Google Maps**: Replace the link in Page 6

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers

## Image Requirements

- **Format**: JPG, PNG, or WebP
- **Naming**: Must be exactly `proposal-image.jpg` and `final-image.jpg`
- **Location**: Same folder as `index.html`
- **Size**: Recommended max width 1200px for optimal loading

## Troubleshooting

**Images not showing?**
- Check file names match exactly: `proposal-image.jpg` and `final-image.jpg`
- Ensure images are in the same folder as `index.html`
- Check file extensions (jpg vs jpeg)

**Buttons not working?**
- Make sure JavaScript is enabled in your browser
- Try refreshing the page (Ctrl+F5 / Cmd+Shift+R)

**Layout looks broken on mobile?**
- Clear browser cache and reload
- Try rotating device for landscape view

## Credits

Created with love for Valentine's Day 2025! 💕

Dobiti Dobiti Doo 🍜❤️
