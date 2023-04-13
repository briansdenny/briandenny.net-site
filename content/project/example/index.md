---
title: Using jQuery Selectors to Customize Microcontent Display Rules
summary: Step-by-step instructions for identifying jQuery selectors and applying them to Whatfix display rules
tags:
  - L&D
date: '2023-04-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

jQuery selectors are used to select HTML elements on a webpage based on the element attributes (e.g. id, class, attribute, type, value, etc.) specified in the jQuery selector. This functionality allows web developers to identify and interact with HTML elements in a variety of ways. For instance, digital adoption platforms like Whatfix, Userpilot, and WalkMe allow  content developers to configure display rules for microcontent based on jQuery selectors. In my role as a Technical Writer at Consensus Cloud Solutions, I spearhead the company's work with Whatfix by ideating, designing, writing, configuring, testing, and analyzing microcontent that sits on top of several of our existing web applications. While teaching myself how to use Whatfix, I also learned the basics of jQuery selectors, and this has allowed me to create more refined, customized, and adaptive Whatfix microcontent. I created the following set of step-by-step instructions as an easy reference that allows anyone to identify jQuery selectors for use in Whatfix display rules.


jQuery('[<span style="color:red">attribute</span>="<span style="color:blue">content</span>"]') 

```markdown
{{% callout note %}}
Because HTML and the jQuery function rely on a nested coding language syntax, typing your queries in a nested fashion can help avoid mistakes. Work from the outside in.
{{% /callout %}}
```

jQuery('')  
jQuery('[] []')  
jQuery('[attribute="content"]')  