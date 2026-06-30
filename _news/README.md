# Adding a news entry

Create a new file here named `YYYY-MM-DD-short-slug.md` (the date in
the filename doesn't have to be exact -- the `date:` field below is
what actually controls ordering).

```
---
title: "A short headline for the update"
date: 2026-07-01
category: Publication        # or: Conference, Award, New member, etc. Optional -- delete the line if you don't want one.
image: /assets/images/news/your-photo.jpg   # optional -- delete the line if there's no photo
---

One or two sentences of body text. This is what shows on the News
page. Markdown and links work here, e.g. [like this](https://example.com).
```

That's it -- it'll show up automatically on `/news/`, and on the
homepage if it's among the 3 most recent entries (homepage only shows
the title line, not the full body text).

See `2026-06-15-permafrost-paper.md` (with a photo) and
`2026-05-20-agu-talk.md` (without one) in this folder as examples.
