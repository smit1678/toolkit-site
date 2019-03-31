# HOT Toolkit Site

## Build process


```sh
git checkout gh-pages
hugo
git add public
git commit -m "new build"
git subtree push --prefix public origin gh-pages
```