# Image Resizer - WeChat Friendly

A browser-based image resizing and compression tool that processes images entirely in your browser. Perfect for preparing images for WeChat sharing where file size limits apply (3 MB).

## Features

### 📤 Upload & Drag & Drop
- Drag and drop images directly onto the upload area
- Click to browse and select multiple files
- Supports batch uploading

### 📏 Resolution Options
Select from preset resolutions or use custom dimensions:
- **4K Ultra HD** (3840×2160)
- **1080p HD** (1920×1080)
- **720p Standard** (1280×720)
- **480p SD** (854×480)
- **Custom** (specify your own width and height)

### 🔄 Aspect Ratio Control
- **Maintain original aspect ratio** (default): Images are scaled proportionally to fit within the selected dimensions
- **Unchecked**: Images are stretched/cropped to exactly match the resolution

### 🎚️ Quality Control
- **Low (60%)** - Smaller file size, faster processing
- **Medium (80%)** - Balanced quality and size
- **High (92%)** - Best quality (recommended for photos)
- **Custom** - Specify your own quality percentage (1-100%)

### 📦 Download Options
- **Download All** - Downloads each compressed image individually (triggers multiple downloads)
- **Download All in Zip** - Bundles all compressed images into a single ZIP file for easy sharing

### 🌓 Dark Mode
Toggle between light and dark themes for comfortable viewing in any environment.

### 🌐 Multilingual Support
- **English** (default)
- **Chinese (简体中文)**

### 📊 Real-time Statistics
Each compressed image displays:
- Original and new resolution
- File size comparison
- Compression rate
- Quality setting

### 🚫 Clear All
Remove all uploaded and compressed images with one click.

## Supported Formats
- **JPEG/JPG**
- **PNG**
- **WebP**

## Privacy & Security
🔒 **All processing happens entirely in your browser.** No files are uploaded to any server. Your images never leave your device.

## WeChat Compatibility
This tool is optimized for WeChat sharing. The default settings are configured to help you stay under WeChat's 3 MB file size limit for shared images.

## How to Use

1. **Upload Images**
   - Drag and drop your images onto the upload area, or click to browse
   - Multiple files are supported

2. **Select Resolution**
   - Choose from preset resolutions or select "Custom" for specific dimensions

3. **Adjust Quality**
   - Select a quality level that balances file size and visual quality

4. **Compress**
   - Click "Resize All" to process your images
   - Progress bar shows processing status

5. **Download**
   - Individual: Click the download button on any image card
   - All images: Click "Download All" (downloads each separately)
   - All as ZIP: Click "Download All in Zip" (single ZIP file)

## Technical Details

### Libraries Used
- **JSZip 3.10.1** - For creating ZIP files in the browser
- Pure JavaScript, no frameworks required

### Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

### Processing
Images are processed using the HTML5 Canvas API with:
- Automatic aspect ratio calculation
- Portrait image orientation detection
- Smart scaling to prevent upscaling
- Base64 encoding for preview and download

## Features Not Yet Implemented
- Image rotation
- Batch processing with progress cancellation
- Preview before compression
- Advanced image editing (crop, filter, etc.)

## License
MIT

## Credits
Built with vanilla JavaScript and browser APIs. No server required.
