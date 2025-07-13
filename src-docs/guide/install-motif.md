---
title: Install Motif
---

# Install Motif

Motif will be used to both generate the Motif API and test the extension.

1. [Download](https://github.com/plxtra/motif/releases) or clone the [Motif repository](https://github.com/plxtra/motif) in a `motif` folder directly under the `motif-extensions` folder.

1. Change director to the `motif` folder (contains motif workspace) and clean install its npm dependencies:
    ```
    cd ./motif
    npm ci
    ```

1. Change director to the `motif` package in the workspace.  This package contains both the Motif app and its API.
    ```
    cd ./motif
    ```

1. Build the API
    ```
    npm run api
    ```

1. Make the API available to other npm packages on your computer
    ```
    npm link
    ```

1. You can confirm this package is available for linking with:
   ```
   npm ls -g
   ```