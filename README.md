# Wipe.css

It's a CSS library to reset default styles with some opinionated changes.

* **Reset block margins:** from every elements;
* **Reset the headings** and set a default font style on body;
* **Remove unncessary styles:** such as: background repeat, list styles, etc;
* **Reset form fields:** buttons and inputs looks the same now, in so any styles;
* **Prevent chrome autofill style:** remove that yellow box on fields;
* **Border-box box sizing:** so that borders and paddings don't affect the set dimensions;
* **Responsive media:** images with right size;

## Install

```sh
$ yarn add wipe.css
```

or

```sh
$ npm install wipe.css
```

## How to Use

<details><summary><strong>Pure HTML</strong></summary>
<p>

```html
<head>
  ...
  <link href="./wipe.css" rel="stylesheet" type="text/css" />
</head>
```
</p>
</details>

<details><summary><strong>Pure CSS</strong></summary>
<p>

```css
@import 'wipe.css';
```
</p>
</details>

<details><summary><strong>Styled Components</strong></summary>
<p>

```js
import wipeCSS from 'wipe.css'
import { createGlobalStyle } from 'styled-components'

export const GlobalStyle = createGlobalStyle`
  ${wipeCSS}
`
```
</p>
</details>

## Based on:

[sanitize.css](https://github.com/jonathantneal/sanitize.css)

[normalize.css](https://github.com/necolas/normalize.css)
