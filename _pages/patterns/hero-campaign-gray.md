---
layout: pattern
categories: [patterns, hero]
title: Campaign Page Hero (Gray)
type: [detail-page]
permalink: /patterns/hero-campaign-gray/
variations: true
description: |
overview: This layout allows for an image with padding.

usa-link:
specification: 
spec:
cards:
  - title: Card 1
    content: card 1 content
    button: Learn more about card 1
    img: https://designsystem.digital.gov/img/introducing-uswds-2-0/built-to-grow--alt.jpg
    alt: placeholder image
    media-class: usa-card__media--inset
  - title: Card 2
    content: card 2 content
    button: Learn more about card 2
    img: https://designsystem.digital.gov/img/introducing-uswds-2-0/built-to-grow--alt.jpg
    alt: placeholder image
    media-class: usa-card__media--inset
  - title: Card 3
    content: card 3 content
    button: Learn more about card 3
    img: https://designsystem.digital.gov/img/introducing-uswds-2-0/built-to-grow--alt.jpg
    alt: placeholder image
    media-class: usa-card__media--inset
yml: |
  
  cards:
  - title: Card 1
    content: card 1 content
    button: Learn more about card 1
    img: https://designsystem.digital.gov/img/introducing-uswds-2-0/built-to-grow--alt.jpg
    alt: placeholder image
    media-class: usa-card__media--inset

jekyll: |

  "{% include patterns/hero/hero-campaign-gray.md %}"
### Paths to view design and code... 
## designimg: can be used to show an image of the design until a coded version can be created. The htmlpath & csspath should be located in the pattens folder. Read more about creating coded components in /docs/creating-patterns 
# designimg: 
htmlpath: patterns/hero/hero-campaign-gray.md
csspath: patterns/hero/index.scss
---