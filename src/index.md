---
home: true
heroImage: https://mb.com.ph/wp-content/uploads/2020/07/dam.jpg
tagline: Presentation of various irrigation structures and their uses.
actionText: Start →
actionLink: /intro/
xfeatures:
- title: Introduction
  details: Introduction to irrigation system.
  link: /intro/
- title: Structures
  details: Presentation of basic and commonly used irrigation structures.
  link: /structures/
- title: Link
  details: Website link for this presentation.
  link: /link/
footer: Made by Alexius Academia with ❤️ alexius.academia@gmail.com
---

<div class="features">
  <div class="feature" v-for="feat in $page.frontmatter.xfeatures">
    <h2><a v-bind:href="feat.link">{{ feat.title }}</a></h2>
    <p>{{ feat.details }}</p>
  </div>
</div>
