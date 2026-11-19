# LaTeX D's Beamer Presentation Template

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A clean, minimalist LaTeX Beamer presentation template built on the **Dresden** theme, featuring a custom title slide, a two-tier informational footer, and uncluttered content slides.

## 👀 Preview

You can view the compiled PDF of this presentation template directly in your browser without installing $\LaTeX$ locally:

[📄 **View the compiled PDF**](https://latexonline.cc/compile?git=https://github.com/physicslog/D-s-Beamer&target=dmain.tex)

Alternatively, you can instantly open and edit this template in a private Overleaf project:

[![Open in Overleaf](https://img.shields.io/badge/Open%20in-Overleaf-479e47?logo=overleaf)](https://www.overleaf.com/docs?snip_uri=https://github.com/physicslog/D-s-Beamer/archive/refs/heads/main.zip&main_document=dmain.tex)

## 📥 Quick Download

You can download the standalone template file directly here: [**Download `main.tex`**](https://raw.githubusercontent.com/physicslog/D-s-Beamer/refs/heads/main/dmain.tex)

---

## ✨ Features

- **Distraction-Free Layout:** Removes the default Dresden top navigation headline and bottom navigation symbols to maximize slide space.
- **Custom Title Page:** Centered layout supporting author, department, institution, event/conference name, and date.
- **Smart Two-Line Footer:** Automatically hidden on the title slide (`frame 1`) and displayed on all subsequent slides:
  - **Row 1:** Author name, optional website URL (`| URL`), and short date.
  - **Row 2:** Short presentation title and slide counter (`current of total`).
- **Square ToC Markers:** Styled section and subsection indicators on the outline slide.

## 🛠 Custom Metadata Commands

Edit the metadata block below the `NO EDIT` section in `main.tex`:

| Command | Description | Behavior |
| :--- | :--- | :--- |
| `\title{...}` | Presentation title (supports `[Short Title]` for the footer) | Required |
| `\author{...}` | Presenter name(s) | Required |
| `\web{...}` | Website URL shown next to the author in the footer | Optional (leave `{}` empty to hide) |
| `\department{...}` | Department or research group on the title slide | Optional |
| `\institute{...}` | University or organization name | Required |
| `\event{...}` | Conference, seminar, or workshop name on the title slide | Optional |
| `\date{...}` | Presentation date | Required |

### Example Configuration

```latex
\title[Short Title]{Presentation Title}
\author{Author Name}
\web{} % URL if any or just leave it empty
\department{Department Name}
\institute{University Name}
\event{Event Name}
\date{19 Nov 2026}
```

## 📝 Notes

- Leave the block bounded by `% !!!!!!!!!!!!!!!!!! NO EDIT !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!|` untouched unless you want to modify the core title page or footer layout.
- Uncomment `\usepackage{hyperref}`, `\usepackage{xcolor}`, or `\usepackage{graphicx}` in the packages section as needed.

ENJOY!
