# Creative Machines, Creative Sketches

Static workshop website for SIGGRAPH Asia 2026. The homepage is a single HTML file and uses `assets/teaser_v2.png`. No dependencies or build step are required.

## Local preview

Run `python3 -m http.server 8000` from the project directory, then open http://localhost:8000.

## GitHub Pages

1. Push the project files, including `.nojekyll`, to the GitHub repository's `main` branch.
2. In the repository's **Settings → Pages**, select **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` directory, then save.

The image uses a relative path, supporting both user or organization sites and project sites at `https://<username>.github.io/<repository>/`.
