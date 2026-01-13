# GitHub Pages Setup

This directory contains the GitHub Pages website for vibe-mofa.

## Configuration

The website is configured to be served from the `docs` folder on the main branch.

## Files

- `index.html` - Main landing page for the website
- `_config.yml` - Jekyll configuration file

## Local Development

To run the site locally:

1. Install Jekyll: `gem install jekyll bundler`
2. Navigate to the docs directory: `cd docs`
3. Start the Jekyll server: `jekyll serve`
4. Open http://localhost:4000 in your browser

## Deployment

The site is automatically deployed by GitHub Pages when changes are pushed to the main branch.

To enable GitHub Pages:
1. Go to repository Settings
2. Navigate to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select the branch (usually `main`) and `/docs` folder
5. Click "Save"

The site will be available at: https://xiaokuge.github.io/vibe-mofa/
