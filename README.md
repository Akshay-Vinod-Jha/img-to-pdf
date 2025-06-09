# Image to PDF Converter

A simple and efficient web-based tool to convert your images into PDF documents. Supports drag-and-drop functionality and multiple image formats for seamless PDF creation.

## 🔗 Live Demo

**Convert your images:** [https://akshay-vinod-jha.github.io/img-to-pdf/](https://akshay-vinod-jha.github.io/img-to-pdf/)

## ✨ Key Features

- **Drag & Drop Interface**: Simply drag your images into the drop zone
- **Multiple Upload Options**: Choose files via file browser or drag-and-drop
- **Multiple Image Support**: Convert multiple images into a single PDF
- **Format Support**: Supports common image formats (JPEG, PNG, GIF, WebP)
- **Client-Side Processing**: All conversions happen in your browser
- **No Upload Required**: Images never leave your device
- **Instant Download**: Get your PDF immediately after conversion
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Progress Indicator**: Real-time conversion progress feedback

## 🖼️ Supported Image Formats

| Format | Extension | Support |
|--------|-----------|---------|
| JPEG | `.jpg`, `.jpeg` | ✅ Full |
| PNG | `.png` | ✅ Full |
| GIF | `.gif` | ✅ Full |
| WebP | `.webp` | ✅ Full |
| BMP | `.bmp` | ✅ Full |
| SVG | `.svg` | ✅ Full |

## 🚀 How to Use

### Method 1: Drag & Drop
1. **Drag Images**: Drag your image files into the drop zone
2. **Preview**: See your selected images in the preview area
3. **Convert**: Click "Convert To PDF" button
4. **Download**: PDF will be generated and downloaded automatically

### Method 2: File Upload
1. **Upload Files**: Click "UPLOAD FILES" button
2. **Select Images**: Choose multiple images from your device
3. **Convert**: Click "Convert To PDF" button
4. **Download**: Your PDF will be ready for download

## 🛠️ Technologies Used

- **HTML5**: File API and drag-and-drop functionality
- **CSS3**: Modern styling and responsive design
- **JavaScript ES6**: Core conversion logic and DOM manipulation
- **PDF.js or jsPDF**: PDF generation library
- **Canvas API**: Image processing and manipulation
- **GitHub Pages**: Hosting and deployment

## 📁 Project Structure

```
img-to-pdf/
├── index.html          # Main application interface
├── style.css           # Styling and responsive design
├── script.js           # Image processing and PDF generation
├── README.md           # Project documentation
└── assets/             # Icons and images
    ├── icons/          # UI icons
    └── images/         # Demo images
```

## ⚙️ Core Functionality

### Image Processing Pipeline
1. **File Selection**: Handles both drag-drop and file picker
2. **Image Validation**: Checks file types and sizes
3. **Canvas Rendering**: Converts images to canvas for processing
4. **PDF Generation**: Creates PDF document with proper sizing
5. **Download Trigger**: Automatically downloads the generated PDF

### Key Features Implementation
- **Drag & Drop**: HTML5 drag events with visual feedback
- **File Validation**: Client-side format and size checking
- **Image Optimization**: Automatic resizing and compression
- **Multi-page PDF**: Combines multiple images into single document
- **Progress Tracking**: Real-time conversion status updates

## 🔧 Local Development

### Prerequisites
- Modern web browser with HTML5 support
- No additional software required

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/akshay-vinod-jha/img-to-pdf.git
   cd img-to-pdf
   ```

2. **Open in browser**
   ```bash
   # Direct method
   open index.html
   
   # Or with local server
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

3. **Start converting**
   - Drag images or use upload button
   - Test with various image formats
   - Check conversion functionality

## 📊 Performance Features

- **Client-Side Processing**: No server dependency
- **Memory Efficient**: Optimized image handling
- **Fast Conversion**: Immediate processing without delays
- **Batch Processing**: Handle multiple images simultaneously
- **Progress Feedback**: Visual indicators during conversion

## 🎨 User Experience

### Interface Design
- **Clean Layout**: Minimalist and intuitive design
- **Visual Feedback**: Clear drag-and-drop indicators
- **Responsive**: Adapts to all screen sizes
- **Accessibility**: Keyboard navigation support
- **Error Handling**: Clear error messages and recovery options

### Conversion Process
1. **Upload Stage**: Drag-drop or file selection
2. **Preview Stage**: Show selected images
3. **Processing Stage**: Convert with progress indicator
4. **Download Stage**: Automatic PDF download

## 🌐 Browser Compatibility

| Browser | Version | Support | Notes |
|---------|---------|---------|-------|
| Chrome | 50+ | ✅ Full | Recommended |
| Firefox | 45+ | ✅ Full | Full support |
| Safari | 10+ | ✅ Full | Works well |
| Edge | 79+ | ✅ Full | Modern Edge |
| Mobile Chrome | Latest | ✅ Full | Touch optimized |
| Mobile Safari | Latest | ✅ Full | iOS compatible |

## 🔒 Privacy & Security

- **No Data Upload**: All processing happens locally
- **Privacy First**: Images never leave your device
- **No Storage**: Files are not stored anywhere
- **Secure Processing**: Client-side only operations
- **No Tracking**: No analytics or user tracking

## 🤝 Contributing

Help improve this image to PDF converter!

### How to Contribute
1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/improvement`)
3. **Commit** your changes (`git commit -m 'Add enhancement'`)
4. **Push** to branch (`git push origin feature/improvement`)
5. **Open** a Pull Request

### Contribution Ideas
- [ ] Add password protection for PDFs
- [ ] Implement image compression options
- [ ] Add custom page sizes (A4, Letter, etc.)
- [ ] Include image rotation functionality
- [ ] Add batch conversion with zip download
- [ ] Implement image cropping tools
- [ ] Add watermark functionality
- [ ] Create PDF merge capabilities

## 🎯 Future Enhancements

- **PDF Customization**: Page size, orientation, margins
- **Image Editing**: Basic editing tools (crop, rotate, resize)
- **Batch Operations**: Convert multiple sets of images
- **Cloud Integration**: Optional cloud storage integration
- **Advanced Options**: Compression levels, quality settings
- **Template Support**: Pre-defined PDF layouts
- **OCR Integration**: Text recognition from images

## ⚠️ Limitations

- **File Size**: Large images may take longer to process
- **Browser Memory**: Limited by browser memory constraints
- **Format Support**: Depends on browser image support
- **Processing Speed**: Varies based on device performance

## 📱 Mobile Optimization

- **Touch Friendly**: Optimized for touch interactions
- **Responsive Design**: Adapts to mobile screen sizes
- **File Access**: Uses mobile file picker
- **Performance**: Optimized for mobile browsers

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Developer

**Akshay Vinod Jha**
- GitHub: [@akshay-vinod-jha](https://github.com/akshay-vinod-jha)
- Project: [Image to PDF Converter](https://github.com/akshay-vinod-jha/img-to-pdf)

## 🙏 Acknowledgments

- HTML5 File API for client-side file handling
- Canvas API for image processing
- PDF generation libraries for document creation
- GitHub Pages for free hosting
- Open source community for inspiration

---

📄 **Convert your images to PDF instantly!** 🖼️➡️📄

*"Transform your images into professional PDF documents with just a few clicks."*
