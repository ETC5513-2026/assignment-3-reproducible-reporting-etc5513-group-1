# ETC5513 Assignment 3

## Group Members

- Shixu Xiao
- Anali Nanayakkara Palliya Guruge
- Tiansi Zhu
- Sum Yee Chong

## Topic

Which retail industries and states drove Australia's post-pandemic recovery between 2020 and 2025?

## Repository Structure

```
.
├── data/                  # Data files
├── reports/               # Final report
│   ├── report.qmd
│   ├── report.pdf
│   └── references.bib
├── slides.qmd             # Presentation source
├── slides.html            # Rendered presentation slides
├── Presentation.mp4       # Final presentation video
├── renv/                  # Reproducible package environment
├── renv.lock
├── README.md
└── LICENSE
```

## Key Outputs

### Final Report

- Source: `reports/report.qmd`
- Submission version: `reports/report.pdf`

### Presentation Slides

- Source: `slides.qmd`
- Rendered slides: `slides.html`

### Presentation Video

- Final video: `Presentation.mp4`

## Reproducibility

This project uses:

- Quarto for reporting and presentation
- Git and GitHub for version control
- `renv` for package management and reproducibility
- `.gitignore` to exclude unnecessary generated files and temporary files from version control

To restore the project environment:

```r
renv::restore()
```
