# iota-css-theme

## Usage

In your main React file, you could do :

```shell
import "iota-css-theme";
```

### Fonts
You have to manually include fonts in your project, for instance if you are using [create-react-app](https://github.com/facebook/create-react-app), you need to copy the whole *assets* under your *public* folder and include the font file like the following:

```html
    <!-- public/index.html -->
    <link href='%PUBLIC_URL%/assets/iota-icons.ttf' rel='stylesheet' type='text/css'>
```

Make sure to always clear the cache and reload, it's very common that the browser keeps the same file having the same name! 
So either rename it or clear the cache.

## Documentation

View the Styleguide at <https://iota-css-theme.dag.sh>

## Development

To build the package run:

```shell
npm run build
```

or to build and then serve the style guide locally:

```shell
npm run build-serve
```

or to watch the sass files and automatically rebuild once they have been served you can use:

```shell
npm run build-serve-watch
```
