# ETHIstanbul — Conference Landing Page

A responsive conference landing page built with HTML and CSS as a learning and portfolio project. The page brings together an event introduction, speaker cards, a three-day schedule, merchandise previews, and venue information.

> Unofficial educational project inspired by ETHIstanbul. This is not the official event website, ticket service, or merchandise store. Event details represent the original project content, not current event information.

## Features

- Responsive layouts using CSS Grid, Flexbox, and media queries
- Speaker cards and a three-day conference schedule
- Merchandise grid and venue section with a map link
- CSS-only demo modal using the `:target` selector
- Entrance animations with Animate.css and reduced-motion support
- Keyboard focus styles and a skip link for navigation

## Built with

- HTML5
- CSS3
- [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins)
- [Animate.css](https://animate.style/)

No JavaScript, package installation, or build step is required. Google Fonts and Animate.css load from external services; the page uses a fallback font when they are unavailable.

## Run locally

Open `index.html` directly in a browser, or use a static server such as the VS Code Live Server extension and choose **Open with Live Server** on `index.html`.

## Project structure

```text
web-ethistanbul/
├── index.html       # Page structure and content
├── style.css        # Layout, components, and responsive styles
├── img/             # Speaker, venue, background, and merchandise images
├── .editorconfig    # Shared formatting preferences
├── .gitattributes   # Text file normalization
└── .gitignore       # Local files excluded from version control
```

## Scope

This project demonstrates static page structure, CSS layout, responsive design, and visual styling. The ticket and notification modal is a UI demo: its fields are disabled and no personal information is collected or submitted. There is no backend, checkout, registration, or email integration. The CSS-only modal does not implement JavaScript dialog behavior such as focus trapping or Escape-to-close.

## GitHub Pages

After pushing the repository to GitHub, open **Settings → Pages**, choose **Deploy from a branch**, then select **main** and **/ (root)**. The site uses relative asset paths so it can be served from a repository subdirectory without a build step.

## Credits and assets

The event name, event content, speaker portraits, organization logos, and event imagery relate to [ETHIstanbul](https://ethistanbul.io/) and their respective owners. The venue image depicts Rami Library. Merchandise images are included from the original project; their original source and reuse permissions have not been verified. No ownership of third-party branding or imagery is claimed.

No blanket license is applied to the repository because third-party asset permissions have not been established. Before reusing or redistributing those assets, verify the relevant permissions or replace them with assets you own.
