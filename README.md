
# GitHub Actions Deployment Workflow

## Project Overview

This project demonstrates Continuous Integration and Continuous
Deployment (CI/CD) using GitHub Actions and GitHub Pages.

The workflow automatically deploys a static website whenever
the `index.html` file is changed and pushed to the `main` branch.

## Technologies

- GitHub Actions
- GitHub Pages
- HTML
- YAML

## How It Works

1. A change is made to `index.html`.
2. The change is pushed to the `main` branch.
3. GitHub Actions detects the change.
4. The workflow deploys the website to GitHub Pages.

Changes to other files do not trigger the deployment workflow.

## Website

https://litedan.github.io/gh-deployment-workflow/
