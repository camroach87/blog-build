# blog-build

Files to build blog. Based on nodejh hugo-theme-cactus-plus.

## Instructions

1. Posts go in the `content/post` directory. Easiest to just copy and paste an old one and update date as required.
2. Run `blogdown::serve_site()` to run the site locally.
3. If the site looks ok it's time to commit. In terminal, navigate to the `public` directory and add/commit/push. The public directory is set up as its own git repo and is pushing to `camroach87/camroach87.github.io`.

## Notes

* Deleting a post in blog-build does not delete it from public folder. Need to manually delete all files and then rebuild site. Be careful not to delete the git files!
* Don't understand difference between `blog_build` and `serve_site`.