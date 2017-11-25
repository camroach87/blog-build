# blog-build

Files to build blog. Based on nodejh hugo-theme-cactus-plus.

## Instructions

1. Posts go in the `content/post` directory. Easiest to just copy and paste an old one and update date as required.
2. Run `blogdown::serve_site()` to run the site locally.
3. If the site looks ok it's time to commit. In terminal, navigate to the `public` directory and add/commit/push. The public directory is set up as its own git repo and is pushing to `camroach87/camroach87.github.io`.

## Notes

* Use `build_site()` to completely rebuild site. I \*think\* that `serve_site()` uses cached versions of the pages? Seems like sometimes not everything gets updated/deleted if I only run `serve_site()`. Need to double-check documentation.