# SCSS Grid Fluent

NPM Repository for installing reset styles.

## Installation

You can install the package:

```bash 
npm install --save https://github.com/getscope/npm-scss-grid-fluent
```

or include the dependency in the `package.json` file:

```json
{
    "dependencies": {
        "@getscope/npm-scss-grid-fluent": "github:getscope/npm-scss-grid-fluent"
    }
}
```

and run the following command in the CLI:

```bash 
npm update
```

## Examples of use

### SCSS

```scss 
@import "node_modules/@getscope/npm-scss-grid-fluent/src/scss/components/_config.scss";

@import "node_modules/@getscope/npm-scss-grid-fluent/src/scss/components/_core.scss";

@import "node_modules/@getscope/npm-scss-grid-fluent/src/scss/_all.scss";
```

### Config

```scss
$grid-config-template-name: 'grid-template';
$grid-config-template-prefix: 'template-';
$grid-config-template-width-default: 100%;
$grid-config-template-width-min: 100%;
$grid-config-template-width-max: 100%;
$grid-config-template-count: 12;
$grid-config-template-spacing-x: 1%;
$grid-config-template-spacing-y: 0.5%;

$grid-config-region-name: 'grid-region';
$grid-config-region-prefix: 'reg-';
$grid-config-region-width-default: 100%;
$grid-config-region-width-min: 100%;
$grid-config-region-width-max: 100%;
$grid-config-region-count: 12;
$grid-config-region-spacing-x: 1%;
$grid-config-region-spacing-y: 0.5%;

$grid-config-string-name: 'grid-string';
$grid-config-string-prefix: 'str-';
$grid-config-string-width-default: 100%;
$grid-config-string-width-min: 1200px;
$grid-config-string-width-max: 100%;
$grid-config-string-count: 12;
$grid-config-string-spacing-x: 1%;
$grid-config-string-spacing-y: 0.5%;

$grid-config-column-name: 'grid-column';
$grid-config-column-prefix: 'col-';
$grid-config-column-count: 12;
$grid-config-column-spacing-x: 1%;
$grid-config-column-spacing-y: 0.5%;

$grid-option-wrap-name: 'data-grid-wrap';
$grid-option-align-name: 'data-grid-align';
$grid-option-size-name: 'data-grid-size';
$grid-option-offset-name: 'data-grid-offset';
$grid-option-spacing-name: 'data-grid-spacing';
```

## Development dependencies

```json 
{
    "devDependencies": {
        "resolve-url-loader": "^3.1.0",
        "sass": "^1.26.10",
        "sass-loader": "^8.0.0"
    }
}
```

## Licenses

* The software is licensed under the [MIT license](https://github.com/getscope/npm-scss-grid-fluent/blob/main/LICENSE).
