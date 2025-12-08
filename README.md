# Simple NPM Project

This is a simple Node.js project to demonstrate CI/CD using a separate Devops repository.

## Project Structure

- `index.js`: Simple Express app that returns "Hello, CI/CD World!".
- `package.json`: Project dependencies and scripts.
- `.github/workflows/trigger-devops-ci.yml`: Workflow to trigger CI/CD from Devops repo.

## How to Run Locally

1. Install dependencies:
```bash
npm install
2. start the app
node index.js

## CI/CD ##
CI/CD is handled in a separate repository called Devops.

Any push to main branch triggers the Devops workflow via GitHub Actions.
