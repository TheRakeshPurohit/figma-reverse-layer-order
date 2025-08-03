# Figma plugin: Reverse Layer Order

A Figma plugin that reverses the stacking order of selected layers within their parent container.

## Installation

1. Clone this repository
2. Run `tsc` to compile TypeScript (or configure your build process)
3. In Figma, go to Plugins → Development → Import plugin from manifest
4. Select the `manifest.json` file

## Development

1. Make changes to `code.ts`
2. Run `tsc` to compile to `code.js`
3. Reload the plugin in Figma after making changes

## Usage

1. Select 2 or more layers within the same parent container
2. Run the "Reverse Layer Order" plugin
3. The selected layers will be reordered in reverse stacking order

## License

© 2025 Mike Gowen

MIT License
