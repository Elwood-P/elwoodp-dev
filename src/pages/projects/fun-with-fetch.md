---
layout: ../../layouts/ProjectLayout.astro
title: Fun with Fetch & Array Methods
description: Fun with data from The One API
year: 2021
order: 3
sourceUrl: /Elwood-P/fun-with-fetch-and-array-methods
liveUrl: https://jsv-fetch-array.netlify.app/
imageUrl: "https://kimba-imagecdn.imgix.net/elwoodp-dev/github-screenshots/fun-fetch-screenshot-v2.png"
icon: javascript
---

<!-- NB: This is a copy of the readme on GitHub which is loaded remotely. -->

# Fun with Fetch & Array Methods

> One of several projects undertaken to sharpen my skill in vanilla javascript.
> [View project live](https://jsv-fetch-array.netlify.app/)

## Key Features
- Fetch data from API using async/await
- Handle fetch errors gracefully
- Fetch error handling
- Secure API secrets using Netlify functions - read the [blog post](https://elwoodp.dev/articles/how-to-hide-api-keys/) detailing the challenge
- Demonstrate proficiency in using array methods

## Technologies
-   JavaScript (Vanilla)
-   Netlify Functions

## Setup
```shell
# Run local server
$ netlify dev

# Publish changes to netlify
$ git push origin main
```

## Todo
- [ ] Fix deliberate fetch error button
- [ ] Implement fetch timeout - https://stackoverflow.com/questions/46946380/fetch-api-request-timeout
- [ ] Change simulate fetch error button to use timeout
- [ ] Add a loading spinner
- [ ] Style table with no rows and handle table overflow

