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
$grid-config-module-name: 'grid-module';
$grid-config-module-prefix: 'mod-';
$grid-config-module-width-default: 100%;
$grid-config-module-width-min: 100%;
$grid-config-module-count: 12;
$grid-config-module-spacing: 8px;

$grid-config-region-name: 'grid-region';
$grid-config-region-prefix: 'reg-';
$grid-config-region-width-default: 100%;
$grid-config-region-width-min: 100%;
$grid-config-region-count: 12;
$grid-config-region-spacing: 8px;

$grid-config-string-name: 'grid-string';
$grid-config-string-prefix: 'str-';
$grid-config-string-width-default: 100%;
$grid-config-string-width-min: 1200px;
$grid-config-string-count: 12;
$grid-config-string-spacing: 8px;

$grid-config-column-name: 'grid-column';
$grid-config-column-prefix: 'col-';
$grid-config-column-count: 12;
$grid-config-column-spacing: 8px;

$grid-option-size-name: 'data-grid-size';
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
