# GitHub Pages Deployment

A simple GitHub Actions workflow that automatically deploys `index.html` to GitHub Pages whenever it changes on the `main` branch.

## Project URL
https://roadmap.sh/projects/github-actions-deployment-workflow

## Live site
https://WilliamFly.github.io/gh-deployment-workflow/

## How it works
The workflow in `.github/workflows/deploy.yml` triggers only when `index.html` is modified and pushed to `main`, then deploys the static site to GitHub Pages using GitHub's official Pages deployment actions.
