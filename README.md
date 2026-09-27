# Afeez Akano — Instructional Design Portfolio

Personal portfolio website built for an Instructional Design Capstone project. Static HTML/CSS/JS, hosted on GitHub Pages.

**Live site:** https://laplace125.github.io/idc-portfolio/

## Structure

```
idc-portfolio/
├── index.html                       Main page (all sections)
├── style.css                         Styles
├── script.js                          Mobile nav + active-link highlighting
├── artifacts/
│   ├── artifact.css                     Shared styles for artifact pages
│   ├── needs-analysis.html               Artifact 1
│   ├── learning-objectives.html           Artifact 2
│   ├── storyboard.html                     Artifact 3
│   ├── learning-materials.html              Artifact 4
│   └── assessment.html                       Artifact 5
├── assets/
│   ├── images/                        Add photos/screenshots here
│   └── documents/                      Add PDFs/docs here
└── README.md
```

The five artifact pages under `artifacts/` are already written up from your capstone design document
(needs analysis, learning objectives, storyboard, learning materials, and assessment) and are linked
directly from the "View..." buttons on the main page — no external hosting needed. Each page also links
to the next one in the sequence at the bottom.

## Publishing to GitHub Pages

1. Create a repository named `idc-portfolio` under the `Laplace125` account.
2. Push these files to the `main` branch (they can sit at the repo root).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`.
5. Save — the site will publish at `https://laplace125.github.io/idc-portfolio/` within a minute or two.

## Things to customize before submitting

- **Capstone video link**: replace the placeholder YouTube URL in `index.html` (search for `id="capstoneLink"` and the matching link in the Artifacts section under "Final learning product") with your real video link.
- **Contact section**: replace the placeholder email, LinkedIn, and YouTube links near the bottom of `index.html`.
- **Artifact content**: the five artifact pages are pre-filled from your design document. If you revise the capstone design later, edit the corresponding file directly (e.g. `artifacts/storyboard.html`) rather than relinking anywhere.
- **Images**: if you'd like to add a portrait or project screenshots, drop them into `assets/images/` and reference them with a relative path.
