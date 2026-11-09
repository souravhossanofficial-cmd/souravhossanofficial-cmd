# Install this GitHub Profile README

1. Open the repository that powers your profile: `souravhossanofficial-cmd/souravhossanofficial-cmd`.
2. Copy the contents of this package into the **root** of that repository, preserving the `.github/workflows/` and `assets/` folders. Replace the existing `README.md`.
3. Commit and push the files. Adding or updating `.github/workflows/profile-cards.yml` triggers the first analytics-card generation automatically.
4. To refresh the cards manually, open the repository's **Actions** tab, select **Refresh GitHub Profile Cards**, and click **Run workflow**.
5. The workflow refreshes the cards daily at 01:23 UTC.

## If the workflow cannot push its generated SVGs

In the profile repository, open **Settings → Actions → General → Workflow permissions** and enable **Read and write permissions**. Then rerun the workflow.

## What is generated

The workflow writes the following light- and dark-theme SVGs into `assets/`: `overview`, `momentum`, `contributions`, `lifetime`, `cadence`, `repositories`, and `languages`. These SVGs are stored in your own repository, so your README does not depend on a third-party image host for its analytics cards.

The supplied SVGs are initial placeholders. They are valid local images and are replaced with live GitHub data after the first successful workflow run. The overview reports **public** repository totals and stars earned across public repositories; it does not expose private-repository details. GitHub contribution data can include private contributions when you enable **Include private contributions on my profile** in your GitHub profile settings.
