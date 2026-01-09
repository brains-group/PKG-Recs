# Knowledge Graph-Powered Decentralized Personalization

Tutorial website for the European Semantic Web Conference 2026 (ESWC 2026).

## About

This repository contains the Quarto website for the tutorial "Knowledge Graph-Powered Decentralized Personalization" to be presented at ESWC 2026 in Dubrovnik, Croatia, May 10-14, 2026.

## Website Structure

The website includes the following sections:
- **Title and Abstract**: Tutorial title and abstract
- **Speaker Bios**: Information about tutorial presenters
- **Detailed Outline**: Point-form outline of tutorial content
- **References**: Key references and suggestions for further reading
- **Materials**: Slides, handouts, demos, and software resources

## Building the Website

This website is built using [Quarto](https://quarto.org/). To build and preview the website:

1. **Install Quarto** (if not already installed):
   ```bash
   # Visit https://quarto.org/docs/get-started/
   ```

2. **Preview the website locally**:
   ```bash
   quarto preview
   ```

3. **Render the website**:
   ```bash
   quarto render
   ```

4. **View the rendered site**:
   The rendered website will be in the `_site/` directory.

## Publishing to GitHub Pages

This website is automatically published to GitHub Pages at [https://brains-group.github.io/PKG-Recs/](https://brains-group.github.io/PKG-Recs/) using GitHub Actions.

### Automatic Deployment

The website will automatically rebuild and deploy when you:
- Push commits to the `main` or `master` branch
- Merge pull requests into `main` or `master`

The GitHub Actions workflow (`.github/workflows/publish.yml`) handles:
1. Installing Quarto
2. Rendering the website
3. Deploying to GitHub Pages

### Manual Setup (First Time)

If this is the first time setting up GitHub Pages for this repository:

1. Go to your repository settings on GitHub
2. Navigate to **Pages** under **Settings**
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically deploy on the next push to `main`/`master`

The website will be available at: **https://brains-group.github.io/PKG-Recs/**

## Customization

- Edit `index.qmd` for the main content
- Edit `_quarto.yml` for website configuration
- Modify `styles.css` and `custom.scss` for custom styling
- Add materials to the appropriate sections as they become available

## License

See LICENSE file for details.
