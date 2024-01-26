# Lux

## A modern configurable CSS stylesheet.

Lux is a pure, vanilla CSS stylesheet using variables to allow for user configuration!

Simply [link `lux.css` into your HTML](#using-lux) to apply the default styling, and [overwrite any of the variables to customize your look](#customizing-lux).

### Using Lux
Include this tag in the HTML you wish to style with Lux.
```HTML
<link rel="stylesheet" href="lux.css">
```

### Customizing Lux
Define this block in a CSS file or style tag _after_ Lux to override any styles.
```CSS
:root {
    /* Colors */
    --color-text: #333333;
    --color-text-special: #222222;
    --color-page: #ffffff;
    --color-page-special: #cccccc;
    --color-input: #cccccc;
    --color-input-special: #d6d6d6;
    --color-input-text: #000000;
    --color-input-text-special: #ffffff;
    --color-accent: #0070A0;
    --color-accent-special: #2090D0;
    --color-border: #dddddd;

    /* Spacing */
    --space-none: 0;
    --space-smaller: 4px;
    --space-small: 8px;
    --space-medium: 12px;
    --space-large: 16px;
    --space-larger: 20px;

    /* Sizing */
    --input-size: 2rem;

    /* Weight */
    --weight-none: 0;
    --weight-smaller: 1;
    --weight-small: 2;
    --weight-medium: 3;
    --weight-large: 4;
    --weight-larger: 5;

    /* Fonts */
    --font-family-regular: arial;
    --font-family-heading: arial;

    --font-weight-none: 0;
    --font-weight-smaller: 200;
    --font-weight-small: 300;
    --font-weight-medium: 400;
    --font-weight-large: 700;
    --font-weight-larger: 800;

    --font-size-none: 0;
    --font-size-smaller: 12px;
    --font-size-small: 14px;
    --font-size-medium: 16px;
    --font-size-large: 18px;
    --font-size-larger: 20px;

    /* Sizes */
    --width-none: 0;
    --width-smaller: 200px;
    --width-small: 400px;
    --width-medium: 800px;
    --width-large: 1200px;
    --width-larger: 1600px;

    --height-none: 0;
    --height-smaller: 80px;
    --height-small: 120px;
    --height-medium: 240px;
    --height-large: 400px;
    --height-larger: 800px;

    /* Borders */
    --border-width: 1px;
    --border: var(--border-width) solid var(--border-color);
    --border-radius: var(--space-small);

    /* Transition */
    --hover-transition-duration: 200ms;
}
```

This repository is intended to be included in projects that require Lux. If you wish to develop lux, please have a look at the [Lux Development Repository](https://github.com/lucania-software/lux-development).