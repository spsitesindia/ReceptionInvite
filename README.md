# Wedding invitation website — version 2

A three-page static invitation site, ready for GitHub Pages. Version 2 removes the QR codes from pages 2 and 3 and shows the venue address as text on page 3. The artwork and text are in the SVG files under `assets/`.

## Publish on GitHub Pages

1. Create a GitHub repository. If you want the invitation to stay private, check that your GitHub plan supports Pages from a private repository. A public repository makes the invitation pages publicly accessible.
2. Upload the **contents** of this folder to the repository root. Make sure `index.html` is at the root, alongside `page-2.html`, `page-3.html`, `README.md`, and the `assets` folder.
3. Commit the uploaded files.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the `main` branch and the `/(root)` folder, then save.
7. After GitHub finishes publishing, use the site link shown on the Pages settings screen. It usually looks like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

To change wording or artwork later, edit the corresponding SVG in `assets/`, then commit the changes. Page links are in `index.html`, `page-2.html`, and `page-3.html`.