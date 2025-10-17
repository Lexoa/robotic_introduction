# CM - Course Materials (Cours Magistral)

This folder contains the course presentations for the robotics introduction class.

## Content

- LaTeX Beamer presentations covering theoretical concepts
- Lecture slides on robotics fundamentals
- Key concepts and principles of robotic systems

## Structure

Each presentation is organized as a self-contained LaTeX project with:
- Main `.tex` file for the presentation
- Supporting figures and diagrams
- Bibliography files if needed

## Building

To compile a presentation:
```bash
pdflatex presentation_name.tex
```

For presentations with bibliography:
```bash
pdflatex presentation_name.tex
bibtex presentation_name
pdflatex presentation_name.tex
pdflatex presentation_name.tex
```
