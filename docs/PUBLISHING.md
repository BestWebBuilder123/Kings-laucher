# Publish the Kings Laucher website

The repository includes a responsive landing page in the docs folder and a GitHub Actions workflow that deploys it.

The connected GitHub integration cannot create or change this repository's Pages setting, so the owner must enable it once.

## One-time setup

1. Open the [Kings Laucher repository settings](https://github.com/BestWebBuilder123/Kings-laucher/settings/pages).
2. Find **Build and deployment**.
3. Set **Source** to **GitHub Actions**.
4. Open the repository's **Actions** tab.
5. Select **Deploy project site** and choose **Run workflow** on the main branch.

The workflow also runs automatically when files under docs change.

## Website address

After the deployment succeeds, the site should be available at:

https://bestwebbuilder123.github.io/Kings-laucher/

If GitHub Pages is not available for this repository, the landing page can still be viewed in the source tree at [docs/index.html](https://github.com/BestWebBuilder123/Kings-laucher/blob/main/docs/index.html).

## What the workflow does

- Checks out the main branch.
- Publishes the contents of docs as a Pages artifact.
- Deploys the artifact with the official GitHub Pages deployment actions.

The workflow does not build or modify the Windows executable.
