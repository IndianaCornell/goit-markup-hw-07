### Project

- **A1** Refactored the HTML code using the **BEM** methodology.
- **A2** Refactored the CSS code using the **SASS** preprocessor.
- **A3** The root directory contains a `sass` folder with all preprocessor stylesheets.
- **A4** The `sass` folder includes a `main.scss` file where all SASS partials (`_name.scss`) are imported.
- **A5** The layout’s color palette and font sets are defined as variables in `variables.scss`, located in `sass/utils`. Both CSS and SASS variables may be used.
- **A6** Each component has a separate partial stylesheet in `sass/components`, e.g. `_page-header.scss`, `_logo.scss`, etc.
- **A7** The `index.html` and `portfolio.html` files include the minified stylesheet `main.min.css` from the `css` folder.

### Markup

- **B1** Box classes are named according to the **BEM** methodology.
- **B2** Element classes follow **BEM** naming conventions.
- **B3** Modifier classes are named per **BEM** standards.
- **B4** Mixin classes are named using **BEM** principles.
- **B5** All **BEM** class names are clear, descriptive, and written in English.

### Styling

- **C1** Selector nesting is applied.
- **C2** Maximum selector nesting depth is **2 levels**.
- **C3** The concatenation operator `&` is used for pseudo-classes and pseudo-elements.
