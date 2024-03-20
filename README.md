# Urban Jungle UI Themes

Urban Jungle UI Themes is a library designed to help developers effortlessly integrate themed styles into their web projects. It combines the power of TailwindCSS with the flexibility of custom themes, processed through PostCSS, autoprefixer, and cssnano for optimal performance and compatibility.

## Features

- **Sass to CSS conversion**: Easily compile your Sass themes into CSS.
- **Automatic prefixing**: Ensure your CSS works across different browsers with autoprefixer.
- **CSS Minification**: Reduce CSS file size for faster loading times using cssnano.
- **TailwindCSS Integration**: Optionally integrate TailwindCSS for utility classes, enhancing the power of your themes.

## Installation

To install `urban-jungle-ui-themes`, use npm:

```bash
npm install urban-jungle-ui-themes
```

## Usage

To use `urban-jungle-ui-themes` in your project, follow these steps:

1. Import `generateThemeCSS` from the package.

```javascript
import generateThemeCSS from 'urban-jungle-ui-themes';
```

2. Call `generateThemeCSS` with the name of your theme.

```javascript
// Example: Generate CSS for the 'default' theme
generateThemeCSS('default').then(() => {
console.log('Theme CSS generated successfully.');
});
```

Make sure you have the corresponding `.scss` file for your theme under the `themes/` directory.

## Contributing

Contributions are welcome! Please feel free to submit pull requests, report issues, or suggest enhancements to the library.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
