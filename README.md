# Hexo Theme: Landscape-AlphaGeek

## What is it?

A custom version of the [default theme](https://github.com/hexojs/hexo-theme-landscape) for [Hexo](https://hexo.io).

## Customisations

* Removed default menu options
* Added ability to use raw HTML in menu items
* Added `openbadge` custom post type to display Open Badge data

## Why does it exist?

This theme was created to enable showcasing of custom plugins for Hexo, whilst providing the ability to link back to a
primary site and a plugin specific page.

## Installation

1. Fork this repository
2. Clone the fork into your Hexo project in the `themes/landscape-alphageek` directory
3. Update `_config.yml`, changing the `theme:` line to `theme: landscape-alphageek`
4. Add configuration for the menu to your `_config.yml`, for example:
   ```yaml
   theme_config:
     menu:
       "<img src=\"https://alphageek.com.au/favicon/favicon-32x32.png\">": https://alphageek.com.au
       "&lt; Back to Theme Page": https://software.alphageek.com.au/hexo/theme-landscape-alphageek
       Home: /
   ```
