# ACT Network data push summaries on GitHub Pages

## Setup instructions

1. If you don't have one already, create a GitHub account
2. Fork this repository (button at the top right)
3. Add your MATOS username and password to the repository's secrets
  a. Click "Settings"
  b. Click "Secrets and variables" under "Security"
  c. Click "Actions"
  d. In the "Secrets" tab, click "New repository secret"
    1. Under "Name", write "MATOS_USER"
    2. Write your username under "Secret" and click "Add secret" to save
    3. Repeat, with "MATOS_PASS" under "Name" and your password under "Secret"
4. Activate GitHub Pages for this repository
  a. "Settings" -> "Code and automation" -> "Pages"
  b. "Build and Deployment" -> "Source" -> "GitHub Actions"
