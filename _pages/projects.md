---
permalink: /projects/
title: "Projects"
layout: splash
header:
  overlay_image: /assets/images/kalte-wasser.jpg
  overlay_filter: 0.8 # same as adding an opacity of 0.5 to a black background
# excerpt: "Some open source projects I made in the process of learning."
intro: 
  - excerpt: "Some open source projects I have made in the process of learning."
feature_row:
  - image_path: /assets/images/project-images/design-donts.jpg
    image_caption: "Photo by [Frat_Panda](https://www.reddit.com/user/Frat_Panda) on [Reddit](https://www.reddit.com/)"
    alt: "Image for The Don'ts of Design"
    title: "The Don'ts of Design (WORK IN PROGRESS)"
    excerpt: "An archive of bad design put together using some CV, some NLP, a lot of (wo)man hours and r/CrappyDesign"
    url: "https://github.com/sanikamnjoshi/design-donts"
    btn_label: "Repo"
    btn_class: "btn--primary"
  - image_path: /assets/images/project-images/github-trending.jpg
    image_caption: "Photo by [Patrick Tomasso](https://unsplash.com/@impatrickt) on [Unsplash](https://unsplash.com/)"
    alt: "Image for GitHub Trending"
    title: "GitHub Trending"
    excerpt: "A Python script that scrapes the GitHub trending page and writes the repo links to a text file. Made using BeautifulSoup."
    url: "https://github.com/sanikamnjoshi/github-trending"
    btn_label: "Repo"
    btn_class: "btn--primary"
  - image_path:  /assets/images/project-images/commit-count.jpg
    image_caption: "Photo by [Yancy Min](https://unsplash.com/@yancymin) on [Unsplash](https://unsplash.com/)"
    alt: "Image for Commit Count"
    title: "Commit Count"
    excerpt: "Python code for getting the number of commits made in a repo using GitPython."
    url: "https://github.com/sanikamnjoshi/commit-count"
    btn_label: "Repo"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/project-images/ekal.jpg
    image_caption: "Photo by [NORTHFOLK](https://unsplash.com/@northfolk) on [Unsplash](https://unsplash.com/)"
    alt: "Image for eKal"
    title: "eKal"
    excerpt: "A simple web application for team collaboration."
    url: "https://github.com/sanikamnjoshi/eKal"
    btn_label: "Repo"
    btn_class: "btn--primary"

# feature_row2:
#   - image_path: /assets/images/kalte-wasser.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** # formatting. Left aligned with `type="left"`'
#     url: "https://sanikamnjoshi.github.io/commit-count/"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/kalte-wasser.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** # formatting. Right aligned with `type="right"`'
#     url: "https://sanikamnjoshi.github.io/github-trending/" 
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/kalte-wasser.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** # formatting. Centered with `type="center"`'
#     url: "https://sanikamnjoshi.github.io/eKal/"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# {% include feature_row id="feature_row2" type="left" %}

# {% include feature_row id="feature_row3" type="right" %}

# {% include feature_row id="feature_row4" type="center" %}
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2"%}