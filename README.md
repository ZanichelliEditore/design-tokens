![Zanichelli logo](https://www.zanichelli.it/static/zanichelli/templates/zanichelli/_template_style/images/logo-print.png)

# Zanichelli Design Tokens

## Intro
This repo is an auxiliary project to `zanichelli/design-system` [repo](https://github.com/ZanichelliEditore/design-system); it contains `.scss` files to generate css design tokens.

## Structure

- `src/main.css`:
  index file where everything is imported

- `src/modules`:
  folder that contains every needed module

- `src/modules/theme`:
  folder that contains themes files

- `src/modules/palette`:
  folder that contains every available color in the palette

## Naming Convention for Themes:

In case of implementation of a new theme, the following convention must be followed:
- theme file name: `{primary-color}-{secondary-color}.scss`
- theme class name: `.theme-{primary-color}-{secondary-color}`

## Usage

#### Build Github Markdown Preview

```bash
yarn build
```

### Import in your project
```html
<link rel="stylesheet" src="[***]/dist/themes/<theme-name>.css" />
<link rel="stylesheet" src="[***]/dist/tokens.css" />
```

or
```css
@import "~@zanichelli/albe-design-tokens/dist/tokens.css";
```
