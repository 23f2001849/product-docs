# Software Product Documentation with Marp

## Overview

This repository contains a comprehensive software product documentation presentation built with Marp, demonstrating modern technical writing practices and version-controlled documentation workflows.

## Features

- ✅ **Marp Markdown Presentation** - Professional slides with custom styling
- ✅ **Email Integration** - Contact information included as requested
- ✅ **Custom Theme** - Modern dark theme with syntax highlighting
- ✅ **Page Numbers** - Automatic pagination using Marp directives
- ✅ **Background Image** - Professional workspace imagery
- ✅ **Mathematical Equations** - Algorithm complexity analysis with MathJax
- ✅ **Version Control Ready** - Markdown format for easy Git tracking
- ✅ **Multiple Export Formats** - PDF, HTML, and image exports

## Repository Structure

```
├── slides.md              # Main Marp presentation file
├── docs-workspace.png     # Background image for slides
├── README.md              # This documentation file
├── .github/               # GitHub configuration
│   └── workflows/         # CI/CD workflows
│       └── marp.yml       # Marp build and deploy workflow
└── resources/             # Additional resources
    ├── templates/         # Documentation templates
    └── examples/          # Code examples
```

## Presentation Content

### Slide Sections

1. **Title & Introduction** - Overview and table of contents
2. **Documentation Fundamentals** - Best practices and principles
3. **API Documentation** - Standards and examples
4. **Algorithm Complexity** - Mathematical analysis
5. **Version Control** - Git integration workflows
6. **Tools & Automation** - Modern documentation toolchain
7. **Quality Assurance** - Testing and metrics
8. **Performance Optimization** - Speed and efficiency
9. **Security & Compliance** - Documentation security
10. **Analytics & Improvement** - Data-driven documentation
11. **Case Studies** - Real-world examples
12. **Future Trends** - Emerging technologies

### Key Features Implemented

- **Custom Styling**: Modern dark theme with blue accents
- **Mathematical Equations**: Algorithm complexity formulas
- **Interactive Elements**: Code blocks, tables, and diagrams
- **Professional Design**: Clean typography and layout
- **Responsive Design**: Works on all device sizes

## Usage

### Viewing the Presentation

1. **Marp CLI** (Recommended):
   ```bash
   npm install -g @marp-team/marp-cli
   marp slides.md -w
   ```

2. **VS Code Extension**:
   - Install "Marp for VS Code" extension
   - Open `slides.md` and use preview mode

3. **Export to PDF**:
   ```bash
   marp slides.md --pdf
   ```

4. **Export to HTML**:
   ```bash
   marp slides.md --html
   ```

### GitHub Integration

The presentation is automatically deployed to GitHub Pages when changes are pushed to the main branch. The raw Markdown file can be accessed via:

```
https://raw.githubusercontent.com/23f2001849/software-docs/main/slides.md
```

## Technical Specifications

### Marp Configuration

- **Theme**: Custom dark theme with syntax highlighting
- **Size**: 16:9 aspect ratio (1920×1080)
- **Pagination**: Automatic page numbering
- **Background**: Professional workspace imagery
- **Math Support**: MathJax for mathematical equations

### Dependencies

- **Marp CLI**: Latest version
- **Node.js**: 16.x or higher
- **Git**: For version control

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test the presentation locally
5. Submit a pull request

## Contact

For questions or feedback, please contact:

- **Email**: [23f2001849@ds.study.iitm.ac.in](mailto:23f2001849@ds.study.iitm.ac.in)
- **GitHub**: [@23f2001849](https://github.com/23f2001849)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Quick Start

### Prerequisites

- Node.js (16.x or higher)
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/23f2001849/software-docs.git
cd software-docs

# Install Marp CLI globally
npm install -g @marp-team/marp-cli

# View the presentation
marp slides.md -w

# Export to PDF
marp slides.md --pdf

# Export to HTML
marp slides.md --html
```

### Development

1. Edit `slides.md` to modify content
2. Use `marp slides.md -w` for live preview
3. Commit changes to Git for version control
4. Push to GitHub for automatic deployment

## Troubleshooting

### Common Issues

1. **Marp CLI not found**: Ensure Node.js and Marp CLI are installed globally
2. **Images not displaying**: Check image paths and file permissions
3. **Math not rendering**: Verify MathJax support in your viewer
4. **Styling issues**: Ensure all CSS is properly included

### Support

For technical support, please:

1. Check the [Marp documentation](https://marpit.marp.app/)
2. Search existing [GitHub issues](https://github.com/23f2001849/software-docs/issues)
3. Create a new issue with detailed information

## Acknowledgments

- **Marp Team** for the excellent presentation framework
- **Technical writing community** for best practices and insights
- **Open source contributors** for tools and inspiration