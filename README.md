css.sugars
===========

Simple css/scss class helpers.

Install
---------

### npm
`npm install -S @sfem/css-sugars`

Usage
---------
Include css in your html

```html
<link rel="stylesheet" type="text/css" href="sugars.css">
```

or import module to your scss

```scss
@import '~@sfem/src/sugars';
```

SCSS Config
---------

```scss
$sugar-paddings: (0, 10px, 20px, 30px, 40px) !default;
$sugar-ratios: ((1, 1), (2, 1), (3, 2), (4, 3)) !default;

$sugar-fw-list: (normal, bold) !default;
$sugar-fs-list: (italic, normal) !default;
$sugar-ta-list: (left, center, right, justify);
$sugar-va-list: (baseline, bottom, middle, sub, super, text-bottom, text-top, top);

$sugar-pm-sides: (left, right, top, bottom) !default;

$sugar-enable-ta: true !default;
$sugar-enable-fs: true !default;
$sugar-enable-fw: true !default;
$sugar-enable-ellipsis: true !default;
$sugar-enable-bw: true !default;
$sugar-enable-paddings: true !default;
$sugar-enable-margins: true !default;
$sugar-enable-hiders: true !default;
$sugar-enable-aspect-ratio: true !default;
$sugar-enable-va: true !default;
```