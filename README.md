# BSc Thesis – Collaborative Robotic Arms

This repository contains the LaTeX source files for the BSc Mechatronics Engineering thesis on collaborative multi-robot brick assembly using ABB and AR4 robotic arms.

---

## Required Software

### Visual Studio Code Extensions (Mandatory)

Install the following extension in Visual Studio Code:

- LaTeX Workshop (by James Yu)

This extension provides:
- PDF compilation
- Forward / inverse sync
- Build automation
- Error highlighting

---

## How to Build the Thesis

1. Open the repository folder in Visual Studio Code
2. Open `main.tex`
3. Click **Build LaTeX Project** from the LaTeX Workshop panel
4. The output PDF will be generated automatically

---

## File Organization Guidelines

### main.tex

- Handles document class, packages, and formatting
- Includes all chapters using \include{} or {\input}

### references.tex

- Contains all references using \bibitem
- Included once at the end of main.tex

### chapters/

- Each chapter has its own folder
- Each topic or section is written in a separate .tex file

### figures/

- Figures are grouped by chapter and topic
- All figures are referenced using relative paths
