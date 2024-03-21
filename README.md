# German-Notebook
A place to record my learning as I go.

## Mkdocs
So there are 2 branches:
* main - code
* gh-deploy - built site being served

To test and or see the site before building\pushing:
> From root dir
```bash
cd mkdocs
mkdocs gh-deploy
```

* `mkdocs gh-deploy` builds a `site` directory as a sibling to the docs folder and child of the mkdocs folder. We don't need it unless we want to inspect so we ignore from `.gitignore`.
* The site folder "is" however what is pushed to the `gh-pages` branch so this will continually change with `mkdocs gh-deploy` and then be pushed to the `gh-pages` branch.