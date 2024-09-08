---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
<head>
  <meta property="og:title" content="{{ page.title | escape }}">
  <meta property="og:description" content="{{ site.description | default: page.excerpt | escape }}">
  <meta property="og:url" content="{{ page.url | absolute_url }}">
  <meta property="og:image" content="{{ site.url }}/assets/media/images/backgrounds/txw_background_01_large.jpg">
  <meta property="og:type" content="website">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
</head>

# Gamedev Projects
<style>
  body {
    position: relative;
    height: 100vh; /* Full viewport height */
    margin: 0;
    padding: 0;
  }

  body::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('/assets/media/images/backgrounds/txw_background_01_large.jpg');
    background-size: cover; /* Stretches the image while maintaining aspect ratio */
    background-repeat: no-repeat;
    background-position: center center;
    opacity: 0.3; /* Adjust the opacity here */
    z-index: -1; /* Ensures the background is behind the content */
  }
</style>
[Lonesome Wastes](/lonesome_wastes) - A game about the dark irony of finding happiness in the Apocalypse. An action-rpg flight sim.

[Heli Evac](/heli_evac) - Haunted PS1, FPS horror test.
