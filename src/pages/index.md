---
title: Alan Laidlaw
subtitle: A home for conventional text
eleventyNavigation:
    key: Home
permalink: "/"
---
<figure>
[^{-} Based entirely on Eleventufte by the inestimable *Jeff Eaton*.] 
[tufte-css](https://github.com/edwardtufte/tufte-css)
</figure>

A quick-start template that combines the front-end styling of [tufte-css](https://github.com/edwardtufte/tufte-css), the custom parser of [tufte-markdown](https://github.com/luhmann/tufte-markdown), and the flexibility of [Eleventy](https://11ty.dev) in the style of [Edward Tufte's much-loved books](https://www.edwardtufte.com/tufte/).

The [Features page](features/) gives a more thorough run-down of the Markdown enhancements it offers. If you're interested in cloning and using it yourself, [head on over to Github](https://github.com/nerdhaus/eleventufte)…

## Recent posts…
{%- import "list.njk" as list -%}
{{ list.details(collections.posts) }}
