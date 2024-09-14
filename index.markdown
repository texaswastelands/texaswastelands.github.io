---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
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
---
<div class="image-grid">
  <a href="/lonesome_wastes/">
    <img src="../assets/media/images/screenshots/thumbnails/tn_home_base_heli_far.jpg" alt="Thumbnail 5">
  </a>
</div>

## [Lonesome Wastes](/lonesome_wastes) - An action-rpg flight sim prototype

<br>

<div class="image-grid">
  <a href="/heli_evac/">
    <img src="../assets/media/images/screenshots/thumbnails/tn_heli_evac.jpg" alt="Thumbnail 5">
  </a>
</div>

## [Heli Evac](/heli_evac) - Haunted PS1, FPS horror test

---

### Built in Unity

- With a focus on game and systems design and aesthetics for the prototype, create original C# code for all game logic and game systems, while leveraging and modifiying 3rd party tools and code for some of the more technical but less design-focused elements such as the helicopter flight controller for Lonesome Wastes.

- Original sound effects and music

- Art assets primarily external, from Unity Asset Store or CGTrader or Itch.io. Original animations.

- Using [HPSXRP](https://github.com/pastasfuture/com.hauntedpsx.render-pipelines.psx) custom render pipeline from pastafuture

- Most of my time spent during prototyping was to determine performance demands, explore aesthetic styles and intricacies of custom render pipeline, and validate game and systems design while learning essential tools and processes.