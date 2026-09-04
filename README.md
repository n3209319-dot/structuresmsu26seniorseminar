# 3D Printed Compliant Origami Hinges Website

This folder contains the complete static website for the senior seminar project:

**Development of 3D Printed Compliant Hinges for Use in Thick Panel Origami Structures**

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Extract the ZIP file on your computer.
3. Upload everything inside the extracted folder to the root of the repository. Make sure `index.html` is at the repository root.
4. Open the repository's **Settings**.
5. Select **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and the `/ (root)` folder, then select **Save**.
8. GitHub will provide the published website address after deployment finishes.

The address will normally follow this pattern:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Edit the Website

- `index.html`: home page
- `project/index.html`: project overview
- `design/index.html`: design and computational analysis
- `testing/index.html`: testing and results
- `progress/index.html`: project progress
- `team/index.html`: team and advisors
- `documents/index.html`: project documents
- `assets/styles.css`: colors, typography, spacing, and responsive layout
- `assets/site.js`: mobile navigation behavior
- `assets/statement-of-work.pdf`: downloadable Statement of Work

You can edit the HTML and CSS directly on GitHub by opening a file and selecting the pencil icon. Commit each change to the `main` branch, and GitHub Pages will republish the updated site.

## Add Project Results

Replace the pending-results text in `testing/index.html` with verified test information. Add photographs, CAD images, and graphs to the `assets` folder, then reference them with relative paths such as:

```html
<img src="../assets/hinge-test.jpg" alt="Compliant hinge installed in the fatigue test fixture">
```

Use descriptive alternative text, figure captions, labeled axes, and units.

