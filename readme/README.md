# SEB Angular Material 
[![Build Status](https://travis-ci.org/sebgroup/seb-angular-material.png?branch=master)](https://travis-ci.org/sebgroup/seb-angular-material)

This is SEB theme for [Angular Material components](https://material.angular.io)

[Demo app](https://sebgroup.github.io/seb-angular-material/)

## Installation

* add npm dependency for Angular Material: `npm install --save @angular/material @angular/cdk @angular/animations`

To install using NPM use this command:

```bash
`npm i --save @sebgroup/seb-angular-material-theme`
```

## Usage

* in your top level style file (for ex. `styles.sass`), add SEB Material styles (lib contains both seb-mat-theme.css and seb-mat-theme.scss files):
  ```
  @import "node_modules/@sebgroup/seb-angular-material-theme/seb-mat-theme.css";
  ```
  or add it in angular.json
  ```
  "styles": [
    ..,
    "node_modules/@sebgroup/seb-angular-material-theme/seb-mat-theme.css"
  ],
  ```
* in your markup body:
  ```html
  <body class="mat-body">...</body>
  ```
* in your components, use Angular Material directives:
  ```html
  <button mat-raised-button color="primary" type="button"></button>
  ```

For more info on usage and examples, consult [Angular Material docs](https://material.angular.io).

## Development server

Angular demo application is available.

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Releasing

The library is released via [semantic-release](https://www.npmjs.com/package/semantic-release).

