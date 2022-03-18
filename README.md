https://nnierrr.github.io/nieric-resume/

In order to deploy the local changes you made:

```sh
# Clear working tree
$ git add .
$ git commit -m "Before deploy"

# build project to dist directory
$ npm run build

# Use push-dir to push dist to gh-pages
$ npm run deploy
```
