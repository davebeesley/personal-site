---
layout: main
title: David Beesley | Web Developer
description: David Beesley is a Web Developer based in Cheltenham, England
canonical: https://davidbeesley.co.uk/
---

Hi, thanks for stopping by. As you can see, I have taken the bold step of rebuilding my site in the wild!

This is just a static holding page for now, and intentionally unstyled to be as accessible as possible, just plain old html

Over time I will be building this site out using [11ty](https://www.11ty.dev/) and blogging about what I have learned along the way, along with my decision making process

Don't worry, if you stopped by to find out more about me, it is available at [legacy.davidbeesley.co.uk](https://legacy.davidbeesley.co.uk/)

In the meantime, I can be contacted by email at [hello@davidbeesley.co.uk](mailto:hello@davidbeesley.co.uk) or you can spot me on Twitter at [twitter.com/davebeesley](https://www.twitter.com/davebeesley)

Want to see the code and commits? Head on over to [github.com/davebeesley/personal-site](https://github.com/davebeesley/personal-site)

---

## Progress

**Start (20/02/2020 20:45 GMT/UTC):** Started building out new site with a static html file

**Update (20/02/2020 21:45 GMT/UTC):** I have rebuilt the homepage as a [markdown](https://www.markdownguide.org/) file with the requisit [front matter](https://www.11ty.dev/docs/data-frontmatter/), separated the markup into a [layout](https://www.11ty.dev/docs/layouts/), and built using [11ty](https://www.11ty.dev/)

**Update (20/02/2020 21:50 GMT/UTC):** In order to allow the site to build on [Netlify](https://www.netlify.com/), I needed to add a `package.json` using the command `npm init`. Then added netlify as a dev dependency using the command `npm install --save-dev @11ty/eleventy` - I have also configured [Netlify](https://www.netlify.com/) to build the site with [11ty](https://www.11ty.dev/) from the [master branch](https://github.com/davebeesley/personal-site) and serve from the compiled `_site` directory using the following code in `netlify.toml` saved at the root of the site

```toml
[build]
  publish = "_site"
  command = "eleventy"
```

**Update (20/02/2020 22:05 GMT/UTC):** Couldn't resist adding a header and footer

**Update (08/04/2020 17:05 GMT/UTC):** Due to being made redundant, and needing a working website for job hunting. This project has been moved onto the `beta.` subdomain. My legacy iteration of the website has been restored in the short term
