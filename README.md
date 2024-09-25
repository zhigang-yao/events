# Template of conference homepage

## This repo is based on *cayman*:
[![.github/workflows/ci.yaml](https://github.com/pages-themes/cayman/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/cayman/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)

*Cayman is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/cayman), or even [use it today](https://github.com/pages-themes/cayman?tab=readme-ov-file#usage).*


## Usage of this repo

To use the Template:

- Change the site information in `_config.yml`.

- Make a new page like the provided one, and change the details.

- Revise the list information in `index.md`.

## Local run

Need to [setup Jekyll](https://jekyllrb.com/docs/) first. 

Then, for preview, run: 
```
bundle exec jekyll serve --livereload
```

For locally build:
```
bundle exec jekyll build
```
The built website is created in *_site/*

To clean up the temp files:
```
bundle exec jekyll clean
```