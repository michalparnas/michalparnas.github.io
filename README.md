# Michal Parnas — Academic Homepage

This is a simple, free, static academic homepage for GitHub Pages. No framework, installation, or command line is required.

## Publish on GitHub

1. Sign in to https://github.com/ (create a free account if necessary).
2. Create a **public** repository named `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your exact GitHub username). Choose **Add a README file** if GitHub asks.
3. In the repository choose **Add file → Upload files** and upload `index.html` and `style.css` from this folder (upload the files themselves, not the ZIP). Commit the changes.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**; select `main` and `/(root)`; save.
5. Visit `https://YOUR-USERNAME.github.io/`. Publishing may take a few minutes.

## Personalize

- Edit `index.html` using GitHub's pencil/edit button.
- Replace every placeholder in square brackets, especially publications and courses.
- To add a portrait, upload e.g. `portrait.jpg`, then replace the entire portrait `<div class="portrait" ...>...</div>` with `<img class="portrait" src="portrait.jpg" alt="Portrait of Michal Parnas">`. You may want to adjust the `.portrait` CSS to include `object-fit:cover`.
- For more publications, duplicate an `<li>...</li>` inside the `publication-list`.
- To customize colors, edit `--accent` in `style.css`.

The content is a draft, not a verified bibliography or teaching history. Review all text before publishing.
