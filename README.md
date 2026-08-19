# Yichao Du — Academic Homepage

This folder is a dependency-free static website prepared for GitHub Pages.

## Preview locally

Run the following command inside this folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to GitHub Pages

1. Create or open the repository that will host the website.
2. Copy all files in this folder to the repository root.
3. Commit and push the files to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, then choose `main` and `/ (root)`.

For a user site, name the repository `duyichao.github.io`. For a project site, the relative asset paths in this package also work under a repository subpath.

## Update content

- Edit `index.html` for biography, experience, publications, links, and contact details.
- Edit `styles.css` for colors, typography, and layout.
- Replace `profile.jpg` with a new portrait using the same filename.
- Replace `og-v2.png` to update the social sharing card.

If the deployed domain is not `https://duyichao.github.io/`, update the `og:image` URL in `index.html`.
