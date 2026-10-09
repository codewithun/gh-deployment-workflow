# GitHub Actions Deployment Workflow

A simple static website deployed automatically to GitHub Pages using GitHub Actions.

## Features

- Automatic deployment to GitHub Pages
- Triggered by changes to `index.html` on the `main` branch
- Uses GitHub-hosted runners
- No external deployment server required

## Tech Stack

- HTML
- GitHub Actions
- GitHub Pages

## How It Works

1. Update `index.html`.
2. Commit and push the change to `main`.
3. GitHub Actions runs the deployment workflow.
4. The website is published to GitHub Pages.

Changes to files other than `index.html` do not trigger deployment.

## Live Website

https://codewithun.github.io/gh-deployment-workflow/

## Project Reference

https://roadmap.sh/projects/github-actions-deployment-workflow
