# Portfolio

## Summary
For this project I set up a portfolio website using GitHub Pages, which effectively turns a GitHub repo into a site.

It's been interesting experimenting with this minimal dev setup. All I do, after initial setup, is write markdown files and push them to the GitHub repo. Pages runs the pipeline, and I can see the live page almost immediately. Real nice and simple

## Intro to GitHub Pages
GitHub Pages builds and hosts a static site from a public GitHub repository, using Jekyll as a template & theming engine. You commit files to your site repo (in this case treecko16.github.io), and the Pages CI genie realises there's new files. The build process is run (in this case, just running `jekyll build`, though I may add linters and build pass/fail reporting later on).