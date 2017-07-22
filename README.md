# Nicholas

A fork of [Casper](https://github.com/TryGhost/Casper), the default theme for [Ghost](https://github.com/TryGhost/Ghost).

&nbsp;

![screenshot-desktop](/assets/screenshot-desktop.png)

&nbsp;

## Compatibility

**The current Nicholas version is 1.3.6, is tested against Ghost 0.11.7 and is expected to work with Ghost 0.9.0.**

If the current version of Nicholas is not compatible with the version of Ghost you're running, try looking for an older one in the [Releases section](https://github.com/juangesino/Nicholas/releases).

## Installation

* Download the [latest release](https://github.com/juangesino/Nicholas/releases/latest) as a zip file.
* Rename `partials/disqus.hbs.example` to `partials/disqus.hbs` and customize it with your Disqus shortname.
* Rename `partials/sidebar-external.hbs.example` to `partials/sidebar-external.hbs` and customize it with your own external links.
* Go to your blog's Settings page (typically `/admin` or `/ghost`).
* In the Labs tab, enable the [Ghost Public API](http://support.ghost.org/public-api-beta/). This is required for search functionality.
* In the General tab, upload and activate Nicholas.

If the process fails, try [installing the theme manually](https://www.ghostforbeginners.com/how-to-install-a-ghost-theme/#uploadmanually).

# Development

Nicholas styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need Node and Gulp installed globally. After that, from the theme's root directory:

`$ npm install`

`$ gulp`

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.


## Copyright & License

Copyright (c) 2013-2017 Ghost Foundation - Released under the [MIT license](LICENSE). (Original)  
Copyright (c) 2017 Juan I. Gesino - Released under the [MIT license](LICENSE). (Modifications)
