---
title: Getting Started
menu: cms
type: doc
weight: 10
---

Test summary.

## Stack

Static site generator (Hugo) and headless CMS (Cloudcannon). Why headless?

Not required to use Hugo. Download the HTML, CSS, and Javascript. Can use any static site generator. However, docs...

## Setting Up a Hugo Site

Read their docs.

1. If you’re a Prof. Tech., request a website. We’ll set up a repo for you. Or create your own.
1. Create a new Hugo site. From your local `hugo_themes` directory, `hugo new mysite`.
1. `cd` into your new site.
1. Fire up local server. From site’s root directory `hugo server`.
1. Visit `localhost`. You should see a site, but with no styling, Javascript, etc. Next, you’ll need to pull in some remote...
1. Edit your config file. This will install the DSv3 Hugo theme as a module, which contains CSS, Javascript, etc.
1. Mount component library.
1. Start adding content.
1. Add your site to the repo
1. Commit your changes.

## If Using Cloudcannon

Once you’ve followed the steps above...

1. Log into Cloudcannon.
1. Connect your site.
1. Make changes.
1. Save/Publish.
1. Pull `git pull origin main`.