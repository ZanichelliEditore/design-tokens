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
  folder that contains theming config files
  
- `src/modules/palette`:  
  folder that contains every availabele color in the palette

## Usage

#### Build Github Markdown Preview

```bash
yarn build
```

### Import in your project 
```html 
<link rel="stylesheet" src="[***]/dist/themes/default.css" />
<link rel="stylesheet" src="[***]/dist/tokens.css" />
```

or 
```css
@import "~@zanichelli/albe-design-tokens/dist/tokens.css";
```