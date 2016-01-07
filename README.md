# typescript-node-starter
Starter template for TypeScript for NodeJS with VS Code

When running (or debugging) in Visual Studio Code the build task will automatically call the compile-script and compile all TypeScript files.

The build script is based on that of a VS Code extensions project for TypeScript.

## Prerequisites

Requires the latest version of NodeJS with support for ECMAScript 2015/6 features (classes and generators etc) 

## Getting started

### VS Code

To run in VS Code, simply press Run or Debug and the compile script will execute before actually running.

### Command line

As usual, from the commandline:

```sh
tsc 
```

Or for watcher:

```sh
tsc watch
```