# SCSS WebFont Inter

Package for integrating `Inter` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@m2collective/scss-webfont-inter?style=for-the-badge)

___

## Installation

This package can be deployed automatically using NPM:

```
npm i @m2collective/scss-webfont-inter
```

## Usage

Font files are located in the `fonts` directory. To import all fonts, you can use:

```scss
@use "@m2collective/scss-webfont-inter";
```

You can also configure which fonts will be used when importing:

```scss
@use "@m2collective/scss-webfont-inter" with (
  $font-display: swap,
  $font-weights: (100, 200, 300, 400, 500, 600, 700, 800, 900),
);
```

```scss
body {
  font-family: 'Inter', sans-serif;
}
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the `SIL
Open Font License v1.1`. Some fonts use the `Apache 2.0` license. The Ubuntu fonts use the `Ubuntu Font License v1.0`.
