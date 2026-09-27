# Cultural Convergence

A static, single-page puzzle game. No build step.

## Deploy with the Vercel CLI
    npm i -g vercel
    cd cultural-convergence
    vercel          # preview deploy (framework: Other, no build command)
    vercel --prod   # production

## Deploy with GitHub
Push this folder to a GitHub repo, then in Vercel choose Add New -> Project,
import the repo, set Framework Preset to "Other", and deploy.

## Updating
Replace index.html with a new build and redeploy (or push to GitHub).

Note: player progress is saved in each browser's localStorage for your domain.
