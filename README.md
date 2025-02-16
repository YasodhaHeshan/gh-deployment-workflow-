# GitHub Actions Deployment Workflow

This project demonstrates how to use GitHub Actions to deploy a simple HTML website to GitHub Pages.

## Files

- `index.html`: The main HTML file that will be deployed.
- `.github/workflows/deploy.yml`: The GitHub Actions workflow file that handles the deployment.

## Deployment

Every push to the `main` branch that changes the `index.html` file will trigger the workflow to run and deploy the website to GitHub Pages.

The website will be accessible at the GitHub Pages URL for the repository: `https://<username>.github.io/gh-deployment-workflow/`.