# Rogers Respite and Community Services — one-page website

A responsive, single-page website designed for GitHub Pages. No web framework, build step, plugins or subscription required.

## Quick start

1. Create a new GitHub repository (for example, `rogers-respite-website`).
2. Upload **both `index.html` and `profile.jpg`** to the **root** of the repository (not inside a folder).
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**; choose **main** and **/(root)** and save.
4. Open the published site URL displayed in Settings → Pages.

## What to edit

Open `index.html` in GitHub and select the pencil icon to edit it. All changes are in one file.

| Edit | Find in `index.html` |
| --- | --- |
| About Me biography | `EDIT ABOUT ME` |
| FAQ questions and answers | `EDIT FAQ` |
| Your photo | **`profile.jpg` is included**; replace it with another photo of the same name to update your picture |
| Rates | Search for `Standard hourly rate`, `6-hour package` and `9-hour package` |
| Phone | Search for `519-350-7373` **and** `+15193507373` |
| Email | Search for `evan@rogersrespite.ca` |
| Registration number | Search for `843082` |
| Blue colour | Change the CSS variable `--blue: #2e78a9` near the top |
| Services and other website text | Edit the corresponding HTML paragraphs |

**Photo tips:** Use a clear, vertically framed JPG. The website crops the photo to fit; a 900×1050 pixel or larger original is suitable. The photo file name must be exactly `profile.jpg` (lowercase).

## Custom domain (`rogersrespite.ca`)

In **Settings → Pages → Custom domain**, enter `rogersrespite.ca`, then follow GitHub's domain-verification/DNS instructions for your DNS provider. Enable **Enforce HTTPS** once available. The website can coexist with Google Workspace email: **do not delete your existing MX, SPF, DKIM, or other Google Workspace-related TXT records** when updating the website DNS records. Only update the records GitHub instructs you to change for web traffic. You can also use a `www` subdomain if preferred.

GitHub's current instructions: <https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site>

## Pricing represented on this site

- Standard: **$30/hour**
- Six hours: **$25/hour × 6 = $150**, saving **$30**
- Nine hours: **$25/hour × 9 = $225**, saving **$45**

The website deliberately does not claim specific cancellation terms, package expiry, transport arrangements or taxes. Add these details only after you have set your policies.

## Important before publishing

- The FAQ answers have been filled in. Review them for accuracy before publishing.
- Review the About Me and services text to ensure it accurately reflects what you offer.
- Verify your contact details and rates.
- The provided photo is included as `profile.jpg`.

The page currently uses telephone links; it does not collect or store client information through a web form.

## Updating an existing GitHub Pages website

1. Open your website repository on GitHub and choose **Add file → Upload files**.
2. Upload **both** `index.html` and `profile.jpg` from this updated package into the repository root.
3. If GitHub asks about overwriting an existing `index.html`, replace the old file (or open it, choose the pencil icon and paste in the updated HTML).
4. Commit the changes to `main`. Existing GitHub Pages and domain settings remain unchanged.
5. Refresh the published page after the deployment completes. If the old page remains cached, try a private browsing window.

**Important:** Don't upload just the ZIP to the GitHub repository; unzip it first and upload the individual files.
