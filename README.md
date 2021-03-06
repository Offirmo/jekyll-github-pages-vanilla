#

The latest GitHub pages compatible vanilla Jekyll for reference.

## Introduction
A free, quality hosting solution is to use Jekyll on GitHub pages.
Due to its particular structure, Jekyll changes are hard to track
and it may be difficult to distinguish between vanilla Jekyll files and our custom files.

This repo features the latest (on my discretion ;) vanilla, unmodified, GitHub-compatible Jekyll install
to serve as a reference when either:
- upgrading Jekyll
- evaluating Jekyll themes and plugins

Need ruby

Created following instructions here:
* https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
* https://help.github.com/articles/creating-a-custom-404-page-for-your-github-pages-site/
* http://jekyllrb.com/docs/drafts/

## run and update
Need ruby installed: https://github.com/Offirmo-team/wiki/wiki/Ruby#installation
```sh
bundle update
bundle exec jekyll serve --drafts
bundle exec jekyll new . --force   <- XXX review the changes to undo some lines
```

## Interesting read
Links:
* https://github.com/Offirmo-team/wiki/wiki/GitHub#h%C3%A9bergement-pages
  * https://pages.github.com/
  * https://help.github.com/articles/using-a-custom-domain-with-github-pages/
  * https://help.github.com/articles/securing-your-github-pages-site-with-https/
  * ...
* https://github.com/Offirmo-team/wiki/wiki/jekyll
  * https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/
  * https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
  * ...
