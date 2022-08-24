# KH STATS -- blog/portfolio code

## Hugo template

This website uses this hugo theme: [kishaningithub/hugo-creative-portfolio-theme](https://github.com/kishaningithub/hugo-creative-portfolio-theme), found on Bootstrapius.

## Creating in R

1. R -> New Project -> new blog -> blogdown; then cited the Github repo for my theme [kishaningithub/hugo-creative-portfolio-theme](https://github.com/kishaningithub/hugo-creative-portfolio-theme)

2. Once in the R project, ran `blogdown::serve_site()`

3. Changed the "portfolio" folder to "blog" to match my previous Hugo Academic urls

## Adding math equation compatibility

1. Installed latest version of KaTeX by running `npm install katex` in my terminal (on a Mac) (see https://katex.org/docs/node.html for other options)

2. Put a katex.html file under themes/layouts in my project directory