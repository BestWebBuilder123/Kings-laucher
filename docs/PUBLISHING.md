# Publish the Kings Laucher website

The project landing page is already committed at `docs/index.html`. Publish it directly from the `main` branch using GitHub Pages.

## One-time setup

1. Open [Kings Laucher Pages settings](https://github.com/BestWebBuilder123/Kings-laucher/settings/pages).
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Under **Branch**, select **main**.
4. In the folder dropdown, select **/docs**.
5. Click **Save**.

GitHub will publish the landing page from the docs folder. No workflow, build command, or local software is required.

## Website address

After GitHub finishes the first deployment, the site should be available at:

https://bestwebbuilder123.github.io/Kings-laucher/

You can check the deployment status in the repository's **Settings → Pages** section.

## Updating the website

Edit files under `docs/` on the `main` branch. GitHub Pages will publish the changes automatically after the commit is processed.

The landing page is `docs/index.html`; its logo is `docs/assets/brand.svg`.

## Troubleshooting

- Confirm the repository is public.
- Confirm the source is **Deploy from a branch**.
- Confirm the branch is `main` and the folder is `/docs`.
- Confirm `docs/index.html` exists on `main`.
- Wait for the Pages deployment status to show a successful publication, then reload the site.
