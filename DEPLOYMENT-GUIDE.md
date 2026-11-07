# GitHub Pages deployment guide

1. Sign in to GitHub and open `ssemakulaarthur23.github.io` (create it as a public repository if it does not exist).
2. Upload all files and folders from this package to the repository root. Do not upload the outer `arthur-portfolio-v2` folder itself.
3. Confirm the repository root contains `index.html`, `styles.css`, `script.js`, and `assets/`.
4. Confirm `assets/` contains both `Ssemakula_Arthur_CV.pdf` and `favicon.svg`.
5. Commit the uploaded files to the `main` branch.
6. Go to **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main`, folder `/(root)`, and click **Save**.
9. Wait for deployment, then visit `https://ssemakulaarthur23.github.io`.
10. Test the CV directly at `https://ssemakulaarthur23.github.io/assets/Ssemakula_Arthur_CV.pdf`.

If the CV returns 404, check exact spelling and capitalization and ensure the PDF is committed inside the `assets` folder.
