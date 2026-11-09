# Setup (5 minutes)

1. Repo name must be exactly: ABHISHEK-DHARIYAL/ABHISHEK-DHARIYAL (public).
2. Upload everything in this zip to the repo root, keeping the folders:
   - README.md
   - .github/workflows/snake.yml
   - .github/workflows/metrics.yml
3. Settings > Developer settings > Personal access tokens (classic):
   create a token with the read:user scope.
4. Repo > Settings > Secrets and variables > Actions:
   add a secret named METRICS_TOKEN with that token.
5. Repo > Actions tab: enable workflows if asked, then run
   "Generate Snake" and "Metrics" with "Run workflow".
6. Wait ~1-2 minutes and refresh your profile.

Checks:
- Snake: branch "output" exists in the repo.
- Metrics: github-metrics.svg appears in the repo root.
- Repo Settings > Actions > General > Workflow permissions:
  set to "Read and write permissions".
