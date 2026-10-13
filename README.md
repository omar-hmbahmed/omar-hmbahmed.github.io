# Research Scientist Website

A responsive single-page academic website (`docs/index.html`) with Home, Research, Publications, CV, and Contact sections. No software, news, or blog sections.

## Publish now (works independently of a site generator)

1. Create a GitHub repository named `YOUR_USERNAME.github.io`.
2. Upload the files from this project, including the `docs` directory.
3. In **Settings → Pages**, choose **Deploy from a branch**, `main`, `/docs`.
4. Visit `https://YOUR_USERNAME.github.io/` after deployment.

## Personalise

Edit the HTML files in `docs/` to replace Dr. Alex Morgan, generic biography, placeholder publications, email and profile links. Edit `docs/assets/style.css` to change styling. Add your CV PDF as `docs/cv.pdf`.

## oxie integration

The `content/` directory contains Markdown copies of the page outlines intended as a starting point for an oxie-based authoring workflow. **This project does not claim to implement oxie's native templates or build command**: its package API and output layout could not be verified in this environment. The `docs/` website is complete, standalone static HTML, so it can be deployed immediately. Once you have a working oxie installation, migrate these Markdown pages into its scaffold and adapt the templates using the installed version's documentation.
