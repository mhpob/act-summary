# ACT Network data push summaries on GitHub Pages

This repository automatically summarizes a given project and data type and posts 
it on a GitHub page for easy access and sharing. You can find the page created 
by this repository here: <https://mhpob.github.io/act-summary/>.

It utilizes the [matos](https://matos.obrien.page) and [otndo](https://otndo.obrien.page) 
R packages within a GitHub Action to post the summary directly to your given page.

## Initial setup:

Don't worry, this only needs to be done once!

1. If you don't have one already, create a GitHub account
2. Fork this repository (button at the top right)
3. Add your MATOS username and password to the repository's secrets
  a.  Click "Settings"
  b. Click "Secrets and variables" under "Security"
  c. Click "Actions"
  d. In the "Secrets" tab, click "New repository secret"
    1. Under "Name", write "MATOS_USER"
    2. Write your username under "Secret" and click "Add secret" to save
    3. Repeat, with "MATOS_PASS" under "Name" and your password under "Secret"
4. Activate GitHub Pages for this repository
  a. "Settings" -> "Code and automation" -> "Pages"
  b. "Build and Deployment" -> "Source" -> "GitHub Actions"


## Project setup

1. Open `config.yaml` and replace `project` with your own project code and 
`data_type` with the desired summary (tag or receiver).
2. Commit your changes and follow along in the "Actions" tab -- your summary 
will be posted shortly at "https://[YOUR GH USERNAME].github.io/act-summary".
