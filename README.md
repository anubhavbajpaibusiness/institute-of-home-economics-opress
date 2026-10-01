# Institute of Home Economics Voicebox

Anonymous complaint & suggestion box for the Institute of Home Economics
(University of Delhi) Students' Union.

Static frontend in `public/`, three serverless API routes in `api/`, shared
auth helper in `lib/`, and data stored in Upstash Redis. The frontend is a
single HTML file — no build step, no framework, no external JS dependencies.

## Deploy in 5 minutes

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "ihe-voicebox"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main