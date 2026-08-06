# A-SMART Lab — Professional GitHub Pages Site

This folder is a complete static website designed for the repository:

`https://github.com/martin-z-ma/a-smart-lab`

## Publish it

1. Download and unzip the package.
2. In your GitHub repository, remove the old website files or upload these files and allow replacement.
3. Keep the folder structure exactly as provided.
4. Commit the changes to the `main` branch.
5. Open **Settings → Pages** and choose **Deploy from a branch**, `main`, `/(root)`.
6. Visit `https://martin-z-ma.github.io/a-smart-lab/` after the deployment finishes.

The `.nojekyll` file is intentional. This version is plain HTML/CSS/JavaScript and does not require a Jekyll theme.

## Most useful edits

- Homepage wording: `index.html`
- Biography: `about.html`
- Research areas: `research.html`
- Projects: `projects.html`
- Team members: `people.html`
- Publication list: `publications.html`
- Email and footer text: each HTML page (search for `martin.ma@singaporetech.edu.sg`)
- Colours and layout: `assets/css/style.css`
- Portrait: replace `assets/img/martin-ma.jpg` with a file using the same name

## Notes before publishing

- Review the student names and project titles on `people.html`.
- Review the biography, publication count and project descriptions for any updates.
- The publication list was reformatted from the existing repository. Two malformed DOI links in the source were repaired during formatting.
- `news.html` is included but is not shown in the main navigation; you can add it later when you have more updates.
