# Setup
title: Sokit Network
tagline: play.sokit.tk
url: https://noir.essentialenemy.com
paginate: 1
baseurl: ""
permalink: :title/

kramdown:
    footnote_backlink: "&#10548;"

# Gems
plugins:
  - jekyll-gist
  - jekyll-paginate
  - jekyll-seo-tag
  - jekyll-target-blank

# Optimize Jekyll
exclude:
  - .editorconfig
  - .git
  - .jekyll-cache
  - Gemfile
  - Gemfile.lock
  - LICENSE.md
  - README.md

sass:
  sass_dir: _sass
  style: :compressed

# Options

# Replace this value and uncomment to enable Google Analytics tracking
# ga_analytics: UA-000000-0

# Specify the author for blog posts
author:
  name: Victor Johnson
  url: https://twitter.com/essentialenemy
  email: me@essentialenemy.com

# Custom vars
version: 1.3.0
github:
  repo: https://github.com/essentialenemy/noir
