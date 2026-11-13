# Wedding invitation website — version 4

A three-page static invitation site, ready for GitHub Pages. Version 4 carries forward the version 3 invitation content and design. The page 1 title and page 3 reception details appear in sequence; page 2 reveals its sections one by one after load. Animations respect reduced-motion preferences. Artwork and text are in the SVG files under `assets/`.

`assets/border-portrait.svg` and `assets/border-page2.svg` are editable border masters; the page SVGs include inline border copies. `assets/bengali-emblem.png` and `assets/kalpana-unicode.ttf` are used on page 2.

## Publish on GitHub Pages

1. Create a GitHub repository. If you want the invitation to stay private, check that your GitHub plan supports Pages from a private repository. A public repository makes the invitation pages publicly accessible.
2. Upload the **contents** of this folder to the repository root. Make sure `index.html` is at the root, alongside `page-2.html`, `page-3.html`, `README.md`, and the `assets` folder.
3. Commit the uploaded files.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the `main` branch and the `/(root)` folder, then save.
7. After GitHub finishes publishing, use the site link shown on the Pages settings screen. It usually looks like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

To change wording or artwork later, edit the corresponding SVG in `assets/`, then commit the changes. Page links are in `index.html`, `page-2.html`, and `page-3.html`.

