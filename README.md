# Dither Me This

A Windows 95-themed image dithering tool that brings retro aesthetics to your modern images. Transform photos with classic dithering algorithms and vintage color palettes - all running in your browser!

![Screenshot Placeholder](./screenshot.png)
*Screenshot coming soon*

## Features

- **7 Dithering Algorithms**
  - **Floyd-Steinberg** - Natural, organic-looking patterns (most popular)
  - **Atkinson** - Classic Macintosh high-contrast style
  - **Jarvis-Judice-Ninke** - Smooth gradients with fewer artifacts
  - **Stucki** - Excellent detail preservation
  - **Bayer 8x8** - Medium crosshatch patterns (newspaper print effect)
  - **Bayer 16x16** - Large visible patterns (retro video game look)
  - **Bayer 32x32** - Dramatic patterns for artistic effects

- **Multiple Preset Palettes**
  - Black & White
  - Game Boy (4 greens)
  - CGA (4 colors)
  - Commodore 64
  - Apple II
  - Web Safe (216 colors)

- **Custom Palette Creation**
  - Create your own color palettes with up to 16 colors
  - Visual color picker for each palette color
  - Real-time preview as you adjust colors

- **Batch Processing**
  - Upload and process multiple images at once
  - Download all results as a ZIP file
  - Individual download option available

- **Pattern Size Control**
  - Adjust the dithering pattern scale (10-100%)
  - Lower values create chunkier, more visible dots
  - Higher values produce finer detail

- **Nostalgic Windows 95 UI**
  - Authentic retro interface styling
  - Classic window chrome and controls
  - Period-accurate color scheme and typography

## Technical Details

- **Single-file HTML** - No installation, no build process
- **Client-side processing** - Your images never leave your browser
- **No server required** - Works offline after initial load
- **Canvas-based rendering** - Fast, native image manipulation
- **Modern JavaScript** - ES6+ features for clean, maintainable code
- **Zero tracking** - Complete privacy, no analytics or data collection

### Dependencies

The tool uses only one external library:
- [JSZip](https://stuk.github.io/jszip/) (via CDN) - For creating ZIP archives when downloading multiple images

Everything else is vanilla HTML/CSS/JavaScript!

## Usage

### Quick Start

1. Open `index.html` in any modern web browser
2. Click "Choose Files" to select one or more images
3. Select a dithering algorithm and color palette
4. Click "Process" to apply the effect
5. Download your dithered image(s)

### Algorithm Selection Guide

- **For photos and portraits** → Floyd-Steinberg or Jarvis
- **For logos and bold graphics** → Atkinson
- **For detailed textures** → Stucki
- **For retro/artistic effects** → Any Bayer pattern

### Tips for Best Results

- Start with preset palettes to understand each algorithm's style
- Use lower pattern sizes (30-60%) for more pronounced retro effects
- Game Boy palette works great for landscapes
- Black & White with Floyd-Steinberg produces classic newspaper-style images
- Experiment with custom palettes to match your brand colors

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

Requires JavaScript enabled and HTML5 Canvas support.

## Live Demo

🚀 **[Try it now!](https://nchandrasekharr.github.io/dither-me-this/)**

## Development

This is a single-file application, so development is straightforward:

1. Clone the repository
2. Open `index.html` in your browser
3. Make changes and refresh to see results

No build tools, package managers, or compilation required!

## Contributing

Contributions are welcome! Some ideas:

- Additional dithering algorithms
- More preset palettes
- Export format options (GIF, WebP)
- Histogram visualization
- Before/after comparison slider

## License

MIT License - feel free to use this project for any purpose!

## Credits

Inspired by classic dithering techniques from early personal computers and the aesthetic of Windows 95.

## Acknowledgments

- Floyd-Steinberg, Atkinson, Jarvis-Judice-Ninke, and Stucki algorithms are classic error-diffusion techniques
- Bayer matrix dithering provides ordered patterns common in early printing and displays
- Windows 95 UI recreated with modern CSS

---

Made with nostalgia for the golden age of personal computing 🖥️✨
