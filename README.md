# iota-css-theme

[Demo](https://dist-rfxcerjmcx.now.sh)

## Pre-requisites

```shell
npm install
```

## Building

To build the styles from sass to css and the living style guide.

```shell
npm run build
```

## Viewing

To view the living style guide.

```shell
npm run serve
```

## Development

If you are developing the styles you can serve the guide with watchers on the content. As you make changes to the scss files they will be compiled and the server reloaded. Make sure you have done a full build first then run:

```shell
npm run watch
```

## Linting

The sass linting is run as part of the build process but you can run it by itself using:

```shell
npm run build-lint
```

If you use VSCode the linting also integrates with this [VSCode Plugin](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint) with no extra configuration needed.