# Portfolio update notes

This branch adds dedicated pages for Vape Lords and Technologia Scope and turns the homepage into a project hub.

## New pages

- `/vape_lords/`
- `/technologia_scope/`

## Adding media

The new pages intentionally use CSS media placeholders so the site does not show broken image links before assets are ready.

Suggested asset folders:

```text
assets/media/images/vape_lords/
assets/media/images/technologia_scope/
assets/media/video/vape_lords/
assets/media/video/technologia_scope/
```

### Replace a screenshot placeholder

Replace:

```html
<div class="media-placeholder">
  <strong>SCREENSHOT 01</strong>
  <span>UI / combat / world</span>
</div>
```

with:

```html
<a href="/assets/media/images/vape_lords/full_image.png">
  <img src="/assets/media/images/vape_lords/full_image.png" alt="Vape Lords combat interface">
</a>
```

### Replace the hero video placeholder with YouTube

Use the site's existing responsive video classes:

```html
<div class="video-wrapper">
  <div class="video-container">
    <iframe
      src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
      title="Vape Lords gameplay"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen>
    </iframe>
  </div>
</div>
```

### Homepage thumbnails

The Vape Lords and Technologia Scope cards currently use styled CSS placeholders. Once hero images exist, replace the placeholder divs in `index.markdown` with the same `project-thumb-image` pattern used by Lonesome Wastes.

Example:

```html
<div class="project-thumb project-thumb-image"
     style="background-image:url('/assets/media/images/vape_lords/hero.jpg');"></div>
```

## Local preview

If Ruby/Jekyll is installed:

```bash
bundle install
bundle exec jekyll serve
```

Then browse to `http://127.0.0.1:4000`.

## Added media
- Vape Lords gameplay video: https://youtu.be/CHx14s7bmUk
  - Embedded at the top of `vape_lords/index.markdown`.
