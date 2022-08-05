# Chris Tham Personal Site

This is a version of my personal blog/web site written in Markdown and [Hugo](https://gohugo.io). The site design was originally a fork of [Doks](https://getdoks.org), but I have added various features, including:

- changed colour scheme based on [Rosely](https://rosely.hellotham.com)
- reverted back to standard Bootstrap 12-column grid system (16 columns were just too weird for me)
- Carousel and hero on home page
- Card based blog list with featured image
- `map` shortcode using [leaflet.js](https://leafletjs.com) and [Open Street Map](https://openstreetmap.org)
- Photo Gallery shortcode using CSS based masonry and [PhotoSwipe](https://photoswipe.com), inspired by [Creating a Gallery Component for the Hugo Static Site Generator](https://brunoamaral.eu/post/creating-a-gallery-component-for-the-hugo-static-site-generator/) but updated for PhotoSwipe v5
- Use [Bootstrap Icons](https://icons.getbootstrap.com/)
- Taxonomy pages

It is hosted on [Github Pages](https://pages.github.com) and deployed via Github Action workflow.

To run a local version of the website, clone the repository and execute:

```bash
npm install
npm run start
```
