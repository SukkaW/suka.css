# Suka.css

[![NPM](https://img.shields.io/npm/v/suka.css.svg?style=flat-square)](https://www.npmjs.com/package/suka.css)
[![Author](https://img.shields.io/badge/Author-Sukka-b68469.svg?style=flat-square)](https://skk.moe)
[![Size](https://badge-size.herokuapp.com/SukkaW/suka.css/master/dist/suka.min.css?compression=gzip&style=flat-square)](https://github.com/SukkaW/suka.css/tree/master/dist)
[![Travis](https://img.shields.io/travis/SukkaW/suka.css.svg?style=flat-square)](https://travis-ci.org/SukkaW/suka.css)
[![devDependency Status](https://img.shields.io/david/dev/SukkaW/suka.css.svg?style=flat-square)](https://david-dm.org/SukkaW/suka.css?type=dev)
[![LICENSE](https://img.shields.io/github/license/sukkaw/suka.css.svg?style=flat-square)](./LICENSE)
[![](https://data.jsdelivr.com/v1/package/npm/suka.css/badge)](https://www.jsdelivr.com/package/npm/suka.css)

The most useless css framework.

## Getting Started

### Introduction

**Suka.css** is a lightweight (less than 2KB gziped), and the most useless CSS framework for faster and extensible development.

Suka.css provides basic styles for many utilities.

### Install

There are many ways to get started with Suka.css in your projects. You can either install manually, from CDN or use package managers.

#### Install manually

Download the compiled and minified [Suka CSS File](https://github.com/sukkaw/suka.css/releases)

Then include `suka.min.css` located in `/dist` in your website or Web app.

#### Install using npm

```bash
npm i suka.css
```

#### Install from CDN

Alternatively, you can use the [unpkg](https://unpkg.com/) or [jsdelivr](https://www.jsdelivr.com) CDN to load compiled Suka.css.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/suka.css@0.2.0">
```

```html
<link rel="stylesheet" href="https://unpkg.com/suka.css@0.2.0/dist/suka.min.css">
```

### Compiling CSS

Suka.css uses Gulp for compiling CSS. Firstly you need to install NPM, which is used to manage Gulp and other dependencies.

Then, you can build the CSS file from the command line:

- Navigate to the root directory of Suka.
- Run `npm i`. NPM will install all dev dependencies as listed in `package.json`.
- When completed, run `gulp build` task to compile CSS and minify files.
- You can find compiled CSS files in /dist directory.

All available Gulp tasks:

- `gulp build` - compile Sass to CSS and minify files (default)
- `gulp watch` - watch file changes and re-compile CSS files

### Browser support

Suka.css uses [Autoprefixer](https://github.com/postcss/autoprefixer) to make most styles compatible with earlier browsers. For best compatibility, these browsers are recommended:

- Chrome `38+`
- Edge `Last 4`
- Firefox `54+`
- Opera `Last 4`
- IE `10+`

## Color

### Text Color

<span class="sk-text-gray">sk-text-gray</span>

<span class="sk-text-light" style="background: #000">sk-text-light</span>

<span class="sk-text-dark">sk-text-dark</span>

<span class="sk-text-success">sk-text-success</span>

<span class="sk-text-warning">sk-text-warning</span>

<span class="sk-text-error">sk-text-error</span>

```html
<span class="sk-text-gray">sk-text-gray</span>
<span class="sk-text-light">sk-text-light</span>
<span class="sk-text-dark">sk-text-dark</span>
<span class="sk-text-success">sk-text-success</span>
<span class="sk-text-warning">sk-text-warning</span>
<span class="sk-text-error">sk-text-error</span>
```

### Background Color

<span class="sk-bg-dark sk-p-2">sk-bg-dark</span>

<span class="sk-bg-gray sk-p-2">sk-bg-gray</span>

<span class="sk-bg-success sk-p-2">sk-bg-success</span>

<span class="sk-bg-warning sk-p-2">sk-bg-warning</span>

<span class="sk-bg-error sk-p-2">sk-bg-error</span>

```html
<div class="sk-bg-dark">sk-bg-dark</div>
<div class="sk-bg-gray">sk-bg-gray</div>
<div class="sk-bg-success">sk-bg-success</div>
<div class="sk-bg-warning">sk-bg-warning</div>
<div class="sk-bg-error">sk-bg-error</div>
```


## Cusors

<span class="sk-bg-gray sk-p-2 sk-m-1 sk-c-hand">sk-c-hand</span>
<span class="sk-bg-gray sk-p-2 sk-m-1 sk-c-move">sk-c-move</span>
<span class="sk-bg-gray sk-p-2 sk-m-1 sk-c-zoom-in">sk-c-zoom-in</span>
<span class="sk-bg-gray sk-p-2 sk-m-1 sk-c-zoom-out">sk-c-zoom-out</span>
<span class="sk-bg-gray sk-p-2 sk-m-1 sk-c-not-allowed">sk-c-not-allowed</span>
<span class="sk-bg-gray sk-p-2 sk-m-1 sk-c-not-auto">sk-c-not-auto</span>

```html
<div class="sk-c-hand">sk-c-hand</div>
<div class="sk-c-move">sk-c-move</div>
<div class="sk-c-zoom-in">sk-c-zoom-in</div>
<div class="sk-c-zoom-out">sk-c-zoom-out</div>
<div class="sk-c-not-allowed">sk-c-not-allowed</div>
<div class="sk-c-not-auto">sk-c-not-auto</div>
```

## Display

### property value display

```html
<!-- display: block; -->
<div class="d-block"></div>
<!-- display: inline; -->
<div class="d-inline"></div>
<!-- display: inline-block; -->
<div class="d-inline-block"></div>
<!-- display: flex; -->
<div class="d-flex"></div>
<!-- display: inline-flex; -->
<div class="d-inline-flex"></div>
<!-- display: none; -->
<div class="d-none"></div>
```

### display method of text

```html
<!-- hide text contents -->
<div class="text-hide"></div>
<!-- assistive text for screen reader -->
<div class="sk-text-assistive"></div>
```

## Margin & Padding

Series of margin/padding utilities. Default the multiples of 4px.

`sk-{value}{position}-{size}`

### value

- `m` - Margin
- `p` - Padding

### position

- `t` - Top
- `b` - Bottom
- `l` - Left
- `r` - Right
- None - All direction

### size

- `0` - 0px
- `1` - 4px
- `2` - 8px
- `3` - 12px
- `4` - 16px
- `5` - 20px
- `6` - 24px
- `7` - 28px
- `8` - 32px

## Media

`.sk-fluid` Make the element adaptive to the width of its parent element.

## Shapes

<div class="sk-bg-dark sk-m-3 docs-shape sk-rounded">sk-rounded</div>
<div class="sk-bg-dark sk-m-3 docs-shape sk-circle">sk-circle</div>

```html
<!-- rounded element -->
<div class="sk-rounded">sk-rounded</div>
<!-- circle element -->
<div class="sk-circle">sk-circle</div>
```

## Float

```html
<!-- clear float -->
<div class="sk-clearfix"></div>
<!-- float: left and right -->
<div class="sk-fk">FLoat Left</div>
<div class="sk-fr">Float Right</div>
```

## Position

```html
<!-- position: relative, absolute and fixed -->
<div class="sk-relative"></div>
<div class="sk-absolute"></div>
<div class="sk-fixed"></div>
```

## Center

Make any element to center it horizontally if it have its own width.

```html
<div class="sk-center"></div>
```

## Valign

Make any element to center it vertically if its parent eleent have its own height.

```html
<div class="sk-valign"></div>
```

## Shadow

Series of shadow.

`sk-shadow-{size}`

`{size}` can be 1 to 8

<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-1">sk-shadow-1</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-2">sk-shadow-2</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-3">sk-shadow-3</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-4">sk-shadow-4</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-5">sk-shadow-5</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-6">sk-shadow-6</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-7">sk-shadow-7</div>
<div class="sk-bg-gray docs-shape sk-m-8 sk-shadow-8">sk-shadow-8</div>

## Text

### Position (text align)

```html
<!-- left-aligned text -->
<div class="sk-text-left"></div>
<!-- center-aligned text -->
<div class="sk-text-center"></div>
<!-- right-aligned text -->
<div class="sk-text-right"></div>
```

### Transform

```html
<!-- Lowercased text -->
<div class="sk-text-lowercase"></div>
<!-- Uppercased text -->
<div class="sk-text-uppercase"></div>
<!-- Capitalized text -->
<div class="sk-text-capitalize"></div>
```

### Text Truncate

```html
<div class="sk-text-truncate"></div>
```

### Shape

```html
<!-- Normal Weight -->
<div class="sk-text-normal"></div>
<!-- Bold -->
<div class="sk-text-bold"></div>
<!-- Italic -->
<div class="sk-text-italic"></div>
<!-- Larger Text -->
<div class="sk-text-large"></div>
<!-- Smaller Text -->
<div class="sk-text-small"></div>
```

### Link

```html
<div class="sk-link"></div>
```

### Hide Text

Hide text without touching display

```html
<div class="sk-text-hide"></div>
```

### Font Size

Series of margin/padding utilities. Default the multiples of 4px.

`sk-font-{size}`

### size

- `12` - 12px
- `14` - 14px
- `16` - 16px
- `18` - 18px
- `20` - 20px
- `22` - 22px
- `24` - 24px
- `26` - 26px
- `28` - 28px

## Visibility

### Hide element

```html
<div class="sk-hidden"></div>
<div class="sk-hide"></div>
```

### Visible

```html
<div class="sk-invisible"></div>
<div class="sk-visible"></div>
```

### Responsive

|       |<= 480px|<= 600px|<= 840px|<= 960px|<= 1280px|
|:-----:|-------|-------|-------|-------|-------|
|sk-hide-xs||<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|
|sk-hide-sm|||<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|
|sk-hide-md||||<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|
|sk-hide-lg|||||<div class="sk-bg-dark docs-dot">|
|sk-hide-xl||||||
|sk-hide||||||
|sk-hidden||||||
|sk-show-xs|<div class="sk-bg-dark docs-dot">|||||
|sk-show-sm|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">||||
|sk-show-md|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|||
|sk-show-lg|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">||
|sk-show-xl|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|<div class="sk-bg-dark docs-dot">|