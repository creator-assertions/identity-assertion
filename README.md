# Identity Assertion

TO DO: Add links to community spec documents.

## About this site

This document is the source code for a public specification available at [(TEMPORARY SITE to be named later)](https://reliable-sprite-ac392c.netlify.app/identity/0.1-draft/).

The site content is built using [Antora](https://antora.org), which takes Asciidoc (.adoc) plain text files and renders them to HTML and other formats.

The primary content of this document is available in [docs/modules/ROOT/pages/index.adoc](https://github.com/content-authorship/identity/blob/main/docs/modules/ROOT/pages/index.adoc) in this repo.

## Local preview

You can render the site of this content locally if you wish to test the appearance of changes you are making. To do this:

1. Ensure that you have a current version of node.js installed ([installers are here](https://nodejs.org/en/download/)).
2. Install Antora and other project dependencies.

```
$ cd (root of this repo)
$ npm install
```

Each time you wish to preview content, run the following:

```
$ npx antora antora-playbook-local.yml
Site generation complete!
Open file:///(root of this repo)/build/site/index.html in a browser to view your site.
```

Antora does not have a live-preview feature, so you will need to re-run this command to ensure that the rendered site reflects any changes you have made.
