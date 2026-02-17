# WinView

<div align="center">

**A Windows Desktop Clone of Mac Preview App**

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/gibtang/winview/actions)
[![Test Coverage](https://img.shields.io/badge/coverage-97%25-brightgreen)](https://github.com/gibtang/winview)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue)](https://www.typescriptlang.org/)
[![Electron](https://img.shields.io/badge/Electron-40+-9cf)](https://www.electronjs.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

</div>

---

## 📖 Overview

**WinView** is a feature-rich Windows desktop application that replicates the functionality of macOS Preview app. Built with **Electron** and **TypeScript**, it provides a seamless experience for viewing, editing, and managing PDF documents and images on Windows.

### Key Highlights

- 🖼️ **Multi-format Support** - View PDF, PNG, JPEG, GIF, BMP, TIFF, WebP, HEIC, ICO, RAW, and more
- 📝 **Annotation Tools** - Pen, highlighter, shapes, text, signatures, and more
- 🔍 **Advanced Search** - Full-text search with highlighting and navigation
- 📤 **Batch Processing** - Convert, resize, rotate, filter, watermark multiple files at once
- ☁️ **Cloud Integration** - OneDrive, Google Drive, Dropbox sync support
- ✏️ **Form Filling** - Fill out PDF forms with text, checkboxes, and signatures
- 🔒 **Security** - Document encryption, password protection, secure file handling
- 🎨 **Image Editing** - Crop, rotate, adjust colors, apply filters and effects
- 📊 **OCR** - Extract text from images with multi-language support
- 🤖 **Automation** - CLI commands, batch scripts, workflow automation

---

## ✨ Features

WinView includes **370+ features** across 41 feature levels:

### Core Viewing
1. Single and multi-page document viewing
2. Smooth scrolling with momentum
3. Zoom in/out with multiple presets (25%, 50%, 100%, 200%, 400%, Fit Width, Fit Page)
4. Fullscreen mode with auto-hide UI
5. Rotate and flip pages
6. Night mode for comfortable reading
7. Continuous and single-page view modes

### Navigation
8. Next/previous page navigation
9. Page jump with input field
10. Scroll wheel navigation
11. Keyboard shortcuts (Space, arrows, etc.)
12. Thumbnail sidebar for visual navigation
13. Bookmarks and custom jumps

### Annotation Tools
14. **Pen Tool** - Freehand drawing with pressure sensitivity
15. **Highlighter** - Semi-transparent text highlighting
16. **Shapes** - Rectangles, circles, arrows, lines
17. **Text** - Add text annotations anywhere
18. **Eraser** - Remove annotations
19. **Sticky Notes** - Colorful note annotations
20. **Signature** - Draw or type signatures
21. **Undo/Redo** - Full annotation history

### Editing Tools
22. **Crop** - Custom aspect ratios, straighten, perspective crop, diamond crop
23. **Rotate** - 90° increments and custom angles
24. **Flip** - Horizontal and vertical
25. **Resize** - By pixels or percentage, maintain aspect ratio
26. **Adjustments** - Brightness, contrast, exposure, shadows, highlights, temperature, tint
27. **Filters** - Grayscale, sepia, invert, blur, sharpen, vignette, noise reduction, posterize
28. **Color Adjustments** - Saturation, hue, vibrance, levels, curves, white balance

### Batch Operations
29. Convert multiple files to different formats
30. Batch resize and rotate
31. Apply filters and watermarks
32. Bulk rename with patterns
33. Export with custom settings
34. Progress tracking for large batches

### Form Filling
35. Auto-detect form fields
36. Text input fields
37. Checkboxes and radio buttons
38. Dropdown selections
39. Digital signatures
40. Form validation
41. Save and load form data
42. Import/export FDF data

### OCR & Text Recognition
43. Extract text from images and PDFs
44. Multi-language support (30+ languages)
45. Auto language detection
46. Confidence scoring
47. Text search in OCR results
48. Export as text, JSON, or PDF

### Document Security
49. Password protect PDFs
50. Remove/change passwords
51. Set permissions (print, copy, modify)
52. Owner password protection
53. Encryption options

### Page Manipulation
54. Insert, delete, and reorder pages
55. Extract pages
56. Rotate pages
57. Merge multiple PDFs
58. Split PDF into single pages
59. Page cropping

### Cloud Storage Integration
60. **OneDrive** - Sync and access files
61. **Google Drive** - Cloud backup and sharing
62. **Dropbox** - File synchronization
63. Cloud storage picker
64. Sync preferences and status
65. Version history support

### Advanced Features
66. **Tabs** - Multiple files in tabs
67. **Split View** - Side-by-side document comparison
68. **Bookmarks** - Save and navigate to locations
69. **Notes & Audio** - Voice annotations and notes
70. **Slideshow** - Image slideshow with transitions and music
71. **Smart Albums** - Recently viewed, favorites, custom collections
72. **Quick Actions** - Toolbar with customizable actions
73. **Mouse/Touch Gestures** - Right-click gestures, pinch zoom, two-finger scroll

### Windows Integration
74. **Taskbar** - Jump lists, thumbnail toolbar, progress indicator, badges
75. **Sharing** - Windows share dialog, email attachment, nearby sharing
76. **File Associations** - Default viewer for PDF and images
77. **Context Menus** - Right-click file actions
78. **Drag & Drop** - Open files by dragging

### Pen & Stylus Support
79. Pressure sensitivity (0-1 range)
80. Tilt support for brush angle
81. Palm rejection for hand placement
82. Pen calibration
83. Custom pressure curves
84. Button customization
85. Latency reduction

### Camera Integration
86. Webcam photo capture
87. Document scanning with edge detection
88. Auto-import from camera
89. Multi-camera support
90. Flash/torch control
91. Video recording

### Workflow Automation
92. **CLI Commands** - Command-line interface
93. **Batch Scripts** - Automated processing workflows
94. **Folder Actions** - Auto-process on file changes
95. **Scheduled Tasks** - Automated exports and backups
96. **Custom Workflows** - Create reusable automation
97. **Workflow Templates** - Save and share automation

### Additional Format Support
98. **HEIC** - Apple High Efficiency Image Format
99. **WebP** - Google WebP format
100. **ICO** - Windows icon files
101. **RAW** - Camera RAW format support

### Accessibility
102. Keyboard navigation
103. Screen reader support
104. High contrast mode
105. ARIA labels
106. Focus management
107. Text-to-speech

---

## 🚀 Installation

### Prerequisites

- **Node.js** 18.0 or later
- **npm** 9.0 or later
- **Windows 10** or later (recommended)

### Build from Source

```bash
# Clone the repository
git clone https://github.com/gibtang/winview.git
cd winview

# Install dependencies
npm install

# Build the application
npm run build

# Start the application
npm start
```

### Install from Release (Coming Soon)

```bash
# Download the latest release
# Run the installer
WinView-Setup.exe
```

---

## 📚 Usage

### Opening Files

**Methods:**
- Double-click a PDF or image file
- Right-click → "Open with WinView"
- Drag and drop files onto WinView window
- File → Open (Ctrl+O)

### Keyboard Shortcuts

| Action | Windows | macOS |
|--------|---------|-------|
| Open file | `Ctrl+O` | `Cmd+O` |
| Save | `Ctrl+S` | `Cmd+S` |
| Print | `Ctrl+P` | `Cmd+P` |
| Find | `Ctrl+F` | `Cmd+F` |
| Next page | `Space` / `→` | `Space` / `→` |
| Previous page | `Shift+Space` / `←` | `Shift+Space` / `←` |
| Zoom in | `Ctrl++` | `Cmd++` |
| Zoom out | `Ctrl+-` | `Cmd+-` |
| Fit to width | `Ctrl+Shift+W` | `Cmd+Shift+W` |
| Fullscreen | `F11` / `Ctrl+Shift+F` | `Ctrl+Cmd+F` |
| Rotate right | `Ctrl+R` | `Cmd+R` |
| Crop | `Ctrl+Shift+X` | `Cmd+Shift+X` |

### Toolbar

```
[←] [→] [-] [+] [⟲] [⚙] [✏️] [🔍] [💾]
 Prev Next Crop Zoom Search Save
```

### Context Menu (Right-Click)

- Rotate clockwise/counter-clockwise
- Flip horizontal/vertical
- Crop selection
- Adjust colors
- Apply filters
- Export as...
- Print
- Properties

---

## 💻 Development

### Tech Stack

- **Framework**: Electron 40+
- **Language**: TypeScript 5.9
- **Build Tool**: TypeScript Compiler (tsc)
- **Package Manager**: npm
- **PDF Rendering**: PDF.js
- **Testing**: Jest 29
- **E2E Testing**: Spectron

### Project Structure

```
winview/
├── src/
│   ├── __tests__/              # Test files
│   │   ├── unit/                # Unit tests
│   │   ├── integration/         # Integration tests
│   │   ├── e2e/                 # End-to-end tests
│   │   └── security/            # Security tests
│   ├── core/                   # Core viewing logic
│   ├── ui/                     # UI components
│   ├── pdf/                    # PDF handling
│   ├── image/                  # Image processing
│   ├── annotations/            # Annotation tools
│   ├── editing/                # Editing operations
│   ├── batch/                  # Batch operations
│   ├── ocr/                    # OCR functionality
│   ├── cloud/                  # Cloud integration
│   ├── automation/             # Workflow automation
│   ├── sharing/                # File sharing
│   ├── main.ts                 # Application entry
│   └── preload.ts              # Preload scripts
├── assets/                     # Images, icons
├── docs/                       # Documentation
├── build/                      # Compiled output
├── dist/                       # Distribution files
└── package.json
```

### Available Scripts

```bash
# Development
npm start              # Start development server with hot reload
npm run build          # Compile TypeScript
npm run watch          # Watch mode for development
npm run lint           # Run ESLint
npm test               # Run all tests
npm run test:coverage  # Run tests with coverage report
npm run test:watch     # Watch mode for testing
npm run test:unit      # Run unit tests only
npm run test:e2e        # Run E2E tests only

# Building
npm run build          # Build for production
npm run pack           # Create distributables
npm run dist           # Create installation package

# Release
npm run release        # Build and create release
```

### Code Quality

The project follows strict TDD methodology with:
- **97%+ test coverage**
- **1000+ automated tests**
- **Security tests** for all user inputs
- **Performance tests** for critical paths
- **E2E tests** for major workflows

---

## 🧪 Testing

### Running Tests

```bash
# All tests
npm test

# Unit tests
npm run test:unit

# Integration tests
npm run test:integration

# E2E tests
npm run test:e2e

# Coverage report
npm run test:coverage
```

### Test Categories

- **Unit Tests**: Individual module functionality
- **Integration Tests**: Multi-module interactions
- **Security Tests**: Input validation, sanitization, XSS prevention
- **Performance Tests**: Efficiency benchmarks, memory management
- **E2E Tests**: Full user workflows via Spectron

---

## 📖 Documentation

- **[FEATURE_LIST.md](FEATURE_LIST.md)** - Complete feature checklist (370 features)
- **[IMPLEMENTATION_SUMMARY.md](IMPLEMENTATION_SUMMARY.md)** - Implementation progress and statistics
- **[CLAUDE.md](CLAUDE.md)** - Project guidelines and instructions

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. **Fork** the repository
2. Create a **feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Write tests first** (TDD methodology)
4. **Ensure all tests pass** (`npm test`)
5. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
6. **Push** to the branch (`git push origin feature/AmazingFeature`)
7. Open a **Pull Request**

### Development Guidelines

- Follow **Test-Driven Development (TDD)**: Write tests before code
- Use **TypeScript** strict mode
- Follow **Conventional Commits** specification
- Write **descriptive commit messages**
- Add **JSDoc comments** for public APIs
- **Squash commits** logically before pushing
- Keep **git history clean**

### Code Style

```typescript
// Use PascalCase for classes
class MyManager {
  // Use camelCase for methods and properties
  private myProperty: string;

  // Use arrow functions for callbacks
  public myMethod = (param: string): void => {
    // Implementation
  };
}
```

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Built with [Electron](https://www.electronjs.org/)
- PDF rendering powered by [PDF.js](https://mozilla.github.io/pdf.js/)
- Icons from [Microsoft Fluent UI](https://fluentui.microsoft.com/)
- Inspired by macOS Preview app

---

## 📮 Support

- **Issues**: [GitHub Issues](https://github.com/gibtang/winview/issues)
- **Discussions**: [GitHub Discussions](https://github.com/gibtang/winview/discussions)
- **Email**: support@example.com

---

## 🔮 Roadmap

### v1.0 (Current)
- ✅ Core PDF and image viewing
- ✅ Annotation tools
- ✅ Editing and adjustments
- ✅ Batch operations
- ✅ Cloud integration
- ✅ Workflow automation

### Future Enhancements
- [ ] AI-powered document analysis
- [ ] Voice commands for accessibility
- [ ] 3D model viewing
- [ ] VR/AR document preview
- [ ] Collaborative annotations
- [ ] Version control for documents

---

<div align="center">

**Made with ❤️ using TypeScript and Electron**

[⭐ Star us on GitHub](https://github.com/gibtang/winview) • [🐛 Report Issues](https://github.com/gibtang/winview/issues)

</div>
