[![Author](https://img.shields.io/badge/author-Daniel%20M.%20Hendricks-lightgrey.svg?colorB=9900cc )](https://www.danhendricks.com?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=file-icon-vectors)
[![Release](https://img.shields.io/github/release/dmhendricks/file-icon-vectors.svg)](https://github.com/dmhendricks/file-icon-vectors/releases)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](https://raw.githubusercontent.com/dmhendricks/file-icon-vectors/master/LICENSE)
[![StackShare](https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/dmhendricks/file-icon-vectors?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=file-icon-vectors)
[![GitHub Downloads](https://img.shields.io/packagist/dt/dmhendricks/file-icon-vectors.svg?label=GitHub%20downloads)](https://github.com/dmhendricks/file-icon-vectors/releases)
[![NPM](https://img.shields.io/npm/v/file-icon-vectors.svg)](https://www.npmjs.com/package/file-icon-vectors?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=file-icon-vectors)
[![NPM Downloads](https://img.shields.io/npm/dt/file-icon-vectors.svg?label=npm%20downloads)](https://www.npmjs.com/package/file-icon-vectors?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=file-icon-vectors)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/dmhendricks/file-icon-vectors.svg?style=social)](https://twitter.com/danielhendricks)

# File Vector Icons

A collection of file type/extension SVG icons, licensed MIT and available free for use in your applications.

* Please post [feedback or issues](https://github.com/dmhendricks/file-icon-vectors/issues).
* I pay to license many of the icons used in these sets. **[Donations](https://paypal.me/danielhendricks) are appreciated**.
* :bulb: If you have an idea, such as new icon requests, additional collections/designs, and/or are willing to contribute a library/design, please [let me know](https://github.com/dmhendricks/file-icon-vectors/issues)! My time is limited, but I will get to it eventually.
* :star: If you use this library to create something cool, [tell me](https://twitter.com/danielhendricks) about it!

## Icon Sets

Currently, there are two icon sets in the `dist/icons` directory:

* **Classic** - An expansion of the Redboot [free-file-icons](https://github.com/redbooth/free-file-icons) designs.
* **Vivid** - Inspired by [Erlen Masson](https://www.sketchappsources.com/svg-resource/1856-vector-file-type-icons-sketch-freebie-resource.html?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
* **Square Outline** (in progress) - Modified from and inspired by [Cotne Nazarashvili](https://github.com/thecotne/square-file-icons)


### :pushpin: Demo: [View Icon Sets](https://danhendricks.com/demo/github/dmhendricks/file-icon-vectors/demo/?utm_source=danhendricks.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)

## Installation

#### NPM

```bash
npm install file-icon-vectors
```

#### Bower

```bash
bower install file-icon-vectors
```

#### Composer

```bash
composer require dmhendricks/file-icon-vectors
```

## Linking Stylesheets

To display a file icon, simply link to one or both of the icon set CSS files in the `css` directory:

```html
<link rel="stylesheet" href="dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="dist/file-icon-vivid.min.css" />
```

#### CDN: unpkg

Recommended for performance.

```html
<link rel="stylesheet" href="https://unpkg.com/file-icon-vectors/dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="https://unpkg.com/file-icon-vectors/dist/file-icon-vivid.min.css" />
```

#### CDN: jsDelivr

Supports both HTTP and HTTPS.

```html
<link rel="stylesheet" href="//cdn.jsdelivr.net/gh/dmhendricks/file-icon-vectors/dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="//cdn.jsdelivr.net/gh/dmhendricks/file-icon-vectors/dist/file-icon-vivid.min.css" />
```

#### CDN: RawGit

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/dmhendricks/file-icon-vectors/0.8.1/dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="https://cdn.rawgit.com/dmhendricks/file-icon-vectors/0.8.1/dist/file-icon-vivid.min.css" />
```

## Example Usage

From there, you can use CSS classes to display the icons:

```html
<span class="fiv-cla fiv-icon-ppt"></span>
<span class="fiv-cla fiv-icon-xls"></span>
<span class="fiv-viv fiv-icon-pdf"></span>
<span class="fiv-viv fiv-icon-wav"></span>
<span class="fiv-sqo fiv-icon-doc"></span>
```

Notice that the classes contain either `flv-cla` for the Classic set or `flv-viv` for the Vivid set.

If you want to override the size of the icons, you can do so with CSS:

```html
<style>
   .fiv-cla, .fiv-viv, .fiv-sqo { font-size: 3em; }
</style>
```

If you prefer, you may also use `.fiv-size-md`, `.fiv-size-lg` and `.fiv-size-xl` to modify the icon sizes:

```html
<span class="fiv-viv fiv-icon-pdf fiv-size-lg"></span>
```

## Special Thanks

- [unpkg](https://unpkg.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) and [jsDelivr](https://www.jsdelivr.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
- [Markdown Editor](https://jbt.github.io/markdown-editor/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) by James Taylor
- [SVG optimiser](http://petercollingridge.appspot.com/svg-optimiser?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) by Peter Collingridge
- [SVGito](http://sketchmaster.com/svg-optimizer/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) by [Sketch Master](http://sketchmaster.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
- [Gulp](https://gulpjs.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) and [Sass](https://sass-lang.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)

Even though I'm paying for them, thanks also to [Adobe](https://www.adobe.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors), [The Noun Project](https://thenounproject.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) and [FlatIcon](https://www.flaticon.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) for providing great tools and services. :+1: :smile:

[![Analytics](https://ga-beacon.appspot.com/UA-67333102-2/dmhendricks/file-icon-vectors)](https://github.com/dmhendricks/file-icon-vectors)

## Legal Stuff

All icons used in the creation of this library were licensed MIT or purchased royalty-free, with exceptions noted below.

If you feel that you have a copyright issue, please feel free to [post it](https://github.com/dmhendricks/file-icon-vectors/issues).

### Attribution

* [Android icon](https://www.flaticon.com/free-icon/android-logo_61120?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) made by [Google](https://www.flaticon.com/authors/google?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) via [flaticon.com](https://www.flaticon.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
* [BitTorrent icon](http://www.icons101.com/icon/id_73504/setid_2388/Minimalist_Black_Icons__WIP_by_noshery/bittorrent?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors) made by [noshery](http://www.icons101.com/artist/id_2388/noshery) from [icons101.com](http://www.icons101.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
* [GIMP Icon](https://icons8.com/icon/39867/gimp) provided by [Icons8 LLC](https://icons8.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
* [Git Icon](https://icons8.com/icon/44898/git) provided by [Icons8 LLC](https://icons8.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)
* Vivid set [Folder Icon](https://www.iconfinder.com/icons/173016/close_folder_icon) made by [Snip Master](https://www.iconfinder.com/snipicons) from [Iconfinder](https://www.iconfinder.com?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=file-icon-vectors)

## Screenshot - Vivid Collection

![Vivid Icon Collection](https://cdn.danhendricks.com/demo/github/dmhendricks/file-icon-vectors/demo/screenshot.png "Vivid Icon Collection")
