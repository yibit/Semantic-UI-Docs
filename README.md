# Semantic Docs

This folder contains the templates used to generate the static website for [semantic-ui.com](http://www.semantic-ui.com)

## How to Use

```bash

mkdir -p ~/semantic-ui
cd ~/semantic-ui

npm install -g docpad
docpad install eco;
docpad update; docpad upgrade;

git clone https://github.com//Semantic-Org/Semantic-UI ui --depth=1
git clone https://github.com//Semantic-Org/Semantic-UI-Docs docs --depth=1

cd ui
gulp build-docs # Generating SUI for Docs

cd docs
docpad run  # Running the Server
```

Watch for changes from your UI folder, and serve to the docs instance:

```
gulp serve-docs
```


## Help Fix Typos and Errors

If you find any typos or mistakes, submitting a fix is easy!

- [Open the `documents/` folder](https://github.com/Semantic-Org/Semantic-UI-Docs/tree/master/server/documents) on GitHub
- Click the “Edit” button on the appropriate page
- Click to submit a pull request

