<div align="center">

# Professional LaTeX Report Template

![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge) ![LaTeX](https://img.shields.io/badge/LaTeX-Professional-blue?style=for-the-badge&logo=latex) ![Version](https://img.shields.io/badge/Version-2.0-orange?style=for-the-badge) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge) ![Maintenance](https://img.shields.io/badge/Maintained-Yes-green.svg?style=for-the-badge) ![Overleaf](https://img.shields.io/badge/Overleaf-Compatible-47A141?style=for-the-badge&logo=overleaf&logoColor=white)

**Professional, modular LaTeX template** for internship reports, thesis, and academic documents.  
Modern typography • Automated compilation • Cross-platform compatibility

[📖 Complete Tutorial](TUTORIAL.md) • [🚀 Quick Start](#-quick-start) • [🔧 Commands](#-commands) • [🤝 Contributing](#-contributing)

</div>

---

## ✨ Key Features

- **Professional Typography** - Times New Roman, optimized spacing, clean layouts
- **Automated Compilation** - Python scripts with auto-watch mode
- **Modular Architecture** - Separated configuration, content, and templates
- **Cross-Platform** - Windows, macOS, Linux, and Overleaf compatible
- **Smart References** - Automatic numbering and hyperlinked cross-references
- **Academic Standards** - Follows international formatting guidelines

## 📸 Preview

See Sample tutorial document based on this template [here](build/main.pdf).

<details open>
<summary><strong>Template Screenshots</strong></summary>

<table>
<tr>
    <th></th>
    <th></th>
</tr>
<tr>
    <td>
    <strong>Title Page</strong>
    </td>
    <td>
    <strong>Chapter Layout</strong>
    </td>
</tr>
<tr>
    <td>
    <img src="assets/images/examples/title-page.png"/>
    </td>
    <td>
    <img src="assets/images/examples/chapter-layout.png"/>
    </td>
</tr>
<tr>
    <td>
        <strong>Tables and Figures</strong>
    </td>
    <td>
        <strong>Bibliography</strong>
    </td>
</tr>
<tr>
    <td>
        <img src="assets/images/examples/tables-figures.png"/>
    </td>
    <td>
        <img src="assets/images/examples/bibliography.png"/>
    </td>
</tr>
</table>

</details>

## 🛠️ Tech Stack

This template leverages modern LaTeX packages and tools for optimal document production:

<details>
<summary><strong>↕️ Expand for more!</strong></summary>
<br/>

<div align="center">


| **Category** | **Technology** | **Role** |
|--------------|----------------|----------|
| **Document Engine** | ![LaTeX](https://img.shields.io/badge/LaTeX-2023+-008080?style=for-the-badge&logo=latex) | Document typesetting |
| | ![XeLaTeX](https://img.shields.io/badge/XeLaTeX/pdfLaTeX-Latest-4CAF50?style=for-the-badge&logo=latex) | Compilation engine |
| | ![Biber](https://img.shields.io/badge/Biber-2.19+-FF6B35?style=for-the-badge) | Bibliography processor |
| **Typography** | ![Times](https://img.shields.io/badge/Times/mathptmx-Latest-8E44AD?style=for-the-badge) | Font system |
| | ![FontAwesome](https://img.shields.io/badge/FontAwesome-6+-339AF0?style=for-the-badge&logo=fontawesome) | Icon system |
| | ![Geometry](https://img.shields.io/badge/Geometry-Latest-E67E22?style=for-the-badge) | Page layout |
| **Core Packages** | ![biblatex](https://img.shields.io/badge/biblatex-Latest-2ECC71?style=for-the-badge) | Bibliography management |
| | ![hyperref](https://img.shields.io/badge/hyperref-Latest-3498DB?style=for-the-badge) | PDF features |
| | ![tcolorbox](https://img.shields.io/badge/tcolorbox-Latest-9B59B6?style=for-the-badge) | Advanced boxes |
| | ![tikz](https://img.shields.io/badge/tikz/pgfplots-Latest-E74C3C?style=for-the-badge) | Graphics engine |
| **Development Tools** | ![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white) | Build automation |
| | ![VS Code](https://img.shields.io/badge/VS_Code-Latest-007ACC?style=for-the-badge&logo=visualstudiocode) | Development environment |
| | ![Git](https://img.shields.io/badge/Git-2.0+-F05032?style=for-the-badge&logo=git&logoColor=white) | Version control |
| **Online Platforms** | ![Overleaf](https://img.shields.io/badge/Overleaf-Cloud-47A141?style=for-the-badge&logo=overleaf&logoColor=white) | Cloud editing |
| | ![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white) | Repository hosting |
| **Diagram Tools** | ![PlantUML](https://img.shields.io/badge/PlantUML-Latest-orange?style=for-the-badge) | UML diagrams |
| | ![Mermaid](https://img.shields.io/badge/Mermaid-Latest-FF3670?style=for-the-badge&logo=mermaid&logoColor=white) | Flowcharts |
| | ![TikZ](https://img.shields.io/badge/TikZ-Latest-red?style=for-the-badge) | Technical drawings |

</div>

</details>

## 📋 Prerequisites

**For Local Use:**
- LaTeX Distribution (TeX Live 2023+ or MiKTeX)
- Python 3.8+
- Git

## 🚀 Quick Start

### Option 1: Use Online (Easiest)

1. **Download** this repository as ZIP
2. **Upload to [Overleaf](https://overleaf.com)**
3. **Set compiler** to `pdfLaTeX`
4. **Edit `metadata.tex`** with your information
5. **Start writing** in `content/chapters/`

### Option 2: Local Development

```bash
# Clone and setup
git clone https://github.com/sikatikenmogne/latex-report-template.git
cd latex-report-template

# Check environment
python scripts/check.py

# Compile document
python scripts/compile.py

# Watch for changes (auto-compile)
python scripts/watch.py
```

**For Online Use:**
- [Overleaf](https://overleaf.com) account (free)

## 🔧 Commands

| Command | Description |
|---------|-------------|
| `make build` | Compile the document |
| `make watch` | Auto-compile on file changes |
| `make release TAG=v1.0.0` | Create new release |
| `python scripts/check.py` | Validate environment |
| `python scripts/release.py list` | List all releases |

## 📁 Project Structure

```
latex-report-template/
├── main.tex                    # Main document
├── metadata.tex                # Your information here
├── titlepage.tex               # Custom title page
├── internshipreport.cls        # Document class
├── config/                     # Template configuration
│   ├── colors.tex              # Color scheme
│   ├── packages.tex            # LaTeX packages
│   └── style.tex               # Typography
├── content/                    # Your content
│   ├── chapters/               # Main chapters
│   └── frontmatter/            # TOC, abstract, etc.
├── scripts/                    # Build automation
│   ├── compile.py              # Compilation script
│   ├── watch.py                # Auto-compiler
│   └── release.py              # Release management
└── assets/                     # Images and logos
    ├── images/                 # Your figures
    └── logos/                  # Institution logos
```

## 📖 Documentation

**📘 Complete Guide:** [TUTORIAL.md](TUTORIAL.md) - Comprehensive documentation with examples

**⚡ Quick References:**
- [Installation Guide](TUTORIAL.md#-quick-start)
- [Configuration](TUTORIAL.md##️-basic-configuration)
- [Writing Content](TUTORIAL.md##️-writing-content)

## 🎯 Quick Configuration

Edit `metadata.tex` with your information:

```latex
\renewcommand{\reporttitle}{Your Report Title}
\renewcommand{\reportauthor}{Your Name}
\renewcommand{\company}{Company Name}
\renewcommand{\university}{Your University}
\renewcommand{\defensedate}{Date}
```

That's it! The template handles the rest automatically.

## 🚀 Release Management

Create automatic releases with PDF generation:

```bash
# Create release (any tag format)
python scripts/release.py create v1.0.0
python scripts/release.py create final
python scripts/release.py create 2024-12-19

# Or with make
make release TAG=v1.0.0
```

GitHub Actions automatically compiles LaTeX and creates releases with PDF attachments.

## 🎨 Customization

### Colors
Edit `config/colors.tex`:
```latex
\definecolor{primarycolor}{RGB}{25,118,210}
\definecolor{secondarycolor}{RGB}{0,82,147}
```

### Environments
Use custom environments:
```latex
\begin{infobox}[Title]
Important information here
\end{infobox}

\begin{successbox}
Achievement or positive result
\end{successbox}
```

### Commands
Special text formatting:
```latex
\important{highlighted text}
\technology{React.js}
\company{Microsoft}
```

## 🤝 Contributing

Contributions welcome! Please follow our guidelines for the best experience.

### Quick Contribution
1. Fork the repository
2. Create feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push and create Pull Request

### Reporting Issues
- 🐛 [Bug Reports](https://github.com/sikatikenmogne/latex-report-template/issues/new?template=bug_report.yml)
- ✨ [Feature Requests](https://github.com/sikatikenmogne/latex-report-template/issues/new?template=feature_request.yml)

## 📄 License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

**TL;DR:** Free to use, modify, and distribute for any purpose.

## 🆘 Support

**Need Help?**
- 📖 [Read the Tutorial](TUTORIAL.md)
- 💬 [GitHub Discussions](https://github.com/sikatikenmogne/latex-report-template/discussions)
- 🐛 [Report Issues](https://github.com/sikatikenmogne/latex-report-template/issues)
- 📧 [Email Support](mailto:sikatikenmogne@gmail.com)

**Common Solutions:**
- Compilation errors → `python scripts/check.py`
- Missing packages → Install full LaTeX distribution
- VS Code setup → Install LaTeX Workshop extension

---

<div align="center">

**⭐ Found this useful? Give it a star!**

[Star this repo](https://github.com/sikatikenmogne/latex-report-template) • [Fork it](https://github.com/sikatikenmogne/latex-report-template/fork) • [Download ZIP](https://github.com/sikatikenmogne/latex-report-template/archive/refs/heads/main.zip)

**Built with ❤️ for the latex lovers**

</div>