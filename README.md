# Miguel Rua — Portfolio Homepage

A responsive personal portfolio for **Miguel Ángel Rua Ruiz**, an engineering student growing into full-stack development through practical software projects.

This site was created for [The Odin Project's Homepage assignment](https://www.theodinproject.com/lessons/node-path-advanced-html-and-css-homepage). It focuses on responsive layout, visual hierarchy, accessibility, and a clear presentation of selected work.

## Deployment

The production target is:

**[miguelrcol.github.io/homepage](https://miguelrcol.github.io/homepage/)**

The link will become available after this repository is created on GitHub and its first Pages workflow completes successfully.

This is a standalone repository dedicated to the portfolio homepage. Pushes to `main` trigger [the Pages workflow](.github/workflows/pages.yml), which publishes only:

- `index.html`
- `styles.css`
- `assets/`

## Highlights

- Responsive from 320 to 1,920 pixels.
- Three-column, two-column, and single-column project layouts.
- Semantic HTML with clear heading and landmark structure.
- Keyboard-visible focus states and a skip link.
- Light and dark color schemes based on system preferences.
- Support for increased contrast and reduced motion preferences.
- GitHub, live-demo, LinkedIn, and email links with accessible labels.
- Six selected projects with descriptions and technology summaries.

## Design direction

The interface uses a restrained, content-first visual system inspired by principles commonly associated with Apple design: clear hierarchy, generous spacing, consistent interaction patterns, and minimal decoration.

The pink accent comes from Miguel's geometric GitHub avatar. Editorial project numbers, asymmetric artwork, warm neutral colors, and compact corners give the site its own identity without imitating an Apple product interface.

## Built with

- HTML5
- CSS3
- CSS Grid and Flexbox
- Responsive media queries
- Inline and reusable SVG icons
- GitHub Actions and GitHub Pages

The site has no framework, JavaScript runtime, package manager, or build dependency.

## Project structure

```text
homepage/
├── .github/
│   └── workflows/
│       └── pages.yml
├── assets/
│   ├── icons/
│   └── images/
├── index.html
├── styles.css
└── README.md
```

## Run locally

You can open `index.html` directly, or serve the repository with a local static server:

```bash
python -m http.server 4173
```

Then visit `http://127.0.0.1:4173/`.

## Selected work

The homepage currently features:

- Atmos Weather
- Battleship
- FocusBoard
- Restaurant Page
- Admin Dashboard
- Odin Calculator

Each project includes its source repository and, when available, a live GitHub Pages deployment.

## Contact

- [GitHub](https://github.com/MiguelRcol)
- [LinkedIn](https://www.linkedin.com/in/miguel-angel-rua-ruiz-32827726a/)
- [miguelruaruiz@gmail.com](mailto:miguelruaruiz@gmail.com)

## Acknowledgements

- Project brief and responsive-design practice: [The Odin Project](https://www.theodinproject.com/)
- Avatar and project identity: Miguel Ángel Rua Ruiz
