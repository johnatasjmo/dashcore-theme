README.MD

This is a theme for using with gohugo

Pushing to github

added on repo


# add theme as submodule
```
git submodule add https://github.com/johnatasjmo/dashcore-theme site/themes/dashcore-theme
git submodule init
git submodule update
git status
git add -A
git commit -m "git submodule added"
```

# To update submodule
```
git submodule update --remote
```

# to reset submodule
```
cd site/themes/dashcore-theme
git reset --hard
```