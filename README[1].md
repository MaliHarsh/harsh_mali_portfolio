# EFx Robotics — GitHub Pages

A standalone, static deployment of the supplied EFx project-page HTML, without the ChatGPT editor widget or any ChatGPT-domain asset links.

## Publish
1. Create a **public** repository named `YOUR-USERNAME.github.io` (replace with your exact GitHub username).
2. Upload the **contents of this folder** to the root of the `main` branch.
3. In **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)`, and save.
4. Visit `https://YOUR-USERNAME.github.io/`.

## Missing content from original upload
The upload contained only the EFx page HTML. Its original CSS, JS, photographs, portfolio homepage, résumé, and supporting document were not included or accessible. A replacement stylesheet and lightbox script are bundled, a standalone electronics page is derived from EFx material, and the root index redirects to the EFx page. The three SVGs in `assets/` are **clearly labeled placeholders**, not original photography. Replace them with the real images and update paths in `efx.html`. For the complete portfolio you will need to supply its other original pages and assets.

GitHub Pages provides **static hosting**. No backend is included.
