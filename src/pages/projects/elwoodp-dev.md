---
layout: ../../layouts/ProjectLayout.astro
title: elwoodp.dev
description: Personal web development website and blog
year: 2022
order: 5
sourceUrl: /Elwood-P/elwoodp-dev
liveUrl: https://elwoodp.dev
imageUrl: "https://kimba-imagecdn.imgix.net/elwoodp-dev/github-screenshots/elwoodp-screenshot-v2.png"
icon: astro
---

<!-- NB: This is a copy of the readme on GitHub which is loaded remotely. -->
# elwoodp.dev

> I’m Paul, a designer-developer based in York, UK. I’ve been building websites for 20 years. The web has changed quite a bit in that time, so I’m taking some time to sharpen my skills and become a better developer. This website charts my progress.  
> 
> Built with Astro.  
> 
> [View Project Live](https://elwoodp.dev)

## Key Features
- Astro blog with support for tags and drafts
- Fetch project READMEs from a project's GitHub repo
- Custom fluid Tailwind text and vertical spacing utilities
- Theme switcher with a custom-built Sass mixin to define theme values for specific properties

## Technologies Used
- [Astro ](https://github.com/withastro/astro)
- [Tailwind](https://github.com/tailwindlabs/tailwindcss) via [astrojs/tailwind](https://github.com/withastro/astro/tree/main/packages/integrations/tailwind)
- Netlify

  ## Setup
```shell
# Run local server (Vite)
$ npm run dev

# Publish changes live to Netlify
$ git push origin main
```

## Todo
- [ ] Pagination to index pages
- [ ] Extract custom tailwind utilities into a plugin
