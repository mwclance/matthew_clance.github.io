# matthew_clance.github.io

A personal website built using the [privefl/rmarkdown-website-template](https://github.com/privefl/rmarkdown-website-template).

## Getting Started

Follow these steps to build and deploy the website.

### Prerequisites

- **R**: [Download R](https://cran.r-project.org/)
- **RStudio** (optional but recommended): [Download RStudio](https://www.rstudio.com/products/rstudio/download/)
- **Git**: [Download Git](https://git-scm.com/downloads)

### Building the Website

You can build the website using R or RStudio:

1. **Using R Console:**

    ```r
    rmarkdown::render_site(encoding = "UTF-8")
    ```

2. **Using RStudio:**

    - Press `Ctrl + Shift + B` (Windows/Linux) or `Cmd + Shift + B` (Mac) to build the site.

### Deployment

After building the website, deploy it by committing and pushing the changes to GitHub:

```bash
git add .
git commit -m "Build and deploy website"
git push origin main