# brew-meta
meta packages

##Build

Test it with `git-buildpackage --git-ignore-new`

##Deploy

* git `git add -A && git commit -am "some comment"`
* changelog `git-dch -R`
* git `git add -A && git commit -am "some comment"`
* build `git-buildpackage --git-tag`
* push `git push && git push --tags`
* clean `debuild clean`