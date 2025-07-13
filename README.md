# Motif API

[![NPM version](https://img.shields.io/npm/v/@plxtra/motif-api)](https://www.npmjs.com/package/@plxtra/motif-api) [![License](https://img.shields.io/github/license/plxtra/motif-api)](https://github.com/plxtra/motif-api/blob/main/LICENSE)

API used to build Motif extensions

## API Documentation

Use this documentation to understand how to build a Motif Extension using this Motif API:

[https://plxtra.org/motif-api/Overview/](https://plxtra.org/motif-api/Overview/)

## Install

```
npm i @plxtra/motif-api
```

## Build API

This generates the API documentation directly from the Motif repository.  This is useful if you are using Motif to debug an extension and want to ensure that the Motif API exactly matches the Motif being used to debug the extension.

1. Install the Plxtra [`motif` repository](https://github.com/plxtra/motif) and this [`motif-api` repository](https://github.com/plxtra/motif-api) in the same folder.
1. Set the version in this `@plxtra/motif-api` package so that it matches the `@plxtra/motif` (Motif) package version.
1. Run the `dist` script in this `@plxtra/motif-api` package:
    ```
    npm run dist
    ```

## Publish API

1. [Build the API](#build-api):
1. Review files to be published with:
    ```
    npm pack
    ```
1. Publish to npm
    ```
    npm publish
    ```

## Build API documentation

1. Install the following Plxtra repositories in the same folder:
    * [`@plxtra/motif-api`](https://github.com/plxtra/motif-api)
    * [`motif`](https://github.com/plxtra/motif)
    * [`TsDemo Motif Extension`](https://github.com/plxtra/ts-demo-motif-extension)
    * [`Website embed Motif Extension`](https://github.com/plxtra/website-embed-motif-extension)
    * [`Highcharts Extension`](https://github.com/plxtra/highcharts-motif-extension)
1. [Build the API](#build-api):
1. Run the `docs:build` script in this `@plxtra/motif-api` repository:
    ```
    npm run docs:build
    ```

## View the built API documentation

1. [Build the API documentation](#build-api-documentation)
1. Run the `docs:serve` script in this `@plxtra/motif-api` repository:
    ```
    npm run docs:serve
    ```
