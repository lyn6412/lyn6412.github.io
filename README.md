# Academic Homepage

A lightweight, dependency-free academic homepage designed for GitHub Pages and
OpenReview profile verification.

## 1. Review personal information

The page is currently configured with:

- Name: `Yining Li`
- Email: `302024512117@zjut.edu.cn`
- GitHub: `lyn6412`
- ORCID: `0009-0007-6507-8537`

These should match the information used for the OpenReview account. Review the
prewritten research descriptions and edit any wording that does not precisely
match your current status.

## 2. Preview locally

Double-click `index.html`, or run a local server from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## 3. Publish with GitHub Pages

1. Create a public repository named `lyn6412.github.io`.
2. Upload the contents of this folder to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. After deployment, the homepage will be available at
   `https://lyn6412.github.io/`.

If you publish this page in another repository, its default URL will be
`https://lyn6412.github.io/REPOSITORY_NAME/`.

## Notes

- No framework, package manager, API key, or build step is required.
- The page is responsive and works on desktop and mobile devices.
- Keep contact information accurate and avoid publishing private details.
