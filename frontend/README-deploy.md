Frontend build & deploy

Local build
1. cd frontend
2. npm ci
3. npm run build

This project uses GitHub Actions to build and deploy the `frontend/dist` folder to the `gh-pages` branch. The workflow file is `.github/workflows/deploy-frontend.yml`.

If you want the site served at the repository root instead of `/LMS/`, remove the `--base=/LMS/` flag in the workflow build step.
