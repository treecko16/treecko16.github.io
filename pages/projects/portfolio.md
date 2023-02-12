# Portfolio

## Project summary
For this project I set up a portfolio website using GitHub Pages, which effectively turns a GitHub repo into a site.

It's been interesting experimenting with this minimal dev setup. All I do, after initial setup, is write markdown files and push them to the GitHub repo. Pages runs the pipeline, and I can see the live page almost immediately. Real nice and simple

## Intro to GitHub Pages
[GitHub Pages](https://pages.github.com/) builds and hosts a static site from a public GitHub repository, using [Jekyll](https://jekyllrb.com/) as a template & theming engine. You just commit files to your site repo (in this case [treecko16/treecko16.github.io](https://github.com/treecko16/treecko16.github.io)), and the Pages CI genie realises there's new files. The build process is run (in this case, just running `jekyll build`, though I may add linters and build pass/fail reporting later on), and the finished site is published.
In short:
1. Write .md or .html content
2. Commit to GitHub repo
3. Pages CI checks and builds site using Jekyll
4. Pages publishes the built site at username.github.io

## Intro to Jekyll
(WIP)

## What I've learnt
- Making a simple website can be very easy
- I don't have to touch icky security stuff if all I want is a static site (GitHub signs my Pages for me)
- Jekyll is a lovely little tool for turning content like Markdown files into webpages
- I should look into Ruby and its Gems ecosystem, it seems neat

## To do
I've still got many things to do here. I need more content (project writeups) first and foremost, but I also want to add a nav breadcrumb bar at the top of the page. Wouldn't hurt to have a demo of some other project (e.g. a small game or blockchain explorer) running too.