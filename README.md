# lunch-and-learn-fork

A template Vue.js app with Bootstrap taken from Frank during my time working at TD Lab

## Instructions

```bash
npm install
npm run serve
```

Now go to http://localhost:8080/

## Deployment

Enter this into terminal in your root dir:

```bash
npm run build
```

This will generate a bunch of production-ready files in the ./dist folder.

To deploy to GitHub pages, we want to commit those files into the gh-pages branch:

```
git add dist && git commit -m "Initial dist subtree commit"
git subtree push --prefix dist origin gh-pages
```

Now go to settings in your repo and make sure that GitHub Pages's source is your gh-pages branch. 
