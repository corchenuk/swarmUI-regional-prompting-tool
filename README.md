# SwarmUI Regional Prompting Tool

A visual tool for creating regional prompts in SwarmUI. Draw regions on a canvas to generate the exact syntax needed for SwarmUI's regional prompting feature.

## Features

- 🎨 **Visual region editor** - Click and drag to create regions
- 🖼️ **Image overlay support** - Load existing images to plan regional edits
- 📋 **One-click copy** - Copy complete syntax ready for SwarmUI
- 📊 **Live preview** - See region coverage and percentages in real-time
- 🎛️ **Adjustable opacity** - Control region transparency for better visibility

## Usage

### Quick Start
1. Open `index.html` in your browser (or use [GitHub Pages link])
2. Set your image dimensions or load an existing image
3. Click and drag to create regions
4. Copy the generated syntax
5. Paste into SwarmUI's prompt field

### SwarmUI Syntax
The tool generates regions in SwarmUI's format:
```
<region:x,y,width,height>
```
Where all values are percentages (0-1) of the image dimensions.

### Example Workflow
1. Generate an image in SwarmUI with a specific seed
2. Load that image into the tool
3. Draw regions where you want changes
4. Copy the regional syntax
5. Use the same seed + regional prompts for targeted refinements

## Controls

- **Load Image** - Use an existing image as reference
- **Grid Toggle** - Show/hide alignment grid  
- **Opacity Slider** - Adjust region transparency
- **Clear All** - Remove all regions

## Installation

No installation required! Simply:
- Download `index.html` and open locally, or
- Access via GitHub Pages: [your-username.github.io/swarmUI-regional-prompting-tool]

## License

MIT
