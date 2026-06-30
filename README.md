# Hydrology and Landscape Dynamics Lab — site source

A minimal Jekyll site, built from scratch with help from Claude.

## Where to edit things

| What you want to do                          | File to edit                                  |
|-----------------------------------------------|------------------------------------------------|
| Change the homepage hero image, headline, mission text, or "current directions" list | `index.md` |
| Add/edit a research topic and its publications | `research.md` (front matter `topics:` list)  |
| Add a lab member                              | `people.md`                                   |
| Edit teaching content                          | `teaching.md`                                 |
| Edit opportunities/recruiting text             | `opportunities.md`                            |
| Add a news update                              | new file in `_news/` (see `_news/README.md`)  |
| Add a new simple page (e.g. expand Lab values) | `lab-values.md`, `software.md`, or copy one of these as a template for a new page |
| Site title, email, GitHub Pages URL            | `_config.yml`                                 |
| Colors, fonts, spacing                          | `assets/css/main.css` (CSS variables at the top) |

Every `.md` file above has comments in its front matter explaining the
fields. You generally won't need to touch anything in `_layouts/` or
`_includes/` unless you want to change the structure of a page type
(e.g. how the research blocks are arranged), not just its content.

## Adding a new top-level nav page

1. Create `new-page.md` at the root, copying the front matter pattern
   from `lab-values.md` (`layout: default`, a `title:`).
2. Add a link to it in `_includes/nav.html` -- either as a main tab or
   inside the "More" dropdown.

## Photos

Drop images in `assets/images/research/`, `assets/images/people/`,
or `assets/images/news/` and point to them by path in the relevant
front matter field (e.g. `image: /assets/images/research/my-photo.jpg`).
Placeholder gray boxes are there until you do.

- Research/news thumbnails: roughly 4:3, at least 800px wide.
- People photos: square, at least 600px.
- Homepage hero: wide, at least 1600px, with enough contrast at the
  bottom-left for white text to sit on top of it.

## Running locally

```
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

## Deploying to GitHub Pages

1. Push this repo to `username.github.io` (or any repo, with Pages
   enabled and built from this branch).
2. Update `url:` in `_config.yml` to match.
3. GitHub Pages will build it automatically using the `github-pages`
   gem specified in the Gemfile -- no extra build step needed.
