# Oaxaca syntax theme

A minimal syntax theme for Atom.

**Current syntax support**: CSS, HTML, Handlebars, Javascript,
JSON, Less, Sass.

<img
  alt="JS syntax screenshot"
  src="https://www.dropbox.com/s/e67trvkqnluh4n0/screenshot.jpg?raw=1"
  style="width: 100%;"
/>

**Screenshot**: UI theme - [One Dark](https://github.com/atom/one-dark-ui).
Font - [Source Code Pro](https://github.com/adobe-fonts/source-code-pro).

---

## Contributing

Contributions are **very** welcome :star2:

An Atom syntax theme is essentially just CSS.
You will be writing in
[Less (a CSS pre-processor)](http://lesscss.org), but the
build process is already set up for you so it's super easy.

The only file you will need to touch is
[base.less](https://github.com/colinmeinke/oaxaca-syntax-theme/blob/master/styles/base.less) -
take a look to see
[just how easy it is to add new syntax highlighting](https://github.com/colinmeinke/oaxaca-syntax-theme/commit/8daae8057ab4f116000cfe59f9a58c4cccd6a924).

### Process

1. [Fork](https://help.github.com/articles/fork-a-repo) the
   [Oaxaca syntax theme repository](https://github.com/colinmeinke/oaxaca-syntax-theme).
2. Make your changes.
3. [Make a pull request](https://help.github.com/articles/using-pull-requests).
4. Your pull request will then be reviewed, merged and
   released!

### Setting up Atom for theme development

Working on a theme locally is really easy in Atom. Follow the
steps below and the theme will live reload as you work on it:

1. First, install Oaxaca syntax theme -
   `apm link /local/path/to/oaxaca-syntax-theme`.
2. Then enable `Oaxaca` as your **syntax theme** in Atom -
   *Atom > Preferences > Themes*.
3. Then open `/local/path/to/oaxaca-syntax-theme` in dev mode -
   *View > Developer > Open in dev mode*.

Atom is built with web technologies and has Chrome dev tools
baked in. This is exceptionally helpful for syntax development
as it allows us to easily inspect an element within Atom and
grab the associated classes. We can then target those classes
in our CSS. The OSX shortcut to open dev tools in Atom is
`⌘+⌥+i`. Then hit the magnifying glass icon to inspect
elements.

### Committing

This repository uses [Commitizen](https://commitizen.github.io/cz-cli)
to guide you through the process of writing commit messages that follow
[Angular's commit message conventions](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#-git-commit-guidelines).

First, install Commitizen and dependencies with `npm install`.
Then `git add` your changes and commit with `npm run commit`.
You will then be prompted for various pieces of information
about the changes you have made.

Take a look at
[the existing commits](https://github.com/colinmeinke/oaxaca-syntax-theme/commits/master)
if you're a little unsure.

**Thank you!**
