---
layout: layouts/project.njk
title: Project Generated by CMS
thumbnailSrc: static/media/uploads/Gleam.jpg
thumbnailAlt: Thumbnail alt generated by CMS
description: This is a description entered directly through the CMS UI.
tags:
  - projects
  - UX-Design
---
<div class="stack><div class="stack>
  <h2>Project Generated by CMS</h2>
  <p>This is a project that was generated directly by CMS. Does it work? Who knows?This is a project that was generated directly by CMS. Does it work? Who knows?</p>
  <p>Let's try out some html with our custom CSS, below we'll make a grid of images with grid gap of 1rem.</p>

  <div class="grid gap:s0">
    <article class="frame-square">
      <img src="https://picsum.photos/800/400">
    </article>
    <article class="frame-square">
      <img src="https://picsum.photos/800">
    </article >
    <article class="frame-square">
      <img src="https://picsum.photos/800">
    </article>
    <article class="frame-square">
      <img src="https://picsum.photos/800">
    </article>
    <article class="frame-square">
      <img src="https://picsum.photos/800">
    </article>
  </div>

  <p> Literally every line of css used in the site is available to us here. We can even define our custom styles, specific to this blog post right here.</p>

  <style>
    .random-flex-container-lol {
      display: flex;
      justify-content: space-between;
    }

    .random-flex-container-lol > * {
      width: 40%;
    }
  </style>

  <div class="random-flex-container-lol">
    <img src="https://picsum.photos/800">
    <img src="https://picsum.photos/800">
  </div>
</div>