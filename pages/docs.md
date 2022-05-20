---
title: How to use this theme
layout: page
permalink: /docs
---


Who is it for (communities who need simple, no-database, archiving with minimal workflows)
How do we use it (Github and cameras)
Pros and Cons (doesn't have IIIF, lots of workflows; folks with more robust needs but not needing a full DB should look at Minicomp/Wax)
Example site (idahatiu.github.io)


# About your community's collection

See a sample collection at https://idahatiu.github.io/archives/

Some community archives use different words to describe their community members. We've included default language here, along with some suggestions.

## Collection

The collection of items built by the community can have lots of different names. Options include: archive, community archive, collection, compilation.

This is used in the main navigation for your site, and in the descriptions of your site's 

## Items

Items are the individual things that form a collection. Options include: item, object, heirloom, contribution

## Contributor

A contributor is the person who contributed an object. Options include: person, contributor, community member, descendant

## Groups

A group helps organize individual contributors into related sections in any way you choose. Options include: group, family, related items

## Stories

A story adds your community's voices to the web site. Options include: story, history, narrative, tale, memoir

## Team Members

Team members are the folks who work with the community to help collect and post items. This may or may not be part of your community's collection process. If it is, leave these blank.

# Item Listings

YAML format options:

`layout: item
format: photo`

- photo (includes photos of objects, scans of photos and documents)
- media (includes audio, video)
- outsidelink (includes social media posts, newspaper articles)


`
├── LICENSE.txt
├── README.md
├── _includes
│   ├── footer.html
│   ├── google-analytics.html
│   ├── head.html
│   ├── header.html
│   ├── icon-github.html
│   ├── icon-github.svg
│   ├── icon-twitter.html
│   └── icon-twitter.svg
├── _layouts
│   ├── default.html
│   ├── home.html
│   ├── page.html
│   └── post.html
├── _sass
│   ├── minima
│   │   ├── _base.scss
│   │   ├── _layout.scss
│   │   └── _syntax-highlighting.scss
│   └── minima.scss
└── assets
    └── main.scss
`

# Theme Doc Info for Pushing Theme to remote status

- ***https://jekyllrb.com/docs/themes/#creating-a-gem-based-theme***
- https://www.siteleaf.com/blog/making-your-first-jekyll-theme-part-2/
- https://github.com/benbalter/jekyll-remote-theme
- https://jekyllrb.com/docs/themes/
