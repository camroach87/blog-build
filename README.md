# blog-build

Files to build blog. Based on nodejh hugo-theme-cactus-plus.

## Instructions

1. Posts go in the `content/post` directory. Easiest to just copy and paste an old one and update date as required.
2. Run `blogdown::serve_site()` to run the site locally.
3. If the site looks ok it's time to commit. In terminal, copy the `public` directory to the `camroach87.github.io` git repo. Stage, commit and push the changes.

## Notes

* Deleting a post in blog-build does not delete it from public folder. Need to manually delete all files and then rebuild site. Be careful not to delete the git files!
