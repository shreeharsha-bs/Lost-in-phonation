# Lost in Phonation: A Benchmark for Voice Quality in Speech Synthesis

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://shreeharsha-bs.github.io/Lost-in-phonation)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository hosts the project website for **Lost in Phonation**, a comprehensive benchmark for evaluating voice quality in modern speech synthesis systems.

## 🌐 Live Website

Visit the live website at: [https://shreeharsha-bs.github.io/Lost-in-phonation](https://shreeharsha-bs.github.io/Lost-in-phonation)

## 📁 Repository Structure

```
Lost-in-phonation/
├── _config.yml              # Jekyll configuration
├── _includes/
│   └── head.html           # HTML head with meta tags
├── _layouts/
│   └── default.html        # Main page layout
├── assets/
│   ├── css/
│   │   └── style.scss      # Custom styles
│   └── audio/              # Audio examples directory
│       └── README.md       # Audio file instructions
├── index.md                # Main content page
├── README.md               # This file
└── LICENSE                 # License file
```

## 🚀 Quick Start

### Local Development

1. **Install Jekyll** (if you haven't already):
   ```bash
   gem install bundler jekyll
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/shreeharsha-bs/Lost-in-phonation.git
   cd Lost-in-phonation
   ```

3. **Create a Gemfile** (if not present):
   ```bash
   bundle init
   bundle add jekyll
   bundle add minima
   ```

4. **Serve the site locally**:
   ```bash
   bundle exec jekyll serve
   ```

5. **View in browser**: Navigate to `http://localhost:4000`

### Deploying to GitHub Pages

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as the source
   - Save

3. **Wait for deployment**: GitHub will build and deploy your site (usually takes 1-2 minutes)

## 📝 Adding Audio Files

1. Place your audio files in the `assets/audio/` directory
2. Use the naming convention specified in `assets/audio/README.md`
3. Supported formats: WAV, MP3 (WAV recommended for quality)

### Example Audio File Names:
- `example1_reference.wav`
- `example1_model_a.wav`
- `example1_model_b.wav`
- etc.

## ✏️ Customizing Content

### Update Paper Information

Edit `index.md` and replace:
- Author names and affiliations
- Abstract text
- Paper links (PDF, GitHub, Dataset)
- Contact information

### Update Audio Examples

1. Add your audio files to `assets/audio/`
2. The HTML `<audio>` tags in `index.md` will automatically reference them
3. Update the prompts and descriptions in the audio example sections

### Modify Styles

Edit `assets/css/style.scss` to customize:
- Colors and gradients
- Layout and spacing
- Font sizes and styles
- Responsive breakpoints

## 🎨 Features

- ✅ Responsive design (mobile-friendly)
- ✅ Professional gradient theme
- ✅ Organized audio example sections
- ✅ Model comparison tables
- ✅ Smooth animations and transitions
- ✅ SEO optimized
- ✅ Social media preview cards

## 📊 Section Overview

The website includes:
1. **Hero Section**: Title, authors, paper links
2. **Abstract**: Research overview
3. **Key Contributions**: Main findings
4. **Voice Quality Dimensions**: Interactive grid
5. **Benchmark Results**: Performance summary
6. **Audio Examples**: Multiple example categories
7. **Comparison Table**: Side-by-side model comparison
8. **Dataset Information**: Download and structure
9. **Methodology**: Research approach
10. **Code Resources**: Quick start and examples
11. **Citation**: BibTeX format
12. **Team & Contact**: Author information

## 🔧 Troubleshooting

### Site Not Building?
- Check that all files are properly committed
- Verify `_config.yml` has correct settings
- Check GitHub Actions tab for build errors

### Audio Not Playing?
- Ensure audio files are in `assets/audio/`
- Check file paths match exactly (case-sensitive)
- Verify audio format is supported (WAV, MP3)

### Styles Not Applying?
- Clear browser cache
- Ensure `style.scss` has front matter (`---` at top)
- Check browser console for errors

## 📄 License

This project is licensed under the Creative Commons Attribution 4.0 International License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or issues:
- Open an issue on GitHub
- Contact: [your-email@example.com]

---

**Note**: This website is designed to complement your research paper. Make sure to update all placeholder content with your actual research data and audio examples before publishing!
