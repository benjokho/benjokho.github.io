<<<<<<< HEAD
# BlackDoc

BlackDoc is a two-column [Jekyll](http://jekyllrb.com) theme that's ideal for websites that require a master-detail layout for viewing of content. It's based on [Poole](http://getpoole.com), the Jekyll butler, and the [Hyde](http://hyde.getpoole.com) theme.

![BlackDoc screenshot](https://raw.githubusercontent.com/karloespiritu/blackdoc/master/public/images/blackdoc-screenshot.jpg)

## Contents

- [Features](#features)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Options](#options)
  - [Sidebar menu](#sidebar-menu)
  - [Scrolling sidebar content](#scrolling-sidebar-content)
  - [Themes](#themes)
  - [Reverse layout](#reverse-layout)
- [Development](#development)
- [Author](#author)
- [License](#license)
- [Thanks](#thanks)

## Features

* Now compatible with Jekyll 3.x
* Two-column layout with scrolling sidebar content
* Ideal for websites that require  master-detail view of content

## Quick Start

Download the zip file or clone the BlackDoc repo.

```bash
$ git clone git@github.com:karloespiritu/BlackDoc.git mysite
$ cd mysite
```
Make sure you have Ruby 2.0.0 or higher installed.

```bash
$ ruby --version
ruby 2.x.x
```

Install bundler and install dependencies.

```bash
$ gem install bundler
$ bundle install
```

Build and run your BlackDoc site.

```bash
$ jekyll serve
```

## Usage

BlackDoc is a theme built on top of [Poole](https://github.com/poole/poole), which provides a fully furnished Jekyll setup—just download and start the Jekyll server. See [the Poole usage guidelines](https://github.com/poole/poole#usage) for how to install and use Jekyll.


## Options

BlackDoc includes some customizable options, typically applied via classes on the `<body>` element.


### Sidebar menu

Create a list of nav links in the sidebar by assigning each Jekyll page the correct layout in the page's [front-matter](http://jekyllrb.com/docs/frontmatter/).

```
---
layout: page
title: About
---
```

**Why require a specific layout?** Jekyll will return *all* pages, including the `atom.xml`, and with an alphabetical sort order. To ensure the first link is *Home*, we exclude the `index.html` page from this list by specifying the `page` layout.


### Scrolling sidebar content

By default, BlackDoc includes a scrolling sidebar that will display your markdown files in alphabetical order.

### Themes

BlackDoc ships with eight optional themes based on the [base16 color scheme](https://github.com/chriskempson/base16). Apply a theme to change the color scheme (mostly applies to sidebar and links).

To use a theme, add anyone of the available theme classes to the `<body>` element in the `default.html` layout, like so:

```html
<body class="theme-base-08">
  ...
</body>
```

To create your own theme, look to the Themes section of [included CSS file](https://github.com/karloespiritu/blackdoc/blob/master/public/css/blackdoc.css). Copy any existing theme (they're only a few lines of CSS), rename it, and change the provided colors.

### Reverse layout

![BlackDoc reverse screenshot](https://raw.githubusercontent.com/karloespiritu/BlackDoc/master/public/images/reverse-screenshot.png)

BlackDoc's page orientation can be reversed with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```

## Author

**Karlo Espiritu**
- <https://github.com/karloespiritu>
- <https://twitter.com/karloespiritu>

## License

Open sourced under the [MIT license](LICENSE.md).

\m/

## Thanks

Thanks to [@mdo](https://twitter.com/mdo) for creating the awesome [Poole](http://getpoole.com) project.
=======
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/benjokho/benjokho.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/benjokho/benjokho.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
>>>>>>> origin/master
