## Personal blog powered by Jekyll

Slightly modified Jekyll theme (see source links below) with automatic build and deployment to Github Pages.

Build and deploy are automated by Github Actions – [.github/workflows/website.yaml](.github/workflows/website.yaml).

Deploy goes to gh-pages branch which is confiogured for Github Pages.

## Markdown CV with rendering to HTML

Base directory – [cv](cv).

"source code" for the CV is a Markdown file which is rendered by pandoc utility. Font, layout and other customizations are made in .css file, as ususally. There are no customizations to renderigng.

Build and deploy are automated by Github Actions – [.github/workflows/cv.yaml](.github/workflows/cv.yaml).

Deploy goes to the same gh-pages branch.

## Technologies used: 

- Artem Shedulko's Jekyll theme - https://github.com/artemsheludko/flexible-jekyll
- Jekyll static website generator - https://jekyllrb.com
- Pandoc document converter - https://pandoc.org and https://hub.docker.com/r/pandoc/latex
- Github Pages and Github Actions