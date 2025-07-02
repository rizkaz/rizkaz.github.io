---
title: "About"
permalink: "/about/"
layout: page
---


## Dependencies
 - ruby
   - Ensure Ruby 2.4 or higher
 - update dependencies
   - bundle update
## Install

```bash
bundle install
```

## Build

```bash
bundle exec jekyll build
```



## Running Locally

Serve with drafts: To include draft posts (files in _drafts/ folder):
```
  bundle exec jekyll serve --drafts
```

Serve with future posts: To include posts with future dates:
```
  bundle exec jekyll serve --future
```

Custom port: If port 4000 is in use, specify a different port:

```bash
  bundle exec jekyll serve --port 4001
```
