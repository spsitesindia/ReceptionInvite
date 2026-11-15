# Wedding invitation website — version 7

A three-page static invitation site, ready for GitHub Pages. Version 7 carries forward the latest invitation content and design from version 6.5. The page 1 cover uses the new ritual-art background, with the names moved into its open upper area; the page 3 reception details appear in sequence; page 2 reveals its sections one by one after load. Animations respect reduced-motion preferences. A matching loading screen stays visible until each page's artwork is ready; the cover artwork is preloaded. Artwork and text are in the SVG files under `assets/`.

The page SVGs contain their border artwork and use optimized WebP artwork. Page 2 uses the Lipishree Unicode Bengali font at `assets/lipishree-unicode.woff`; page 3 embeds subset WOFF fonts.

## Publish on GitHub Pages

1. Create a GitHub repository. If you want the invitation to stay private, check that your GitHub plan supports Pages from a private repository. A public repository makes the invitation pages publicly accessible.
2. Upload the **contents** of this folder to the repository root. Make sure `index.html` is at the root, alongside `page-2.html`, `page-3.html`, `README.md`, and the `assets` folder.
3. Commit the uploaded files.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the `main` branch and the `/(root)` folder, then save.
7. After GitHub finishes publishing, use the site link shown on the Pages settings screen. It usually looks like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

To change wording or artwork later, edit the corresponding SVG in `assets/`, then commit the changes. Page links are in `index.html`, `page-2.html`, and `page-3.html`.

