---
title: Guide
children:
    - ./install-motif.md
    - ./package.md
    - ./extension.md
    - ./frame.md
    - ./strings.md
    - ./entry-point.md
    - ./config.md
    - ./bundling.md
    - ./test.md
    - ./deploy.md
---

# Guide

This guide will step you through creating an extension similar to the [TsDemo example](../examples/ts-demo/index.md).  This includes coding, bundling, testing and deploying the extension.

The main steps are:

1. **Root Folder**\
Create or select a folder under which you will create the motif extension(s).  Let's call it, `extensions-dev`.

1. **[Install Motif](./install-motif.md)**\
Install the `motif` repository under the `extensions-dev` folder.

1. **Custom Extensions Folder**\
Create a folder for custom extensions under the `custom-motif-extensions` folder.  In this case, `ts-demo`.

1. **[Create NPM Package file](./package.md)**\
Create the NPM package file for the new motif extension in the extension (`ts-demo`) folder.

1. **[Extension](./extension.md)**\
Create the `TsDemoExtension` extension class.

1. **[Frame](./frame.md)**\
Create the `BlueFrame` Frame class.

1. **[Strings](./strings.md)**\
Create the translatable strings.

1. **[Entry Point](./entry-point.md)**\
Create the entry point (`index.js`) module.

1. **[Config](./config.md)**\
Create the `tsconfig.json` file needed to compile the extension.

1. **[Bundling](./bundling.md)**\
Create the webpack `tsconfig.json` file needed to compile the extension.

1. **[Test](./test.md)**\
Test and debug the extension with Motif.

1. **[Deploy](./deploy.md)**\
Include the extension in a Motif deployment.
