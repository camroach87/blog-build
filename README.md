# blog-build

Files to build blog. Based on nodejh hugo-theme-cactus-plus.

## Instructions

1. Posts go in the `content/post` directory. Easiest to just copy and paste an old one and update date as required.
2. Run `blogdown::serve_site()` to run the site locally.
3. If the site looks ok it's time to commit. In terminal, navigate to the `public` directory and add/commit/push. The public directory is set up as its own git repo and is pushing to `camroach87/camroach87.github.io`.

## Setting up

If I ever need to set this all up on another computer do this:

1. Clone `blog-build`.
2. Inside the `blog-build` directory, clone `camroach87.github.io`.
3. Rename the resulting `camroach87.github.io` folder to `public`.

Whenever I build the site using `blogdown`, the site files will be placed in the `public` folder. Since this is a git repo, I can then just push any changes to `camroach87.github.io` to update the website

## Notes

* Deleting a post in blog-build does not delete it from public folder. Need to manually delete all files and then rebuild site. Be careful not to delete the git files!
* Don't understand difference between `blog_build` and `serve_site`.