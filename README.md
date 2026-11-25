# Professional Portfolio

White-and-gold responsive portfolio, with the original leadership-first design and an offline visual editor. No Node.js, Python, npm, hosting service account or API token is required for editing.

## Start on Windows or macOS

1. On the repository page, select **Code > Download ZIP** (or clone with GitHub Desktop).
2. Extract the entire folder.
3. Double-click **editor.html** to open Portfolio Studio in Chrome or Edge.
4. Use **Choose file** and select **docs/index.html**.
5. Pick a section, edit text, duplicate or remove a project, change colors, and click **Refresh preview**. Select Mobile to check a narrow layout.
6. Click **Download updated index.html**. Move the file to the **docs** folder and replace the previous index.html. Check it by opening docs/index.html directly.
7. Save another copy if you need a backup. Edits are not automatically written to your disk or repository.

## Publish once using GitHub Pages

1. Open https://github.com/mussadiqali958-ux/portfolio/settings/pages
2. Under Build and deployment, choose **Deploy from a branch**.
3. Choose branch **main** and folder **/docs**, then Save.
4. Check the Pages settings and deployment status. The expected address is https://mussadiqali958-ux.github.io/portfolio/ (use the actual address GitHub displays once deployment succeeds).

Only the docs folder is published as the website. The editor is source code outside that folder. The repository is public, so never store confidential documents, private information, client data, credentials or unpublished drafts in it.

## Publish future edits

### Simple browser method
After exporting, open docs/index.html on GitHub. Select the pencil icon, replace the entire contents with the new file's contents (open it in Notepad and copy all), then commit changes to main. Alternatively upload the updated index.html into the docs directory using Add file > Upload files and commit. Do not put the replacement at the repository root.

### GitHub Desktop method
Clone the repository once from GitHub Desktop. Pull the latest changes before editing. Edit locally using Portfolio Studio, replace docs/index.html, then review the diff, enter a commit message, Commit to main, and Push origin. Check Pages for successful deployment. Your portfolio URL does not change.

## Files
- docs/index.html — public portfolio; self-contained styling, illustrations, and interactions.
- editor.html — offline editing tool; no account or API access.
- README.md — this guide.

For advanced edits, open docs/index.html in a text editor. Its CSS, HTML and JavaScript are inline. Use GitHub history to restore an earlier version if necessary. The editor preserves existing markup when modifying displayed text; changing structure beyond project duplication/removal requires source editing.

## Before publishing
Check career claims, dates and any new content for accuracy. Do not include private contact details or confidential network records. The initial version omits unverified figures, direct contact details and private data. Public links and publication settings must be checked after enabling Pages.
