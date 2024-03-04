# Nuvocargo Primer CSS

This repository contains a custom build of Primer CSS, tailored for Nuvocargo with our own nuvocargo-light theme and color-modes structure & variables. It's designed to stay in sync with upstream Primer while allowing for requirements.

## Quick Start

```bash
npm install   # Install dependencies
npm start     # Start the development server with live reloading
```

## Customizations

- **Custom Themes**: Incorporates `nuvocargo-light.css` for a branded look and feel.
- **Variable Adjustments**: Our own variable set is included for consistent theming.
- **Reduced Complexity**: Marketing components have been removed for simplicity.

## Documentation

We've focused on enhancing the documentation to make it more comprehensive and user-friendly compared to the official Primer documentation.

## Development

The `npm start` command sets up a development environment that watches for changes in the `src` folder. The lite server provided enables live reloading to streamline your workflow.

## Building for Production

Compile your SCSS to CSS for production use:

```bash
npm run build-css  # Compiles SCSS to CSS in the dist folder
```

## Contributions

Contributions are welcome. Please submit your changes via pull requests.

## Acknowledgements

Built on [GitHub's Primer CSS](https://primer.style/css/), modified for Nuvocargo's branding and component structure.
