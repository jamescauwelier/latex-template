# Latex template

A template for the automatic building and releasing of LaTeX documents

Just write your LaTeX file as usual and commit to your github repository.  when you're ready to release a new version, tag your master branch using a semver pattern, e.g. v0.1 or v0.2.1.

Afterwards, push that tag to your repository.  

The whole workflow should look a bit like this:

```
# do some changes in your repository
git add --all
git commit -m "Something to describe your changes"
git push
git tag v0.1
git push --tags
```
