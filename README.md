# Will You Be My Valentine? 💕

A beautiful, single-page Valentine's mini-site featuring an interactive 3×3 drag-and-drop puzzle game.

## Features

- **Landing Page**: Opens with a personal message
- **Drag-and-Drop Puzzle**: Fully functional 3×3 puzzle using a single image
- **Smart Snap Detection**: Tiles lock in place when dropped on the correct slot
- **Text Reveal**: Emotional messages fade in once the puzzle is solved
- **Evasive NO Button**: The "No" button moves away whenever the user tries to interact with it
- **Confetti Animation**: Celebratory confetti on "Yes" click
- **Mobile Support**: Works on desktop and touch devices
- **Gallery Aesthetic**: Clean, minimal design with subtle shadows and elegant typography

## Setup

1. **Prepare Your Image**:
   - Place your painting image in the same folder as `index.html`
   - Name it: `painting.png`
   - Recommended size: 300×300 pixels (or larger for better quality)

2. **Open the Site**:
   - Double-click `index.html` to open it in your default browser
   - Or right-click and select "Open with" your preferred browser

3. **No Dependencies**:
   - Pure HTML/CSS/JavaScript
   - No external libraries or frameworks needed
   - Works offline

## Hosting

You can host this anywhere:
- **GitHub Pages**: Push to a GitHub repo, enable Pages in settings
- **Netlify**: Drag and drop the folder at netlify.com
- **Vercel**: Connect your repo to Vercel
- **Any Static Host**: Amazon S3, Firebase Hosting, your own server, etc.

## How It Works

1. **Landing**: User reads the personal message and clicks "Start"
2. **Puzzle**: 9 shuffled tiles appear in a tray below a 3×3 grid
3. **Drag & Drop**: 
   - Drag tiles from the tray into the grid
   - Correct placement: tile locks in place
   - Wrong placement: tile shakes and returns to tray
4. **Solved**: When all 9 tiles are placed correctly, the emotional text reveals
5. **Question**: "Will you be my Valentine?" appears with YES/NO buttons
6. **YES Button**: Launches confetti and shows the ending
7. **NO Button**: Runs away on every interaction attempt (with funny hints)

## Customization

Edit the text in `index.html`:

- **Landing message**: Lines 346-350
- **Puzzle label**: Line 373
- **Text reveals**: Lines 404-410
- **Ending message**: Lines 432-433
- **Hints for NO button**: Lines 151-159

You can also adjust:
- Colors: Look for `background:`, `color:`, and `border:` in the CSS
- Fonts: Modify the `font-family` at the top of the CSS
- Animation speeds: Adjust `animation:` values
- Button styles: Modify `.btn-yes` and `.btn-no` classes

## Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
beMyValentine/
├── index.html          (Complete website - all CSS & JS embedded)
├── painting.png        (Your image - place here before opening)
└── README.md          (This file)
```

## Tips

- **Image Quality**: Use a high-quality painting for the best visual effect
- **Aspect Ratio**: Square or near-square images work best
- **Mobile Testing**: Open on a phone to verify touch functionality
- **Share**: Send the folder to your special someone or host it online!

---

**Made with ❤️ for your special someone.**

*Happy Valentine's Day!*
