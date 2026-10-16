# Publish Your Portfolio with GitHub Pages

## 1. Download and extract
Download `arthur-cybersecurity-portfolio-finished.zip` and extract it. Open the extracted folder and check that `index.html`, `styles.css`, `script.js`, `README.md`, `DEPLOYMENT-GUIDE.md`, `assets/`, and `project-templates/` are visible.

## 2. Create the correct GitHub repository
1. Sign in to https://github.com/ssemakulaarthur23.
2. Create a **public** repository named exactly `ssemakulaarthur23.github.io`.
3. If the repository already exists, open it and continue with the upload/update step.

## 3. Upload the site files
1. Open the repository and select **Add file → Upload files**.
2. Upload the *contents inside* the extracted portfolio folder, not the outer folder itself.
3. Make sure `index.html`, `styles.css`, and `script.js` are in the repository root, and the CV is at `assets/Ssemakula_Arthur_CV.pdf`.
4. Commit the changes to the `main` branch.

## 4. Turn on GitHub Pages
1. Open **Settings → Pages** in that repository.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch `main` and folder `/(root)`.
4. Click **Save**.
5. Wait for the Pages deployment to finish. First publication can take several minutes.

## 5. Open and test the website
- Website: https://ssemakulaarthur23.github.io
- Test the mobile menu, each project link, email link, LinkedIn link, and CV download.
- If the website does not appear, check the repository's **Actions** tab and the **Settings → Pages** status.

Official instructions: https://docs.github.com/en/pages/quickstart and https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Final security check
GitHub Pages is public. Before publishing, remove secrets, API keys, credentials, private target details, unredacted screenshots, and sensitive internship/client information. Publish only work you are authorized to share.
