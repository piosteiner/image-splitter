# Battle Map Splitter

A web application that splits large battle maps from Procreate into printable A4-sized tiles. Perfect for tabletop RPG enthusiasts who want to print large maps created in Procreate.

## 🎯 Purpose

This tool supports two grid layouts for different battle map sizes:

### 2×3 Grid (6 tiles) - Standard Battle Maps
- **Input Dimensions:** 570 mm × 554 mm
- **DPI:** 150 DPI
- **Pixel Resolution:** 3366 × 3276 pixels
- **Perfect for:** Standard battle encounters, room layouts

### 3×3 Grid (9 tiles) - Large Dungeon Maps
- **Input Dimensions:** 570 mm × 831 mm
- **DPI:** 150 DPI  
- **Pixel Resolution:** 3366 × 4911 pixels
- **Perfect for:** Large dungeons, outdoor areas, multi-room encounters

## 📐 Output Specifications

Each tile will be:
- **Print Size:** 190 mm × 277 mm (fits A4 with margins)
- **Resolution:** 1122 × 1638 pixels at 150 DPI
- **Margins:** 1cm white border around each tile for clean printing
- **Format:** PNG or PDF export options

## 🚀 How to Use

1. **Open the Web App**
   - Open `index.html` in any modern web browser
   - No installation required - runs entirely in your browser

2. **Choose Your Grid Layout**
   - Select **2×3 Grid** for standard battle maps (6 tiles)
   - Select **3×3 Grid** for large dungeon maps (9 tiles)
   - Each layout shows the required input dimensions

3. **Upload Your Battle Map**
   - Click "Choose File" or drag and drop your image
   - Supported formats: PNG, JPG, JPEG
   - The app will validate dimensions against your selected grid

4. **Preview and Configure**
   - View your image with a grid overlay showing all tiles
   - Choose export format: PNG images or PDF files
   - Review the split configuration

5. **Export Tiles**
   - Click "Export Tiles" to generate all tiles
   - Each tile includes 1cm white margins for clean printing
   - Download links will appear for each tile

6. **Print and Assemble**
   - Print each tile on A4 paper
   - Arrange tiles in the selected grid to reconstruct your battle map

## 📁 Project Structure

```
image-splitter/
├── index.html          # Main web page
├── styles.css          # Styling and responsive design
├── script.js           # Core functionality and image processing
└── README.md           # This documentation
```

## 🛠️ Technical Features

- **Dual Grid Support:** Choose between 2×3 (6 tiles) or 3×3 (9 tiles) layouts
- **Smart Validation:** Warns if image dimensions don't match selected grid requirements
- **Client-Side Processing:** No server required, works offline
- **Responsive Design:** Works on desktop, tablet, and mobile
- **Progress Tracking:** Visual progress bar during export
- **Interactive Grid Selection:** Visual preview of grid layouts before upload
- **Drag & Drop:** Easy file upload with drag and drop support
- **Grid Preview:** Visual overlay shows exact tile boundaries

## 🎨 Perfect for Procreate Users

### For Standard Battle Maps (2×3 Grid):
1. Set canvas size to 570mm × 554mm at 150 DPI
2. Create your battle map
3. Export as PNG or JPG
4. Upload to web app and select **2×3 Grid**
5. Print 6 tiles and assemble your battle map!

### For Large Dungeon Maps (3×3 Grid):
1. Set canvas size to 570mm × 831mm at 150 DPI
2. Create your large dungeon or outdoor map
3. Export as PNG or JPG
4. Upload to web app and select **3×3 Grid**
5. Print 9 tiles and assemble your massive battle map!

## 🖥️ Browser Compatibility

Works with all modern browsers that support:
- HTML5 Canvas
- File API
- ES6+ JavaScript

Tested on:
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📱 Mobile Support

The app is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones (for smaller edits)

## 🔧 Customization

The app can be easily customized by modifying the constants in `script.js`:
- `expectedWidth/Height`: Change expected input dimensions
- `tileWidth/Height`: Adjust tile output size
- `marginPixels`: Modify margin size around tiles

## 💡 Tips for Best Results

1. **Use the recommended Procreate settings** for optimal tile sizing
2. **Check image dimensions** before exporting from Procreate
3. **Print at 100% scale** - do not allow your printer to resize
4. **Use high-quality paper** for better results
5. **Test print one tile first** to verify scaling

## 🐛 Troubleshooting

**Image too small/large warning:**
- Your image doesn't match the expected 3366 × 3276 pixels
- The app will still work, but tiles may not fit perfectly on A4

**Blurry output:**
- Ensure your original image is high resolution (150 DPI minimum)
- Check that you're printing at 100% scale

**Tiles don't align:**
- Make sure you print all tiles at the same scale
- Verify your printer settings don't have auto-scaling enabled

## 📄 License

This project is open source and available for personal and commercial use.

---

**Happy Gaming! 🎲**

Perfect for D&D, Pathfinder, and any tabletop RPG that needs large battle maps!