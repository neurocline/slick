# Slick

A Hugo theme focused on content, cleanliness, speed, responsiveness and privacy.

> Slick is a fork of [temple](https://github.com/aos/temple) with many
  improvements.

> Temple is a fork of [nofancy](https://github.com/gizak/nofancy) with many
  improvements.


## Table of Contents
* [Features](#features)
* [Installation](#installation)
* [Customizing](#customizing)
* [Components](#components)
* [Development](#development)
* [Contributing](#contributing)
* [License](#license)
* [Images](#images)


## Features
The main features of this theme include:
* Supports taxonomies of tags, categories and series with their own pages
* Pagination of content lists
* RSS Feed with complete entries
* [Open Graph](http://ogp.me), [Schema.org](https://schema.org) and
  [Twitter Cards](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/overview/abouts-cards.html) support
* Fully customizable menu entries in the header
* Footer with fully customizable links and RSS
* Customizable favicon (will report correct mime type for png files)
* Relies on chroma for syntax highlighting
* Not even one external request (privacy!) - Everything needed is part of this
  theme (Fonts, CSS, JS, ...)


## Installation
Just download the theme or clone it into
your `themes/` directory:
```
$ cd themes && git clone https://github.com/spookey/slick.git
```
Then reference it in your `config`:
```
theme = "slick"
```
Or when building the site, pass it in to the CLI:
```
$ hugo -t slick
```


## Customizing
Your `config` file will hold all your options.

Please have a look into the `exampleSite` folder for a working example.
It is highly recommended to make some adjustments to the ``main``
and the ``footer`` menu (e.g. to link to your **About** page).


## Components
* [PureCSS](https://purecss.io/)
* [Source Code Pro](https://fonts.adobe.com/fonts/source-code-pro)
* [Source Sans Pro](https://fonts.adobe.com/fonts/source-sans-pro)
* [Source Serif Pro](https://fonts.adobe.com/fonts/source-serif-pro)
* [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme)
  as color scheme (Tomorrow Night for syntax highlighting)

**Please Note**:
Files inside the [static](static) folder are only updated on tagged
commits (releases).


## Development
This theme uses
[rollup.js](https://rollupjs.org) and [postCSS](https://postcss.org)
to bundle all files together.
[Components](#components) are drawn in by [npm](https://www.npmjs.com).

Please have a look inside the [package file](package.json) for commands and
tools required for building.

Use ``npm version`` to tag a commit.


## Contributing
Contributions are welcome.

**Features**:
If you are adding a feature, fork the repository, create a new branch
for your feature and submit a PR.
Please make sure to put documentation for your new feature:
- Place a comment about what your feature is doing above the code.
- If making additions that will affect the `config` file, make sure you update
  the [config.toml](exampleSite/config.toml) in the `exampleSite` folder.

**Issues/Bugs**:
Submit a new issue with information about your issue and/or bug. If you
have a solution, then submit a new PR with the guidelines posted above in the
**features** section and link your issue to it using the keyword
"[*closes*](https://help.github.com/articles/closing-issues-using-keywords/)".


## License
Licensed under the MIT License. See the [LICENSE](LICENSE).


## Images

**Screenshot**

![Screenshot](https://raw.githubusercontent.com/spookey/slick/master/images/screenshot.png)

**Thumbnail**

![Thumbnail](https://raw.githubusercontent.com/spookey/slick/master/images/tn.png)
