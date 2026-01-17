# 🔍 Different Detective

An interactive "Spot the Difference" game featuring adorable characters from "Different Isn't a Dirty Word."

## 🎮 Play the Game

[Live Demo](#) *(Add your GitHub Pages link here)*

## ✨ Features

- **3 Hidden Differences** - Can you find them all?
- **Interactive Click Detection** - Click on either image to mark differences
- **Visual Feedback** - Green circles mark found differences, red X for wrong clicks
- **Timer & Stats** - Track your time, clicks, and accuracy
- **Hint System** - Get up to 3 hints if you're stuck
- **Responsive Design** - Works great on desktop, tablet, and mobile
- **Victory Screen** - Celebrate your success with detailed stats

## 🎯 The Differences

1. **Purple Creature** - The flying purple character is flipped horizontally
2. **Ball → Kite** - The basketball transforms into an orange kite
3. **Blue Creature's Eye** - One eye changes color

## 🚀 Getting Started

### Quick Start

1. Clone this repository:
```bash
git clone https://github.com/yourusername/different-detective.git
```

2. Open `index.html` in your web browser

That's it! No build process or dependencies required.

### GitHub Pages Deployment

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select your main branch as the source
4. Your game will be live at `https://yourusername.github.io/different-detective`

## 📁 Project Structure

```
different-detective/
├── index.html          # Main game file (HTML, CSS, JS all in one)
├── image1.png          # Original scene
├── image2.png          # Scene with differences
└── README.md           # This file
```

## 🎨 Customization

### Adjusting Difference Locations

Edit the `differences` array in the JavaScript section:

```javascript
const differences = [
    { x: 23, y: 35, radius: 8, name: "Purple Creature" },
    { x: 42, y: 35, radius: 8, name: "Ball to Kite" },
    { x: 72, y: 50, radius: 6, name: "Blue Creature's Eye" }
];
```

- `x` and `y` are percentages (0-100) of image dimensions
- `radius` is the clickable area size
- `name` is just for reference

### Changing Colors

Main color scheme is defined in CSS variables at the top of the style section:
- Primary gradient: `#667eea` to `#764ba2`
- Success color: `#10b981`
- Error color: `#ef4444`
- Hint color: `#f59e0b`

### Adding More Differences

1. Add a new object to the `differences` array
2. Update the total count in the HTML: `<div class="info-value" id="total-count">3</div>`
3. Adjust the subtitle: `Can you spot all X differences?`

## 🎓 How to Play

1. Look carefully at both images
2. Click on any differences you spot (you can click on either image)
3. Green circles will appear when you find a difference
4. Red X marks appear for incorrect clicks
5. Use hints if you get stuck (you have 3)
6. Find all differences to win!

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or libraries
- **Single File** - Everything in one `index.html` for easy deployment
- **Responsive Grid** - Side-by-side on desktop, stacked on mobile
- **Percentage-Based Coordinates** - Works at any screen size
- **CSS Animations** - Smooth, engaging visual feedback

## 📱 Browser Support

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## 📝 License

This game was created for "Different Isn't a Dirty Word" book promotion.

## 🙏 Credits

Based on the wonderful illustrations from "Different Isn't a Dirty Word"

---

**Made with ❤️ for promoting inclusivity and celebrating differences!**
